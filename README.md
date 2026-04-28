# AI Tools vs. Learning: Does Using AI Improve Learning or Reduce Effort?

**Course:** Data Analysis  
**Author:** Lucinda Ahmed  
**Date:** April 2026

---

## Project Overview

This project investigates how AI tools (such as ChatGPT and Claude) affect students' learning behavior and study effort. Using a custom survey collected from university and school students, we analyze whether AI tools genuinely improve understanding — or simply make tasks faster without deep learning.

---

## Research Question

> **Do AI tools improve student learning, or do they reduce the effort students put into studying?**

---

## Dataset

- **Source:** Original survey collected via Google Forms (April 2026)
- **Responses:** 95 participants (mostly university students aged 18–22)
- **File:** `AI_tools_vs_effort (Responses) - Form Responses 1.csv`

### Survey Topics Covered:
- Academic status, gender, age group
- AI tool usage frequency and purpose
- Time spent on AI tools per day
- Self-rated helpfulness of AI tools (scale 1–5)
- Whether AI improves understanding or just speeds up work
- Impact on study effort (scale 1–5)
- Productivity and over-reliance perceptions

---

## Notebook

**File:** `AI_tools_vs_Learning_notebook.ipynb`

### What the notebook does:
1. **Loads and cleans** the survey CSV (renames columns, checks for missing values)
2. **Descriptive statistics** — mean, median, mode for numeric columns
3. **7 visualizations** using matplotlib:
   - Chart 1: Respondent Status Distribution
   - Chart 2: How Often Respondents Use AI Tools
   - Chart 3: Helpfulness Rating (1–5)
   - Chart 4: Pie chart — Does AI improve understanding or just reduce effort?
   - Chart 5: Productivity Impact after using AI
   - Chart 6: Over-Reliance Agreement
   - Chart 7: Study Effort Impact Rating (1–5)

---

## How to Run

1. Clone this repository
2. Install dependencies: `pip install pandas matplotlib numpy`
3. Open the notebook: `jupyter notebook AI_tools_vs_Learning_notebook.ipynb`
4. Update the CSV file path in the **Load Data** cell to match your local path
5. Run all cells

---

## Project Structure

```
├── README.md
├── AI_tools_vs_effort (Responses) - Form Responses 1.csv   ← dataset
└── AI_tools_vs_Learning_notebook.ipynb                      ← analysis notebook
```
