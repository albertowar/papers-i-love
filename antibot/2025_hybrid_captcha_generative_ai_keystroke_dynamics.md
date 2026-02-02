---
title: "A Hybrid CAPTCHA Combining Generative AI with Keystroke Dynamics for Enhanced Bot Detection"
authors: ["Alex Johnson", "Maria Lee", "Hiroshi Tanaka"]
year: 2025
venue: "arXiv preprint"
doi: "10.48550/arXiv.2510.02374"
tags: [security, bot-detection, AI, CAPTCHA]
rating: ⭐⭐☆☆☆
verdict: "Low Signal"
---

## TL;DR
This paper presents a new type of CAPTCHA that mixes AI-generated questions with checks on how you type (keystroke patterns) to tell humans and bots apart. Humans can answer the questions normally, but bots are caught if they paste answers or type unnaturally. Tests show it’s easy for people to use while stopping most automated bots.

## Notes
Thea implementation seems a bit brittle since people may type semantically good answers in different ways and that will fail the hash.

Using keystroke dynamics is not necessarily new and can now be easily replicated by bots.

## Thoughts
- I like its potential for a fun project for university students to learn about bot detection.

- I didn't like that the use of AI here felt a bit buzzwordy. It doesn't really explain why this is better than any other hardcoded questions or considers the additional cost of using LLMs for this at scale.