# 🔍 Bias Detection in Text

This is where you can find all the resources we used to build datasets and models for bias detection this summer.

## NER (Token-level)

💻 [Notebook](NER/ner_annotation_pipeline.ipynb) for annotating any dataset with the entities: Generalizations, Unfairness, and Stereotypes.

💻 [Notebook](NER/ner_bert_training.ipynb) for training BERT for multi-label token classification (for nested entities).

## Binary Classification (Sequence-level)

💻 [Notebook](BinaryClassification/bert_bias_binary_training.ipynb) for training BERT to classify entire text sequences with a 0-1 probability of social bias.
