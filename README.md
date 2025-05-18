# AI Resume Critiquer

AI Resume Critiquer is a Streamlit web app that allows users to upload their resumes (PDF or TXT) and receive AI-powered, tailored feedback to improve their resumes. The app uses OpenAI's GPT-4o-mini model to provide detailed analysis and constructive suggestions based on the uploaded resume content and optionally the targeted job role.

---

## Features

- Upload resumes in PDF or TXT formats.
- Optional input for a specific job role to customize feedback.
- AI-powered critique focusing on:
  - Content clarity and impact
  - Skills presentation
  - Experience descriptions
  - Specific improvement recommendations
- Clear and structured feedback from an expert virtual HR reviewer.


## Getting Started

### Prerequisites

- Python 3.8+
- An OpenAI API key with access to the GPT-4o-mini model
- `uv` package manager

### Installation

1. Clone the repository or copy the script.

2. Install dependencies:

```bash
uv install streamlit PyPDF2 openai python-dotenv

3. Run the project:
uv run streamlit run main.py
