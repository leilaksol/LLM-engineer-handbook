# LLM-engineer-handbook
🔥 Large Language Models(LLM) have taken the ~~NLP community~~ ~~AI community~~ **the Whole World** by storm. 
The LLM space is complicated! This repo provides a curated list to help you navigate; it includes a collection of Large Language Model frameworks and tutorials, covering model training, serving, fine-tuning, and building LLM applications.

## Table of Content

- [Applications](#applications)
- [Pretraining](#pretraining)
- [Fine-tuning](#fine-tuning)
- [Serving](#serving)
- [Datasets](#datasets)
- [Benchmarks](#benchmarks)
- [Learn LLM Applications](#learn-llm-applications)
- [Understand LLM](#understand-llm)
- [Social Accounts](#social-accounts)

## Applications

**Build & Auto-optimize**

- [AdalFlow](https://github.com/SylphAI-Inc/AdalFlow) - The library to build & auto-optimize LLM applications, from Chatbot, RAG, to Agent. It is AI-first with PyTorch-like design patterns.

- [dspy](https://github.com/stanfordnlp/dspy) - DSPy: The framework for programming—not prompting—foundation models.

**Build**

- [LlamaIndex](https://github.com/jerryjliu/llama_index) — A Python library for augmenting LLM apps with data.
- [LangChain](https://github.com/hwchase17/langchain) — A popular Python/JavaScript library for chaining sequences of language model prompts.

**Prompt Optimization**

- [AutoPrompt](https://github.com/Eladlev/AutoPrompt) - A framework for prompt tuning using Intent-based Prompt Calibration
- [PromptFify](https://github.com/promptslab/Promptify) - A library for prompt engineering that simplifies NLP tasks (e.g., NER, classification) using LLMs like GPT.

**Others**

- [LiteLLM](https://github.com/BerriAI/litellm) - Python SDK, Proxy Server (LLM Gateway) to call 100+ LLM APIs in OpenAI format.


## Pretraining

- [PyTorch](https://pytorch.org/) - PyTorch is an open source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing.
- [TensorFlow](https://www.tensorflow.org/) - TensorFlow is an open source machine learning library developed by Google.
- [JAX](https://github.com/jax-ml/jax) - Google’s library for high-performance computing and automatic differentiation.
- [tinygrad](https://github.com/tinygrad/tinygrad) - A minimalistic deep learning library with a focus on simplicity and educational use, created by George Hotz.
- [micrograd](https://github.com/karpathy/micrograd) - A simple, lightweight autograd engine for educational purposes, created by Andrej Karpathy.
## Fine-tuning

- [Transformers](https://huggingface.co/docs/transformers/en/installation) - Hugging Face Transformers is a popular library for Natural Language Processing (NLP) tasks, including fine-tuning large language models.
- [Unsloth](https://github.com/unslothai/unsloth) - Finetune Llama 3.2, Mistral, Phi-3.5 & Gemma 2-5x faster with 80% less memory!
- [LitGPT](https://github.com/Lightning-AI/litgpt) - 20+ high-performance LLMs with recipes to pretrain, finetune, and deploy at scale.

## Serving

- [TorchServe](https://pytorch.org/serve/) - An open-source model serving library developed by AWS and Facebook specifically for PyTorch models, enabling scalable deployment, model versioning, and A/B testing.

- [TensorFlow Serving](https://www.tensorflow.org/tfx/guide/serving) - A flexible, high-performance serving system for machine learning models, designed for production environments, and optimized for TensorFlow models but also supports other formats.

- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) - Part of the Ray ecosystem, Ray Serve is a scalable model-serving library that supports deployment of machine learning models across multiple frameworks, with built-in support for Python-based APIs and model pipelines.

- [NVIDIA Triton Inference Server](https://developer.nvidia.com/triton-inference-server) - A high-performance inference server supporting multiple ML/DL frameworks (TensorFlow, PyTorch, ONNX, etc.), optimized for GPU deployments, and ideal for both cloud and on-premises serving.

- [vllm](https://github.com/vllm-project/vllm) - An optimized, high-throughput serving engine for large language models, designed to efficiently handle massive-scale inference with reduced latency.

- [sglang](https://github.com/sgl-project/sglang) - SGLang is a fast serving framework for large language models and vision language models.

- [LitServe](https://github.com/Lightning-AI/LitServe) - LitServe is a lightning-fast serving engine for any AI model of any size. Flexible. Easy. Enterprise-scale.

## Datasets

Use Cases

- [Datasets](https://huggingface.co/docs/datasets/en/index) - A vast collection of ready-to-use datasets for machine learning tasks, including NLP, computer vision, and audio, with tools for easy access, filtering, and preprocessing.
- [Argilla](https://github.com/argilla-io/argilla) - A UI tool for curating and reviewing datasets for LLM evaluation or training.
- [distilabel](https://distilabel.argilla.io/latest/) - A library for generating synthetic datasets with LLM APIs or models.

Fine-tuning

- [LLMDataHub](https://github.com/Zjh-819/LLMDataHub) - A quick guide (especially) for trending instruction finetuning datasets
- [LLM Datasets](https://github.com/mlabonne/llm-datasets) - High-quality datasets, tools, and concepts for LLM fine-tuning.

Pretraining

- [IBM LLMs Granite 3.0](https://www.linkedin.com/feed/update/urn:li:activity:7259535100927725569?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7259535100927725569%2CFEED_DETAIL%2CEMPTY%2CDEFAULT%2Cfalse%29) - Full list of datasets used to train IBM LLMs Granite 3.0

## Benchmarks

- [lighteval](https://github.com/huggingface/lighteval) - A library for evaluating local LLMs on major benchmarks and custom tasks.

Agent

- [TravelPlanner](https://osu-nlp-group.github.io/TravelPlanner/) - [paper](https://arxiv.org/pdf/2402.01622) A Benchmark for Real-World Planning with Language Agents

## Understand LLM

Prompt Engineering

- [Brown, Tom B. "Language models are few-shot learners." arXiv preprint arXiv:2005.14165 (2020).](https://rosanneliu.com/dlctfs/dlct_200724.pdf)

Reasoning & Planning

- [Kambhampati, Subbarao, et al. "LLMs can't plan, but can help planning in LLM-modulo frameworks." arXiv preprint arXiv:2402.01817 (2024).](https://arxiv.org/abs/2402.01817)

## Learn LLM

### Training

- [Chip's Blog](https://huyenchip.com/blog/) - Chip Huyen's blog on training LLMs, including the latest research, tutorials, and best practices.
- [Lil'Log](https://lilianweng.github.io/) - Lilian Weng(OpenAI)'s blog on machine learning, deep learning, and AI, with a focus on LLMs and NLP.

### Applications

#### General

- [AdalFlow documentation](https://adalflow.sylph.ai/) - Includes tutorials from building RAG, Agent, to LLM evaluation and fine-tuning.

- [CS224N](https://www.youtube.com/watch?v=rmVRLeJRkl4) - Stanford course covering NLP fundamentals, LLMs, and PyTorch-based model building, led by Chris Manning and Shikhar Murty.

- [LLM-driven Data Engineering](https://github.com/DataExpert-io/llm-driven-data-engineering) -  A playlist of 6 lectures by [Zach Wilson](https://www.linkedin.com/in/eczachly) on how LLMs will impact data pipeline development 

- [LLM Course by Maxime Labonne](https://github.com/mlabonne/llm-course) - An end-to-end course for AI and ML engineers on open source LLMs.

#### Agent

1. Lectures

- [LLM Agents MOOC](https://youtube.com/playlist?list=PLS01nW3RtgopsNLeM936V4TNSsvvVglLc&si=LAonD5VfG9jFAOuE) - A playlist of 11 lectures by the Berkeley RDI Center on Decentralization & AI, featuring guest speakers like Yuandong Tian, Graham Neubig, Omar Khattab, and others, covering core topics on Large Language Model agents.

2. Projects

- [CAMEL](https://github.com/camel-ai/camel) - First LLM multi-agent framework and an open-source community dedicated to finding the scaling law of agents. by [CAMEL-AI](https://www.camel-ai.org/).
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Open source agents for developers by [AllHands](https://www.all-hands.dev/).

## Social Accounts

- [Chip Huyen](https://www.linkedin.com/in/chiphuyen)
- [Damien Benveniste, PhD](https://www.linkedin.com/in/damienbenveniste/)
- [Jim Fan](https://www.linkedin.com/in/drjimfan/)
- [Li Yin](https://www.linkedin.com/in/li-yin-ai)
- [Paul Iusztin](https://www.linkedin.com/in/pauliusztin/) LLMOps
- [Armand Ruiz](https://www.linkedin.com/in/armand-ruiz/) AI product at IBM
- [Pascal Biese](https://www.linkedin.com/in/pascalbiese/) Daily LLM papers
- [Maxime Labonne](https://www.linkedin.com/in/maxime-labonne/) LLM fine-tuning



## Contributing

This is an active repository and your contributions are always welcome!

I will keep some pull requests open if I'm not sure if they are not an instant fit for this repo, you could vote for them by adding 👍 to them.

---

If you have any question about this opinionated list, do not hesitate to contact [Li Yin](https://www.linkedin.com/in/li-yin-ai)




