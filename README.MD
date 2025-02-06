# LangChain Framework Examples

This repository serves as a learning playground demonstrating how to integrate and use the LangChain framework to build LLM-powered applications.

## Overview

The project showcases various LangChain features through practical examples, focusing on:
- Basic LLM integration
- Prompt templating
- Output parsing
- Structured response handling
- Analyzing sentences and extracting information

## Prerequisites

- Python 3.8+
- OpenAI API key
- Required packages:
  ```bash
  pip install python-dotenv openai langchain-openai langchain_community
  ```

### Example Use Cases

1. **[Basic Concepts](1-model-prompts-parser.ipynb)**
   - Basic LLM integration
   - Prompt templates
   - Output parsing
   - Structured responses

2. **[Memory and State Management](2-memory.ipynb)**
   - Conversation memory implementation
   - State persistence across interactions
   - Different memory types and use cases
   - Managing context in conversations

3. **[Chains, Sequential Processing](3-chains.ipynb)**
   - LLMChain for single-step processing
   - SimpleSequentialChain for linear sequential tasks
   - SequentialChain for complex multi-step processing with multiple outputs

4. **[Router Chains](4-routerchain.ipynb)**
   - Router Chain implementation for dynamic prompt routing based on input type
   - Examples include review analysis, requirements processing, and test automation

*Note: More examples will be added regularly to showcase additional LangChain features.*

## Usage

1. Clone the repository
2. Update the OPEN_AI_KEY in the notebook with your API key. Currently, it reads from the keychain. You can use https://github.com/shroffsagar/get-passw for managing your secrets in mac securely instead of env.
3. Navigate to the notebook of interest
4. Follow the examples and explanations in each notebook

## Notes

This is a learning resource and example playground. The code is documented with comments explaining each step and concept for better understanding of the LangChain framework's capabilities.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.