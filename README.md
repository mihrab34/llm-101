# LLM-101

================
# Overview

A project utilizing the Groq API to interact with various open source large language models (LLMs).

## Description
This project leverages the Groq API to generate responses to user queries using a selection of pre-trained LLMs. It includes a simple script that demonstrates the core functionality.

## Features
- Seamless integration with Groq API
- Support for multiple LLM models
- Simple query-response interface
- Easy-to-use script implementation

## Requirements
- groq
- uvicorn
- fastapi
- python-dotenv

## Usage
1. Install the required dependencies:
```bash
pip install -r requirements.txt
```
2. Set the `GROQ_API_KEY` environment variable using a `.env` file or your preferred method.
3. Run the script:
```bash
python main.py
```

## Models
The project currently supports the following LLMs:
- qwen/qwen3-32b
- openai/gpt-oss-20b
- llama-3.3-70b-versatile
- gemma2-9b-it

## Generating Responses
The `generate_message` function takes in a model, query, and optional temperature parameter to generate a response. The response is then printed to the console.

## Contributing