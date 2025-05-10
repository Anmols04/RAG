Expert Knowledge Worker - RAG-based Q&A Assistant
This project is a prototype of a cost-effective expert knowledge worker assistant designed for internal use by employees at Insurellm, an insurance technology company. It uses Retrieval-Augmented Generation (RAG) with LangChain and OpenAI tools to provide high-accuracy answers from internal documentation.

🔍 Objective
Build a low-cost, accurate question-answering system

Use OpenAI embeddings and a vector database (ChromaDB)

Visualize and interact with data through a web interface built using Gradio

🛠️ Tech Stack
Python

LangChain

OpenAI (GPT-4o-mini for cost-efficiency)

Chroma for VectorDB

Gradio for UI

Plotly for vector visualization

scikit-learn (t-SNE) for dimensionality reduction

📁 Project Structure
Document Loaders: Load text files from directories using DirectoryLoader.

Text Splitting: Break large texts into chunks using CharacterTextSplitter.

Embedding: Convert text into vector form using OpenAIEmbeddings.

Vector Store: Store and retrieve vector data using ChromaDB.

Conversational Memory: Keep track of conversations using ConversationBufferMemory.

Conversational Retrieval Chain: Use LangChain's ConversationalRetrievalChain to generate context-aware responses.

📊 Vector Visualization
Uses t-SNE to reduce vector dimensions.

Plots the embeddings using Plotly for intuitive understanding.

🔐 Environment Variables
Store your OpenAI API key and other credentials securely in a .env file using dotenv.
