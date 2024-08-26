# Applicant-Tracking-System
Applicant Tracking System (ATS) is built using the Gemini Pro LLM model for natural language processing and classification. It allows users to streamline their hiring process by efficiently managing resumes, extracting text from various file formats, and providing insights into applicant data.

## Features:
- Resume Tracking: Easily manage and track resumes of job applicants.
- Text Extraction: Extract text content from PDF and DOCX files for further processing.
- Streamlit Interface: User-friendly web interface powered by Streamlit.
- Natural Language Processing: Utilizes the Gemini Pro LLM model for text classification and analysis.
- Google Generative AI Integration: Enhances the application with advanced AI capabilities.
- Environment Configuration: Integration with python-dotenv for environment variable management.

## Dependencies:
- Gemini Pro LLM: Natural language processing model for text classification.
- Streamlit: Web application framework for building interactive web applications.
- Google Generative AI: Integrates advanced AI capabilities into the application.
- python-dotenv: Manages environment variables for configuration.
- pdf2image: Converts PDF files to images for text extraction.
- docx2txt: Extracts text content from DOCX files.
- PyPDF2: Library for reading and manipulating PDF files.

## Installation:
Clone the repository:
```
git clone https://github.com/nisarg-github2000/Applicant-Tracking-System.git
```
Navigate to the project directory:
```
cd Applicant-Tracking-System
```
Create a Python virtual environment:
```
python3 -m venv .
```
Activate venv:
```
source bin/activate
```
Install the required dependencies:
```
pip install -r requirements.txt
```
Make a .env file and add your Google Gemini API Key to the file
```
GOOGLE_API_KEY="your_key"
```
Run the Streamlit application:
```
streamlit run app.py
```
Access the application through your web browser using the provided local address.

## Contributing 🤝
Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, feel free to open an issue or submit a pull request.
