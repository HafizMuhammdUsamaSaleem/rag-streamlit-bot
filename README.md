## rag-streamlit-bot
A Retrieval-Augmented Generation (RAG) chatbot built with Streamlit, LangChain, and OpenAI. Upload documents, index them into a vector store, and chat contextually with your data.

## Project Structure
'''

├── Documents
│   ├── advanced-security-guide.pdf
│   ├── database-security-guide.pdf
│   └── enterprise-user-security-administrators-guide.pdf
├── README.md
├── chat_history.json
├── db
│   └── chroma.sqlite3
├── main.py
├── requirements.txt
├── templates
│   ├── bot.jpg
│   ├── human.jpg
│   └── pdf_icon.png
├── utils
│   ├── chunking.py
│   ├── conversation.py
│   ├── embeddings.py
│   ├── helpers.py
│   ├── history.py
│   ├── pdf_processing.py
│   └── retrieval.py
└── web_template.py

'''