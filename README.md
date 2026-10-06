# Context management for multi-step retrieval agents with small language models

Agents that search and reason in several steps keep appending retrieved documents, so the input grows and non-evidence sentences can pile up. This project studies what an agent should pass on at each step for a small language model:

- **What to keep:** evidence along a document-graph path, as in [HOPPER-G](https://github.com/sungchul02/HOPPER-G).
- **When to compress:** once the accumulated context exceeds the length the model reads well (see [WHEN-TO-COMPRESS](https://github.com/sungchul02/WHEN-TO-COMPRESS)).

**Status:** planned extension; one pre-pilot so far. Code will be released with the results.

Author: Sungchul Choi, Baekseok University (advisor: Prof. Jin-Keun Hong).
