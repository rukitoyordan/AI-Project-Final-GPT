# AI Project Final Char-Level GPT
## Fabián Perez Munoz 
## CIIC5015-096 (UPRM)

# FINAL PROJECT – Scaled Dot-Product Attention with Character-Level GPT

# Overview
This project implements a programming component called a Transformer.
- Implement Scaled Dot-Product Attention mechanism (Task 1)
- Assemble a complete character-level generative Transformer (GPT) and train using a text 'corpus'. (Task 2)
- Extend the Transformer to solve a real problem and analyze what was built.

## Create .venv
1. Install pytorch, numpy, and matplotlib (Source: Berkeley AI Course)
```
pip install torch torchvision torchaudio
pip install numpy
pip install matplotlib
```

## models.py
```
python models1.py
```

## gpt_model.py
```
python gpt_model.py
```

## train_gpt.py
```
python train_gpt.py
```

# References:
1) ["minGPT" implemented by Andrej Karpathy](https://github.com/karpathy/minGPT)
2) ["nanoGPT" implemented by Andrej Karpathy](https://github.com/karpathy/nanoGPT/blob/master/data/shakespeare_char/prepare.py)
3) [the official GPT-2 TensorFlow implementation released by OpenAI](https://github.com/openai/gpt-2/blob/master/src/model.py)
4) [huggingface/transformers PyTorch implementation](https://github.com/huggingface/transformers/blob/main/src/transformers/models/gpt2/modeling_gpt2.py)
5) [Berkeley AI course project](https://inst.eecs.berkeley.edu/~cs188/archive/sp25/projects/proj5/)
6) [“Attention Is All You Need” (Vaswani et al.) Submitted on 12 Jun 2017 (v1), last revised 2 Aug 2023 (this version, v7)](https://arxiv.org/abs/1706.03762)
7) [Avatar: The Last Airbender: The Rise of Kyoshi (Chronicles of the Avatar Book 1 by F.C. Yee, 2019)(ISBN: 978-1683355335)](https://archive.org/details/avatar-the-last-airbender-the-f.-c.-yee/mode/2up)


