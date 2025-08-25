# The Rise of AI Engineering


1. From Language Models → LLMs → AI Engineering

* Language models have existed since the 1950s.

* Progress over decades + self-supervision enabled today’s large language models (LLMs).

* Apps like ChatGPT or Copilot are not sudden inventions — they’re the result of many breakthroughs in modeling language at scale.

2. What is a Language Model?

* A language model predicts how likely a word (or token) is in a given context.

* Example: “My favorite color is __” → “blue” is more likely than “car.”

* Core concept: it encodes the statistical structure of language.

* Rooted in history: Sherlock Holmes (1905) used letter frequency; Claude Shannon (1951) formalized it with entropy.

3. Tokens & Vocabulary

* Tokens = smallest units (character, word, or word part like -ing).

* GPT-4 tokenizes “I can’t wait to build AI applications” into 9 tokens.

* Why use tokens (not words/chars)?
 
* Capture meaning (e.g., “cooking” → “cook” + “ing”).

* Smaller vocabularies = efficiency.

* Handle unknown/new words by breaking them down (e.g., “chatgpting”).

* Vocabulary sizes: Mixtral 8x7B ≈ 32k tokens, GPT-4 ≈ 100k tokens.

4. Two Main Types of Language Models

-> Masked Language Models (MLMs) → fill in blanks.

* Use both before & after context.

* Example: “My favorite __ is blue” → “color.”

* Famous example: BERT.

* Best for non-generative tasks (sentiment analysis, classification, debugging).

-> Autoregressive Language Models (ARLMs) → predict next token.

* Use only previous context.

* Can generate text token by token → basis for ChatGPT, GPT-4, Llama, etc.


* Better suited for generative AI tasks.


5. Generative Nature

* Outputs are open-ended → infinite possible completions.

* LM = “completion machine”: given a prompt, it predicts continuations.

Example:

* Prompt: “To be or not to be” → Completion: “, that is the question.”

*Tasks like translation, summarization, spam detection, coding, math solving can all be reframed as completion problems.

6. Limitations

* Completions are probabilistic predictions — not guaranteed to be correct.

* A completion machine ≠ conversational AI.

* Models sometimes generate irrelevant or wrong outputs until post-training (alignment, reinforcement learning, fine-tuning) makes them user-friendly.










