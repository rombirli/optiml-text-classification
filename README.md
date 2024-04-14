# OptiML Project - Text classification models optimization

## Introduction
This project is a part of the course "Optimization for Machine Learning" at EPFL.
The goal of this project is to classify texts and try to improve our models by using different optimization techniques.

## Data
The data used in this project is the "text-classification-dataset-example" dataset from Hugging Face that can be found [here](https://huggingface.co/datasets/cwchang/text-classification-dataset-example) and imported using the following code:

```python
from datasets import load_dataset

dataset = load_dataset("cwchang/text-classification-dataset-example")
```

## Models
We used the following models in our project:
- Embedding : BERT (Bidirectional Encoder Representations from Transformers)

## Authors
- [Jenane Azza](https://github.com/jenaneAzza)
- [Kathryn Helena Dullerud](https://github.com/kdullerud)
- [Romain Birling](https://github.com/rombirli)
