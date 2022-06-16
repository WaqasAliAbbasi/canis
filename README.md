# canis

A dog breed identifier built on top of [deploif.ai](https://deploif.ai/).

## Development Setup

### Ubuntu/WSL

1. Install Python: `sudo apt update && sudo apt install -y python3-venv python3-pip libpq-dev && pip install wheel`
1. Setup python virtualenv: `python3 -m venv .venv`
1. Activate virtualenv: `source ./.venv/bin/activate`
1. Install dependencies `pip install -r requirements.txt`

## Common Tasks

1. Freeze dependencies: `pip list --format=freeze > requirements.txt`
