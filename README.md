# Llama2 Medical Bot

The Llama2 Medical Bot is a powerful tool designed to provide medical information by answering user queries using state-of-the-art language models and vector stores. This README will guide you through the setup and usage of the Llama2 Medical Bot.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
The Llama2 Medical Bot leverages advanced natural language processing techniques to assist users in obtaining accurate medical information. It is designed for healthcare professionals, researchers, and anyone seeking reliable medical answers.

## Prerequisites
Before you can start using the Llama2 Medical Bot, make sure you have the following prerequisites installed on your system:

- Python 3.6 or higher
- Required Python packages (you can install them using pip):
  - langchain
  - chainlit
  - sentence-transformers
  - faiss
  - PyPDF2 (for PDF document loading)

## Installation
To install the Llama2 Medical Bot, follow these steps:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/AtharvaThakare14/Medical_chatbot.git
   cd Medical_chatbot.git
   

## Create a Python virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

## Install the required Python packages
pip install -r requirements.txt

## Download the required language models and data
# Please refer to the Langchain documentation for specific instructions on how to download and set up the language model and vector store.

## Set up the necessary paths and configurations in your project
# Update the DB_FAISS_PATH variable and other configurations as per your needs