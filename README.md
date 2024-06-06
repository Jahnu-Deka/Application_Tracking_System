# Application_Tracking_System

Gen AI Project

This project leverages Google Generative AI to create an Application Tracking System (ATS) that evaluates resumes against job descriptions. Users can copy job descriptions from job sites like LinkedIn or Naukri.com, paste them into the application, upload a PDF resume, and receive a professional evaluation or a percentage match based on the provided job description.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [License](#license)

## Features
- Upload a PDF resume
- Copy and paste job descriptions from job sites like LinkedIn or Naukri.com
- Generate responses based on the resume content using Google Generative AI
- Professional evaluation of the resume against the job description
- Percentage match of the resume to the job description
- Simple and intuitive Streamlit interface

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Application_Tracking_System.git
    cd Application_Tracking_System
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up your Google API key:
    - Create a `.env` file in the project directory.
    - Add your Google API key to the `.env` file:
      ```
      GOOGLE_API_KEY=your_google_api_key
      ```

## Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. In the Streamlit interface:
    - Copy a job description from a job site like LinkedIn or Naukri.com.
    - Paste the job description into the "Job Description" text area.
    - Upload your resume (PDF format) using the file uploader.
    - Click on "Tell Me About the Resume" to get a professional evaluation.
    - Click on "Percentage match" to get the percentage match of the resume to the job description.

## Requirements

- Python 3.x
- streamlit
- google-generativeai
- python-dotenv
- pdf2image

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
