# resume-parser-job-matcher
Resume Parser & Job Matcher

📌 Project Overview

This project is an automated resume parser and job matcher that:

Extracts job titles and skills from a PDF resume.

Searches Indeed API for matching job listings based on extracted skills.

Returns a list of best-matching remote job opportunities.

🚀 Features

✅ Extracts text from resumes (PDF format) using PyMuPDF.
✅ Uses spaCy NLP to detect job titles and skills.
✅ Calls Indeed API to search for matching jobs.
✅ Filters and ranks jobs based on extracted skills.
✅ Outputs job title, company, location, and apply link.

🛠️ Requirements

Ensure you have Python installed, then install the required dependencies:

pip install spacy pymupdf requests
python -m spacy download en_core_web_trf

pip install spacy pymupdf requests
python -m spacy download en_core_web_trf

⚙️ Setup & Usage

Clone the repository:

git clone https://github.com/your-username/resume-parser-job-matcher.git
cd resume-parser-job-matcher

Replace INDEED_API_KEY in resume_parser.py with your actual Indeed API key.

Run the script with your resume:

python resume_parser.py

Check the extracted skills & job matches in the console output.

📂 Output Example

Extracted Job Titles: ['Software Engineer']
Extracted Skills: ['Python', 'JavaScript', 'SQL', 'Data Analysis']

Best Matching Jobs:
Python Developer at ABC Tech - Remote
Apply Here: https://indeed.com/job/python-developer-123

🔥 Future Enhancements

Improve job title detection using a larger dataset.

Add LinkedIn API integration for more job sources.

Create a web UI for uploading resumes and viewing job matches.

🤝 Contributions

Feel free to fork this project, submit pull requests, or open issues! 🚀


