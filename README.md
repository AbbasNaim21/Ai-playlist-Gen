
# 🎧 AI Playlist Generator

An AI-powered playlist generator that creates **mood-based music recommendations** using lyrics and semantic search.

---

## 🚀 Features

- 🔍 **Mood-Based Input** — Enter a mood, vibe, or situation (e.g., *"studying on a rainy day"*, *"gym motivation"*)
- 🎵 **Smart Recommendations** — Returns a personalized 5-song playlist with lyrics previews
- 🧠 **NLP-Powered Matching** — Uses Sentence-BERT to capture the *semantic meaning* of user input and lyrics
- ⚡ **FAISS Similarity Search** — Quickly finds songs with similar emotional themes
- 🌐 **Interactive UI** — Built with Gradio for live testing and sharing
- 🔗 **YouTube & Spotify Links** — Auto-generated links for quick listening
- 🎛️ **Dropdown Presets** — Choose from predefined moods or input your own

---

## 🛠️ Tech Stack

| Component     | Tool                                           |
|---------------|------------------------------------------------|
| Language      | Python                                         |
| Embeddings    | [Sentence-BERT (all-MiniLM-L6-v2)](https://www.sbert.net/) |
| Search Engine | [FAISS](https://github.com/facebookresearch/faiss) |
| UI            | [Gradio](https://gradio.app/)                  |
| Dataset       | 5M Song Lyrics (Genius via Kaggle)             |
| Environment   | Google Colab (T4 GPU)                          |

---

## 📦 Dataset

- **Source**: [Kaggle - 5 Million Song Lyrics Dataset](https://www.kaggle.com/datasets/nikhilnayak123/5-million-song-lyrics-dataset)
- Filtered: Only top 10k lyrics used to optimize performance

---

## 💻 How to Run

1. Clone this repo
2. Upload your `kaggle.json` (API token)
3. Run `main.ipynb` in Google Colab
4. Explore playlists with Gradio UI

---

## 📹 Demo

Watch the [video demo](#) showcasing the full experience (add your link)

---

## 📌 Use Cases

- Music recommendation apps
- Mood-based playlist generators
- Educational NLP demos
- Emotion-aware interfaces

---

## 🤝 Contributions

Open to ideas, extensions (e.g. genre filters, audio previews), and community feature requests!
