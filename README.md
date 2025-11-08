# AI Resume Matcher App

An intelligent web application that matches resumes with job descriptions using Natural Language Processing (NLP) and machine learning techniques. Built with Python, Flask, and scikit-learn.

## 🚀 Features

- **Multi-format Support**: Upload resumes in PDF, DOCX, or TXT formats
- **Intelligent Matching**: Uses TF-IDF vectorization and cosine similarity to find the best matches
- **Top Results**: Displays top 5 matching resumes with similarity scores
- **Web Interface**: User-friendly Flask web application
- **Real-time Processing**: Fast and efficient resume matching

## 🛠️ Technologies Used

- **Python 3.x**: Core programming language
- **Flask**: Web framework for building the application
- **scikit-learn**: Machine learning library for TF-IDF vectorization and cosine similarity
- **PyPDF2**: PDF text extraction
- **docx2txt**: DOCX file text extraction
- **NLP**: Natural Language Processing for text analysis

## 📋 Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone <your-github-repo-url>
   cd AI-Resume-Matcher-App
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**
   
   On Windows:
   ```bash
   venv\Scripts\activate
   ```
   
   On macOS/Linux:
   ```bash
   source venv/bin/activate
   ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` doesn't exist, install packages manually:
   ```bash
   pip install flask docx2txt PyPDF2 scikit-learn
   ```

## 🎯 Usage

1. **Start the Flask application**
   ```bash
   python main.py
   ```

2. **Open your web browser** and navigate to:
   ```
   http://localhost:5000
   ```

3. **Upload resumes** (PDF, DOCX, or TXT format)

4. **Enter the job description** in the text area

5. **Click "Match Resumes"** to get the top matching candidates with similarity scores

##  Screenshots

<img width="1918" height="1026" alt="Image" src="https://github.com/user-attachments/assets/b0d630cc-2d5b-4693-9003-1760bed51037" />

<img width="1905" height="1026" alt="Image" src="https://github.com/user-attachments/assets/7578c323-f120-4e4e-bffa-6d9e73291507" />

<img width="1905" height="1029" alt="Image" src="https://github.com/user-attachments/assets/88937b71-fe86-47b6-8eff-d193ad9ef3f6" />

## 📁 Project Structure

```
AI-Resume-Matcher-App/
├── main.py                 # Main Flask application
├── templates/
│   └── matchresume.html    # Web interface template
├── uploads/                # Uploaded resume storage
├── CVs/                    # Sample resumes
├── venv/                   # Virtual environment
└── README.md               # Project documentation
```

## 🔍 How It Works

1. **Text Extraction**: The application extracts text from uploaded resume files (PDF, DOCX, or TXT)
2. **Vectorization**: Both the job description and resumes are converted into TF-IDF vectors
3. **Similarity Calculation**: Cosine similarity is used to measure the match between job description and each resume
4. **Ranking**: Resumes are ranked based on their similarity scores, and the top 5 matches are displayed

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

Widushan

## 🔗 GitHub Repository

**Repository URL**: [https://github.com/widushan/AI-Resume-Matcher-App.git](<your-github-repo-url>)

---

⭐ If you find this project helpful, please consider giving it a star on GitHub!
