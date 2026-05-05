# Playwright Singlish Transliteration Testing

## IT3040 – ITPM | Assignment 1 | Option 1

This project automates testing of the Chat Sinhala transliteration function at [https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator) using Playwright.

---

## Prerequisites

- Python 3.11 or 3.12
- Google Chrome (recommended)

---

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/ishani995371/playwright-assignment.git
   cd playwright-assignment
   ```

2. Install dependencies:
   ```
   pip install -U pip
   pip install playwright openpyxl
   playwright install
   ```

---

## Running the Tests

```
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

---

## Test Results

- Total test cases: 50
- All 50 test cases cover the 24 Singlish input types defined in Appendix 1
- Results are saved automatically in `Assignment 1 - Test cases.xlsx`
