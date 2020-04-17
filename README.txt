## Introduction

This directory contains our pytorch implementation of Tensorized Transformer. The code is based on the code( https://github.com/kimiyoung/transformer-xl). Note that our state-of-the-art results reported in the paper were obtained by training the model on a GPU.

## Prerequisite
- Pytorch 1.0.0

## Data Prepration(Language Modeling)

PTB, Wiki-Text-103, One-Billion.

## Training and Evaluation

if run Language Modeling Test in the case of one core, then
bash run_(ptb/wt1o3).sh
if run Language Modeling Test in the case of multiple core, then 
first set the hyperparameter core_nums in the transformer_upload.py file to 2, then run the bash file.

The URL of this paper is "https://papers.nips.cc/paper/8495-a-tensorized-transformer-for-language-modeling.pdf"

@article{ma2019a,
title={A Tensorized Transformer for Language Modeling},
author={Ma, Xindian and Zhang, Peng and Zhang, Shuai and Duan, Nan and Hou, Yuexian and Zhou, Ming and Song, Dawei},
pages={2229--2239},
year={2019}}
    

