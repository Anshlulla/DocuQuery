# DocuQuery
## Project Overview
This project focuses on developing a system that can answer questions directly based on the content of a PDF document. By leveraging Llama2, an advanced language model, in combination with Retrieval-Augmented Generation (RAG), this system effectively retrieves and processes the most relevant information from a PDF to provide accurate and contextually appropriate answers. The project simplifies the process of extracting useful information from lengthy and detailed documents, making it more accessible and efficient.

## Key Components
1. **Llama2**   
Description: A powerful language model designed to understand and generate human-like text, enabling it to process complex language tasks.  
Purpose: Used to generate contextually appropriate answers based on retrieved information.
2. **Retrieval-Augmented Generation (RAG)**  
Description: A technique that retrieves the most relevant information from the document before generating a response.  
Purpose: Ensures that the answers provided are not only accurate but also grounded in the specific content of the PDF.
3. **ChromaDB**  
Description: A vector database used to store and retrieve embeddings of text chunks.  
Purpose: Helps in efficiently querying and retrieving relevant document chunks based on the user’s question.
4. **ChatPromptTemplate**   
Description: A template for structuring the input to the language model.  
Purpose: Provides a standardized format for queries and context, ensuring the model processes them correctly.
5. **BitsAndBytes, Tokenization, Embedding, Chunking**  
Description: They are used to optimize, tokenize, transform, and split text data for efficient and meaningful processing by the model.  
Purpose: These components are used to preprocess and optimize the input text data, making it suitable for processing by the model.

## How to Use  
1. **Input the PDF:** Load your PDF document into the system.
2. **Ask a Question:** Enter your query in the provided textbox.
3. **Get the Answer:** The system retrieves the most relevant information and provides an accurate answer.

## Project Workflow: Overview
![image](https://github.com/user-attachments/assets/81c34976-855f-4923-b529-937583f76381)


