### AI Resume Analyzer

## Overview

- The AI Resume Analyzer is a tool designed for parsing and analyzing resumes using natural language processing. It extracts relevant information, identifies keywords, categorizes resumes into different sectors based on key terms, and provides recommendations and predictions to applicants and recruiters.

## Features

# Applicant Features:

- Extracts and displays personal information, skills, and key terms from uploaded resumes.

- Provides recommendations on additional skills, certifications, and courses that can enhance the resume.

- Predicts suitable job roles based on the extracted keywords.

- Assigns an overall score to the resume based on industry relevance.

- Offers interview tips and resources.

- Administrator Features:

- Collects and structures applicant data in a tabular format.

- Exports data as CSV files for further analysis.

- Manages uploaded resumes.

- Displays user feedback and ratings.

- Generates pie charts for various statistics, including:

- Resume ratings

- Predicted job roles

- Experience levels

- User demographics

- Resume scores

## Feedback System:

- Allows users to submit ratings and comments.

- Displays overall user feedback statistics.

- Scope and Applications

- Converts unstructured resume data into structured formats suitable for analytics.

- Helps users improve their resumes with suggestions and iterative testing.

- Assists educational institutions in analyzing student resumes before placements.

- Identifies job roles that applicants are most interested in.

- Enhances the tool's functionality through user feedback.

## Technology Stack

- Frontend: Web-based interface for user interaction.

- Backend: Python-based API for data processing.

- Database: MySQL for storing user data and analytics.

- Modules Used: NLP-based libraries for resume parsing and keyword extraction.

## System Requirements

- To run this project, ensure you have the following installed:

- Python (3.9.12) – Download

- MySQL – Download

- Visual Studio Code (Recommended Editor) – Download

- Visual Studio Build Tools for C++ – Download

## Installation Guide

- Clone the repository using Git:

- git clone https://github.com/deepakpadhi986/AI-Resume-Analyzer.git

- Navigate to the project directory and set up a virtual environment:

- python -m venv venvapp
- cd venvapp/Scripts
- activate

## Install required dependencies:

cd ../..
cd App
pip install -r requirements.txt
python -m spacy download en_core_web_sm

Create a MySQL database named cv and update the connection details in App.py.

Replace the resume_parser.py file in the pyresparser module with the customized version included in the repository.

Run the application:

streamlit run App.py

## Troubleshooting

- If a GeocoderUnavailable error occurs, check your internet connection.

- For installation issues, refer to the provided setup guide or video tutorials.

## Usage

- Upload a resume to see extracted data and suggested improvements.

- Use the provided test resumes to explore the tool’s features.

## Admin credentials:

Username: admin

Password: admin@resume-analyzer

Future Enhancements

Predicting applicant experience levels.

Enhancing resume scoring criteria.

Expanding recommendations to additional job sectors.

Extracting more details from resumes.

Implementing user profile tracking for deeper analytics.