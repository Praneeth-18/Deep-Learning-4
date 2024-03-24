# a)
# ChatBot Project

This project demonstrates the implementation of a chatbot using OpenAI's GPT-3.5-turbo model. It leverages the OpenAI Python API to create an interactive chat interface that can maintain context over a conversation, making it suitable for a wide range of applications, from customer service bots to educational tools.

## Features

- **Single Query Response**: Allows for one-off queries to the chat model without needing context.
- **Contextual Conversations**: Manages a conversation's history, enabling the chatbot to provide contextually relevant responses based on the interaction history.
- **Error Handling**: Basic error handling for API calls, ensuring robustness in interactions.

## Getting Started

To use this project, you'll need to have an OpenAI API key. The project is designed to be run in environments like Google Colab or local machines where Python is installed.

### Prerequisites

- Python 3.x
- openai Python package
- Access to OpenAI API (requires API key)

### Setup

1. Install the openai Python package using pip:
   ```bash
   pip install openai
   ```
2. Ensure your OpenAI API key is set up correctly in your environment.

### Usage

Initialize the `OpenAIChatBot` with your API key and preferred model. You can interact with the chatbot using the `send_message` method for contextual conversations or the `ask` method for one-off questions.

## Project Structure

- **OpenAIChatBot Class**: The core of the project, providing methods to interact with OpenAI's chat model.
- **Chat History Management**: Methods to manage and utilize chat history for contextual conversations.
- **Error Handling**: Basic structure for handling exceptions during API interactions.


