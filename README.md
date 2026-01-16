# Transformer Resources
I have provided several resources for learning about transformers.

* **Lecture slides:** _TransformerLecture_, introduce and explain transformers, building from embeddings and generative AI. It covers theory, use, and considerations.
* **Encoder Example:** _BERT_TextClassification.ipynb_, train a DistilBert model to classify text
* **Decoder Example:** _LLMPrompting.ipynb_, that demonstrates methods for prompting LLMs (decoders).
  * Requires the installation of a local LLM, instructions are provided in the notebook. Feel free to point the code at another LLM/API
* **Encoder-Decoder Example:** _T5_Summarization.ipynb_, train a T5 model that summarizes text.

* **LLM Evaluation:**
  * _LLMTesting_NER.ipynb_, that demonstrates methods for testing LLMs (decoders) ability to perform **Named Entity Recognition (NER) tasks** (Understanding).
    * Requires access to the LLM you desire to test (*see decoder installation above*)
    * Testing data is accessed via API
  * _LLMTesting_QandA.ipynb_, that demonstrates methods for testing LLMs (decoders) ability to perform **Question and Answer (Q&A) tasks** (Reasoning).
    * Requires access to the LLM you desire to test. (*see decoder installation above*)
    * Testing data is accessed via API
  * _LLMTesting_Summarization.ipynb_, that demonstrates methods for testing LLMs (decoders) ability to perform **Summarization tasks** (Reasoning and Generation).
    * Requires access to the LLM you desire to test. (*see decoder installation above*)
    * Testing data is accessed via API

Some additional links for exploring word embeddings
* Explanation of transformer architecture with a link to code for exploration: https://jalammar.github.io/illustrated-transformer/
* Visual exploration of Transformer architecture: https://poloclub.github.io/transformer-explainer/
* Another visual exploration of Transformer architecture: https://bbycroft.net/llm
* Tool for visualizing attention weights: https://amanvir.com/gpt-2-attention
