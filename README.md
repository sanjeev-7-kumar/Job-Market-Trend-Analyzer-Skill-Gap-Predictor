# Career Analytics — Job Market Trends & Skill Gap Predictor

## Overview

Career Analytics is a project that tracks job market trends, salary distributions, and skill gaps by comparing resumes against job descriptions. It helps job seekers and students identify in-demand skills, understand job trends, and bridge gaps in their resumes to improve their career prospects.

This project uses **Python**, **Streamlit**, and **machine learning** techniques to provide meaningful insights into the job market. It also includes **data visualization** and **skill gap prediction** to help individuals align their skill sets with industry needs.

---

## Features

- **Job Market Trends**: Analyze job market trends over time.
- **Salary Heatmap**: Visualize role-wise average salaries by city.
- **City-Wise Job Distribution**: Understand the job distribution across different cities.
- **Job Description Clustering**: Group job descriptions to identify role-specific trends.
- **Skill Gap Analysis**: Upload a resume and identify missing skills for specific job roles.

---

## Installation

### Requirements

- **Python 3.11** or later
- **VS Code** or any code editor

### Setup Instructions

1. **Download the Project**  
   Download the project ZIP:  
   [Career Analytics Starter](sandbox:/mnt/data/career_analytics_starter.zip)  
   Extract it to a folder (e.g., `C:\projects\career_analytics_starter`).

2. **Install Python 3.11**  
   - Install from [Python.org](https://www.python.org/downloads/)  
   - Make sure to check “Add Python to PATH” during installation.

3. **Install Dependencies**  
   Open a terminal in VS Code or Command Prompt and run:
   ```bash
   cd C:\projects\career_analytics_starter
   python -m venv .venv
   .venv\Scripts\activate
   pip install --upgrade pip
   pip install streamlit pandas scikit-learn pdfplumber plotly
