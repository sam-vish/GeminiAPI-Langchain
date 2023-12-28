# Gemini API with Langchain

This repository demonstrates the integration of Gemini API with Langchain framework in a Google Colab notebook. It showcases various functionalities of the Gemini API in combination with Langchain for language model processing and interactions.

## Installation

To run this notebook, you will need to install the following Python packages:

```bash
!pip install -q langchain_experimental langchain_core
!pip install -q google-generativeai==0.3.1
!pip install -q google-ai-generativeLanguage==0.4.0
!pip install -q langchain-google-genai
!pip install -q "langchain[docarray]"
```
## Usage

The Google Colab notebook offers examples utilizing Gemini API and Langchain for diverse language model tasks. Here's a brief summary:

- Setting up authentication and environment variables for the Gemini API.
- Listing available models with their descriptions.
- Generating text using the Gemini Pro model based on provided prompts.
- Demonstrating various language model chains using Langchain:
  - Basic LLM Chain
  - Basic Multi Chain
  - More Complicated Chain - Mini RAG
  - Pal Chain (Problem Answering Language Chain)
  - Multi Modal (Combining Text and Image)

## Google Colab Notebook
The Gemini_API_with_Langchain.ipynb file contains the complete code and explanations for integrating Gemini API with Langchain in a Google Colab environment.

## Resources

- [Colab Notebook](https://colab.research.google.com/drive/12Oqo8AB0fta8rD4bIm6KCtdzHBfLc71i?usp=drive_link) - Official repository for Langchain.
- [Google GenerativeAI Package](https://python.langchain.com/docs/get_started/introduction) - Documentation Langchain

Contributions, suggestions for improvements, or issue reports are welcome via pull requests or raised issues in this repository.

## License
This project is licensed under the MIT License.
