# Enhancing Pseudo Label Quality for Semi-Supervised Domain-Generalized Medical Image Segmentation(AAAI 2022)
PyTorch implementation of Enhancing Pseudo Label Quality for Semi-Supervised Domain-Generalized Medical Image Segmentation.
Huifeng Yao, Xiaowei Hu, Xiaomeng Li

Architecture:
- config.py(config file)
- inference_mms.py(inference file for M&Ms dataset)
- inference_scgm.py(inference file for SCGM dataset)
- mms_dataloader.py(dataloader for M&Ms dataset)
- scgm_dataloader.py(dataloader for SCGM dataset)
- mms_train.py(train file for M&Ms dataset)
- scgm_train.py(train file for SCGM dataset)

## Preparation
```
conda env create -f environment.yml
```
### Dependencies

### Datasets

* We followed the setting of [Semi-supervised Meta-learning with Disentanglement for Domain-generalised Medical Image Segmentation](https://arxiv.org/abs/2106.13292).
* We used two datasets in this paper: [Multi-Centre, Multi-Vendor & Multi-Disease Cardiac Image Segmentation Challenge (M&Ms) datast ](https://www.ub.edu/mnms/) and [Spinal cord grey matter segmentation challenge dataset](http://niftyweb.cs.ucl.ac.uk/challenge/index.php)
### preprocessing

We followed the preprocessing of [Semi-supervised Meta-learning with Disentanglement for Domain-generalised Medical Image Segmentation](https://arxiv.org/abs/2106.13292), you can find the preprocessing code [here](https://github.com/xxxliu95/DGNet).

### Environments
We use [wandb](https://wandb.ai/site) to visulize our results.


## How to Run
### Training


## Main Results

## Citation

## License