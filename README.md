# AI Feedback Analysis Dashboard

An AI-powered Customer Feedback Analysis Dashboard built using Streamlit, Gemini AI, SQLite, Pandas, and OpenPyXL.

The application allows businesses to analyze customer feedback automatically using Google's Gemini AI, classify sentiment, identify feedback categories, generate summaries, store results in a database, visualize analytics, and export reports to Excel.

---

## Features

### AI Feedback Analysis
- Analyze customer feedback using Gemini AI
- Detect sentiment automatically
- Classify feedback into categories
- Generate concise summaries

### Multiple Input Methods
- Manual feedback entry
- Excel file upload for bulk analysis

### Database Management
- Store analyzed feedback in SQLite
- View all feedback records
- Search feedback by sentiment
- Delete feedback records

### Dashboard Analytics
- Total feedback count
- Positive feedback count
- Negative feedback count
- Neutral feedback count
- Sentiment distribution chart

### Reporting
- Export complete analysis reports to Excel
- Generate summary statistics automatically
- Download individual feedback analysis results

---

## Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Core Programming |
| Streamlit | Web Application UI |
| Gemini 2.5 Flash | AI Feedback Analysis |
| SQLite | Database Storage |
| Pandas | Data Processing |
| OpenPyXL | Excel Report Generation |

---

## Project Architecture

Customer Feedback
        ↓
Manual Entry / Excel Upload
        ↓
Gemini AI Analysis
        ↓
Sentiment Detection
        ↓
Category Classification
        ↓
Summary Generation
        ↓
SQLite Database Storage
        ↓
Dashboard Analytics
        ↓
Search / Delete Operations
        ↓
Excel Report Export

---

## Database Schema

Table: FeedbackAnalysis

| Column | Data Type |
|----------|----------|
| id | INTEGER PRIMARY KEY AUTOINCREMENT |
| feedback | TEXT |
| sentiment | TEXT |
| category | TEXT |
| summary | TEXT |
| analyzed_at | TEXT |

---

## Installation

pip install streamlit
pip install pandas
pip install google-generativeai
pip install openpyxl

### Upload & Analyze
- Enter customer feedback manually
- Upload Excel files containing feedback
- Generate sentiment, category, and summary using AI
- Store analyzed results in the SQLite database
- Download individual feedback analysis reports

### Dashboard
- View total feedback statistics
- Monitor positive, negative, and neutral feedback counts
- Visualize sentiment distribution using charts
- Browse all stored feedback records
- Track overall customer sentiment trends

### Search Feedback
- Filter feedback records by sentiment
- View matching records instantly
- Quickly locate positive, negative, or neutral feedback

### Delete Feedback
- Remove feedback records using Feedback ID
- Maintain clean and updated database records

### Export Report
- Generate comprehensive Excel reports
- Export all analyzed feedback records
- Generate summary metrics automatically
- Download reports for business analysis and reporting

---

## Example Feedback Analysis

### Input

"The product quality is excellent and delivery was quick."

### AI Output

**Sentiment:** Positive

**Category:** Product

**Summary:** Customer is satisfied with the product quality and delivery experience.

---

## Excel Report Structure

### Sheet 1: Analysis Results

- ID
- Feedback
- Sentiment
- Category
- Summary
- Analysis Timestamp

### Sheet 2: Summary

- Total Feedback
- Positive Count
- Negative Count
- Neutral Count

---

## Learning Outcomes

This project demonstrates:

- Streamlit Web Application Development
- Gemini AI Integration
- Prompt Engineering
- SQLite Database Operations
- CRUD Operations
- Data Analytics
- Excel Automation
- Dashboard Development
- AI-Powered Business Applications
- Database Design and Management
- AI-Based Text Classification
- Business Intelligence Reporting
- File Handling and Report Generation
