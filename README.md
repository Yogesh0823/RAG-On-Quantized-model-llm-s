# Retrieval-Augmented Generation (RAG) PROJECT.

## Table of Contents
1. [General Info](#Retrieval-Augmented-Generation (RAG))
2. [Installation](#Installation)

***
* ## Retrieval-Augmented Generation.
1. RAG on Quantized LLM's model using machine learning using FAISS (Facebook AI Similarity Search) vector database.
2. RAG doing on LLM's for bash script for generate text to bash script or shell command using only giving single document of any information.
3. Documnent used in this RAG is CP command you can change you own documnet as your requirements in data folder add your pdf document.
***
# Installation
## clone this repo to your folder.
* open terminal.
  
      $ https://github.com/Yogesh0823/RAG-On-Quantized-model-llm-s.git
      $ cd RAG-On-Quantized-model-llm-s
  
## Download Quantized Model GGUF
* link https://huggingface.co/TheBloke/CapybaraHermes-2.5-Mistral-7B-GGUF/blob/main/capybarahermes-2.5-mistral-7b.Q5_K_M.gguf

## Create Virtule Environment
* open terminal in Resume-detection-of-same-persons folder.
  
      $ python -m venv env_name 
* active virtule environment
  
      $ source/env_name/bin/activate
* install requirement.txt
  
      $ pip install -r requirement.txt
* give model path in rag-model.py file from llm-model directory.
  
## Run vector-db.py for creating vectore-db
     $ python3 vectore-db.py
     
## Run Chainlit Chat Bot.
* before running rag-model.py change your model path.
*     $ chainlit run rag-model.py
    
## Output
![result](https://github.com/Yogesh0823/RAG-On-Quantized-model-llm-s/blob/main/result/Screenshot%20from%202024-03-29%2018-28-56.png)
