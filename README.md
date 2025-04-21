# 🧠 Chatbot RAG avec LangChain & LLM

Ce projet met en place un chatbot intelligent capable de répondre à des questions spécifiques à partir d’un corpus documentaire, grâce à l’architecture RAG (Retrieval-Augmented Generation).

## 📌 Objectifs
- Utiliser des LLMs pour répondre à des questions métier/documentation
- Mettre en place un moteur de recherche sémantique avec FAISS/Pinecone
- Intégrer une interface utilisateur via Streamlit

## ⚙️ Technologies
- Python, LangChain, Streamlit
- Modèles LLM (Mixtral / OpenAI)
- Pinecone (ou FAISS) pour la base vectorielle

## 📁 Structure
```
📂 chatbot-rag
├── data/                   # Fichiers source (PDF, txt)
├── app.py                  # Interface utilisateur (Streamlit)
├── rag_pipeline.py         # Logique de récupération + génération
├── requirements.txt
└── README.md
```

## ▶️ Lancer le projet
```bash
pip install -r requirements.txt
streamlit run app.py
```

## 📚 Inspirations
- [LangChain docs](https://docs.langchain.com)
- Tutoriels Credera Engineering, Mistral AI
