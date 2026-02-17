---
{"dg-publish":true,"permalink":"/building-evolutionary-thoughts/about-cognitive-load-scaling-systems-vs-scaling-people/"}
---

Think about a distributed system. It has nodes and some sort of communication between them. If the traffic in the system increases, you need a strategy to support that load:
- **Scale Up:** Buy more powerful nodes (more CPU/RAM).
- **Scale Out:** Spin up more of the same nodes based on a scaling policy (assuming your nodes are stateless 👀).
- **Optimize:** Keep the same amount and type of nodes, but really squeeze every CPU cycle by optimizing the code.

The first two are "cheaper" -- they cost money, but you don't have to touch the code. The third cost more engineering brain power and time because you have to change code, run tests, and deploy.

But overall, it is relatively **easy** to scale a distributed system.

> _You cannot do the same with people._


Hey! but **why** can't I do the same with people?

Well, because you can't simply "Scale Up" a human. Unless you find a way to download more neurons or buy a hardware upgrade for a brain, biology is our hard limit.

So, when the workload increases, we are left with only two architectural options for our teams:

**1. Scale Out**

This means hiring more people.
- Unlike deploying a pod in EKS, spinning up a human takes orders of magnitude longer.
- It requires onboarding, context sharing, and ramp-up time.
- It means, using resources from yours existing humans to spin up the new human.
- Plus, as [Brook's Law](https://en.wikipedia.org/wiki/Brooks%27s_law) famously states: _Nine women can't make a baby in one month._ Adding manpower to a late project makes it later. (Assume money isn't an issue here, even though it usually is).

 **2. Optimize**

If we can't upgrade the hardware (brains), we must optimize the processes where those humans are involved in to reduce the **Cognitive Load**. This means automating and creating self-service platforms.
- **Automate repetitive tasks:** Even the really small ones. More automation means less human error, guaranteed repeatability (idempotency), and most importantly, **less cognitive effort** required for daily operations.
- **Make the rest Self-Service:** Some knowledge work, like specific analysis or custom reports, cannot be fully automated. Make them self-service. Build it like a buffet: hand them a plate, and let the stakeholders serve themselves whatever they want from the available options, without interrupting the engineering nodes.

---

**📚 A recent discovery...**

A while after thinking and writing about this, I stumbled upon a book that talks exactly about this mindset: **An Elegant Puzzle: Systems of Engineering Management** by Will Larson.

I am currently reading it, and it aligns with what I've been thinking: viewing teams of people as systems. I'll probably share more notes here as I progress through the chapters!

---