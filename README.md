# Subtitle Search Engine

## Overview
A search engine that retrieves relevant video subtitles based on user queries using NLP and machine learning.

## Features
- Loads and processes subtitles from an SQLite database
- Uses TF-IDF and BERT for text vectorization
- Stores embeddings in ChromaDB for efficient search
- Retrieves relevant subtitles based on semantic similarity

## Technologies Used
- Python, Pandas, SQLite
- ChromaDB, TF-IDF, BERT (Sentence Transformers)
- Streamlit (Optional for UI)

## Setup Instructions
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the script: `python search_engine.py`

## Future Enhancements
- Improve query processing with advanced NLP
- Support multiple languages
- Integrate real-time subtitle indexing

## App Interface
![image](https://github.com/user-attachments/assets/b3030d24-3b5d-4779-9d66-7ff5d1c55826)
output:
![image](https://github.com/user-attachments/assets/01f232e6-8c16-4186-8061-49afb494a2a3)

