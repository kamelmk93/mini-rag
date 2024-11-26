# mini-rag

## Install Python 3.8 (if not already installed)
```bash
$ sudo apt update
$ sudo apt install python3.8 python3.8-venv python3.8-distutils
```

### Verify Python 3.8 Installation (or later)
```bash
$ python3 --version
```

## Virtual Environment
### create
```bash
$ python3 -m venv mini-rag-app
$ cd mini-rag-app
```
### Activate
```bash
$ source bin/activate
```
### Create mini-rag repo on GitHub and make sure include the following important 3 files README.md, a License, and .gitignore (choose python for it)

## Clone this project into your pc in mini-rag folder
```bash
$ git clone https://github.com/kamelmk93/mini-rag.git mini-rag
$ cd mini-rag
$ code .
```
### (Optional) Setup your command line interface for better readability

```bash
$ export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$"
```

## Installation


### Install required packages

```bash
$ pip install -r requirements.txt
```

### Setup environment variables

```bash
$ cp .env.example .env
```

set your environment variables in the `.env` file (e.g. `BLA_BLA` value)


## Run the fastAPI server

```bash
$ uvicorn main:app --reload --host 0.0.0.0 --port 5000
```