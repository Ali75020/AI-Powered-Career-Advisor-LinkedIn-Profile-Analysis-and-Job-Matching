# AI-Powered Career Advisor 🚀  
**Authors**: Ali CHERIFI ALAOUI, Fodié NIAKATE  

## Overview  
This project leverages cutting-edge **Large Language Models (LLMs)** and **Prompt Engineering** to analyze LinkedIn profiles, suggest tailored job opportunities, and provide salary benchmarks. It integrates OpenAI's GPT-4 and APIs from **RapidAPI** to automate career insights and job recommendations.  

---

## Table of Contents  
1. [Features](#features)  
2. [How It Works](#how-it-works)  
3. [Project Structure](#project-structure)  
4. [Future Enhancements](#future-enhancements)  

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

## Project Structure  
- **linkedin_scraper.py**: Module for scraping LinkedIn profile data via RapidAPI.  
- **profile_analysis.py**: Implements GPT-4 prompt engineering for analysis.  
- **job_search.py**: Integrates job search APIs (via RapidAPI) to find matching job postings.  
- **salary_insights.py**: Fetches salary benchmarks using Glassdoor's Salary API (via RapidAPI).  
- **utils/**: Helper functions and utilities.  

---

## Future Enhancements  
- Expand to include other professional platforms (e.g., GitHub, Behance).  
- Add support for more salary APIs to improve data reliability.  
- Build a web interface for non-technical users.  

---

## Authors  
- **Ali CHERIFI ALAOUI**  
- **Fodié NIAKATE**  

---

## License  
This repository is intended to demonstrate technical proficiency in AI and prompt engineering. It is shared for professional review only and is not intended for replication or commercial use.  
