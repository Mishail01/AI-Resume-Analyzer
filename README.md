<p align="center">
  <small>💡 Best viewed in <a href="https://github.com/settings/appearance">Light Mode</a> and Desktop Site</small>
</p>

<div align="center">
  <h1>🤖 SMART RESUME ANALYZER</h1>
  <p>AI-Powered Resume Parsing, Recommendations & Analytics</p>

  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/build-stable-brightgreen" alt="build status" />
    <img src="https://img.shields.io/badge/python-3.9%2B-blue" alt="python version" />
    <img src="https://img.shields.io/badge/license-MIT-yellow" alt="license" />
    <img src="https://img.shields.io/github/languages/top/shail-ai/Smart-Resume-Analyzer?color=red" alt="language" />
  </p>

  <h4>
    <a href="#-preview">Preview</a>
    <span> · </span>
    <a href="#-setup--installation">Setup</a>
    <span> · </span>
    <a href="#-features">Features</a>
  </h4>

  <p>
    <small>
      Designed and maintained with 💙 by <b>Shail</b>
    </small>
  </p>
</div>

---

## 🧠 About the Project

**Smart Resume Analyzer** is an AI-powered tool that extracts, analyzes, and visualizes information from resumes using Natural Language Processing (NLP).  
It automatically identifies skills, experience levels, and key sectors — then provides **recommendations, predictions, and analytics** to help applicants and recruiters alike.

---

## 🎯 Scope & Use Cases

1. Extract and structure resume data into tabular or CSV format for analytics  
2. Provide resume improvement recommendations based on keyword and skill matching  
3. Enable applicants to self-assess and enhance their resumes using AI insights  
4. Offer colleges and organizations a dashboard for student or applicant insights  
5. Understand hiring trends and skill demand analytics  

---

## 🧩 Tech Stack

<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li>HTML, CSS, JavaScript</li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li>Python</li>
    <li>Streamlit</li>
  </ul>
</details>

<details>
  <summary>Database</summary>
  <ul>
    <li>MySQL</li>
  </ul>
</details>

<details>
  <summary>Core Libraries</summary>
  <ul>
    <li><a href="https://pandas.pydata.org/">pandas</a></li>
    <li><a href="https://pypi.org/project/pdfminer3/">pdfminer3</a></li>
    <li><a href="https://github.com/OmkarPathak/pyresparser">pyresparser</a></li>
    <li><a href="https://plotly.com/">Plotly</a></li>
    <li><a href="https://www.nltk.org/">NLTK</a></li>
  </ul>
</details>

---

## 🚀 Features

### 👤 Applicant / User Side
- Upload a resume and extract structured details  
- Auto-detect **skills**, **keywords**, and **experience level**  
- Get **role-based recommendations** and **resume improvement tips**  
- View an overall **AI-generated resume score**  
- Explore personalized **course & certification suggestions**  

### 🧮 Recruiter / Admin Side
- View all uploaded applicant data in tabular format  
- Export data to CSV for analysis  
- Visualize resume trends using pie charts & analytics  
- Manage feedback and ratings  

---

## ⚙️ Setup & Installation

### Prerequisites
Ensure you have the following installed:
- [Python 3.9+](https://www.python.org/downloads/release/python-3912/)
- [MySQL](https://www.mysql.com/downloads/)
- [VS Code](https://code.visualstudio.com/Download)

### Steps

```bash
# Clone this repository
git clone https://github.com/shail-ai/Smart-Resume-Analyzer.git

# Move into the folder
cd Smart-Resume-Analyzer

# Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate    # (Windows)
# or
source venv/bin/activate # (Mac/Linux)

# Install dependencies
pip install -r requirements.txt
python -m spacy download en_core_web_sm

# Create a database named 'cv' in MySQL
# Update user credentials inside App.py before running

# Run the Streamlit app
streamlit run App.py
```

✅ You’re all set! Upload any resume and start analyzing.

---

## 📈 Future Enhancements

- Integration of transformer-based resume parsing

- Resume similarity detection using embeddings

- Smart ranking of resumes for recruiters

- Streamlit dashboard for college placement analytics

- REST API for enterprise integration

---

## License

This project is licensed under the MIT License.
© 2025 Shail. You are free to use, modify, and distribute this project under the same license.

---

## 🙌 Acknowledgements

Special thanks to the open-source community and NLP contributors who inspired the base version of this analyzer.
