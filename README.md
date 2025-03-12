📌 YouTube Video Summarizer
A NLP-based mini-project that extracts and summarizes YouTube video transcripts using TF-IDF and BART.

🚀 Features
✅ Extracts subtitles using the YouTube Transcript API
✅ Summarizes using TF-IDF or BART
✅ Provides a Streamlit-based web interface for ease of use
✅ Lightweight and easy to deploy

🛠 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/Sankethakumbar/Youtube_Summarizer.git
cd youtube-summarizer

2️⃣ Create a Virtual Environment & Activate It

python -m venv venv
# Activate virtual environment:
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate


3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Run the Streamlit Web App

streamlit run app.py

🖥 Usage
Enter a YouTube video URL in the input field
Choose summarization method (TF-IDF or BART)
Click Summarize to generate the video summary

📜 Technologies Used
🔹 Python
🔹 Streamlit (for Web UI)
🔹 YouTube Transcript API
🔹 Natural Language Processing (NLTK, Transformers)

📌 Future Enhancements

✅ Add support for more summarization models

✅ Improve UI aesthetics

✅ Deploy the project on Streamlit Cloud or Hugging Face Spaces