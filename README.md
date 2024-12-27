# AI-Powered Career Advisor 🚀  
**Authors**: Ali CHERIFI ALAOUI, Fodié NIAKATE  

## Overview  
This project leverages cutting-edge **Large Language Models (LLMs)** and **Prompt Engineering** to analyze LinkedIn profiles, suggest tailored job opportunities, and provide salary benchmarks. It integrates OpenAI's GPT-4 and external APIs to automate career insights and job recommendations.  

---

## Table of Contents  
1. [Features](#features)  
2. [How It Works](#how-it-works)  
3. [Setup Instructions](#setup-instructions)  
4. [Project Structure](#project-structure)  
5. [Future Enhancements](#future-enhancements)  

---

## Features  
- **LinkedIn Profile Analysis**: Extracts and processes LinkedIn profile data.  
- **Job Suggestions**: Uses GPT-4 and prompt engineering to recommend job titles, keywords, and career advice.  
- **Job Matching**: Finds relevant job postings via external job search APIs (e.g., LinkedIn, Glassdoor, Indeed).  
- **Salary Insights**: Provides salary benchmarks based on job title, location, and industry trends.  

---

## How It Works  
1. **Scraping LinkedIn Profiles**  
   - Scrapes LinkedIn profile data using an API to extract career-related insights.  

2. **LLM-Based Analysis**  
   - Processes data with OpenAI GPT-4 to generate actionable career recommendations (e.g., job titles, keywords).  

3. **Job Matching**  
   - Searches job portals for relevant positions matching the suggested job titles and keywords.  

4. **Salary Estimation**  
   - Uses Glassdoor's Salary API to provide median, minimum, and maximum salary data for selected jobs.  

---

## Setup Instructions  

### Prerequisites  
- Python 3.8 or higher  
- API Keys:  
  - OpenAI API Key  
  - LinkedIn API Key  
  - Job Search API Key  
  - Glassdoor Salary API Key  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo-link/ai-powered-career-advisor.git
   cd ai-powered-career-advisor
