# IT23716650
- IT3040 Assignment 1

## Student ID and Name
- Name: Wickramaatachchi W.A.A.I
- Student ID: IT23716650

## Project Title
Automated Testing for Singlish to Sinhala Transliteration System

## Repository
https://github.com/Ashanisuranga2002/itpm-assignment-1-transliteration-testing.git

---

## Project Description
This project automates testing for the Pixelssuite Chat Sinhala transliteration function using Playwright and Python.
The test cases evaluate how accurately the application converts chat-style Singlish input into Sinhala output.

---

## Project Structure
IT23629226/
- IT23629226_test_automation.py  -> Playwright automation script
- IT23629226_Assignment 1 - Test cases.xlsx  -> Excel file with test cases and results
- IT23629226_requirements.txt  -> Python dependencies
- README.md  -> Project documentation
- .venv/ (optional)  -> Virtual environment (not required)

---

## Technologies Used
- Python
- Playwright (UI Automation)
- OpenPyXL (Excel handling)

---

## Prerequisites
- Python 3.11 or 3.12
- Google Chrome or Playwright Chromium
- VS Code

---

## How to Run the Project

1. Open a terminal inside the project folder.

2. (Optional) Create and activate a virtual environment:

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

macOS/Linux:

```bash
source .venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r IT23629226_requirements.txt
playwright install
```

4. Run the automation script:

```bash
python IT23629226_test_automation.py --excel "IT23629226_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"
```

---

## Output
- Results are automatically written to the Excel file.
- Columns updated:
	- Actual output
	- Status (PASS / FAIL)

---

## Test Case Details
- Total Test Cases: 50+
- Test Type: Negative Testing

### Covered Scenarios
- Invalid or mixed script input
- Spelling variations and slang words
- Emojis and special characters
- Numbers and symbols
- Empty input and whitespace-only input
- Long messages and repeated characters
