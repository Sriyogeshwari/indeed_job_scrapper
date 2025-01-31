# indeed_job_scrapper
This script uses Apify's API to scrape job listings from Indeed based on specific filters such as job title, location, and country. It retrieves job data and saves it in a structured CSV file for further analysis. The script is useful for job market research, tracking hiring trends, or personal job searches.

##  Features
✔ Scrapes **job titles, company names, locations, and posting dates**  
✔ Uses **Apify Client** for automated job extraction  
✔ Saves results in a structured **CSV file**  
✔ Simple and lightweight script 

## 🛠 Requirements & Installation

1️⃣ **Install Dependencies**  
pip install apify-client pandas


2️⃣ **Sign Up for Apify & Get API Key**
To use this scraper, you need an Apify API key. 
Follow these steps:

    Go to Apify → https://apify.com/
    Click "Sign Up" (or log in if you already have an account).
    After signing in, go to "Account" > "API&Integrations".
    Click "personal ApI token" and copy the token.
    Replace "your-apify-api-key" in the script with your actual API Token.

⚠️ Apify API Usage Limitations (Free Tier)
Note on Free Tier Limits:

Apify offers a free tier that allows you to run actors (such as the job scraping actor you're using) a limited number of times each month. Once your free runs are exhausted, you'll need to wait for the next month for more runs or upgrade to a paid plan to continue using Apify services.

🚨 Free Plan Details:
The free tier typically allows a set number of actor executions (runs) per month. After those runs are used up, no additional runs will be allowed unless you upgrade to a paid subscription or wait until the next billing cycle.
You can check your usage stats and remaining runs in your Apify dashboard.
