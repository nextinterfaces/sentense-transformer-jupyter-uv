# Sentence Transformers Basic Example 🚀

A simple example to get started with sentence transformers in Jupyter Lab.

## Quick Setup with uv ⚡

uv makes Python dependency management fast and simple. It automatically manages virtual environments and dependency resolution:

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

## Why uv? 🚀

- **10-100x faster** than pip for package installation
- **Automatic virtual environment management** - no manual activation needed
- **Deterministic dependency resolution** - reproducible builds
- **Modern Python project management** - follows current best practices

### Installing uv

```bash
# macOS/Linux/Windows
curl -LsSf https://astral.sh/uv/install.sh | sh

# Or using Homebrew (macOS)
brew install uv
```

## What you'll learn

- How to load a pre-trained sentence transformer model
- How to convert sentences into numerical embeddings
- How to calculate semantic similarity between sentences
- See the magic of semantic understanding in action!

## Files

- `sentence_transformers_basic.ipynb` - Main tutorial notebook
- `pyproject.toml` - Project dependencies and configuration
- `README.md` - This file
- `.venv/` - Virtual environment (created automatically by uv)

## Next Steps

Once you've run through the basic example, you can:
- Experiment with different sentences
- Try other models like `all-mpnet-base-v2`
- Build your own semantic search system

Happy coding! 🎉
