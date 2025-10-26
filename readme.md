**Hugging Face Chapter 7**

**Introduction**

Ask a Question
In Chapter 3, you saw how to fine-tune a model for text classification. In this chapter, we will tackle the following common language tasks that are essential for working with both traditional NLP models and modern LLMs:

Token classification
Masked language modeling (like BERT)
Summarization
Translation
Causal language modeling pretraining (like GPT-2)
Question answering
These fundamental tasks form the foundation of how Large Language Models (LLMs) work and understanding them is crucial for effectively working with today’s most advanced language models.

To do this, you’ll need to leverage everything you learned about the Trainer API and the 🤗 Accelerate library in Chapter 3, the 🤗 Datasets library in Chapter 5, and the 🤗 Tokenizers library in Chapter 6. We’ll also upload our results to the Model Hub, like we did in Chapter 4, so this is really the chapter where everything comes together!

Each section can be read independently and will show you how to train a model with the Trainer API or with your own training loop, using 🤗 Accelerate. Feel free to skip either part and focus on the one that interests you the most: the Trainer API is great for fine-tuning or training your model without worrying about what’s going on behind the scenes, while the training loop with Accelerate will let you customize any part you want more easily.
