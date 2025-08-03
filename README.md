# my-first-repo

## Setup

Create and activate a virtual environment:

```sh
conda create -n my-first-env python=3.11

conda activate my-first-env
```

Install packages:

```sh
# pip install pytest

pip install -r requirements.txt
```

## Usage

Play a game of rock, paper scissors:

```sh
# only works if this file does NOT import from other local py files:
python app/rps.py

# if this file imports from other local py files:
python -m app.rps
```

## Tests

Run the tests:

```sh
# find all the tests and run them:
pytest
```