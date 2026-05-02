# hallucination-eval

A small Python tool for measuring how often LLM answers contradict their
source material. It runs a few frontier models (Claude, OpenAI, Gemini)
on the HaluEval-QA dataset and scores each answer for faithfulness using
a Natural Language Inference (NLI) model (DeBERTa-MNLI).

## Status

Work in progress. I'm building this in the open as a learning project,
one phase at a time. The full writeup, results, and limitations will
land here once the pipeline runs end to end. For now, see
[`LEARNING_LOG.md`](LEARNING_LOG.md) for what I'm working through.
