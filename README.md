# 🌐 AI Powered Multi-Language Translator (Google Translate Based)

This project is a Google Colab notebook that allows users to translate text between multiple languages using **Google Translate**, accessed through the `googletrans` Python library. It's simple, fast, and works entirely in the cloud — no setup required.

---

## ✨ Features

- 🌍 Translate between **100+ languages**
- 🧠 Powered by **Google Translate**
- ⚡ Fast and accurate translations
- 💻 Runs entirely on **Google Colab**
- ✅ No setup or model downloads required

---

## 🧠 Technology Stack

- Google Colab - Cloud notebook environment
- Python - Programming language
- oogletrans - Python wrapper for Google Translate API
- Google Translate - Translation engine (online)

---

## 🔍 How It Works

The notebook uses the `googletrans` library to send requests to **Google Translate** and receive translations in real time.

## 🔧 Code Snippet:

```python
from googletrans import Translator

translator = Translator()
translated = translator.translate("Hello", src='en', dest='fr')
print(translated.text)  # Output: Bonjour
```
You can change src (source language) and dest (destination language) using ISO language codes.

---

## 💬 Example Usage
```python
text = "I love programming!"
source_lang = "en"
target_lang = "es"

result = translator.translate(text, src=source_lang, dest=target_lang)
print("Translated Text:", result.text)
# Output: ¡Me encanta programar!
```

---

## 📚 Use Cases

- Translating content for personal or academic use
- Helping users understand foreign-language text
- Supporting language learners
- Creating multilingual chatbot responses
- Assisting travelers with quick translation tasks

---

## 📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute it with appropriate attribution.

---
## 🙋‍♂️ Disclaimer

This project uses the unofficial googletrans Python library which relies on the web version of Google Translate. It may stop working if Google changes its API or security protocols. For commercial or production use, consider Google Cloud Translation API.

---