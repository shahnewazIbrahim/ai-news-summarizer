# 📰 AI News Summarizer  
### Powered by Google **Gemini 2.5 Flash** Model

This project is an AI-powered News Summarizer built in a Kaggle Notebook.  
It takes long news articles as input and generates clean, concise, structured summaries using **Google Gemini 2.5 Flash** — an ultra-fast and efficient large language model optimized for summarization and text understanding.

---

## ⭐ Features
- 🔹 Summarizes long news articles into short, meaningful bullet points  
- 🔹 Generates clean and coherent paragraphs  
- 🔹 Uses **Gemini 2.5 Flash** for extremely fast inference  
- 🔹 Removes unnecessary noise & cleans the text  
- 🔹 Easy-to-read and ready for automation workflows  
- 🔹 Can be adapted for:
  - News agencies  
  - Media monitoring  
  - Research  
  - Headline and summary generation apps  

---

## 🧠 Model Used: **Gemini 2.5 Flash**
Google's **Gemini 2.5 Flash** model is optimized for:  
- High-speed text processing  
- Summaries & content extraction  
- Low computational cost  
- Real-time applications  

Perfect for news automation systems.

---

## 📁 Project Structure

├── 📥 Data Loading<br>
├── 🧹 Text Cleaning<br>
├── ✍️ Prompt Engineering<br>
├── 🤖 Gemini 2.5 Flash Integration<br>
├── 📝 Summary Generation<br>
└── 🎨 Output Formatting<br>

---

## 🧪 How It Works
1. Loads raw news article text  
2. Cleans noise (extra spaces, symbols, formatting issues)  
3. Sends processed text to the **Gemini 2.5 Flash** model  
4. Receives:
   - Bullet point summary  
   - A short paragraph overview  
   - Optional generated title  
5. Shows clean formatted output  

---

## 📦 Installation (Local Setup)

Install Google Generative AI SDK:

```bash
pip install google-generativeai


---

## 🧪 How It Works
1. Loads raw news article text  
2. Cleans noise (extra spaces, symbols, formatting issues)  
3. Sends processed text to the **Gemini 2.5 Flash** model  
4. Receives:
   - Bullet point summary  
   - A short paragraph overview  
   - Optional generated title  
5. Shows clean formatted output  

---

## 📦 Installation (Local Setup)

Install Google Generative AI SDK:

```bash
pip install google-generativeai


from google import generativeai as genai

genai.configure(api_key="YOUR_API_KEY")

model = genai.GenerativeModel("gemini-2.5-flash")

response = model.generate_content("""
Summarize this news article:
<your article text here>
""")

print(response.text)

