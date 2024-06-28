# LLM

A repository dedicated to various implementations of Large Language Models (LLM). This repository includes examples and techniques integrating LLM with other advanced technologies such as Retrieval-Augmented Generation (RAG). Ideal for researchers and developers looking to explore and innovate in the field of natural language processing and AI.

## Contents

- **RAG_LLaMA3.ipynb**: This notebook demonstrates an implementation of Retrieval-Augmented Generation (RAG) using LLaMA3 and LangChain. It showcases how to create a RAG system that leverages the LLaMA3 model to provide accurate and contextually relevant responses by integrating with a retrieval system. This implementation is useful for applications requiring enhanced information retrieval capabilities combined with language model generation.
  [![Colab](https://img.shields.io/badge/Colab-RAG_LLaMA3-orange)](https://colab.research.google.com/github/brritany/LLM/blob/main/jupyternotebook/RAG_LLaMA3.ipynb)

  ### Key Features:
  - **Contextual Relevance**: Integrates a retrieval system to provide contextually relevant responses.
  - **Enhanced Information Retrieval**: Utilizes LangChain to improve the retrieval and generation process.
  - **LLaMA3 Integration**: Demonstrates the use of LLaMA3 for advanced language generation capabilities.

  ### The following versions of the packages are used in this repository:

  - `langchain`: 0.2.5
  - `langchain_community`: 0.2.5
  - `langchain-huggingface`: 0.0.3
  - `pypdf`: 4.2.0
  - `pymupdf`: 1.24.5
  - `transformers`: 4.41.2
  - `bitsandbytes`: 0.43.1
  - `sentence-transformers`: 3.0.1
  - `faiss-gpu`: 1.7.2
  - `huggingface_hub`: 0.23.4
  - `accelerate`: 0.31.0

- **llama3_cpp.ipynb**: This notebook provides an implementation of the LLaMA-3-8B-Instruct-32k-v0.1 model using the `llama-cpp-python` package. It includes options for both single-turn and multi-turn conversations, allowing users to interact with the model in a conversational manner. The notebook also includes code for downloading the model, setting up the environment, and handling user inputs efficiently.
  [![Colab](https://img.shields.io/badge/Colab-RAG_LLaMA3-orange)](https://colab.research.google.com/github/brritany/LLM/blob/main/jupyternotebook/llama3_cpp.ipynb)

  ### Key Features:
  - **Single-turn conversation**: Interact with the model for one-off questions and responses.
  - **Multi-turn conversation**: Maintain a conversation context across multiple interactions.
  - **CPU-Compatible**: This implementation can be run on CPU, making it accessible for those without access to high-end GPUs.

  ### The following versions of the packages are used in this repository:

  - `llama-cpp-python`: 0.2.79

## Contributing

Feel free to fork this repository and contribute by submitting a pull request. Any contributions, whether it be improving existing code or adding new examples, are greatly appreciated.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
