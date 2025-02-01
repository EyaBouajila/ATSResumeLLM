# Smart ATS

![Screenshot 2025-02-01 152134](https://github.com/user-attachments/assets/3e183229-1eb7-4e82-ac11-391e413d913c)

## Overview
Smart ATS is a web-based application designed to help job seekers optimize their resumes for better compatibility with Applicant Tracking Systems (ATS). The app analyzes resumes against a provided job description, offering suggestions to improve matching accuracy, keyword inclusion, and overall profile summary.

## Features
- Upload a PDF resume and paste a job description.
- The application processes and extracts text from the uploaded resume.
- It uses Google Gemini AI to evaluate the resume against the job description.
- Provides a match percentage and suggests missing keywords to improve the resume.
- Generates a profile summary based on the job description.

## Technologies Used
- **Streamlit**: For creating the interactive web interface.
- **Google Gemini API**: To generate content and evaluate resume-job description matches.
- **PyPDF2**: For extracting text from PDF resumes.
- **dotenv**: To manage environment variables.
- **Python**: For application logic.

