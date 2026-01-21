---
{"dg-publish":true,"permalink":"/building-evolutionary-thoughts/build-your-own-ide-or-why-i-embraced-the-terminal/"}
---


**Convenience makes us lazy.** Yeah, zillions of IDEs with different shapes --all forks of VS Code-- are making us lazy because they hide the machinery.

I decided to move my work entirely to the terminal. I learned Vim, endured the pain, and started using tools like Zellij. And yes, ironically, **I ended up building my own IDE inside the terminal.**

So, what's the point? Why go through the pain just to rebuild what VS Code already gives you?

**It's about ownership.**

When you take the time to craft your own environment, you stop being a passenger and become the mechanic.

1. **Portability:** All my dev setup lives in a GitHub repo. I can deploy my computer on any server in seconds.
2. **Performance:** I choose what runs. No hidden telemetry, no bloat I didn't ask for.
3. **The Mindset Shift:** Visual IDEs are abstractions that hide complexity. When you build your tools via CLI, you are forced to understand what is actually happening when you compile, run, or debug.
4. **Everything at my fingertips:** 
	1. **Do I need to check AWS logs?:** There is a CLI for that. I don't need to navigate a heavy web console; I just query what I need.
	2. **Composable workflows:** I can pipe the output of one tool into another. I can't pipe a button click from a website into my text editor, but I can pipe a curl request directly into a JSON file.


UIs are fine. But **black boxes make us blind.** Don't just consume an IDE; build one that evolves with you.
