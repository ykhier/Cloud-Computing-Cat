# 🌱 PurrFarm – Smart System for Plant Disease Detection

## Overview

**PurrFarm** is a cloud-based intelligent system that integrates Artificial Intelligence, IoT sensors, and a smart search engine (RAG) to detect, analyze, and monitor plant diseases in agricultural environments.

The system enables:
- Plant disease diagnosis using images
- Real-time environmental monitoring (IoT)
- Intelligent search across academic literature related to plant diseases
- Clear and user-friendly data presentation

---

## 🧠 Core Technologies

- **Python**
- **Jupyter Notebook / Google Colab**
- **Firebase** (Realtime Database)
- **NLP & AI**
  - TextRank
  - Inverted Index
  - RAG (Retrieval Augmented Generation)
- **IoT Sensors**
- **Interactive UI**

---

---

## 🔍 index.py – Search Engine

This file is responsible for building the system’s intelligent search infrastructure.

Main capabilities:
- Parsing academic articles (Abstract + Introduction)
- Building an **Inverted Index**
- Computing term importance using **TextRank**
- Storing processed data in Firebase

Key objects and data structures:
- `BeautifulSoup` – HTML content extraction
- `PorterStemmer` – word normalization
- Word co-occurrence graph
- `word_doc_counts` – keyword-to-document mapping
- Orchestration function:
  - `run_textrank_with_firebase`

---

## 🤖 final_hw_cat.py – Functional Logic

This file centralizes the system’s core logic, including:
- User interface screens
- IoT services
- Artificial intelligence mechanisms
- Gamification system
- Integration between system components

---

## 📊 Key System Capabilities

- Plant disease detection from images
- Real-time sensor data visualization
- Intelligent academic information search
- Visual feedback to the user
- Modular and maintainable codebase

