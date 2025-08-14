# Chapter 10: The Mentee

"Absolutely not," Alex said for the third time. "I don't do mentoring."

Sarah's new office—she'd gotten a promotion and a corner suite after the MegaBank deal—had floor-to-ceiling windows that made Alex slightly dizzy.

"It's just for the summer," Sarah said patiently. "Three months. One intern."

"I can barely manage human interaction with people who know what they're doing. An intern? That's like giving me a puppy that can delete production databases."

"Interns don't have production access."

"They'll find a way. They always do."

Sarah pulled up a resume on her screen. "Jordan Kim. Senior at UW. Double major in Computer Science and Philosophy. Published a paper on ethical AI. GPA: 3.9."

"Philosophy?" Alex said with disdain. "What's next, interpretive dance?"

"Their GitHub has 200 repositories. They've contributed to TensorFlow."

Alex paused. That was actually impressive.

"Why me? Brad loves teaching. Marcus is patient. Rita actually likes people."

"Because Jordan specifically asked to work with you. They read your blog post about the race condition fix."

"I didn't write a blog post."

"The one I made you write last month. It has 10,000 views and made it to the front page of Hacker News."

Alex had blocked that traumatic experience from memory.

"Jordan said, and I quote, 'Alex Chen approaches problems with a clarity that cuts through conventional wisdom. I want to learn to think like that.'"

"They want to think like me? That's a terrible life choice."

Sarah leaned forward. "Six months ago, you would have been right. But you're not that person anymore. You collaborate. You mentor without realizing it—you've been teaching Priya advanced algorithms for weeks."

"That's different. Priya's competent."

"So is Jordan. Give them a chance. One week trial. If it's a disaster, I'll reassign them."

Monday morning, Jordan arrived like a hurricane of enthusiasm. They were younger than Alex expected, with bright purple hair, a laptop covered in programming language stickers, and an energy level that should be illegal before noon.

"Alex Chen! I'm Jordan! I've read all your code! Your solution to the distributed transaction problem is genius! Can you explain the Byzantine fault tolerance approach? Also, why did you choose eventual consistency over strong consistency? And—"

"Stop," Alex said, already exhausted. "First rule: one question at a time."

"Sorry! I'm just excited. Where do I sit?"

Alex pointed to the desk next to theirs, which had been empty since the last developer fled to a quieter team.

"Second rule: no talking before I've had coffee. Third rule: read the code before asking questions. Fourth rule: Google first, ask second."

Jordan pulled out a notebook and started writing this down. With a fountain pen. Who used fountain pens?

"What's the fifth rule?" Jordan asked.

"There is no fifth rule. I'll make them up as you annoy me."

"Cool! I mean, understood. Should I start by reading the codebase?"

Alex pulled up the repository. "Start with the transaction validator. Understand it completely. Then tell me three ways to improve it."

Jordan dove in with an intensity that reminded Alex of themselves. For blessed hours, there was silence except for keyboard clicks and Jordan's occasional muttering.

At lunch, instead of disappearing like Alex hoped, Jordan appeared with questions.

"The validator has seventeen nested conditions, but they could be refactored into a strategy pattern with—"

"Stop," Alex said. "Who taught you about strategy patterns?"

"Design Patterns by the Gang of Four. I've read it three times."

Alex suppressed a groan. "Forget everything in that book. It was written when object-oriented programming was the answer to everything. Now tell me why the nested conditions exist."

Jordan looked confused. "Because... the code evolved over time?"

"Because each condition represents a federal regulation. Refactor them into a pattern and you lose the one-to-one mapping between code and law. When regulators audit us, we can point to exact lines that implement their requirements."

Jordan's eyes widened. "Oh. The code structure is documentation."

"Now you're learning. Try again."

The week progressed with Jordan making mistakes and Alex correcting them with decreasing irritation. Jordan had good instincts but, like young Alex, prioritized cleverness over clarity.

"Why did you use a recursive function here?" Alex asked, reviewing Jordan's code.

"It's elegant! Look, the entire algorithm in five lines!"

"Rita would have to special-case this in deployment because it might blow the stack. Marcus would need twenty test cases to cover all branches. James would spend an hour explaining to auditors what recursion is. Is your five-line solution worth thirty hours of other people's time?"

Jordan deleted the code and started over without complaint.

Thursday brought the first real test. A bug in the payment processor that Alex would normally handle alone.

"We're pair programming this," Alex announced, surprising themselves.

"Really? On production code?"

"You'll never learn debugging from textbooks. Sit. Type what I say. Ask questions when confused."

They worked through the problem together, Alex guiding Jordan through log analysis, hypothesis formation, and systematic elimination of possibilities.

"There!" Jordan said suddenly. "Race condition between the cache invalidation and the database write!"

"How do you fix it?"

Jordan's fingers flew across the keyboard, implementing exactly the solution Alex would have chosen. The tests went green.

"Good," Alex said, and Jordan beamed like they'd won a Nobel Prize.

Friday afternoon, Sarah stopped by their desks.

"How's it going?" she asked.

"Jordan found and fixed a production bug," Alex said. "With minimal supervision."

"It was mostly Alex," Jordan said quickly. "They taught me to look at the whole system, not just the code."

