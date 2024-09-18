# Advanced Document Query System

## Project Overview
This project introduces a highly efficient document query system capable of handling various document formats, including PDF, TXT, and DOCX. It utilizes a Gradio-based interface for seamless user interactions and LangChain technology for robust document processing and AI-driven querying.

## Technologies Used
- **Gradio**: For building interactive web interfaces.
- **LangChain**: Leveraging its Chroma vector database and AI models for document embedding and retrieval.
- **Python**: Backend processing and integration.

## Features
- **Document Upload and Processing**: Supports uploading and processing of multiple document types.
- **Persistent Vector Database**: Utilizes Chroma from LangChain to store document vectors persistently.
- **AI-Driven Querying**: Uses Ollama embeddings for document retrieval and the ChatOllama model for answering questions based on document contexts.

## How It Works
1. **Uploading Documents**: Users can upload documents through a user-friendly web interface.
2. **Document Processing**: Documents are processed, and their content is embedded into a vector database.
3. **Querying**: Users can ask questions; the system retrieves relevant document contexts and provides accurate answers.

![System Interface](./UI_1.png)
![Upload Workflow](./UI_2.png)
![Query Workflow](./UI_3.png)

## Setup and Launch
Instructions for setting up the project locally and launching the Gradio interface are provided, ensuring users can easily get the system running on their machines.

## Future Enhancements
- **Expansion of Document Types**: Future versions will include support for more document types and languages.
- **Enhanced AI Models**: Plans to integrate more advanced AI models for better context understanding and response accuracy.

## License
This project is released under the MIT License.


