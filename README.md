# Chat_with_Your_Knowledge_Base_Building_a_Powerful_RAG_Chatbot

## Project Description

This project demonstrates the implementation of a Retrieval-Augmented Generation (RAG) system using LangChain and Google AI. The goal is to build a chatbot that can answer questions based on a provided set of documents (in this case, patient reviews) by retrieving relevant information and using a large language model to generate a coherent response. The project covers loading and processing data, creating a vector database, setting up the language model and prompt templates, and building a RAG chain to combine retrieval and generation.

## Tech Stack

*   **Python:** The primary programming language used for the project.
*   **LangChain:** A framework for developing applications powered by language models.
*   **LangChain-Core:** Core abstractions and components for LangChain.
*   **LangChain-Community:** Third-party integrations for LangChain.
*   **LangChain-Google-Genai:** Integration with Google's Generative AI models.
*   **LangChain-Chroma:** Integration with the Chroma vector database.
*   **Chroma:** An open-source vector database used for storing and searching document embeddings.
*   **GoogleGenerativeAIEmbeddings:** Used for creating numerical vector representations of text using Google's models.
*   **ChatGoogleGenerativeAI:** Used for interacting with Google's chat models.
*   **Gradio:** Used for creating a web-based user interface for the chatbot.
*   **Google Colab:** The environment where the notebook was developed and executed.

## How to Run

1.  **Open the notebook in Google Colab:** Upload or open the notebook file in Google Colab.
2.  **Install dependencies:** Run the initial code cells that install the necessary libraries using `pip`.
3.  **Set up Google API Key:** Obtain a Google API key and add it to Google Colab's secrets manager as `GOOGLE_API_KEY`.
4.  **Load and process data:** Run the cells to load the patient reviews from the CSV file and create the Chroma vector database.
5.  **Run the RAG chain:** Execute the cells that set up the language model, prompt templates, and the RAG chain.
6.  **Launch the Gradio interface:** Run the cell containing the Gradio `ChatInterface` code to launch the chatbot application.
7.  **Interact with the chatbot:** Use the Gradio web interface to ask questions about the patient reviews.
