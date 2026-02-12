# Agentic AI Project

## Overview
This project demonstrates an agentic AI system built with LangChain and LangGraph. It showcases a multi-step workflow that includes:
- LLM inference using Google Gemini
- Token counting for generated responses
- Wikipedia integration for information retrieval

## Features
- **LLM Integration**: Uses Google Gemini API for natural language understanding and generation
- **State Management**: Built with LangGraph for managing complex agent workflows
- **Tool Integration**: Wikipedia API wrapper for knowledge retrieval
- **Message Handling**: Comprehensive message handling with LangChain core

## Project Structure
- `main.py` - Main application entry point
- `test.ipynb` - Notebook with test workflows and demonstrations
- `requirements.txt` - Project dependencies
- `pyproject.toml` - Project configuration

## Setup & Installation

### Prerequisites
- Python 3.8+
- Google Gemini API key

### Installation Steps
1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a `.env` file and add your API keys:
   ```
   GOOGLE_API_KEY=your_google_api_key_here
   ```

## Usage

### Running the Notebook
Open `test.ipynb` in Jupyter and run cells sequentially to see the agent in action.

### Key Workflows
1. **LLM Call Node**: Sends user messages to Google Gemini
2. **Token Counter Node**: Counts tokens (words) in the LLM response
3. **Wikipedia Tool**: Searches Wikipedia for information retrieval

## Technologies Used
- **LangChain**: LLM framework and tools
- **LangGraph**: Agent workflow orchestration
- **Google Gemini**: Large language model
- **Wikipedia API**: Information retrieval
- **Python 3.10+**: Programming language

## Notes
For better Wikipedia search results, use concise query terms (e.g., "Paris capital France" instead of "What is the capital of France?")

## License
MIT 