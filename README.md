---

## Quickstart

# Steps to run the assessment

### 1) Install Python, venv, and Git
```
sudo apt-get update -y
sudo apt-get install -y python3.11 python3.11-venv git
python3.11 --version
```
### Clone your fork and create a virtual environment
```
git clone https://github.com/MChikani/Assessment-debugging.git
cd Assessment-debugging
```
### Create and activate venv
```
python3.11 -m venv .venv
source .venv/bin/activate
```
### Install dependencies
```
python -m pip install --upgrade pip
python -m pip install .
```
### Run the app first
```
python main.py
```
### Then access it through the browser
```
http://127.0.0.1:10030
