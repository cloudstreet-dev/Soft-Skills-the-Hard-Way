# Chapter 6: Meeting the Legend

Dr. Elizabeth Montgomery looked nothing like Alex had imagined. Instead of the stereotypical elderly computer scientist in outdated clothes, she walked into the conference room wearing designer jeans, a vintage MIT hoodie, and sneakers that probably cost more than Alex's monthly rent.

"You must be Alex," she said, extending a hand. "The one who writes commit messages like haikus."

Alex shook her hand, trying not to show their nervousness. "They're getting longer now."

"So I noticed. Sarah's influence?" Dr. Montgomery's eyes twinkled with amusement.

"The team's, actually."

"Ah, even better." She pulled out a laptop that was somehow both ancient and immaculately maintained—a ThinkPad from the early 2000s running what appeared to be a custom Linux distribution.

"Before we dive into COBOL," she said, "tell me why you chose to fix that race condition the way you did."

Alex launched into a technical explanation about mutexes and optimistic locking, but Dr. Montgomery held up a hand.

"No, not the how. The why. You had at least three other solutions. Why that one?"

Alex paused. They'd never really thought about it that way.

"It was... elegant," Alex finally said. "The other solutions would have worked, but they felt like bandages. This one addressed the root cause."

"And?"

"And... Marcus would understand it when he wrote tests. Rita could deploy it without special configuration. James could explain it to the business."

Dr. Montgomery smiled. "There it is. You didn't optimize for the computer. You optimized for the humans. That's the difference between good code and great code."

She opened her laptop and pulled up the original COBOL system.

"Let me tell you a secret," she said. "This system was never supposed to last 30 years. I wrote it as a six-month prototype."

Alex's jaw dropped. "A prototype?"

"The real system was being built by a team of 50 consultants from BigTech Consulting. Million-dollar budget, latest technology, best practices. It failed spectacularly. Meanwhile, my little prototype just kept working, so they put it into production."

She navigated to a file Alex hadn't seen before: `PERSONAL_NOTES.TXT`

"I kept a journal in the code," she explained. "Hidden in plain sight. Read this entry."

```
1994-07-15: The consultants are building something beautiful. Object-oriented, 
distributed, scalable. It crashes if you look at it wrong. Meanwhile, my ugly 
COBOL prototype processed its millionth transaction today. There's a lesson here 
about perfection being the enemy of good enough.

1994-10-22: They want to add multi-currency support. The consultants say it'll 
take six months to redesign their system. I added it to the prototype in three 
days. It's not pretty, but it works. Ship of Theseus paradox: if we keep 
"temporarily" fixing the prototype, when does it become the real system?

1995-01-09: The consultant system failed user acceptance testing. My prototype 
is going live tomorrow. I'm terrified. Note to future self: document everything. 
Future developers will curse your name if you don't.

1995-01-10: We're live. Everything worked. I'm buying the team donuts.
```

Alex scrolled through years of entries, seeing the system evolve through Dr. Montgomery's eyes.

"Why hide these notes?" Alex asked.

"Because honesty is dangerous in corporate environments," she replied. "Admitting uncertainty, documenting failures, showing vulnerability—these things get you labeled as 'not leadership material.' So I hid the human parts in the code, where only other developers would find them."

She pulled up another file, this one showing the complex transaction validation Alex had been struggling with.

"This section here," she pointed, "looks insane, right? Seventeen nested IF statements?"

Alex nodded.

"Each one represents a regulatory requirement that was added over the years. I could have refactored it a dozen times, made it elegant. But every time I tried, I broke some edge case that only happened once a year but would cost millions if it failed."

She leaned back in her chair.

"Sometimes, Alex, the most elegant code is the code that works and that other people can understand, even if it's ugly. Your race condition fix? Elegant and understandable. These nested IFs? Ugly but understandable. Both are correct solutions."

"How do you know when to choose which approach?" Alex asked.

"You ask your team," Dr. Montgomery said simply. "Which is something I never learned to do until too late. I wrote this entire system alone. It's my greatest achievement and my biggest regret."

"Regret?"

"I had a team. Smart people who wanted to help. But I thought I was protecting them from complexity by doing it all myself. Instead, I created a bus factor of one. When I left, nobody understood the whole system."

She pulled up a photo on her phone—a younger version of herself with a team of developers, all smiling at what appeared to be a launch party.

"That's Tom, who tried to help me optimize the transaction engine. I told him I had it handled. He left to join a startup, became a millionaire. That's Lisa, who wanted to pair program with me. I said I worked better alone. She went to Microsoft, runs a whole division now. And that's Carl—"

"Operations Carl?"

"The same. He offered to learn COBOL to help maintain the system. I told him it wasn't necessary, I'd handle everything. So he learned just enough to deploy it, nothing more. For 30 years."

She put the phone away.

"Don't make my mistakes, Alex. Your team isn't a burden to carry. They're your multiplier. The code you write together might be less clever than what you'd write alone, but it'll be understood, maintained, and evolved by everyone."

They spent the next three hours going through the system, but it wasn't the technical deep-dive Alex had expected. Instead, Dr. Montgomery told stories. The time a junior developer found a critical bug she'd missed. The time the CEO wanted a feature that would have broken everything, and how the team talked him out of it. The time she finally admitted she needed help and how liberating it felt.

"One more thing," Dr. Montgomery said as their session wrapped up. "Sarah told me about the production incident. How you asked the team for input instead of just fixing it yourself."

Alex nodded.

"I had a similar incident in 2003. Same root cause, actually—Lunar New Year traffic. I fixed it myself at 3 AM, pushed directly to production, saved the day. Got a bonus and everything."

She paused.

"Nobody learned anything. The same problem happened again in 2005, but I was on vacation. The system was down for six hours because nobody else understood the fix. My heroics had created a dependency."

She stood to leave, then turned back.

"You know what the hardest part of programming is, Alex?"

"Managing complexity?"

"Admitting you're not the smartest person in the room. Even when you are."

She headed for the door, then stopped one more time.

"Oh, and that commit message you wrote after the incident? The one with co-authors? That's the first time in 30 years someone's properly credited the whole team for fixing my system. Thank you for that."

After she left, Alex sat alone in the conference room for a long time, processing everything. Their laptop was open, showing the code they'd been working on. Without thinking, they opened Slack.

**Alex**: Anyone want to pair on the transaction validator refactor? I could use fresh eyes.

Within seconds, responses flooded in:

**Marcus**: Be right there  
**Rita**: Same  
**Priya**: Can I join? Want to learn  
**James**: I'll bring documentation about the business rules

As the team assembled, Alex realized something. Dr. Montgomery hadn't just taught them about COBOL or system design. She'd taught them about the cost of isolation, the value of vulnerability, and the strength that comes from admitting you need help.

"Before we start," Alex said to the gathered team, "I want to document our approach. Not just what we're doing, but why we're doing it and what alternatives we considered."

"Like a decision journal?" Priya asked.

"Exactly. Dr. Montgomery kept one hidden in the code. I think we should keep ours in the open."

Sarah, passing by, overheard and smiled. "That's called an Architecture Decision Record. I'll set up a template."

As the team dove into the code, Alex felt something they'd never experienced before: the joy of shared discovery. Each person brought something different—Marcus's testing perspective, Rita's operational concerns, Priya's fresh questions, James's business context.

The code they produced wasn't just functional. It was a conversation, captured in syntax and logic, between five minds working as one.

It was beautiful in a way Alex's solo code had never been.