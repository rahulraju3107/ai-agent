# Simple AI Agent

A command-line tool that sends a prompt to Google Gemini and prints the response.

## Requirements

- Python 3.12+
- A Gemini API key set in a `.env` file as `GEMINI_API_KEY`

## Usage

```
uv run main.py "Your prompt here"
```

Pass `--verbose` to also print the user prompt and token counts:

```
uv run main.py "Your prompt here" --verbose
```
