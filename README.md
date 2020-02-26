# Dummy REST API

Tool for testing POST Function

## Requirements

* python >= 3.7
* pip3.7

To install python3.7 and pip3.7 on Ubuntu system run:

``` bash
sudo apt install python3.7-minimal
sudo apt install python3-pip
python3.7 -m pip install --upgrade pip
```

> Note that `pip3.7` is installed in directory `/home/{username}/.local/bin` which might not be in the `PATH` variable. Add the directory to the `PATH` variable in order to be able to use it

## Installation

``` bash
git clone https://github.com/themisAnagno/dummyrest.git
cd dummyrest
pip install -e .
```

## Usage

``` bash
gunicorn -w 2 --bind 0.0.0.0:8000 wsgi:app
```
