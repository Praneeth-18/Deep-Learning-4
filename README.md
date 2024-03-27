[YouTube Demo Video Link](https://youtu.be/W5IR564SAO0)

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

---

# b)


# LangChain Agents 

This project explores the utilization of LangChain to create and execute intelligent agents, focusing on question-answering scenarios leveraging tools like Wikipedia for data retrieval and OpenAI's GPT models for processing and generating responses. The project aims to demonstrate how LangChain can be integrated into a workflow to construct agents capable of performing complex tasks such as searching, parsing, and providing answers to various questions.

## Project Overview

The core of this project involves setting up LangChain agents with specific capabilities, including:

- Securely retrieving API keys for services like OpenAI.
- Initializing language models with these keys for processing natural language queries.
- Configuring tools within LangChain to perform specific tasks, such as searching Wikipedia for information.
- Creating agents that can ask follow-up questions, parse responses, and generate answers based on the information gathered from different sources.

## LangChain Agent Types

The project explores the usage of various types of agents provided by LangChain, each designed for specific tasks and scenarios. The following agent types were examined and utilized within the project's context:

- **Zero-shot ReAct**: This agent type is designed to handle tasks without the need for prior examples or training on specific data. It can generate responses or perform actions based on its understanding of the query in a zero-shot manner.

- **Conversational ReAct**: Focused on handling conversational queries, this agent can engage in dialogues, understand context, and provide responses that are coherent within a conversational framework.

- **ReAct Docstore**: Leveraging document stores or databases, this agent type can search, retrieve, and process information from structured data sources to answer queries or provide insights.

- **Self-ask with Search**: This agent is capable of performing self-directed searches based on initial queries. It can formulate follow-up questions, conduct searches to gather necessary information, and synthesize responses based on the data it finds.

Each of these agent types showcases the flexibility of LangChain in creating solutions tailored to different aspects of natural language processing and information retrieval.

## Setup and Configuration

The project setup involves:

1. Installing necessary dependencies, including the LangChain library and any required packages for interacting with OpenAI and Wikipedia.
2. Securely managing API keys, particularly for OpenAI, to ensure that agents can access and utilize these services responsibly.
3. Defining and initializing tools within LangChain that the agents will use to perform their tasks.
4. Configuring agents with these tools and the language model to handle specific types of queries.

## Conclusion

This project demonstrates the versatility and capability of LangChain in creating intelligent agents for question-answering tasks. By leveraging powerful tools and models, it showcases how complex queries can be processed, and informative responses can be generated.


