---
license: apache-2.0
base_model: google-bert/bert-base-uncased
tags:
- generated_from_trainer
model-index:
- name: model
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# model

This model is a fine-tuned version of [google-bert/bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased) on the None dataset.
It achieves the following results on the evaluation set:
- eval_loss: 2.1211
- eval_accuracy: 0.6112
- eval_precision: 0.5704
- eval_recall: 0.5609
- eval_f1: 0.5599
- eval_runtime: 16.4845
- eval_samples_per_second: 26.995
- eval_steps_per_second: 3.397
- step: 0

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 8
- eval_batch_size: 8
- seed: 0
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 20

### Framework versions

- Transformers 4.40.1
- Pytorch 2.4.0.dev20240427
- Datasets 2.19.0
- Tokenizers 0.19.1
