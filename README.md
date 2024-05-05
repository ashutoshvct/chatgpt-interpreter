# chatgpt-interpreter

# Multi Agent Routing
The python code has two agent - one for creating qrcodes and other for answering question from a CSV. Based on the prompt the correct tool will be used and agent will provide the answer.

## Features

- **Code Execution**: Uses a Python REPL tool to execute Python code dynamically.
- **Data Query**: Integrates with a CSV file to answer questions based on data calculations.
- **Extended Functionality**: Can generate QR codes and perform additional tasks as specified.

## Requirements

Before running the script, ensure you have the following installed:
- Python 3.8 or newer.
- `dotenv`: For loading environment variables.
- `langchain`: For integrating language model capabilities.
- `langchain-openai`: For utilizing OpenAI models.
- `qrcode`: For generating QR codes.
- All the other required packages are listed in the Pipfile.

You will also need to set up an environment file (`.env`) containing the necessary API keys and configurations.

## Installation

To install the required Python packages, you can use the following pip command:
All the packages are listed in the Pipfile.

```bash
pip install python-dotenv langchain langchain-openai qrcode 

