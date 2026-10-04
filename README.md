# Blogs

Long-form technical writing on ML systems, LLM inference and search ranking. Each post explains how a system works and why it was built that way, in enough detail that you can check the reasoning yourself.

## Posts

### [Does Quantization Make LLMs Faster?](quantization-llm-speed/)

**September 2026 · 20 min read**

FP8 on an H100, worked out from first principles: why prefill and decode each benefit from a different half of what FP8 does, and what that means for time to first token and decode throughput.

`Quantization` `FP8` `LLM Inference` `H100` `GPU Performance`

### [Evolving Search Ranking: From XGBoost to Multi-Task Deep Learning](search-ranking-multi-task-learning/)

**August 2025 · 9 min read · Originally published on the Meesho Tech Blog**

How Meesho's L1 search ranker replaced two XGBoost models with one multi-task network that learns clicks and purchases together, using CGC experts, entire-space training and knowledge distillation from a BERT cross-encoder.

`Search Ranking` `Multi-Task Learning` `Knowledge Distillation` `Learning to Rank` `E-commerce`

---

Found an error or have a question about a post? [Open an issue](https://github.com/HardikLGupta/blogs/issues).
