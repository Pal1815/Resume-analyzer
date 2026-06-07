# ResumeAI — Know Your Chances Before You Apply

A web app that analyzes your resume against any job posting and gives you a match score with detailed feedback.

## What it does
- Upload your resume as a PDF
- Paste a job posting URL
- Get a match score out of 100
- See which skills you have and which ones are missing
- Get YouTube tutorials and paid courses for every missing skill
- Get specific fixes for your resume with exact rewrites

## How it works
The frontend sends your resume and job URL to an n8n workflow. n8n extracts the resume text, scrapes the job description, and sends both to an AI which returns a detailed analysis as JSON.

## Tech used
- HTML, CSS, JavaScript (frontend)
- n8n (workflow automation)
- OpenAI GPT-4o mini (AI analysis)

## Supported job sites
Internshala, Wellfound, Unstop, Indeed
(LinkedIn and Naukri are not supported)

## Live Demo
(https://resume-analyzerai-one.vercel.app)
