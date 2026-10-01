# InfiniAI

The idea: let Gemma 3n answer questions about far more text than fits in its context window, by pairing it with a text embedder that fetches only the passages that matter for each question.

The working version of this ended up in [Mekomi](https://github.com/Shayneg-eng/Mekomi_), an offline study helper that searches your textbooks with `nomic-embed-text` and answers with Gemma 3n, citing page numbers. The code lives there.
