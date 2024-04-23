# OptiML Project - Text classification models optimization

## Introduction
This project is a part of the course "Optimization for Machine Learning" at EPFL.
The goal of this project is to classify texts and try to improve our models by using different optimization techniques on transformers models.
For this we will fine-tune a RoBERTa model on a text classification dataset and compare the results of different optimization techniques.

## Data
The data used in this project is the "text-classification-dataset-example" dataset from Hugging Face that can be found [here](https://huggingface.co/datasets/cwchang/text-classification-dataset-example) and imported using the following code:

```python
from datasets import load_dataset

dataset = load_dataset("cwchang/text-classification-dataset-example")
```

## Models
We used the following models in our project:
- RoBERTa (Robustly optimized BERT approach) : we fine-tuned the model on our dataset using our own training loop to see the effect of the optimization techniques on the model.

## Authors
- [Jenane Azza](https://github.com/jenaneAzza)
- [Kathryn Helena Dullerud](https://github.com/kdullerud)
- [Romain Birling](https://github.com/rombirli)
