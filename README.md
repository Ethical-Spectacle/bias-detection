# 🔍 Bias Detection in Text

Welcome to [Ethical Spectacle Research](https:/ethicalspectacle.org)'s founding project!!

---

This is where we're publish all the resources we used to build datasets and models for bias detection this summer.

## NER (Token-level)

📝 [Blog post](https://huggingface.co/blog/maximuspowers/bias-entity-recognition) explaining the logic behind our model for identifying socially biased entities at the token level.

💻 [Notebook](ner_annotation_pipeline.ipynb) for annotating any dataset with the entities: Generalizations, Unfairness, and Stereotypes.

💻 [Notebook](ner_bert_training.ipynb) for training BERT for multi-label token classification (for nested entities).

[🚀Try The Model](https://huggingface.co/spaces/maximuspowers/bias-detection-ner) | [Model HF Repo🤗](https://huggingface.co/maximuspowers/bias-detection-ner)

## Binary Classification (Sequence-level)

📝 [Blog post](https://huggingface.co/blog/maximuspowers/bias-detection-in-text) walking through the process of training BERT for binary bias classification.

💻 [Notebook](bert_bias_binary_training.ipynb) for training BERT to classify entire text sequences with a 0-1 probability of social bias.

![Biased text example](hero-pic-smaller.png)

---

## What's Next:

Our paper will be published on Sept 27th!! With it, we'll host a [social bias hackathon](https://ethicalspectacle.org/hackathon?id=8) to see what people build with our final models. 

In the meantime, you should sign up for some a bias detection workshop (phx, az): 

[📅 Intro to NLP, Aug 28, 2024](https://www.meetup.com/ethical-spectacle-research/events/302141069/?eventOrigin=group_events_list) | [📅 Token classification, Sept 11](https://www.meetup.com/ethical-spectacle-research/events/302396840/?eventOrigin=group_events_list)
