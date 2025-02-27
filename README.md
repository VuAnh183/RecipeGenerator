# Recipe Generation from Ingredients

This project is a recipe generation chatbot system that uses a local dataset and a pre-trained model for human-computer interaction. It integrates a front-end interface built with Gradio and allows users to run a chatbot locally.

## Features

- Recipe generation using the [RecipeNLG](https://www.kaggle.com/datasets/paultimothymooney/recipenlg) dataset
- Pre-trained Llama3.2 models from [Ollama](https://ollama.com)
- Chatbot interface powered by Gradio

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- Git
- Llama3.2 model

### Installation Instructions

1. **Clone the Repository**

```
git clone https://github.com/VuAnh183/RecipeGenerator.git
```

2. **Download Ollama Llama3.2 Model**

- Follow instructions to download Ollama framwork from [Ollama](https://ollama.com)
- Run the Llama3.2 model in the repo cmd:

```bash
ollama run llama3.2
```

3. **Install Python Dependencies**

Ensure all necessary Python libraries are installed by running:

```bash
pip install -r requirements.txt
```

### Running the System

To launch the chatbot, simply click on the `Llama3.2-RAG.ipynb` file and run all the cells.
