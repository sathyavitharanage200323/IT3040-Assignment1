#IT3040-Assignment1
Transliteration Accuracy Testing Assignment

##Prerequisites
-Python 3.11 or 3.12
-Google Chrome

##How to Install Dependencies
pip install playwright openpyxl 
python -m playwright install

##How to Run Tests
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

##Project Structure
-test_automation.py - Playwright automation script
-Assignment 1 - Test cases.xlsx - Test cases with results
