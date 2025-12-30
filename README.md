# LangChain Learning & Implementation Guide

A comprehensive collection of LangChain examples and implementations covering core concepts, integrations, and advanced patterns.

## Quick Start

### Prerequisites
- Python 3.8+
- API keys for LLMs (OpenAI, Anthropic, Google, Hugging Face)

### Installation

```bash
pip install -r requirements.txt
```

Set up environment variables in a `.env` file:
```
OPENAI_API_KEY=your_key_here
ANTHROPIC_API_KEY=your_key_here
GOOGLE_API_KEY=your_key_here
HUGGINGFACEHUB_API_TOKEN=your_token_here
```

## Project Structure

### Core Modules
- **Langchain_Models/** - LLMs, Chat Models, and Embeddings
  - 1.LLMs/ - Language models (OpenAI)
  - 2.ChatModels/ - Chat interfaces (OpenAI, Anthropic, Google, Hugging Face)
  - 3.EmbeddingModels/ - Text embeddings and similarity

- **Langchain_Chains/** - Sequential and parallel processing
  - Simple, sequential, parallel, and conditional chains

- **Langchain_Prompts/** - Prompt engineering and templates
  - Templates, chat prompts, message handling, chatbot examples

- **Langchain_Document_Loaders/** - Data ingestion
  - PDF, CSV, Text, Web, and Directory loaders

- **Langchain_Text_Splitters/** - Text chunking strategies
  - Character-based, semantic, markdown, and code splitting

- **Langchain_Output_Parser/** - Output parsing
  - String, JSON, Pydantic, and structured output parsing

- **Langchain_Runnables/** - Composable pipeline components
  - Sequences, parallels, branches, and lambda functions

- **Langchain_Structured_Output/** - Schema-based outputs
  - JSON, Pydantic, and TypedDict examples

- **Langchain_Vector_Store/** - Vector database integration
  - Chroma DB implementations

- **Langchain_RAG/** - Retrieval-Augmented Generation
  - Complete RAG pipeline examples

- **Langchain_Retrievers/** - Custom retrievers
  - Retrieval pattern implementations

- **Langchain_Agent/** - Autonomous agents
  - Agent-based task execution

- **Langchain_Tools/** - Tool integration
  - Tool creation and tool calling

## Key Features

✓ Multiple LLM integrations (OpenAI, Anthropic, Google, Hugging Face)  
✓ Advanced prompt engineering and templating  
✓ Document loading from multiple sources  
✓ Vector embeddings and similarity search  
✓ RAG (Retrieval-Augmented Generation)  
✓ Tool calling and agents  
✓ Structured output parsing  
✓ Composable runnable chains  

## Dependencies

See `requirements.txt` for all package versions. Key packages:
- langchain, langchain-core, langchain-community, langchain-experimental
- langchain-openai, langchain-anthropic, langchain-google-genai, langchain-huggingface
- pydantic, numpy, pandas, scikit-learn
- chromadb, pypdf, beautifulsoup4, streamlit

## Resources

- [LangChain Documentation](https://python.langchain.com)
- [LangSmith Tracing](https://smith.langchain.com)
- [LangChain Hub](https://smith.langchain.com/hub)

## Notes

- Update API keys in `.env` before running examples
- Some examples require specific provider credentials
- For local models, ensure Hugging Face models are downloaded
- Chroma DB data is stored in `Langchain_Vector_Store/my_chroma_db/`
