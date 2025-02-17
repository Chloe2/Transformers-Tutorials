# Transformers-Tutorials

Hi there!

This repository contains demos I made with the [Transformers library](https://github.com/huggingface/transformers) by 🤗 HuggingFace.

Currently, it contains the following demos:
* BERT: 
  - fine-tuning `BertForTokenClassification` on a named entity recognition (NER) dataset
* LayoutLM: 
  - fine-tuning `LayoutLMForTokenClassification` on the [FUNSD](https://guillaumejaume.github.io/FUNSD/) dataset
* TAPAS: 
  - fine-tuning `TapasForQuestionAnswering` on the Microsoft [Sequential Question Answering (SQA)](https://www.microsoft.com/en-us/download/details.aspx?id=54253) dataset
  - evaluating `TapasForSequenceClassification` on the [Table Fact Checking (TabFact)](https://tabfact.github.io/) dataset

If you have any questions regarding these demos, feel free to open an issue on this repository.

Btw, I was also the [main contributor](https://github.com/huggingface/transformers/pull/9117) to add the TAPAS algorithm by Google AI to the library, so this was an incredible learning experience. I can recommend anyone to contribute an AI algorithm to the library.
