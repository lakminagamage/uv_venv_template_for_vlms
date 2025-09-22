This is a template repository for setting up a Python virtual environment using UV for VLM based projects.

1. Install UV
`curl -LsSf https://astral.sh/uv/install.sh | sh`

2. Install Venv
`uv venv`

3. Activate Venv
`source .venv/bin/activate`

4. Install dependencies
use `uv sync` or  `uv add requirements.txt`

5. Run your code
`uv run main.py`