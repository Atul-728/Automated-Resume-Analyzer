# Automated-Resume-Analyzer
The Automated Resume Analyzer is a Python-based tool that matches applicant resumes with recruiter-defined job skills using NLP. It features separate recruiter and applicant interfaces, password-protected recruiter login, and provides real-time feedback to applicants based on skill matching.

## Features
- Separate Recruiter and Applicant Interfaces
- Password-Protected Recruiter Panel
- NLP-Based Resume Skill Matching
- Real-time Feedback for Applicants
- Python GUI (Tkinter) for User Interface

## Technologies
- Python
- Tkinter for GUI
- spaCy for Natural Language Processing (NLP)
- PyPDF2 for Resume Parsing
- Google OAuth2 for Gmail API Integration

## How to Use
1. **Recruiter**:
   - Login with a password (set in the terminal).
   - Define the required job skills.
   - Confirm setup, and skills will be matched automatically against uploaded resumes.
2. **Applicant**:
   - Upload your resume via the GUI.
   - Receive a message indicating selection or rejection based on skill matching.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Atul-728/Automated-Resume-Analyzer.git
   
## Future Enhancements
- Add support for multiple job postings.
- Implement more advanced fuzzy logic for skill matching.
- Improve applicant feedback with detailed skill gap analysis.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
