# mini-rag

This is a minimal implementition of the RAG model for question answering

## Requirements

- Python 3.12 or later

### Install Python using MiniConda

1) Dowload and install MiniConda from [here](https://docs.anaconda.com/miniconda/)
2) Create a new environment using the following command:
```bash 
$ conda create -n mini-rag python=3.12
```
3) Activate the environment using the following command:
```bash
$ conda activate mini-rag
```
### (Optional) Setup you command line interface for better readability
``` bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```
### Install the required packages
```bash
$ pip install -r requirements.txt
```
### Setup the environment variables
```bash
$ cp .env.example .env
```

Set your environment variables in the `.env` file. Like `OPENAI_API_KEY` value.

