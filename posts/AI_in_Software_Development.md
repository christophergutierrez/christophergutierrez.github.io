# AI in Software Development: When Help Only Comes If You Don't Need It

## Executive Summary

AI coding assistance is like a bank loan - you can only get help when you don't need it. After extensive coding with ChatGPT, Claude, Copilot, and Replit, I discovered that AI tools are most valuable when you already know what you're doing.

I've watched several YouTubers showing AI building Snake or Tetris. They celebrate when it runs. That may look cool, but that has nothing to do with production development. "Mostly works" is not acceptable. Getting the last "20%" is a lot of work, especially when the quality of the code is low.

Those demos skip many essential parts of programming, including error handling, edge cases, documentation, and clean architecture. They're party tricks masquerading as development.

## My Journey with AI Tools

I was an early adopter of AI tools in software development. I subscribed to Copilot and ChatGPT in 2022. I was excited to see how these tools could help me write code faster, generate ideas, and improve my productivity. The tools have improved a great deal since then, and I've received a lot of value.
I was suprised to read a GitClear whitepaper reported they expected code churn (code reverted within two weeks) to double as a result of AI. I read similar articles from authored by different companies. This didn't match my experience.

### Hypothesis

I'd worked with AI early, when it was particularly bad. I didn't even think about all the terrible code it sometimes generated. I knew what I was doing, so I could filter out the bad suggestions immediately. What if I didn't know what I was doing?

I decided to try AI for something I didn't know well. Frontend development was a perfect candidate. I am a _terrible_ frontend developer. A css file here, a js file there. I am not always clear when something is called. It's not my skill, and since I don't enjoy it or need to do it, I don't spend the time to learn it. I decided to build a simple website using only AI tools.

### Experiment

#### Replit

I've not used Replit much, but websites seemed like a Replit strenth. Like a YouTube video, I tried a oneshot approach. It created a site that "worked" but it was a mess. I tried to iterate on it, but it remained a disaster. Since I was relatively new to Replit, I wansn't sure if the problem was me or the tool.

#### Copilot, ChatGPT & Claude

I tried to build the website like I would a data pipelines. For pipelines and data science I have an overal design. I know the functions I'll need. I know what formats and libraries they'll need. Copilot does little things like function signatures and obviuos loops. ChatGPT and Claude can help with short and simple functions. 

I crated a simple overall design for my website. Since I know Python well, I chose FastHTML. Though I still don't know proper frontend fundamentals, I knew Python and the AI tools well. It should be easy, right?

Hours later, my site partially worked, and the code base was unreadable. I felt my time was wasted. Generally, when I work of something unfamiliar, I can see progress. Even if it's slow, I begin understanding the problem, the tools, and most importantly the paradigm of the problem and tools. Things start to make sense. I had none of that. I was a cut and paste monkey.

#### Switching Tactics

I took a step back. I read the FastHTML documentation and tried to understand some frontend basics. I used AI to help me learn, before I used it to help me code. 

I started over. This time I looked at the code it gave me and tried to understand it. I assumed it was wrong, and I'd point out errors I thought I saw. Sometimes I was correct, but mostly I was incorrect, and when it explained why I was wrong, I learned more quickly than I would have on my own.

The second attepmt went much better. I am still a terrible frontend developer, as anyone can tell from my code. However, I got something that doesn't just "work." I understand it, and I can maintain it. I can even make changes to it. If I talented devepoer comes along and makes it better, I can examine the diffs and learn from a starting point I understand.

### Conclusion

I learned that AI tools are most valuable when you already know what you're doing. They can help you write code faster, generate ideas, and improve your productivity. However, if you don't know what you're doing, AI tools can be more of a hindrance than a help. They can generate code that "works," but is a mess and difficult to maintain. If you're new to a particular area of development, it's better to take the time to learn the fundamentals before using AI tools. Once you have a solid understanding of the basics, AI tools can help you build on that foundation and take your skills to the next level.

For those wondering how and why I use both ChatGPT and Claude, I'll write a separate article on that.
