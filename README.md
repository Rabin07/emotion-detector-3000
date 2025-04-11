# 🎭 Emotion Detector 3000

A fun and interactive web app that detects emotions from user input using a fine-tuned DistilBERT model. It doesn’t just show the emotion — it makes it come alive with GIFs and songs that match the mood! 🧠🎬🎵

---

## 🚀 Features

- 🧠 Detects emotion from any sentence using a trained transformer model
- 🎯 Supports **28 different emotions** like joy, anger, confusion, excitement, pride, and more
- 🎬 Shows a matching **GIF** based on the predicted emotion
- 🎶 Plays a related **song/audio** to match your vibe
- 📊 Displays **confidence score**
- ⚠️ Handles errors gracefully
- 🌐 Fast, interactive, and super easy to use!

---

## 🛠 Tech Stack

| Component   | Technology Used               |
|-------------|-------------------------------|
| Model       | DistilBERT (fine-tuned)       |
| Backend     | Python, FastAPI, PyTorch      |
| Frontend    | HTML, CSS, JavaScript         |
| Integration | REST API with JSON            |
| Model Tools | Hugging Face Transformers     |
| Training    | Google Colab                  |

---

## 🧪 How It Works

1. User enters any text expressing a thought, feeling, or idea.
2. The app sends this text to the FastAPI backend via a POST request.
3. The backend loads a fine-tuned DistilBERT model to predict one of 28 emotion labels.
4. The predicted emotion, along with the confidence score, is sent back to the frontend.
5. A relevant **GIF** and **audio** are displayed/played to match the detected mood.

---

## 🧠 Emotion Categories

The model predicts from 28 emotions including:

`admiration`, `amusement`, `anger`, `annoyance`, `approval`, `caring`, `confusion`, `curiosity`, `desire`, `disappointment`, `disapproval`, `disgust`, `embarrassment`, `excitement`, `fear`, `gratitude`, `grief`, `joy`, `love`, `nervousness`, `optimism`, `pride`, `realization`, `relief`, `remorse`, `sadness`, `surprise`, and `neutral`.

---

