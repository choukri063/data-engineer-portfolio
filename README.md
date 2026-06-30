👋 Ahmed Choukri — Data Engineer

Spécialisation : NLP · Bases de données vectorielles · Systèmes RAG · Data Engineering

Data Engineer en alternance — Passionné par les LLM et l'IA appliquée

Projet 
🎭 Puls-Events — Système RAG pour la Recommandation d'Événements Culturels
Assistant culturel intelligent basé sur un système RAG (Retrieval-Augmented Generation) combinant Mistral AI, FAISS et LangChain pour recommander des événements culturels en Hauts-de-France.

🏗️ Architecture du système
text
Question utilisateur (langage naturel)
         │
         ▼
Mistral Embeddings (1024 dim)
         │
         ▼
Recherche FAISS IndexFlatIP (< 2ms)
         │
         ▼
Contexte événements (Top-K)
         │
         ▼
Mistral LLM (mistral-small-latest)
         │
         ▼
Réponse naturelle en français
📊 Résultats mesurés
Indicateur	Valeur
Événements indexés	3 879
Chunks vectorisés	4 100
Dimension vecteurs	1 024
Temps réponse moyen	2 003 ms
Recherche FAISS	2 ms
Tests unitaires	8/8 ✅
Paires Q/R annotées	50
🔧 Stack technique
text
LLM          : Mistral AI (mistral-small-latest)
Embeddings   : mistral-embed (1024 dimensions)
Vectoriel    : FAISS IndexFlatIP
Orchestration: LangChain 0.4
Interface    : Streamlit + CLI
Données      : OpenAgenda (18 000 bruts → 3 879 filtrés)
Tests        : Pytest (8/8 passés)
📈 Benchmark performances
text
Embedding Mistral  :  320 ms  ████████░░░░░░░░  16%
Recherche FAISS    :    2 ms  ░░░░░░░░░░░░░░░░  < 1%
Génération LLM     : 1680 ms  ████████████████  84%
─────────────────────────────────────────────────
TOTAL moyen        : 2003 ms  (~2 secondes)
🛠️ Compétences techniques
NLP & Intelligence Artificielle
text
RAG (Retrieval-Augmented Generation)    ████████████████  ★★★★★
LangChain                               ████████████████  ★★★★★
Mistral AI (LLM + Embeddings)           ████████████████  ★★★★★
Prompt Engineering                      ███████████████░  ★★★★☆
Bases de données vectorielles
text
FAISS (IndexFlatIP)                     ████████████████  ★★★★★
Qdrant                                  ████████████░░░░  ★★★★☆
Chunking sémantique                     ████████████████  ★★★★★
Indexation vectorielle                  ███████████████░  ★★★★☆
Data Engineering
text
Python (Pandas, NumPy)                  ████████████████  ★★★★★
ETL Pipeline                            ████████████████  ★★★★★
Pytest (tests unitaires)                ███████████████░  ★★★★☆
API REST (FastAPI)                      ████████████░░░░  ★★★★☆
Cloud & DevOps
text
GCP (Cloud Run, Cloud Functions)        ████████████░░░░  ★★★★☆
Docker & CI/CD                          ███████████░░░░░  ★★★☆☆
Streamlit (déploiement)                 ████████████████  ★★★★★
Projets
🎭 POC RAG — Puls-Events
Système de recommandation d'événements culturels par IA

Pipeline complet : OpenAgenda → Preprocessing → FAISS → RAG → Streamlit

LangChain + Mistral AI + FAISS + Pytest

3 879 événements, 2 secondes de réponse, 8/8 tests

https://img.shields.io/badge/GitHub-View_Project-181717?style=flat-square&logo=github

🗺️ MVP Design — Puls-Events
Étude de design pour la mise en production du système RAG

Architecture cloud GCP (Cloud Run + Qdrant + Redis + FastAPI)

Nouvelles fonctionnalités : mémoire conversationnelle, géolocalisation, monitoring

16 200€ Build · 95 à 2 220€/mois OPEX · Planning 12 semaines

https://img.shields.io/badge/GitHub-View_Project-181717?style=flat-square&logo=github

🎓 Formation
Formation	Établissement	Année
Data Engineer (alternance)	OpenClassrooms	2025-2026
Spécialisation NLP & Bases Vectorielles	Formation continue	2026


