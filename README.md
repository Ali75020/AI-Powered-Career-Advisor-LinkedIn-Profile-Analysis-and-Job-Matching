# AI-Powered Career Advisor 🚀  
**Authors**: Ali CHERIFI ALAOUI, Fodié NIAKATE  

## Overview  
This project leverages cutting-edge **Large Language Models (LLMs)** and **Prompt Engineering** to analyze LinkedIn profiles, suggest tailored job opportunities, and provide salary benchmarks. It integrates OpenAI's GPT-4 and APIs from **RapidAPI** to automate career insights and job recommendations.  

---

## Table of Contents  
1. [Features](#features)  
2. [How It Works](#how-it-works)  
3. [Setup Instructions](#setup-instructions)  
4. [Project Structure](#project-structure)  
5. [Future Enhancements](#future-enhancements)  

---

## Features  
- **LinkedIn Profile Analysis**: Extracts and processes LinkedIn profile data using RapidAPI.  
- **Job Suggestions**: Uses GPT-4 and prompt engineering to recommend job titles, keywords, and career advice.  
- **Job Matching**: Finds relevant job postings via job search APIs (LinkedIn, Glassdoor, Indeed, via RapidAPI).  
- **Salary Insights**: Provides salary benchmarks using Glassdoor Salary API (via RapidAPI).  

---

## How It Works  
1. **Scraping LinkedIn Profiles**  
   - Scrapes LinkedIn profile data using RapidAPI to extract career-related insights.  

2. **LLM-Based Analysis**  
   - Processes data with OpenAI GPT-4 to generate actionable career recommendations (e.g., job titles, keywords).  

3. **Job Matching**  
   - Searches job portals (via RapidAPI) for relevant positions matching the suggested job titles and keywords.  

4. **Salary Estimation**  
   - Uses the Glassdoor Salary API (via RapidAPI) to provide median, minimum, and maximum salary data for selected jobs.  

---

## Setup Instructions  

### Prerequisites  
- Python 3.8 or higher  
- API Keys:  
  - OpenAI API Key  
  - LinkedIn API Key (via RapidAPI)  
  - Job Search API Key (via RapidAPI)  
  - Glassdoor Salary API Key (via RapidAPI)  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo-link/ai-powered-career-advisor.git
   cd ai-powered-career-advisor
