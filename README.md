# chart-agent

## In progress
# Chart Agent

This project implements an AI agent that can generate and analyze charts based on data. The agent uses OpenAI's models, LangChain, and various tools to process data, create visualizations, and answer questions about the data.

## Features

- Data loading and preprocessing
- Chart generation using matplotlib
- Natural language interaction with charts
- Question answering about data and visualizations
- Integration with LangSmith for tracing and debugging

## Setup

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up environment variables in a `.env` file:
   ```
   OPENAI_API_KEY=your_openai_api_key
   TAVILY_API_KEY=your_tavily_api_key
   LANGSMITH_TRACING=true
   LANGSMITH_ENDPOINT=https://api.smith.langchain.com
   LANGSMITH_API_KEY=your_langsmith_api_key
   LANGSMITH_PROJECT="chart-agent"
   ```

## Usage

The main functionality is demonstrated in `test.ipynb`. The notebook shows how to:

1. Load and preprocess data
2. Generate charts based on the data
3. Ask questions about the charts and data
4. Use the agent to perform complex data analysis tasks

## Components

- **Data Processing**: Tools for loading, cleaning, and analyzing data
- **Chart Generation**: Functions to create various types of charts based on data
- **Agent**: LangChain-based agent that can understand requests and use appropriate tools
- **Tools**: Custom tools for data manipulation, chart creation, and analysis

## Future Improvements

- Support for more chart types
- Enhanced data preprocessing capabilities
- Improved natural language understanding
- Integration with more data sources
