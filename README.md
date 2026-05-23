# AI Resume Relevance Scoring Workflow

## Objective
This project automates candidate resume evaluation against a Job Description using AI, Google Drive, Google Sheets, and n8n.

The workflow continuously monitors uploaded resumes, extracts resume content, compares it against the Job Description, generates a relevance score, and updates a centralized evaluation sheet automatically.

---

## Workflow Overview

Google Drive Trigger  
→ Download Resume PDF  
→ Extract Resume Text  
→ Download Job Description PDF  
→ Extract JD Text  
→ AI Resume Evaluation  
→ Google Sheets Output Update

---

## Folder Structure

Main Folder:
- Resumes Folder
- Job Description Folder
- Resume Evaluation Output Sheet

---

## Features

- Automatic resume detection from Google Drive
- PDF text extraction
- AI-powered resume relevance scoring
- Candidate recommendation generation
- Automated Google Sheets update
- Resume tracking with file references
- Explainable reasoning behind scoring

---

## Technologies Used

- n8n
- OpenAI
- Google Drive API
- Google Sheets API

---

## Output Includes

- Candidate Name
- Candidate Mobile
- Candidate Email
- Resume File Name
- Resume File Link
- Relevance Score
- Recommendation
- AI-generated reasoning

---

## Recommendation Logic

- 80+ → Strong Fit
- 60–79 → Moderate Fit
- Below 60 → Low Fit

---

## Brownie Point Enhancements

- AI-generated explainable scoring
- Automated workflow orchestration
- Continuous monitoring of resume uploads
- Recruiter-friendly recommendation system
- Centralized evaluation tracking

---

## Future Enhancements

- Multi-job-description support
- Duplicate resume detection
- Recruiter dashboard
- Resume ranking leaderboard
- Skill-gap analytics
- Candidate shortlist automation

---

## Repository Contents

- n8n Workflow JSON
- Workflow screenshots
- Google Sheet output samples
- Drive folder structure

---

## Author

Kshitij Singh
