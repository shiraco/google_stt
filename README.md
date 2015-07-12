# google_stt
----

Google speech to text sample

## Environment
* Python 2.7 or 3.4

## Install

```bash
$ git clone git@github.com:shiraco/google_stt.git
$ cd google_stt
$ source ./venv/bin/activate
(venv)$ pip install -r requirements.txt
```

## Setting API KEY

 Check your key from https://console.developers.google.com

```python:stt.py
# apikey = os.environ.get("GOOGLE_API_KEY")
apikey = "YOUT_API_KEY_HERE"
```

## Usage

```bash
% python stt.py test.wav
白石です
```
