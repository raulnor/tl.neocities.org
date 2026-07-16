---
date: 2026-06-12
tags: tech
title: "The Fabled LLM"
---

[Fable](https://www.anthropic.com/news/claude-fable-5-mythos-5) launched earlier this week. Fable feels better than Opus message for message. Not a massive jump, but an incremental upgrade. However, there are problems.

<!--more-->

Fable is a neutered version of Mythos. Creating a priesthood people are excluded from is the sort of thing I got into technology to avoid. And the priesthood includes engineers embedded with the NSA, close relationships with [trillion-dollar corporations](https://www.anthropic.com/project/glasswing) with massive security budgets and de-prioritizing [open source maintainers](https://daniel.haxx.se/blog/2026/05/11/mythos-finds-a-curl-vulnerability/).

[Bullshit Bench](https://github.com/petergpt/bullshit-benchmark) measures nonsense detection as a proxy for sycophancy and hallucinations. This is harder to fake than most coding benchmarks. On release day, [Fable scored 29th](https://raw.githubusercontent.com/petergpt/bullshit-benchmark/5fa3f2ce65a224177d5fe35e79ab8cd7dfd52294/docs/images/v2-detection-rate-by-model.png) on a benchmark where versions of Claude hold the entire top 10. The drop in the score stems from a 33% refusal rate. Fable now gives no answer where Opus gave a safe one. Honesty was a core feature [Anthropic PR praised in Opus](https://www.anthropic.com/news/claude-opus-4-8). [RIP](https://raw.githubusercontent.com/petergpt/bullshit-benchmark/5fa3f2ce65a224177d5fe35e79ab8cd7dfd52294/docs/images/v2-detection-rate-over-time.png).

Fable is disappearing from non-token based plans on June 23. After months of hype about a model Anthropic claims they couldn't safely release, users get two weeks to evaluate part of what Mythos can do. Anthropic still wants to bill yearly for the pleasure.

Quality of response is at best inconsistent. Anthropic claims they're falling back to Opus in some cases. Is the quality drop the fallback? Is it a side effect of the neutering? Is it endemic to Fable? Mythos? There's no way to know.

This is the first time I've felt a need to look at local models seriously since Llama 70B. For now, my hardware limits what models I can run and Sonnet/Opus still exist.

**July 10 Update:** After a brief interlude where ["fix this code"](https://www.lutasecurity.com/post/the-fable-5-export-controls-harm-us-cyber-defense) prevented users from accessing Fable, [Fable is neutered even further and Mythos access now requires federal approval](https://www.anthropic.com/news/redeploying-fable-5).
