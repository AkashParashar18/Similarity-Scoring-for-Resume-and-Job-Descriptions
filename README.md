# Similarity Scoring for Resume and Job Descriptions

This project focuses on developing a system that compares resumes to job descriptions and provides a similarity score to optimize the recruitment process for Applicant Tracking Systems (ATS). The objective is to help recruiters assess how well a candidate’s resume matches the requirements of a job posting using machine learning techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project uses **Gemini Pro** for natural language processing, **Streamlit** for the user interface, and **Python** for implementing the backend logic. The system processes resumes and job descriptions, compares them based on their content, and generates a similarity score.

The system is designed to:
- Parse and preprocess resumes and job descriptions.
- Extract relevant features from both documents.
- Compute a similarity score based on these features.
- Visualize the results for easy interpretation.

## Technologies Used
- **Python**: The primary programming language used for data processing, model training, and scoring.
- **Gemini Pro**: Utilized for language model-based similarity comparison.
- **Streamlit**: Used to create an interactive web interface.

## Features
- Upload resumes and job descriptions in various formats (e.g., PDF, DOCX).
- Automatically extract text and process the documents for similarity scoring.
- Visual representation of the similarity score.
- Clean, intuitive user interface for interaction and results display.
- Scalable to handle multiple resumes and job descriptions for bulk processing.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/similarity-scoring-resume-job-description.git
   cd similarity-scoring-resume-job-description
   ```

2. Set up a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate     # For Windows
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

5. Open the application in your browser at `http://localhost:8501`.

## Usage
1. Upload a resume file and a job description.
2. The system will preprocess both documents, compare them, and return a similarity score.
3. The score will reflect how closely the resume matches the job description, helping recruiters quickly assess candidates' suitability.

## Project Structure
```
similarity-scoring-resume-job-description/
│
├── app.py                # Streamlit app for the user interface
├── requirements.txt      # List of dependencies
├── model/                # Pre-trained models or custom models used for NLP
├── utils/                # Helper functions for text preprocessing and similarity calculation
├── data/                 # Folder for storing sample data (optional)
└── README.md             # This README file
```

## Contributing
Contributions are welcome! If you'd like to improve this project, please fork the repository and submit a pull request. Ensure your code follows the existing style and passes tests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
