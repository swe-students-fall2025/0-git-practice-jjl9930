# Article Link

[Article](https://towardsdatascience.com/ai-engineering-and-evals-as-new-layers-of-software-work/)

## Takeaways and notes

1. AI engineering, outside cutting-edge labs, is mostly about shipping software that leverages existing models, not training them from scratch. The job blends product sense, user empathy, and classic SWE concerns with techniques like prompt and context design, RAG, and tool-calling. A central theme is that evaluations are to AI what tests are to software: they catch regressions when you tweak prompts, change retrieval, or swap models, giving teams the confidence to move fast without breaking things—even though evaluation is hard for open-ended tasks and increasingly fluent models.

2. The piece outlines a three-layer stack (application, model, infrastructure) and argues for “eval-driven development." This defines success and measurement up front. It frames evals (evaluations) along quantitative and qualitative dimensions, adds similarity methods, and introduces AI-as-judge for scalable but noisy human proxy scoring. It also emphasizes factual consistency, runtime and memory budgets, and safety. The bottom line is that robust evals are the guardrails that keep AI products reliable and useful as capabilities and complexity grow.

> This repo’s README is public, so I kept it concise and professional.