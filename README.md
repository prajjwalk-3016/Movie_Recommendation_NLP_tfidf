# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built using **Natural Language Processing (NLP)** and **TF-IDF**. The system recommends movies based on their similarity to a movie selected by the user.

The project uses **FastAPI** as the backend and **Streamlit** as the frontend, and is deployed as a live web application.

---

## 🚀 Live Demo

🎥 **Try the Application:**  
https://movierecommendationnlptfidf-egbvcxablnd2hcx2fzsqmf.streamlit.app/

---

## 📌 Project Description

The Movie Recommendation System helps users discover movies similar to a movie they already like.

The system uses movie-related textual information and Natural Language Processing techniques to convert the text into numerical representations using **TF-IDF (Term Frequency-Inverse Document Frequency)**.

The similarity between movies is then calculated, and movies with the highest similarity are recommended to the user.

The project consists of two main parts:

- **FastAPI Backend** – Handles recommendation requests and movie-related processing.
- **Streamlit Frontend** – Provides an interactive and user-friendly interface.

---

## ✨ Features

- 🎬 Content-based movie recommendations
- 🧠 NLP and TF-IDF based recommendation system
- 🔍 Recommends movies similar to the selected movie
- ⚡ FastAPI backend for handling API requests
- 🎨 Interactive Streamlit user interface
- 🎞️ Movie information and posters using TMDB API
- 🌐 Deployed as a live web application
- 📱 Simple and user-friendly interface

---

## 🧠 How It Works

The recommendation system works through the following process:

1. Movie information is taken from the dataset.
2. Relevant textual information is processed using NLP techniques.
3. **TF-IDF Vectorization** converts the text into numerical vectors.
4. Similarity between movies is calculated.
5. Movies with the highest similarity scores are selected.
6. The FastAPI backend processes the recommendation request.
7. The Streamlit frontend displays the recommended movies to the user.

### Workflow

```text
Movie Dataset
      ↓
NLP / Text Processing
      ↓
TF-IDF Vectorization
      ↓
Similarity Calculation
      ↓
Top Similar Movies
      ↓
FastAPI Backend
      ↓
Streamlit Frontend
      ↓
Movie Recommendations
