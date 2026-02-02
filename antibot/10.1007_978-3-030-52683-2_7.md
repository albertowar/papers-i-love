---
title: "Web Runner 2049: Evaluating Third-Party Anti-bot Services"
authors: ["Babak Amin Azad", "Oleksii Starov", "Pierre Laperdrix", "Nick Nikiforakis"]
year: 2020
venue: "Detection of Intrusions and Malware, and Vulnerability Assessment (Lecture Notes in Computer Science)"
doi: "10.1007/978-3-030-52683-2_7"
tags: [web, bots, security, bot-detection]
rating: ⭐⭐⭐⭐☆
verdict: "Interesting"
---

## TL;DR
A solid example of how bot detections can be tested and compared between each other. They could have pushed the limit a bit futher on the device setup to make it less recognizable (residential proxies, etc). Certain providers didn't let them use their product so they ended up pivoting to a "black box" approach using a third party site which limits the visibility on what the detections are doing.

## Notes
- Great reference section with a few leads to continue investigating the problem space.


## Thoughts
- I liked the the test evaluation framework for comparing anti-bot solutions.
- I liked the High-level architecture diagram (Figure 1).
- I liked the Fingerprinting and Automation Detection Mechanisms section where it dives deeper into how these detections work.

- I missed a bit more depth on the evaluation. They could have tried to simulate more real world conditions to make it harder for the bot detections to pick up the changes.
- I missed hCaptcha and reCaptcha in the evaluation.