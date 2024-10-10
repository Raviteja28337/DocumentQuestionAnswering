# DocumentQuestionAnswering

This project utilizes LangChain to process documents, split them into manageable chunks, and create embeddings using OpenAI's models. The processed data is stored in a vector database (Chroma), enabling efficient querying based on similarity.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [License](#license)

## Features

- **Document Loading**: Loads documents from a specified directory.
- **Page Splitting**: Splits documents into pages of a specified size for better processing.
- **Chunking**: Further splits pages into smaller chunks for embedding.
- **Embeddings Creation**: Generates embeddings for the document chunks using OpenAI's model.
- **Similarity Search**: Allows querying the vector store for relevant document chunks based on similarity.

## Technologies Used

- Python
- LangChain
- OpenAI
- Chroma

## Installation

To set up the project, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
