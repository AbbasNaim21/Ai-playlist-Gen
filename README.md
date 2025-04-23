🎧 AI Playlist Generator
An AI-powered playlist generator that creates mood-based music recommendations using lyrics and semantic search.

🚀 Features
🔍 Mood-Based Input — Enter a mood, vibe, or situation (e.g., "studying on a rainy day", "gym motivation")

🎵 Smart Recommendations — Returns a personalized 5-song playlist with lyrics previews

🧠 NLP-Powered Matching — Uses Sentence-BERT to capture the semantic meaning of user input and lyrics

⚡ FAISS Similarity Search — Quickly finds songs with similar emotional themes

🌐 Interactive UI — Built with Gradio for live testing and sharing

🔗 YouTube & Spotify Links — Auto-generated links for quick listening

🎛️ Dropdown Presets — Choose from predefined moods or input your own

Component | Tool
Language | Python
Embeddings | Sentence-BERT (all-MiniLM-L6-v2)
Search Engine | FAISS
UI | Gradio
Dataset | 5M Song Lyrics (Genius via Kaggle)
Dev Environment | Google Colab (T4 GPU)****

📦 Dataset
Source: Kaggle - 5 Million Song Lyrics Dataset
Filtered: Only top 10k lyrics used to optimize performance

💻 How to Run
Clone this repo

Upload your kaggle.json (API token)

Run main.ipynb in Google Colab

Explore playlists with Gradio UI
