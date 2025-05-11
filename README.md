# AI-Powered Resume Screening
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/downloads/)
[![Built with Flask](https://img.shields.io/badge/Built%20with-Flask-yellow?logo=flask)](https://flask.palletsprojects.com/)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)](#)

This project automates the resume screening process by extracting and analyzing resumes and job descriptions using Natural Language Processing (NLP) techniques. It compares skills and qualifications, calculates similarity scores, and ranks candidates based on how closely their profiles match the job requirements.

## 📂 Project Structure

```
AI-Powered-Resume-Screening/
├── App.py                # Main Flask application
├── Notebook.ipynb        # Jupyter Notebook with detailed explanations
├── Data/                 # Directory containing resume and job description files
├── templates/            # HTML templates for the web interface
├── uploads/              # Directory for uploaded resumes
├── README.md             # Project documentation
└── LICENSE               # MIT License
```

## 🚀 Features

- **Automated Resume Parsing**: Extracts text from uploaded resumes.
- **Job Description Analysis**: Processes and analyzes job descriptions.
- **Similarity Calculation**: Uses NLP techniques to compute similarity scores between resumes and job descriptions.
- **Candidate Ranking**: Ranks candidates based on their relevance to the job requirements.
- **Web Interface**: User-friendly interface built with Flask for uploading resumes and viewing results.

## 🛠️ Technologies Used

- **Python**: Core programming language.
- **Flask**: Web framework for building the application.
- **NLTK / SpaCy**: Libraries for natural language processing.
- **Scikit-learn**: Machine learning library for similarity calculations.
- **Pandas / NumPy**: Data manipulation and analysis.
- **Jinja2**: Templating engine for rendering HTML pages.

## 📦 Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/PavanKumar1207/AI-Powered-Resume-Screening.git
   cd AI-Powered-Resume-Screening
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   python App.py
   ```

   The application will be accessible at `http://127.0.0.1:5000/`.

## 📄 Usage

1. **Upload Resumes**: Navigate to the upload section and upload multiple resumes in PDF format.
2. **Enter Job Description**: Input the job description in the provided text area.
3. **Process**: Click on the "Submit" button to process the resumes.
4. **View Results**: The application will display a ranked list of candidates based on their relevance to the job description.

## 📈 Example

*Include screenshots or examples of the application's interface and results here.*

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
