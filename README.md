# Jobify_datics

🌟 Job Portal & Chatbot Application
This project is a powerful Job Portal & Chatbot Application built using Streamlit, Gemini AI, and various Google APIs. It provides job-seekers with a unique tool for job search, chatbot interaction, and resume analysis, all within an intuitive and user-friendly interface.

📜 Project Overview
The Job Portal & Chatbot application enables users to:

Scrape LinkedIn job listings using the Scrapingdog API.
Engage with an AI chatbot that offers tailored job suggestions, resume enhancement tips, and general career advice.
Analyze resumes to match job roles with specific skills, generate job proposals, and offer keywords to strengthen job applications.
Recommend software houses based on specified job roles, locations, and fields using Google Custom Search API and Gemini AI.
🚀 Features
Job Scraping: Fetch job listings from LinkedIn for specific fields, experience levels, and locations, and display them in JSON format.
Intelligent Chatbot: Powered by Gemini AI, the chatbot offers personalized guidance on career development, job role alignment, and job proposal enhancements.
Resume Analyzer: Extracts text from uploaded PDF resumes and matches them with user-specified job roles, generating recommendations and a downloadable PDF job proposal.
Software House Recommendations: Provides a list of relevant software houses based on user-defined job criteria using either Google Search or Gemini AI.
🛠️ Tech Stack
Frontend: Streamlit for an interactive, Python-based UI.
Backend: FastAPI, integrated for efficient backend processes and API handling.
APIs:
Scrapingdog API for LinkedIn job scraping.
Google Custom Search API for software house recommendations.
Gemini AI for advanced job and resume analysis and chatbot interaction.
Python Libraries: requests, PyPDF2 for PDF parsing, and reportlab for PDF generation.
🔍 How It Works
Job Scraper: Enter search parameters, and the app scrapes LinkedIn jobs according to the user's preferred field and experience level, displaying results directly in Streamlit.
Chatbot Interaction: Users can ask career-related questions, with Gemini AI responding in real-time.
Software House Finder: Users receive lists of software houses based on location and specialization.
Resume Analysis and Job Proposal: Users can upload their resumes, receive an AI-suggested job proposal tailored to a specified role, and download a professional proposal PDF.
💡 Key Benefits
Career Alignment: Enhances resume content by matching skills and job requirements.
Simplified Job Search: Retrieves LinkedIn job data directly, saving time on manual job browsing.
