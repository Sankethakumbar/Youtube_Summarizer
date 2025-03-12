📌 YouTube Video Summarizer
A NLP-based mini-project that extracts and summarizes YouTube video transcripts using TF-IDF and BART.

🚀 Features
✅ Extracts subtitles using the YouTube Transcript API
✅ Summarizes using TF-IDF (statistical) or BART (deep-learning-based)
✅ Provides a Streamlit-based web interface for ease of use
✅ Lightweight and easy to deploy

🛠 Installation & Setup
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/Sankethakumbar/Youtube_Summarizer.git
cd youtube-summarizer
2️⃣ Create a Virtual Environment & Activate It
bash
Copy
Edit
python -m venv venv
🔹 Activate the virtual environment:
bash
Copy
Edit
# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
3️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Run the Streamlit Web App
bash
Copy
Edit
streamlit run app.py
🖥 Usage
Enter a YouTube video URL in the input field
Choose a summarization method (TF-IDF or BART)
Click "Summarize" to generate the summary
📜 Technologies Used
🔹 Python
🔹 Streamlit (for Web UI)
🔹 YouTube Transcript API
🔹 Natural Language Processing (NLTK, Transformers)

📌 Future Enhancements
✅ Add support for more summarization models
✅ Improve UI aesthetics
✅ Deploy the project on Streamlit Cloud / Hugging Face Spaces

