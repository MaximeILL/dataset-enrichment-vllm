# Efficient Dataset Enrichment using vLLM

This repository contains a notebook using generative models to enrich large datasets with efficient batch inference with vLLM.

## Description

- Dataset enrichment with generative models  
- Parallel inference across multiple GPUs  
- Large-scale batch processing  
- Built-in error handling and results logging  
- Customizable for different use cases according to user needs

## Installation

* Clone the repository :

```bash
git clone https://github.com/MaximeILL/dataset-enrichment-vllm.git
```

* Navigate to the directory :
  
```bash
cd dataset-enrichment-vllm
```

* Install the dependencies :
  
```bash
pip install -r requirements.txt
```

## Usage

To use the notebook, you should specify :  

1. Your model path (default example uses a local Qwen2-VL)  
2. Your dataset from Hugging Face hub
3. Your custom prompt based on your model and use case


*Note : The prompt format in the example is specific to Qwen2-VL model. Make sure to adapt the prompt template according to your chosen model's documentation*

## Ressources

* https://docs.vllm.ai/en/latest/getting_started/installation.html
