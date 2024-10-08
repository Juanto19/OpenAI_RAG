# OpenAI RAG - Retrieval Augmented Generation

## Table of Contents
- [Description](#description)
- [Key Features](#key-features)
- [Applications](#applications)
- [Installation](#installation)
- [Usage](#usage)
- [Example Use Case](#example-use-case)
- [Contributions](#contributions)
- [License](#license)
- [Contact](#contact)

## Description

This repository contains a Jupyter Notebook titled **OpenAI_RAG**, where a Retrieval Augmented Generation (RAG) system is implemented using the OpenAI API. This system allows integrating external documents (in PDF format), which are embedded to provide context to the language model (LLM), enabling highly relevant and contextualized responses.

The main objective of this project is to demonstrate how LLMs can be enhanced with specific information stored in documents, offering a robust solution for answering questions based on concrete knowledge. It is ideal for applications such as enterprise virtual assistants, document analysis, and personalized information systems.

## Key Features

- **OpenAI API**: Direct integration with OpenAI's language model to generate accurate and coherent responses.
- **Retrieval Augmented Generation (RAG)**: Uses a document retrieval approach, embedding external PDFs as part of the text generation context.
- **Embeddings**: The PDF documents are preprocessed and converted into embeddings to be used by the model, improving the relevance of the responses.
- **Flexible Document Ingestion**: Supports multiple PDF uploads, automatically processing and using them as a knowledge source.

## Applications

- **Intelligent Virtual Assistants**: Creation of assistants that can answer specific questions based on user-provided documents.
- **Enterprise Support Systems**: Implementation of systems that can search and respond to queries related to internal manuals, policies, or knowledge bases.
- **Document Analysis**: Provides automated analysis of large volumes of PDF information, ideal for research or data verification.

## Installation

To set up the project, you will need to install the required dependencies. Run the following command:

```bash
pip install langchain langchain_openai gradio chromadb pypdf
```

If you are using the community version of LangChain, install it with:

```bash
pip install -U langchain-community
```

## Usage

Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/openai-rag-project.git
cd openai-rag-project
```

Open the Jupyter Notebook or your Python environment.

Load the necessary PDFs by updating the `urls` list in the script.

Run the code cells to set up the model and start the Gradio interface.

Use the interface to ask questions related to business documentation in Spain.

## Example Use Case

This project provides an example of how a virtual assistant can respond to complex queries based on the provided documents. For instance, if you upload a technical manual in PDF format, the system can answer questions like:

- "What is the installation procedure for the system?"
- "What technical specifications are required for the product?"

### Process Flow:

The basic flow of the RAG system is as follows:

1. **Document Upload:** PDFs are uploaded to the system.
2. **Preprocessing:** The documents are split into relevant fragments and converted into embeddings.
3. **Retrieval:** Given a user input, the system retrieves the appropriate context from the documents.
4. **Response Generation:** OpenAI's model generates a response using both the user's input and the retrieved context.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this project as per the license terms.


- **Name:** Juan Torralbo Torrado
- **Email:** jtorralbotorrado@gmail.com
- **LinkedIn:**  [https://www.linkedin.com/in/juan-torralbo-torrado/](https://www.linkedin.com/in/juan-torralbo-torrado/)
- **GitHub:** [https://github.com/Juanto19](https://github.com/Juanto19)



