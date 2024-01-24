# Overview

> We might agree that the operation of LLMs will embed in daily programming in the future. So, we use these notebooks to familiarize ourselves with the LLMs tools ecosystem and quantization techniques.

This project is used to many targets:

* Using PyTorch to build a neural network and train it on the dataset
* Fine-tuning the LLMs for practical tasks
  * LoRA
  * QLoRA
* Quantization of the LLMs
  * AWQ
  * LLM.INT8
  * GPTQ
* Distributed training of the LLMs
  * Multiple GPUs
* REHF
  * Supervised-finetuning
  * PPO
  * DDP

All these notebooks have been completed running on the [Kaggle](https://www.kaggle.com/aisuko/code) platform. With the free GPUs. Some of the notebooks use a single GPU P100, some of notebooks use double GPU T4x2, others use CPUs.


## LLMs tools ecosystem

The tools we used in this project are as follows:

<div style="text-align: center"><img src="images/LLMs ecosystems-LLMs ecosystems.png" width="100%" heigh="100%" alt="LLMs tools ecosystem"></div>

See the image's original address [here](https://xmind.ai/share/nEg3GJSn?xid=PK30CWGM) 


## Quantization techniques

The quantization techniques we used in this project are as follows:

<div style="text-align: center"><img src="images/LLMs ecosystems-Weight of Quantization.png" width="100%" heigh="60%" alt="quantization techniques"></div>

See the image's original address [here](https://xmind.ai/share/nEg3GJSn?xid=Ku7E8AEm)


# Credits

Many of the notebooks are based on blogs on Medium or Huggingface docs etc. Thanks for these great works.
