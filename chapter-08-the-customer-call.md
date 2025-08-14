# Chapter 8: The Customer Call

"Absolutely not," Alex said, backing away from Sarah's office as if she'd suggested jumping off the roof.

"It's just a customer call," Sarah said patiently. "Thirty minutes. You explain the technical architecture of the migration."

"To non-technical people? That's James's job."

"James has the flu. Marcus is at a wedding. Rita's handling a production issue. That leaves you."

"What about Brad?"

"Brad's volunteering at a high school coding bootcamp. Part of his rehabilitation."

Alex was out of excuses. "I don't do customer calls. I don't even own a webcam."

Sarah held up a brand new webcam, still in its box. "Company equipment. The call is in one hour. The customer is MegaBank. They process 40% of our transaction volume. They're nervous about the migration."

"Send Priya. She's good with people."

"Priya's brilliant, but she's been here three months. You've been here four years. You know the system inside and out."

"I'll write a detailed technical document. James can present it when he's better."

Sarah's expression softened. "Alex, what are you really afraid of?"

Alex slumped into a chair. "I'll say something wrong. Or too technical. Or not technical enough. I'll make us look incompetent."

"You survived pair programming. You handled Brad's transformation. You can handle this."

"Those were engineers. They speak my language. Customers are... alien."

Sarah pulled up a LinkedIn profile. "The technical lead from MegaBank. Dr. Jennifer Wu. PhD in distributed systems from Stanford. Published three papers on transaction processing. She's more technical than most of our team."

Alex read the profile, feeling slightly better but still anxious.

"What if they ask about business impact? Revenue projections? I don't know any of that."

"Then you say, 'That's a great question. Let me get back to you with accurate numbers.' Nobody expects you to know everything."

Sarah handed Alex a one-page brief. "Key points about MegaBank. They value stability over features. They've been burned by vendors promising revolutionary changes. They want evolution, not revolution."

An hour later, Alex sat at their desk, webcam mounted and active for the first time ever. Their reflection looked terrified.

The call connected. Three faces appeared: Dr. Wu, looking exactly like her LinkedIn photo; a stern-looking man introduced as Robert, the CFO; and a younger woman named Casey, the product manager.

"Thank you for joining us," Dr. Wu began. "We're concerned about the migration's impact on our transaction processing."

Alex's prepared script evaporated. They took a breath and decided to be honest.

"I understand your concern. Can I share my screen and walk you through exactly what changes and, more importantly, what doesn't?"

"Please do," Dr. Wu said.

Alex pulled up the architecture diagram they'd created with the team. It was color-coded: green for unchanged, yellow for modified, red for replaced.

"Notice how much green there is," Alex began, finding their rhythm. "The core transaction logic—Dr. Montgomery's original algorithms—remain untouched. We're replacing the plumbing, not the engine."

"Why keep the old algorithms?" Robert asked. "Surely there are more modern approaches."

Alex remembered something Dr. Montgomery had said. "These algorithms have processed seventeen trillion dollars without losing a cent. Modern isn't always better. Proven is better."

Dr. Wu leaned forward. "Tell me about the rollback plan."

This was Alex's territory. They pulled up the deployment strategy Rita had designed.

"Blue-green deployment with automatic rollback triggers. If any metric deviates by more than 2%, we instantly revert. Transaction integrity is guaranteed by—"

"By running both systems in parallel with reconciliation," Dr. Wu finished, smiling slightly. "I see you've done your homework."

"Actually, that was our DevOps engineer Rita's idea. She's handled every edge case I can think of and several I couldn't."

"You have a strong team," Casey observed. "But what happens if key people leave?"

Alex pulled up something they'd been working on with the team: the knowledge repository.

"Every decision is documented. Every algorithm is explained. We've even recorded video walkthroughs of complex sections. No more bus factor of one."

"This is impressive," Robert said, "but I'm concerned about downtime."

"Zero," Alex said confidently. "The migration happens in phases. Each phase is tested with your actual transaction patterns—with your permission, we'd like to replay last month's transactions through the new system."

"That's... actually brilliant," Dr. Wu said. "Whose idea was that?"

"Marcus, our QA engineer. He believes testing should mirror reality, not theory."

The call continued for another twenty minutes. Alex found themselves naturally crediting the team for various innovations, explaining not just what they'd built but why they'd built it that way.

