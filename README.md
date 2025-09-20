# Sentence Transformers Example Using Jupyter and UV

A simple example to get started with sentence transformers in Jupyter Lab using `uv`

## Quick Setup

```bash
# 1. Install dependencies (automatically creates .venv)
uv sync

# 2. Install Jupyter kernel for this project
uv run python -m ipykernel install --user --name sentence-transformers --display-name "Python (sentence-transformers)"

# 3. Start Jupyter Lab
uv run jupyter lab
```

**What happens:** uv automatically creates a `.venv` directory with an isolated Python environment and installs all dependencies from `pyproject.toml`.

**Important:** After opening the notebook in Jupyter Lab:
- Make sure to select **"Python (sentence-transformers)"** as your kernel
- Look at the top-right corner and click on the kernel selector if needed
- Then run the cells!


## The example showcases

- How to load a pre-trained sentence transformer model
- How to convert sentences into numerical embeddings
- How to calculate semantic similarity between sentences

## Files

- `sentence_transformers_basic.ipynb` - Main tutorial notebook
- `pyproject.toml` - Project dependencies and configuration
- `README.md` - This file
- `.venv/` - Virtual environment (created automatically by uv)

