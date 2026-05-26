# Budget Buddy: Smart Finance Assistant

## Project Overview

Budget Buddy is a Smart Finance Assistant built for the ISYS2001 Final Programming Project. It helps users understand their spending habits by analysing transaction data from a CSV file.

The assistant can clean transaction data, summarise spending by category, identify the highest spending areas, provide simple financial recommendations, answer finance-related questions, and calculate savings goals.

This project is designed to make personal finance easier to understand for students and everyday users.

---

## Features

- CSV transaction upload
- Data cleaning using pandas
- Spending analysis by category
- Financial recommendations
- AI finance chatbot
- RAG-style transaction context
- Savings goal calculator
- Gradio user interface
- Basic function tests
- Integration tests

---

## Input Data Format

The assistant uses a CSV file with these required columns:

- Date
- Amount
- Category
- Description

Example:

| Date | Amount | Category | Description |
|---|---:|---|---|
| 2024-08-01 | $50.00 | Groceries | Woolworths |
| 2024-08-02 | $20.00 | Transport | Bus fare |
| 2024-08-03 | $30.00 | Entertainment | Movie ticket |

---

## How to Run

1. Open `smart_finance_assistant.ipynb` in Google Colab.
2. Run the setup cells.
3. Enter the Hands-on-AI API key when required.
4. Run all notebook cells in order.
5. Use the Gradio interface to upload a transaction CSV file.
6. Ask a finance question.
7. Use the savings goal calculator.
8. Review the Smart Finance Assistant output.

---

## Technologies Used

- Python
- pandas
- hands-on-ai
- Gradio
- Google Colab
- GitHub

---

## Project Structure

- `smart_finance_assistant.ipynb` — main project notebook
- `README.md` — project overview and instructions
- `diary.md` — developer diary and AI collaboration log
- `ai-conversations/` — AI evidence and tracking
- `data/` — optional sample transaction data

---

## Testing

The notebook includes tests for:

- normal transaction data
- refunds and negative values
- missing values
- invalid CSV columns
- savings calculator input validation
- full workflow integration

---

## AI Collaboration

AI was used as a development assistant throughout the project. It helped with understanding the assignment, creating Python functions, designing the chatbot prompt, creating the RAG-style transaction context, building the Gradio interface, and writing tests.

AI use is documented in `diary.md` and the `ai-conversations` folder.

---

## Disclaimer

This project provides educational financial guidance only. It is not professional financial advice.
