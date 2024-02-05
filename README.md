# Overview

> We might agree that the operation of LLMs will embed in daily programming in the future. So, we use these notebooks to familiarize ourselves with the LLMs tools ecosystem and quantization techniques.

This project's notebooks are covering the following some of the following tasks:

<div style="text-align: center"><img src="images/LLMs ecosystems-Map 11.png" width="100%" heigh="100%" alt="LLMs tools ecosystem"></div>

Some are not the tasks, but the techniques we used in this project, like:

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


# Kaggle Platform

All these notebooks have been completed running on the [Kaggle](https://www.kaggle.com/aisuko/code) platform. With the free GPUs. Some of the notebooks use a single GPU P100, some of notebooks use double GPU T4x2, others use CPUs.


# Metrics

And you can check the metrics of the fine-tuning in [wandb.ai](https://wandb.ai/causal_language_trainer?shareProfileType=copy). It includes many of useful metrics, like: training, evaling, system power usage, like below:

<div style="text-align: center"><img src="images/The metrics of fine-tuning.png" width="100%" heigh="100%" alt="LLMs tools ecosystem"></div>


# LLMs tools ecosystem

The tools we used in this project are as follows:

<div style="text-align: center"><img src="images/LLMs ecosystems-LLMs ecosystems.png" width="100%" heigh="100%" alt="LLMs tools ecosystem"></div>

See the image's original address [here](https://xmind.ai/share/nEg3GJSn?xid=PK30CWGM) 


# Quantization techniques

The quantization techniques we used in this project are as follows:

<div style="text-align: center"><img src="images/LLMs ecosystems-Weight of Quantization.png" width="100%" heigh="60%" alt="quantization techniques"></div>

See the image's original address [here](https://xmind.ai/share/nEg3GJSn?xid=Ku7E8AEm)


# License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. See the [LICENSE](LICENSE) file for details. 


# Credits

Many of the notebooks are based on blogs on Medium or Huggingface docs etc. Thanks for these great works.
