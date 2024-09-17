# ATS-using-Gemini-Pro-API

Problem Statement:
The objective of this project was to enhance resume optimization using advanced NLP techniques and the Gemini Pro API. The goal was to develop an Application Tracking System (ATS) that can analyze resumes, provide actionable recommendations based on job descriptions, and offer insights into in-demand skills.

Approach:
To achieve this, I used the pdf2image library to convert uploaded PDF resumes into images. I used the IO and Base64 libraries to convert these images into bytes and then to text that can be interpreted by the Gemini LLM. The application was hosted using Streamlit, providing a user-friendly interface for interacting with the ATS. NLP concepts were applied to clean and preprocess the data, ensuring accurate analysis.

I modified the ATS to offer tailored recommendations for updating resumes according to job descriptions. The system generates a score for the resume and suggests relevant in-demand skills to learn, helping users align their resumes with current job market requirements.

Conclusion:
This project successfully integrated the Gemini Pro API with advanced NLP techniques to create a robust ATS application. By converting PDFs to text vectors and implementing resume recommendations, the tool provides valuable feedback for improving resume effectiveness and aligning with job market trends.
