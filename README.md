# AI Resume Screening & ATS Analysis Workflow
Project Overview

This project is an AI-powered resume screening and ATS analysis workflow built using n8n, Groq, and Google Sheets.

The workflow automates the initial screening of candidate resumes by receiving resume data through a webhook, analyzing the resume using an AI model, generating structured candidate information, and storing the results in Google Sheets for HR and recruitment review.

The system extracts important candidate information such as the candidate name, ATS score, hiring recommendation, screening status, top skills, missing skills, and an overall summary.

The goal of this project is to reduce the time required for manual resume screening and provide HR teams with a consistent, structured, and automated method for evaluating candidates.

Key Workflow

Resume Input → Webhook → AI Resume Analysis → Structured Candidate Data → Google Sheets → Webhook Response

Technologies Used

- n8n for workflow automation
- Groq for AI-powered resume analysis
- Google Sheets for storing candidate evaluation results
- Webhooks for receiving resume data and returning the workflow response

Project Structure

Project Structure

AI-Resume-Screening-Workflow/
│
├── AI_Resume_Screening_Workflow.json
├── workflow.png
└── README.md

File Description

- "AI_Resume_Screening_Workflow.json" - n8n workflow that contains the complete automation logic.
- "workflow.png" - Screenshot of the n8n workflow.
- "README.md" - Project documentation, setup instructions, workflow description, and usage information.


