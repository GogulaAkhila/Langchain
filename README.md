# LangChain Learning

A hands-on learning project for exploring LangChain v1 with Python notebooks. The examples progress from basic LangChain concepts through model integrations, tools, messages, structured output, and middleware. This repository is intended for experimentation and learning, not as a production-ready application or library.

## Notebook Path

Run the notebooks in `updatedlangchain/` in order:

1. `1-langchainintro.ipynb` - LangChain v1 introduction
2. `2-modelintegration.ipynb` - model provider integrations
3. `3-tools.ipynb` - connecting models to tools
4. `4-messages.ipynb` - working with conversation messages
5. `5-structuredoutput.ipynb` - producing structured responses
6. `6-middleware.ipynb` - extending model execution with middleware

## Setup

The project requires Python 3.12 or newer. With [uv](https://docs.astral.sh/uv/), install the project dependencies from the repository root:

```bash
uv sync
```

Open a notebook in VS Code and select the project's `.venv` Python environment as its kernel. Dependencies are also listed in `requirements.txt` for pip-based setups.

## API Keys

Some notebook examples require credentials for the model provider being used. Set the relevant API key in your local environment before running those cells. A local `.env` file is ignored by Git; never commit API keys or other secrets.
