## Dataset
This repo has a paired chart image and table. The source of this dataset is [https://huggingface.co/datasets/chiragtubakad/chart-to-table-mix](https://huggingface.co/datasets/chiragtubakad/chart-to-table-mix).

---
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
dataset_info:
  features:
  - name: image
    dtype: image
  - name: text
    dtype: string
  splits:
  - name: train
    num_bytes: 39979829.0
    num_examples: 990
  download_size: 33926492
  dataset_size: 39979829.0
---
# Dataset Card for "chart-to-table"

[More Information needed](https://github.com/huggingface/datasets/blob/main/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)# chiragtubakad-chart-to-table
