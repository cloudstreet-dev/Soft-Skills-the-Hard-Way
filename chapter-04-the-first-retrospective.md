# Chapter 4: The First Retrospective

Friday afternoon. The team gathered in Conference Room B, which someone had optimistically named "Innovation Station" despite its beige walls and fluorescent lighting that made everyone look vaguely ill.

Sarah stood at the whiteboard with three columns: "What Went Well," "What Didn't," and "What We'll Try Next."

"Our first sprint retrospective," she announced. "No laptops. No phones. Just honest conversation."

Alex's laptop remained open. Sarah walked over and gently closed it.

"Withdrawal is normal," she said with a smile. "You'll survive the next hour."

"Let's start with what went well," Sarah continued. "And please, be specific. No generic 'good teamwork' platitudes."

Silence stretched uncomfortably.

"Fine, I'll start," Rita said. "Alex actually asked me about deployment requirements before writing code. That's never happened before in my five years here."

Alex felt their face warm. Praise was deeply uncomfortable.

"Marcus caught three edge cases I would have missed," Alex admitted quietly. "The payment validation on Korean holidays was... clever."

Marcus beamed. "You refactored my test code without being asked. It's so much cleaner now."

"James translated a 400-page federal regulation into a two-page decision tree," Rita added. "I actually understood it."

Sarah was writing furiously, capturing everything.

"Now, what didn't go well?" she asked. "And remember, we're critiquing processes, not people."

"The COBOL system crashed on Wednesday," James said. "Turns out someone needs to manually clear a log file every week or it fills up the disk."

"That's insane," Alex said.

"That's technical debt," Sarah corrected. "What else?"

"Pair programming is exhausting," Alex said, surprising themselves with the honesty. "I need alone time to think."

Sarah wrote it down without judgment. "What else?"

"The stand-ups are too early," someone mumbled from the back.

"Who said that?" Sarah asked. "Own your feedback."

A junior developer Alex had never noticed before raised her hand. "Me. Priya. I have a forty-minute commute. Getting here by 8 AM means leaving at 6:50."

"Valid point," Sarah said, adding it to the board. "What else?"

The floodgates opened. The CI/CD pipeline was held together with shell scripts and prayer. The test environment didn't match production. Half the team didn't know how to read COBOL, and the other half didn't know the new microservices architecture.

"Excellent," Sarah said when the complaints finally stopped. "Now, what will we try next sprint?"

"Can we move stand-up to 9?" Priya asked hopefully.

"8:30," Sarah compromised. "But we'll make it 15 minutes max. If you're late, you're bringing donuts. Deal?"

Nods around the room.

"What about the pair programming exhaustion?" Sarah asked, looking at Alex.

"Maybe... we could have 'focus time' blocks?" Alex suggested. "Like, mornings for pairing, afternoons for solo work?"

"I like it," Marcus said. "I need solo time too, honestly. Talking all day is draining."

Sarah added it to the "Try Next" column.

"Now for the elephant in the room," Sarah said. "Who's going to tell Carl from Operations that we need him to teach us the deployment process?"

Everyone looked at their shoes.

"I'll do it," Alex said, shocking the room. "He helped me once, two years ago. Debug a production issue. He'll remember."

Sarah's eyebrows rose slightly. "Alex volunteering for human interaction. I'm writing this down."

The room laughed, and Alex found they didn't mind.

"One more thing," Sarah said. "I've been watching you all week. You're becoming a team. Not just a group of people who happen to work on the same project, but an actual team. You cover for each other, you share knowledge, you've started eating lunch together."

"That's because Alex discovered Marcus makes incredible Thai food," Rita said.

"You cook?" James asked Marcus.

"My grandmother owned a restaurant in Bangkok," Marcus shrugged. "I'll bring pad thai Monday if someone else brings dessert."

"I bake," Priya said quietly. "Stress relief. I made too many cookies last night."

"Bring them," everyone said simultaneously.

Sarah smiled. "This is what I'm talking about. You're connecting as humans, not just engineers. That's how great teams are built."

She grabbed a red marker and added one more thing to the "What Went Well" column: "We started caring about each other."

"Cheesy," Alex muttered, but they were smiling.

"Speaking of caring," Sarah said, "I have an announcement. Dr. Montgomery agreed to come next Friday. She's doing a full day workshop on the COBOL system's history and architecture."

The room buzzed with excitement.

"Alex, she specifically wants to have lunch with you. One on one."

Alex's stomach dropped. "Why?"

"She said, and I quote, 'Anyone who can find and fix a race condition at 3 AM understands something about systems thinking that can't be taught. I want to meet them.'"

"That's terrifying," Alex said.

"That's an opportunity," Sarah corrected. "Dr. Montgomery doesn't just know COBOL. She invented three of the algorithms we still use in production. She has two patents on distributed transaction processing. And she chose to meet you."

The meeting wound down with action items and sprint planning for next week. As people filed out, Sarah caught Alex's arm.

"You did good today," she said. "Opening up about needing alone time, volunteering to talk to Carl. That took courage."

"It felt... necessary," Alex said, unable to articulate the shift they felt.

"Growth usually does," Sarah replied. "See you Monday. And Alex? Write a better commit message. Your future self will thank you."

Walking back to their desk, Alex found a sticky note from Marcus: "Your code review caught a SQL injection vulnerability I missed. You saved us from a security nightmare. Thank you. - M"

Alex stared at the note for a long moment, then carefully placed it next to their monitor. Their first instinct was to throw it away—praise was uncomfortable, physical reminders even more so. But something made them keep it.

At 5:47 PM, Alex did something unprecedented: they left the office while others were still working. Not because the code was perfect, not because there were no more problems to solve, but because they'd promised themselves to try this "work-life balance" thing Sarah kept mentioning.

In the elevator, they met Priya heading out.

"Hey," she said. "Thanks for backing me up about the meeting time."

"It was logical," Alex replied. "Tired developers make more mistakes."

"Still. You didn't have to speak up. Most seniors don't care about junior developer problems."

Alex didn't know how to respond to that, so they just nodded.

"See you Monday," Priya said. "I'll bring those cookies. They're chocolate chip with sea salt."

"I'll... look forward to that," Alex said, meaning it.

The drive home felt different. The usual mental replay of code and algorithms was interrupted by thoughts of people. Marcus's insight about test cases. Rita's deployment expertise. James's ability to translate complexity. Priya's courage to speak up. Sarah's leadership style that somehow made vulnerability feel safe.

At home, Alex opened their laptop to work on side projects but found themselves instead typing a new commit message for last night's fix:

```
Fix: Resolve race condition in payment processing system

Problem: Concurrent transactions could result in duplicate charges when 
processing failed payments between 2-4 AM due to batch job interference.

Solution: Implemented optimistic locking with exponential backoff. Added 
transaction ID validation to prevent duplicates. Wrapped critical section 
in mutex with timeout.

Testing: Added unit tests for concurrent scenarios. Verified with 10,000 
simulated transactions. No duplicates detected.

Note: This edge case only occurred during the batch processing window. 
Consider moving batch jobs to avoid transaction peaks.
```

It was the longest commit message Alex had ever written.

It felt right.