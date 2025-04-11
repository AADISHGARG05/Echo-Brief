# 📝 Text Summarizer with Audio Output (Python + NLTK + Tkinter + GTTS)

[![Python](https://img.shields.io/badge/Built%20with-Python%203-blue)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()
[![GUI](https://img.shields.io/badge/UI-Tkinter-green)]()

This is a **fully functional Text Summarization Tool** built purely using classic Python techniques — no machine learning or AI frameworks. It employs natural language processing through **NLTK**, a GUI using **Tkinter**, and converts summarized output into speech using **Google Text-to-Speech (GTTS)**.  

The tool offers an intuitive interface where users can input text, click a button, and receive a condensed version of the content — both visually and audibly.

---

## 🔍 What Makes It Unique?

- ❌ **No AI Models** – Summary is generated using `if-else` logic, keyword detection, and handcrafted rules.
- 🧠 **Rule-Based Summarization** – It identifies key sentences and phrases based on keyword patterns and their frequency.
- 🔊 **Text-to-Speech Integration** – The summary is automatically converted into an **MP3 file** using GTTS.
- 🖥️ **User-Friendly GUI** – Built using Tkinter for a lightweight and interactive experience.

---

## 🚀 Features

- ✅ Accepts raw user input or pasted articles.
- ✅ Highlights and extracts key points and summaries using logical conditions.
- ✅ Saves and plays back the summary as a spoken `.mp3` file.
- ✅ Cross-platform and lightweight — no external AI model downloads.

---

## 📁 Project Structure

```plaintext
├── summarizer.py           # Main Python script
├── requirements.txt        # Required libraries (NLTK, GTTS, Tkinter)
├── output.mp3              # Example output audio (generated dynamically)
