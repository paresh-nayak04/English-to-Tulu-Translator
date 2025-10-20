# 🗣️ English to Tulu Translator

A simple **rule-based and fuzzy matching translator** built with Python.  
It converts English phrases into Tulu equivalents based on a small, manually curated dataset.  

> ⚠️ **Note:** This is a **toy translator**. It is **not advanced** and does **not fully understand grammar or unseen sentences**.  
> It works best for **exact or similar phrases** present in the dataset.

---

## 🚀 Features
- Converts English phrases into Tulu using **fuzzy string matching**.
- Handles **upper/lower case input** (e.g., `HELLO` → `Namaskara`).
- Can match **similar phrases** (e.g., `"what is your name?"` ≈ `"what's your name?"`).
- Uses a **CSV-based dataset**, making it easy to expand and update.
- Lightweight and **fast**, works directly in Python or Google Colab.

---

## 🧠 How It Works
1. Loads translations from `english_tulu.csv`.
2. Normalizes user input (lowercase, strip spaces).
3. Finds the **closest matching English phrase** using fuzzy matching.
4. Returns the corresponding Tulu translation.

---

## 🧩 Example

| English             | Tulu                          |
|--------------------|-------------------------------|
| Hello               | Namaskara                     |
| How are you?        | Yencha ullar?            |
| What is your name?  | Irna pudar dade?            |
| Do you speak tulu?  | Ireg tulu barpunde? |

---

## 📈 Future Scope
- Even though this project works for simple phrases, it can be extended to a more advanced translator:
 1. Train a Seq2Seq / Transformer model for true English → Tulu translation.
 2. Handle unseen phrases and proper grammar automatically.
 3. Add Speech-to-Text input and Text-to-Speech output for voice-based translation.
 4. Build a web or mobile app using Gradio, Streamlit, or Flask for interactive translation.
 5. Expand the dataset with more conversational phrases, numbers, questions, and commands to improve coverage.

## 🧑‍💻 Author
- Paresh Nayak
- B.E in AI & Data Science | Manipal, India
- 💡 Building simple AI tools to connect people through language.

