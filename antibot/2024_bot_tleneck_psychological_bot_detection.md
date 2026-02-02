---
title: "Creating a Bot-tleneck for malicious AI: Psychological methods for bot detection"
authors: ["Christopher Rodriguez", "Daniel M. Oppenheimer"]
year: 2024
venue: "Behavior Research Methods"
doi: "10.3758/s13428-024-02357-9"
tags: [bot-detection, AI, psychological-methods]
rating: ⭐⭐⭐☆☆
verdict: "Interesting"
---

## TL;DR
The paper proposes psychological bot detection as a promising alternative to traditional CAPTCHAs, using tasks based on human cognitive strengths such as causal reasoning, semantic associations, learning from feedback, and theory of mind. In experiments, these methods substantially outperform standard approaches like Google reCAPTCHA v3 at detecting bots in real-world data collection settings, revealing that many bots already evade existing defenses.

However, the authors explicitly show that state-of-the-art LLMs (notably GPT-4) can successfully bypass many of these psychological screeners. While GPT-4 performs worse than humans on some tasks, it still passes often enough that these methods cannot be treated as a reliable long-term solution on their own.

The key conclusion is not that psychological methods “solve” bot detection, but that they:

- Raise the cost of malicious automation (creating a temporary bottleneck)
- Are effective against unsophisticated or mass-scale bots
- And buy defenders time in an ongoing arms race

## Notes
They only mentioned GPT towards the end but it seems it sorts of kills their main argument yet they decide to go ahead with the publication anyway.

## Thoughts
- I liked the cognitive science taxonomy of the different question types.

- I missed a consideration for the additional time that takes to solve these cognitive challenges.
- I missed a consideration on whether these challenges could be be failed by real humans at a higher rate and a deeper evaluation including factors like demographics, education, etc.