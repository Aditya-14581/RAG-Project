# RAG System with Starling-7B LLM

This project implements a Retrieval-Augmented Generation (RAG) system leveraging the Starling-7B large language model from the Hugging Face library. The system efficiently retrieves relevant chunks of data for querying by utilizing advanced vector quantization techniques to reduce memory usage.

## Features

- **RAG Approach**: Utilized the Starling-7B large language model from the Hugging Face library to build a retrieval-augmented generation system, enhancing the accuracy and relevance of generated responses.
  
- **Data Chunking & Storage**: Used `VectorStoreIndex` to chunk and store data, optimizing the retrieval process. The query engine is designed to fetch the top 3 relevant chunks based on the input query, improving the system's efficiency.

- **Memory Optimization**: Enhanced model performance with 4-bit vector quantization using `BitsAndBytesConfig`, significantly reducing the memory usage while maintaining performance.


### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Aditya-14581/RAG-Project.git
   cd repository-name
