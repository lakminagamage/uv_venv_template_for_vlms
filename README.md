This is a template repository for setting up a Python virtual environment using UV for VLM based projects.

1. Install UV
`curl -LsSf https://astral.sh/uv/install.sh | sh`
`source $HOME/.local/bin/env (sh, bash, zsh)`

3. Install Venv
`uv venv`

4. Activate Venv
`source .venv/bin/activate`

5. Install dependencies
use `uv sync` or  `uv add requirements.txt`

6. Run your code
`uv run main.py`
