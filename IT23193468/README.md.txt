# IT3040 - ITPM Assignment 1: Option 1
## Transliteration Accuracy Testing (Singlish to Sinhala)

### Project Overview
This project is designed to evaluate the accuracy of the chat-style Singlish to Sinhala transliteration function available at [Pixels Suite Chat Translator](https://www.pixelssuite.com/chat-translator). 

The goal was to identify 50 test cases where the system fails to correctly convert informal Singlish into Sinhala, covering 24 specific input types as defined in the assignment guidelines.

### Prerequisites
Before running the automation script, ensure you have the following installed:
* **Python:** Version 3.11 or 3.12
* **Web Browser:** Google Chrome (recommended) or Playwright's Chromium

### Installation Instructions

1. **Clone or Download the Repository:**
   Download this repository and navigate to the project directory.

2. **Install Required Dependencies:**
   Open your terminal/command prompt and run the following commands:
   ```cmd
   pip install -U pip
   pip install playwright openpyxl
   python -m playwright install




python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open