# RAG_TEXT

📚 Notebook: Historical_txt.ipynb
This notebook builds a retrieval-augmented generation (RAG) pipeline combining document embedding, vector search, and generative LLMs for intelligent question-answering over historical texts.

🧠 Core Purpose
Semantic search and chat-based Q&A over long-form documents using OpenAI and Pinecone.

🔧 Libraries Used
OpenAI, Pinecone, LangChain, transformers, torch

tiktoken, pypdf, pypdf2, groq, langchain-openai

⚙️ Main Functions
read_doc(): Loads and parses a document (PDF or text)

generate_embeddings(): Uses OpenAI or LangChain to create vector representations

combine_vector_and_text(): Stores embedded vectors into Pinecone

query_pinecone_index(query): Searches for relevant content

query_response(query): Uses an LLM to generate an answer from retrieved context

ask_bot(): Ties everything together into a chatbot-like interface