Sarah smiled. "Sounds like a successful week. Jordan, you're officially on Alex's team for the summer."

After Sarah left, Jordan turned to Alex. "Can I ask you something personal?"

Alex tensed. "You can ask."

"Why do you separate yourself from everyone? You're brilliant, but you act like human connection is poison."

Alex was quiet for so long Jordan started to apologize, but Alex held up a hand.

"I wasn't always like this. In college, I had friends. A girlfriend. A social life. Then I got my first job at a startup. Eighty-hour weeks. I cancelled plans, missed birthdays, lost relationships. But the code got better. I got promotions. Success felt like validation that isolation was worth it."

"Was it?"

"I thought so. Until six months ago when Sarah forced me to work with the team. Turns out, I wasn't a better programmer alone. I was just lonelier."

Jordan absorbed this. "So you changed?"

"I'm changing. Present tense. It's hard. Some days I still want to put on headphones and pretend other people don't exist. But then Marcus makes me laugh, or Priya asks for algorithm help, or Rita explains some deployment magic, and I remember that other people make the work better."

"Is that why you agreed to mentor me? Because Sarah made you?"

"Initially. But you remind me of myself at your age. Brilliant and stupid in equal measure."

"Hey!"

"You tried to implement a distributed cache using blockchain yesterday."

"It would have worked!"

"It would have been a disaster. But you'll learn. Hopefully faster than I did."

Monday of week two, Jordan brought coffee for both of them, having memorized Alex's exact order. They'd also read the entire codebase over the weekend and had intelligent questions about architectural decisions.

"You don't have weekends?" Alex asked.

"Neither do you. I saw your commits from Saturday."

"That's different. I have no life."

"Maybe I don't either."

Alex studied Jordan more carefully. The enthusiasm might be masking something else.

"When's the last time you did something that wasn't coding?" Alex asked.

Jordan looked uncomfortable. "Does reading about coding count?"

"No."

"Then... a while."

Alex made a decision that would have shocked them weeks ago.

"New rule. No coding on weekends. Either of us."

"But—"

"Marcus plays guitar. Rita rock climbs. James cooks. Priya reads fiction. Brad volunteers. Sarah does yoga. Even I learned to hike. Find something."

"What if I'm bad at it?"

"Perfect. Being bad at something teaches humility. I'm terrible at hiking. Still do it."

That afternoon, during code review, Jordan made an observation that stopped Alex cold.

"This authentication logic... it's beautiful. But it's also wrong."

Alex looked closer. Jordan was right. A subtle logic error that would only manifest under specific conditions, but it was definitely there.

"How did you spot that?"

"Philosophy major, remember? I'm good at logical proofs. This code claims A implies B, but there's a case where A is true and B is false."

Alex fixed the bug, then added Jordan as co-author on the commit.

"You didn't have to credit me," Jordan said.

"You found it. Credit goes where credit's due. The team taught me that."

As the weeks passed, Jordan integrated into the team. They pair-programmed with Marcus, learned deployment from Rita, absorbed business context from James. But they always returned to Alex's desk with new insights.

"You're getting good," Alex said one afternoon, reviewing Jordan's code. "Too good. You're going to take my job."

"Never," Jordan said seriously. "You're not just teaching me to code. You're teaching me to think about coding. About systems. About people."

"I'm barely qualified to teach about people."

"You're teaching by example. Six weeks ago, would you have eaten lunch with the team?"

Alex realized they'd been eating with the group every day without thinking about it.

"Point taken."

The summer flew by. Jordan's final project was implementing Priya's idea—a simplified insulin management system prototype. The presentation to the team was flawless.

"This is production-ready," Brad said, impressed.

"It's not," Jordan corrected. "Alex taught me the difference between working code and production code. This needs error handling, monitoring, deployment infrastructure, and about a thousand test cases."

"But it's a start," Priya said, eyes shining. "We could actually build this."

On Jordan's last day, the team threw a small party. Alex had even contributed to the planning, suggesting Jordan's favorite cake flavor (chocolate with raspberry, gleaned from weeks of observation).

"I have something for you," Jordan said, handing Alex a wrapped package.

It was a fountain pen. Expensive-looking, with "Rule #1: One question at a time" engraved on it.

"For your commit messages," Jordan explained. "Though they're already pretty good now."

Alex was surprised to feel emotional. "Thank you. For the pen. And for reminding me why I loved programming before I forgot about the people."

"Will you write me a recommendation letter for grad school?"

"Already done. Sent it yesterday. You're going to do great things, Jordan."

As Jordan left, Sarah appeared at Alex's desk.

"You know you're a natural teacher, right?" she said.

"I'm really not."

"Jordan just told me they're changing their thesis topic to 'Human Factors in System Design' because of what they learned from you."

Alex didn't know what to say to that.

"Next summer, you get two interns," Sarah said with a grin.

"That's cruel and unusual punishment."

"That's growth. Deal with it."

That evening, Alex got a text from Jordan: "Thank you for everything. You taught me the most important lesson: code is for computers, but software is for people."

Alex saved the message. Then they opened their laptop and started writing a blog post: "What I Learned from Teaching: A Mentor's Journey."

The first line: "I used to think mentoring would make me a worse programmer. I was wrong. It made me a better human."