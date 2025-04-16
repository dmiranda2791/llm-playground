# LLM Playground

A collection of Jupyter notebooks demonstrating implementations of Large Language Models (LLMs) using LangChain and LangGraph.

## Overview

This repository contains three notebooks that explore different aspects of LLM application development:

1. **Agent.ipynb**: Implements a basic agent that can perform web searches using the Tavily API and maintain conversation state.
2. **Chatbot.ipynb**: Demonstrates building a chatbot with conversation memory and custom prompt templates.
3. **Simple LLM Application.ipynb**: Covers fundamental LLM interactions and streaming responses.

## Technical Stack

- LangChain: LLM interactions and prompt management
- LangGraph: State management and agent orchestration
- OpenAI API: Model inference
- Tavily API: Web search functionality
- LangSmith: Observability and tracing
- Python 3.11

## Features

### Agent Implementation

- Web search integration using Tavily API
- Basic conversation state management
- Simple memory persistence
- Response streaming

### Chatbot Features

- Conversation memory using LangGraph's MemorySaver
- Custom prompt templates
- Basic token management
- Async processing

### Core LLM Features

- Basic model interactions
- Streaming responses
- Prompt templates
- Environment configuration

### Observability

- LangSmith integration for tracing and monitoring
- Conversation history tracking
- Performance metrics

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/llm-playground.git
   cd llm-playground
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:

   ```bash
   cp .env.example .env
   ```

   Then edit `.env` with your API keys:

   ```
   OPENAI_API_KEY=your_openai_key
   TAVILY_API_KEY=your_tavily_key
   LANGSMITH_API_KEY=your_langsmith_key
   LANGSMITH_PROJECT=your_project_name
   ```

## Development

The notebooks demonstrate:

- Basic LLM application development
- API integration (OpenAI, Tavily)
- Simple state management
- Basic async programming
- Environment configuration
- API key management
- Observability with LangSmith

## Contributing

Contributions are welcome. Please submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or opportunities, please reach out through GitHub or LinkedIn.
