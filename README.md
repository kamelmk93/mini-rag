# mini-rag

## Install Python 3.8 (if not already installed)
```bash
sudo apt update
sudo apt install python3.8 python3.8-venv python3.8-distutils
```

### Verify Python 3.8 Installation
```bash
python3.8 --version
```

## Virtual Environment
### create
```bash
python3.8 -m venv mini-rag-app
cd mini-rag-app
```
### Activate
```bash
source bin/activate
```
### Create mini-rag repo on GitHub and make sure include the following important 3 files README.md, a License, and .gitignore (choose python for it)

## Clone this project into your pc in mini-rag folder
```bash
git clone https://github.com/kamelmk93/mini-rag.git mini-rag
cd mini-rag
code .
```
### (Optional) Setup your command line interface for better readability

```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$"
```