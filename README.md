# **Cold Email Generator** 📧  

## **Overview**  
Cold Email Generator is an AI-powered tool that automates the process of extracting job descriptions from career pages and generating personalized cold emails. It helps professionals and businesses efficiently reach out to potential clients or employers with well-structured, data-driven emails.  

## **Features**  
✅ Extracts job postings from company career pages.  
✅ Cleans and processes job descriptions for better understanding.  
✅ Identifies required skills and matches them with relevant past projects.  
✅ Generates personalized cold emails using AI.  
✅ Provides a simple and interactive **Streamlit UI** for easy usage.  

## **How It Works**  

1. **User Inputs a Job Posting URL**  
   - The user provides a link to a job listing (e.g., Flipkart Careers page).  
   - The application fetches the webpage content.  

2. **Web Scraping & Text Cleaning**  
   - The system extracts raw text from the provided webpage.  
   - HTML tags, unwanted characters, and unnecessary whitespace are removed.  
   - The cleaned job description is prepared for analysis.  

3. **AI-Based Job Information Extraction**  
   - A Large Language Model (LLM) analyzes the job description.  
   - It identifies key details, such as:  
     - **Role** (e.g., Data Scientist, Software Engineer)  
     - **Experience Level** (e.g., Entry-Level, 3+ Years)  
     - **Required Skills** (e.g., Python, Machine Learning)  
     - **Job Description** (Summarized from the listing)  
   - The extracted job data is formatted into structured JSON.  

4. **Portfolio Matching with Relevant Projects**  
   - The system maintains a portfolio database containing past projects and skills.  
   - AI matches the job’s required skills with relevant past projects.  
   - The most relevant portfolio links are selected to showcase expertise.  

5. **Cold Email Generation**  
   - AI generates a personalized cold email using the extracted job details.  
   - The email highlights relevant experience and how the business can meet the job’s needs.  
   - Selected portfolio links are embedded in the email for credibility.  

6. **Email Output & User Interaction**  
   - The generated email is displayed in the **Streamlit UI**.  
   - The user can copy, modify, and send the email directly.  

## **Demo**  
  

https://github.com/user-attachments/assets/e1785bcd-257f-4fb2-9939-21408bb15663



## **Contributing**  
Want to improve this project? Fork the repo, make changes, and submit a PR! 
