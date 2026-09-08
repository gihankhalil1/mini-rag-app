# mini-rag

This is a minimal implementation of the RAG model for question answering.

## Requirments

- python 3.8 or later

#### install python using Miniconda

1) Download and install MiniConda fron [here](https://docs.anaconda.com/free/miniconda/#quick-command-line-install)
2) Create a new environment using the following command:
```bash
$ conda create -n mini-rag-app python=3.8 
```
3) Activate the environment:
```bash
$ conda activate mini-rag-app
```
## Installation

### Install the required packages

```bash
$ pip install -r requirements.txt
```
### Setup the environment variables

```bash
$ cp .env.example .env
```
Set your environment variables in the `.env` file. Like `OPENAI_API_KEY` value.