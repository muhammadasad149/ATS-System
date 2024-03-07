# ATS Resume Expert

**ATS Tracking System**

This Streamlit web application helps in analyzing resumes against job descriptions using Google's Generative AI model, Gemini. It provides insights on how well a resume matches a job description and highlights strengths, weaknesses, and percentage match.

## Features

- Upload resume in PDF format.
- Analyze resume against a job description.
- Get insights on the alignment of the resume with the job requirements.
- Calculate the percentage match between the resume and job description.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/ats-resume-expert.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Set up Google API key:
   
   - Obtain a Google API key from [Google Cloud Console](https://console.cloud.google.com/).
   - Create a `.env` file in the root directory.
   - Add your Google API key to the `.env` file:

     ```
     GOOGLE_API_KEY=your_google_api_key
     ```

## Usage

1. Run the Streamlit app:

```bash
streamlit run app.py
```

2. Access the app in your browser (by default, it will be available at `http://localhost:8501`).

3. Enter the job description in the text area provided.

4. Upload the resume in PDF format.

5. Click on the respective buttons to analyze the resume:
   - "Tell Me About the Resume": Provides professional evaluation of the resume against the job description.
   - "Percentage match": Calculates the percentage match between the resume and job description.
