Folder Structure

ChatBotDevelopment/
│
├── .venv/
│
├── data/
│   └── test_company_handbook.pdf
│
├── qdrant_storage/
│   ├── .deleted/
│   ├── aliases/
│   │   └── data.json
│   │
│   ├── collections/
│   │   └── company_docs/
│   │       └── 0/
│   │           ├── config.json
│   │           ├── shard_key_mapping.json
│   │           └── version.info
│   │
│   └── raft_state.json
│
├── utils/
│   ├── cleaner/
│   │   └── text_cleaner.py
│   │
│   └── loader/
│       └── pdf_loader.py
│
├── app.py
├── chatbot.log
├── docker-compose.yml
├── ingest.py
├── rag.py
├── requirements.txt
├── reranker.py
├── retriever.py
│
├── test_loader.py
├── test_pdf.py
├── test_qdrant.py
└── test_qdrant_data.py

Read Me:
"pip install -r requirements.txt" for virtual environment setup
