# AI Learning Journey

This repository documents my exploration and learning in Artificial Intelligence, focusing on practical implementations of modern AI techniques.

## Chapter 1: Retrieval-Augmented Generation (RAG) with LangChain, ChromaDB, and OpenAI GPT-3.5-turbo

### Overview

In this first chapter, I delved into building a Retrieval-Augmented Generation (RAG) system. The project demonstrates how to combine document retrieval with large language model capabilities to provide more accurate and contextually relevant responses.

### Key Concepts Explored

- **Document Loading and Processing**: Using LangChain's document loaders to handle PDF and Markdown files from a directory structure.
- **Text Chunking**: Implementing RecursiveCharacterTextSplitter to break down large documents into manageable chunks of 200 characters with 50-character overlap.
- **Embeddings Creation**: Utilizing SentenceTransformer's all-MiniLM-L6-v2 model to generate vector embeddings for each text chunk.
- **Vector Database Integration**: Setting up ChromaDB as the vector database to store and query document embeddings efficiently.
- **LLM Integration**: Connecting the system with OpenAI's GPT-5-mini model through LangChain, using structured prompts and output parsing.
- **Response Comparison**: Analyzing the difference between raw retrieval results and LLM-augmented responses to understand the value of RAG.

### Implementation Highlights

- Loaded documents from `github_data/my_articles/` (PDFs) and `github_data/markdown_files/` (Markdown).
- Created embeddings for semantic search capabilities.
- Built a ChromaDB collection to store vectorized content.
- Implemented a question-answering chain that retrieves relevant context and generates coherent responses.
- Demonstrated how RAG improves upon standalone LLM responses by providing domain-specific context.

### Files

- `1_chatgpt_langchain_chromadb_all_mini_l6_v2__llm_rag_integration/rag_llm_integration.ipynb`: Jupyter notebook containing the complete implementation.

---

## Future Chapters

[To be added as new explorations are completed]
