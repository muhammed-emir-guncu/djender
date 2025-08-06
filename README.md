# Djender

## About the Project
Djender is a simple command-line interface (CLI) tool that allows you to interact with a language model to generate code quickly and interactively. It's designed for new developers or anyone looking to rapidly prototype code snippets.

## Setup and Running
### Requirements:

Python 3.x

ollama library (for model interaction)

prompt_toolkit, colorama, pyperclip libraries

A locally running Ollama language model (e.g., gemma3n:e2b).

### Install Dependencies:
Use the following command to install the project's dependencies:

pip install prompt_toolkit colorama pyperclip ollama

### Set Up Ollama Model:
If you haven't already, install Ollama and download the model you wish to use (e.g., gemma3n:e2b):
``` bash
ollama serve
```
### Run the Project:
Start the application by running the main.py file:
``` bash
python main.py
```
## Usage
When the application starts, it will present you with a >>> prompt to enter your initial request.

### Generate Code:

After the >>> prompt, type your code description and press Enter. The model will generate code based on your request.

### Edit/Continue Conversation:

After the model generates code, you'll see a new > prompt. At this stage:

Type a new instruction directly and press Enter to ask the model to edit the generated code or continue the conversation. For example, "Translate this code to Python" or "Add another parameter to this function."

### Copy Code:

After the model generates code, while at the > prompt, press Ctrl + Y to copy the generated code to your clipboard.

### Exit:

At any prompt (both >>> and > prompts), press Ctrl + C to exit the application.

Contributing
If you'd like to contribute to the development, please submit a pull request or report any issues.
