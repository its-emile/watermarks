# Watermarks for LLMs
Python experiments to add, and detect watermarks in natural language text. I originally outlined this idea in a suggestion to OpenAI in September 2022.

With my initial algorithm, some of the original inspiration came from [markov chain based text steganography by H Moraldo, 2014](https://arxiv.org/abs/1409.0915) using n-grams (before LLMs offered reliable probabilities for next token)

## Relevant (but not used)
- Kirchenbauer et al, 2023
- A more robust implementation (including Reed Solomon error correction) is exciting, available [here](https://github.com/jfairoze/publicly-detectable-watermark)
