This repository demonstrates how to implement a Retrieval-Augmented Generation (RAG) pipeline locally using the DeepSeek R1 1.5 model. The project focuses on processing a PDF document, converting it into markdown format, splitting it into meaningful chunks, and setting up a vector store for efficient retrieval. The RAG pipeline is then used to answer questions based on the document's content.

## Key Features
1. **Document Conversion:** Converts PDF documents into markdown format for easier processing.
2. **Text Splitting:** Splits markdown content into chunks based on headers for better context management.
3. **Vector Store:** Utilizes FAISS for efficient similarity search and retrieval of document chunks.
4. **RAG Pipeline:** Integrates DeepSeek R1 1.5 via Ollama for question-answering tasks.
5. **Local Execution:** The entire pipeline runs locally, ensuring privacy and control over the data.
