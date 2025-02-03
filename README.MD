# LangChain Framework Examples

This repository serves as a learning playground demonstrating how to integrate and use the LangChain framework to build LLM-powered applications.

## Overview

The project showcases various LangChain features through practical examples, focusing on:
- Basic LLM integration
- Prompt templating
- Output parsing
- Structured response handling

## Prerequisites

- Python 3.8+
- OpenAI API key
- Required packages:
  ```bash
  pip install python-dotenv openai langchain-openai langchain_community
  ```

## Examples Demonstrated

### 1. Basic OpenAI Integration
- Direct integration with OpenAI's Chat API
- Simple prompt-response pattern
- Temperature control for consistent outputs

### 2. LangChain Prompt Templates
- Creating reusable prompt templates
- Formatting messages with variables
- Text style transformation examples

### 3. Output Parsing
- Structured output parsing
- JSON response formatting
- Schema definition for responses
- Complex data extraction from customer reviews

### Example Use Cases

1. **Text Style Transformation**
   - Converting customer messages between different styles
   - Maintaining tone and content while changing language style

2. **Customer Review Analysis**
   - Extracting structured data from free-text reviews
   - Parsing delivery times, gift status, and price sentiments
   - Converting unstructured text into structured JSON responses

## Structure

The examples are organized in Jupyter notebooks, each focusing on specific LangChain concepts and features:

## Available Notebooks

1. **Basic Concepts (1-model-prompts-parser.ipynb)**
   - Basic LLM integration
   - Prompt templates
   - Output parsing
   - Structured responses

*Note: More examples will be added regularly to showcase additional LangChain features.*

## Usage

1. Clone the repository
2. Update the OPEN_AI_KEY in the notebook with your API key. Currently, it reads from the keychain.
3. Navigate to the notebook of interest
4. Follow the examples and explanations in each notebook

## Notes

This is a learning resource and example playground. The code is documented with comments explaining each step and concept for better understanding of the LangChain framework's capabilities.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.