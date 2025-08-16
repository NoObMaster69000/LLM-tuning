# Level 8: Tools & Frameworks

The LLM tuning ecosystem is rich with powerful tools, primarily centered around the Hugging Face platform. This is a quick reference guide to the most important libraries and frameworks you'll encounter.

| Tool | Purpose | Link |
| :--- | :--- | :--- |
| **Hugging Face Transformers** | The core library for everything related to Transformer models. Used for loading models, tokenizers, and running training pipelines. | [transformers](https://huggingface.co/docs/transformers) |
| **PEFT (Parameter-Efficient Fine-Tuning)** | A library that provides easy-to-use implementations of various PEFT methods, including LoRA, QLoRA, IA³, and Adapters. | [peft](https://github.com/huggingface/peft) |
| **TRL (Transformer Reinforcement Learning)** | A library built on top of `transformers` to simplify the process of SFT, RLHF, and DPO. Contains `SFTTrainer` and `DPOTrainer`. | [trl](https://github.com/huggingface/trl) |
| **Bitsandbytes** | The essential library for quantization. It handles the low-level CUDA operations to enable 4-bit and 8-bit model loading and training. | [bitsandbytes](https://github.com/TimDettmers/bitsandbytes) |
| **Accelerate** | A library from Hugging Face that simplifies distributed training across multiple GPUs or TPUs, and handles device placement (`device_map="auto"`). | [accelerate](https://huggingface.co/docs/accelerate) |
| **Datasets** | The standard library for efficiently loading and processing massive datasets for training. | [datasets](https://huggingface.co/docs/datasets) |
| **Unsloth** | A newer library that provides highly optimized kernels for LoRA training, claiming significant speedups (2-10x) and memory reduction compared to the standard implementation. | [unsloth](https://github.com/unslothai/unsloth) |
| **Axolotl** | A powerful, config-driven framework for fine-tuning a wide variety of LLMs. It abstracts away much of the boilerplate code and allows you to define a complex training run in a single YAML file. | [axolotl](https://github.com/OpenAccess-AI-Collective/axolotl) |
| **OpenLLM** | A framework focused on the deployment and serving of LLMs in production environments. It helps you build APIs for your tuned models. | [OpenLLM](https://github.com/bentoml/OpenLLM) |
