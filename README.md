🌐 AI-Powered Multi-Language Translator
An intelligent multilingual translator built using HuggingFace's facebook/m2m100_418M model, integrated with a clean Gradio interface. This app automatically detects the input language, translates text into a selected target language, and allows tone-based translation options like formal, casual, professional, or friendly.

🚀 Features
🔍 Auto Language Detection – Uses langdetect to identify the source language automatically.
🌐 Multilingual Translation – Supports 10+ major world languages.
🧠 Tone-Based Translation – Choose from multiple tones to suit context.
💡 Transformer-Based Model – Utilizes M2M100, a powerful sequence-to-sequence transformer from Facebook AI.
🎨 Dark Modern UI – Built with Gradio and custom CSS for a sleek, professional look.
🌍 Public Shareable Link – Deploy and share with one click using Gradio’s sharing functionality.

🧰 Tech Stack
Backend: Python, Hugging Face Transformers (M2M100)
Frontend/UI: Gradio
Language Detection: langdetect
Deployment: Gradio's public URL (share=True)


📝 How It Works
User Input: The user enters a sentence or paragraph.
Auto Detection: The source language is auto-detected.
Translation: The model translates it into the selected target language.
Tone Styling: Based on tone, the system modifies how the message is phrased (via prompt-level customization).
Output: The translated and stylized text is shown to the user.

🌐 Supported Languages
English (en)
French (fr)
Spanish (es)
German (de)
Italian (it)
Portuguese (pt)
Hindi (hi)
Chinese (zh)
Japanese (ja)
Russian (ru)


📁 File Structure
pgsql
Copy
Edit
├── app.py
├── requirements.txt
├── README.md
├── screenshots/
│   ├── login.png
│   └── translate.png

📈 Use Cases
🌐 Real-time customer support translation
🧳 Travel and tourism communication
📖 Language learning tools
🤖 Voice bot translation engines
🧑‍🏫 Educational content localization
