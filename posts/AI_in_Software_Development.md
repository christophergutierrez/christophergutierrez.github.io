# AI in Software Development: When Help Only Comes If You Don't Need It

## Executive Summary

AI coding assistance is like a bank loan - you can only get help when you don't need it. After extensive coding with ChatGPT, Claude, Copilot, and Replit, I discovered that AI tools are most valuable when you already know what you're doing.

I've watched several YouTubers showing AI building Snake or Tetris. They celebrate when it runs. That may look cool, but that has nothing to do with production development. "Mostly works" is not acceptable. Getting the last "20%" is a lot of work, especially when the quality of "80%" of the code is low.

Those demos skip many essential parts of programming, including error handling, edge cases, documentation, and clean architecture. They're party tricks masquerading as development.

## My Journey with AI Tools

I was an early adopter of AI tools in software development. I subscribed to Copilot and ChatGPT in 2022. I was excited to see how these tools could help me write code faster, generate ideas, and improve my productivity. The tools have greatly improved since then, and I've received a lot of value.
I was surprised to read that a GitClear whitepaper reported they expected code churn (code reverted within two weeks) to double due to AI. I read similar articles authored by people from different companies. The whitepaper didn't match my experience.

### Hypothesis

Since I'd worked with AI early, when it was awful, I unconsiously filtered the results. I didn't even think about some of the terrible code it sometimes generated. I knew what I was doing, so I could ignore the bad suggestions immediately. What if I didn't know what I was doing?

I decided to try AI for something I didn't know well. Front-end development was a perfect candidate. I am a _terrible_ front-end developer. A CSS file here, a JS file there. I am not always clear when something is called. It's not my skill, and since I don't enjoy it or need to do it, I don't spend the time to learn it. I decided to build a simple website using only AI tools.

### Experiment

#### Replit

I've not used Replit much, but websites seemed like a Replit strength. Like a YouTube video, I tried a oneshot approach. It created a site that "worked" but it was a mess. I tried to iterate on it, but it remained a disaster. Since I was relatively new to Replit, I don't know if the problem was me or the tool.

(Note: my site is now hosted on Replilt. It helped a little on the end and made deployment simple.)

#### Copilot, ChatGPT & Claude

I built the website like I would a data pipeline. For pipelines and data science I have an overall design. I know the functions I'll need. I know what formats and libraries they'll need. Copilot does little things like function signatures and obvious loops. ChatGPT and Claude can help with short and simple functions.

I created a simple overall design for my website. Since I know Python well, I chose FastHTML. Though I still need to learn proper front-end fundamentals, I know Python and the AI tools well. It should be easy, right?

My site partially worked hours later, and the code base was unreadable. I felt my time was wasted. Generally, when I work of something unfamiliar, I can see progress. Even if the progress is slow, when not using AI, I begin understanding the problem, the tools, and most importantly, the paradigm of the problem. Over time, things start to make sense. Because I'd become a cut and paste monkey, I learned nothing.

#### Switching Tactics

I took a step back. I read the FastHTML documentation and tried to understand some front-end basics. I used AI to help me learn, before I used it to help me code.

I started over. This time, I looked at the code it gave me and tried to understand it. I assumed AI was wrong and pointed out errors I thought I saw. Sometimes, I was correct, but mostly, I was incorrect, and when AI explained why I was wrong, I learned more quickly than I would have on my own.

The second attepmt went much better. I am still a terrible front-end developer, as anyone can tell from my code. However, I got something that doesn't just "work." I understand it, and I can maintain it. I can even make changes to it. If a talented developer comes along and makes it better, I can examine the differences
and learn from a starting point I understand. It's not patched together, cut and paste code.

### Conclusion

I learned that AI tools are most valuable when you already know what you're doing. They can help you write code faster, generate ideas, and improve your productivity. However, if you don't know what you're doing, AI tools can be more of a hindrance than a help. They can generate code that "works," but is a mess and difficult to maintain. If you're new to a particular area of development, it's better to take the time to learn the fundamentals. AI can help you learn the fundamentals before you try to code. Once you understand the basics, AI tools can help you build on that foundation and take your skills to the next level.

For those wondering how and why I use both ChatGPT and Claude, I'll write a separate article on that.
