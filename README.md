# NGO_Grant_DataCollector
An automating grant collection from NGOBox.org that extracts all grant announcements from NGOBox.org and saves them in a structured format for easy access. Built to assist with grant tracking, research, and nonprofit outreach, making data collection faster and smarter.

#Overview
This tool automates the extraction of grant announcements from the NGOBox platform. It scrapes grant titles, descriptions, deadlines, and other key information, storing the data in a structured Excel sheet for easy access and further analysis.

Ideal for non-profits, research teams, or student-led consulting groups looking to track funding opportunities efficiently.

#Features
-Scrapes all grant listings from NGOBox
-Extracts key details: Title, Organization, Deadline, and Summary
-Appends results to an Excel sheet
-One scrape at a time — avoids duplication and site overload
-Modular and beginner-friendly codebase

#Upcoming Features
Keyword-based output generation via API:
-Planning to integrate a backend API that allows users to input keywords and get filtered grant listings based on those terms.
-Date-range filtering
-Scrape scheduling (e.g., weekly auto-runs)
-Web UI for easy interaction
-Auto-emailing of results

#Tech Stack
-Python
-BeautifulSoup for web scraping
-requests for HTTP handling
-pandas for data manipulation
-openpyxl for Excel operations
