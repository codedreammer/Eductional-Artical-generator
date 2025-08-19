# 📚 Educational Article Generator (C1 Project)

An AI-powered Streamlit app that generates structured educational articles for different audiences.

## ✨ Features
- Topic-based article generation with headings and bullet points
- Audience level & tone control
- Optional glossary and quick quiz
- Download as **Markdown** or **Word (.docx)**

## 🧰 Tech Stack
- Python, Streamlit
- OpenAI API (gpt-4o-mini by default)
- python-docx for DOCX export
- python-dotenv for key management

## 🚀 Setup & Run
1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Add your OpenAI key**
   - Create a file named `.env` with this line:
     ```
     OPENAI_API_KEY=your_api_key_here
     ```

3. **Run the app**
   ```bash
   streamlit run app.py
   ```

4. **Use it**
   - Enter a topic, choose the audience level, and click **Generate Article**.
   - Download the result as `.md` or `.docx`.

## 🧪 Tips for Demo
- Show quick generation for 1–2 topics
- Open the downloaded DOCX to show formatting
- Talk about future scope: multilingual support, image diagrams, citations

## 📄 License
For educational use.