"One last question," Robert said. "Why should we trust a mid-sized company with our critical infrastructure?"

Alex thought about giving a corporate answer about commitment to excellence or customer satisfaction. Instead, they told the truth.

"Because we're not trying to impress you with complexity. We're trying to solve your problems with clarity. Because every person on our team understands that your transactions are people's mortgages, car payments, and kids' college funds. Because we answer our phones at 3 AM when something breaks, and we don't stop until it's fixed."

Alex paused, then added, "And because we're small enough that losing your trust would hurt us more than it would hurt you. That makes us very motivated to get this right."

Robert nodded slowly. "Thank you for your honesty."

After the call ended, Alex slumped in their chair, exhausted. Their shirt was soaked with sweat.

Sarah appeared moments later. "I watched from my office. You were brilliant."

"I almost threw up twice."

"But you didn't. And you did something I didn't expect—you sold the team, not just the technology."

Alex's phone buzzed with an email from Dr. Wu:

"Alex - Your presentation was refreshingly honest and technically sound. I particularly appreciated your willingness to credit your team members for specific innovations. This shows both humility and leadership. MegaBank is approved to proceed with the migration. P.S. - I'd love to discuss the transaction validator logic in more detail. Are you available for a technical deep-dive next week?"

Sarah read over Alex's shoulder. "She wants a technical deep-dive. With you specifically."

"I should bring Marcus and Rita—"

"No. She wants to talk to you. You've become the face of our technical excellence."

"That's terrifying."

"That's growth. Six weeks ago, you wouldn't have even answered an email from a customer."

That evening, the team celebrated at their usual bar. Word had spread about Alex's successful customer call.

"To Alex, customer whisperer!" Marcus toasted.

"I just told the truth," Alex protested.

"Exactly," James said, finally back from his sick day. "Most vendors promise magic. You promised competence. That's much more valuable."

Priya pulled up her phone. "Dr. Wu posted on LinkedIn. Listen to this: 'Refreshing call with TechNova's Alex Chen. Technical expertise combined with genuine humility and team advocacy. This is what vendor partnerships should look like.'"

"You're LinkedIn famous!" Rita laughed.

"Please no," Alex groaned.

Brad, who'd joined them after his bootcamp session, raised his glass. "You know what this means? You're now our designated customer-facing engineer."

"Absolutely not."

"Too late," Sarah said. "I already have three more customer calls scheduled for you next week."

Alex wanted to protest, but something stopped them. The call had been terrifying, yes. But also... satisfying. Explaining their team's work, helping customers understand the value, building trust through transparency—it was just another form of problem-solving.

"Fine," Alex said. "But I'm bringing backup. Different team member each time. Customers should know all of us, not just me."

"Look at you, thinking about team visibility," Sarah beamed. "Six weeks and you've gone from lone wolf to team advocate."

"It's logical," Alex said. "Single points of failure are bad architecture."

Everyone laughed, but Alex knew it was more than that. Somewhere between the first standup and this customer call, they'd stopped seeing the team as a burden and started seeing them as a strength multiplier.

Their phone buzzed with another email, this one from the CEO:

"Alex - Heard about the MegaBank call. Excellent work. You're getting a raise, and I'm approving your request for a team offsite. Yes, I know you didn't request one, but Sarah did on your behalf. You're becoming quite the leader. - Tom"

"Team offsite?" Alex asked Sarah.

"Surprise! Two days at a cabin in the mountains. No laptops. Just team building and planning."

Old Alex would have called in sick. New Alex was actually curious.

"Can we at least bring one laptop? For emergencies?"

"No," everyone said in unison.

Alex smiled. "Fine. But if production goes down—"

"Rita's got it covered," Marcus said. "She's automated everything that can be automated."

"And I've got the business stakeholders managed," James added.

"And I'll handle any junior developer questions," Priya said.

"And I'll keep my opinions to myself," Brad added, getting another laugh.

Alex looked around the table at these people who had become more than colleagues. They'd become something Alex had never thought they'd need or want: friends.

"To the team," Alex raised their glass.

"To the customer whisperer," everyone countered.

As they clinked glasses, Alex realized that the most important migration wasn't COBOL to microservices.

It was Alex to human.