# 🔍 Bias Detection in Text

Welcome to [Ethical Spectacle Research](https:/ethicalspectacle.org)'s founding project!!

---

This is where we're publish all the resources we used to build datasets and models for bias detection this summer.

## NER (Token-level)

📝 [Blog post](https://huggingface.co/blog/maximuspowers/bias-entity-recognition) explaining the logic behind our model for identifying socially biased entities at the token level.

💻 [Notebook](NER/ner_annotation_pipeline.ipynb) for annotating any dataset with the entities: Generalizations, Unfairness, and Stereotypes.

💻 [Notebook](NER/ner_bert_training.ipynb) for training BERT for multi-label token classification (for nested entities).

[🚀Try The Model](https://huggingface.co/spaces/maximuspowers/bias-detection-ner) | [Model HF Repo🤗](https://huggingface.co/maximuspowers/bias-detection-ner)

## Binary Classification (Sequence-level)

📝 [Blog post](https://huggingface.co/blog/maximuspowers/bias-detection-in-text) walking through the process of training BERT for binary bias classification.

💻 [Notebook](BinaryClassification/bert_bias_binary_training.ipynb) for training BERT to classify entire text sequences with a 0-1 probability of social bias.
