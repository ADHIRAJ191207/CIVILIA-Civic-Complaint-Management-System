# CIVILIA-Civic-Complaint-Management-System

**CIVILIA** is an AI-powered civic complaint management system designed to classify, prioritize, and analyze urban issues submitted by citizens. The system leverages NLP techniques to process complaint descriptions and provides insightful data visualizations and structured summaries. It is built with Python and offers both CLI and GUI interfaces.

---

## Features

### 1. Complaint Collection and Classification
- Command-line interface to collect complaints from users.
- Uses NLP classification to detect issue type, urgency, and tags.
- Automatically timestamps and saves the complaint.

### 2. Natural Language Processing Engine
- Custom-built classifier using spaCy to determine:
  - Issue Type (e.g., pothole, leakage, streetlight failure)
  - Urgency Level (Low, Medium, High)
  - Semantic tags for filtering and analysis

### 3. Structured Data Storage
- All complaints are saved in a centralized `city_complaints.csv` file.
- Ensures persistent and structured logging for every user interaction.

### 4. Data Visualization Dashboard
- Built using Matplotlib and Seaborn.
- Displays:
  - Complaint frequency over time
  - Issue type distribution
  - Urgency distribution
  - Top complaint locations

### 5. Complaint Viewer Interface
- Allows filtered search through stored complaints.
- Supports querying by location, issue type, and urgency.

### 6. PDF Report Generator
- Generates a structured, professional summary report in PDF format.
- Includes:
  - Total complaint count
  - Breakdown by urgency and issue type
  - Latest complaint summary
- Built using `reportlab` and `pandas`

---

## Tech Stack

- Python 3.13
- spaCy
- pandas
- seaborn
- matplotlib
- tkinter
- reportlab

---

## Folder Structure

CIVILIA/
│
├── complaint_input.py # Module 1
├── nlp_classifier.py # Module 2
├── dashboard.py # Module 4
├── complaint_viewer.py # Module 5
├── report_gen.py # Module 6
│
├── data/
│ └── city_complaints.csv # Module 3 - complaint database

## Status

CIVILIA is under active development. More modules and enhancements are planned, including real-time issue tracking, escalation protocols, and smart reminders.

---

## Author

Developed by Adhiraj Singh  
Class 12, India  
Aspiring Computer Science and AI Student  
MIT Applicant 2025-26

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
