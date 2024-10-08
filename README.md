# Twinmo: LinkedIn Web Scraping

### Overview
This project is designed to scrape job listings from LinkedIn for positions that require LabVIEW skills. The goal is to identify companies looking for LabVIEW expertise, which may indicate a need for test automation in their operations. This project targets consumer products and consumer electronics companies, excluding aerospace, defense, and semiconductor firms.

### Features
* State-specific Job Search: Focuses on job listings in various regions of the world.
* Company Identification: Extracts and lists companies that are hiring for LabVIEW positions.
* Industry Filtering: Ignores job listings from aerospace, defense, and semiconductor companies to focus on consumer products and electronics sectors.
* Data Storage: Saves the scraped data into a CSV file for easy analysis and further use.

### Instructions
* Install the packages via terminal given in requirements.txt.
* In lines 9 and 10 of ragavan_linkedin.py enter your username and password.
* For a different region or job role change line 109. Before "&start" paste the url 4 times in that array (eg if you want Program Manager in North Carolina paste
 https://www.linkedin.com/jobs/search/currentJobId=3988382936&geoId=103255397&keywords=program%20manager%20jobs&origin=JOB_SEARCH_PAGE_SEARCH_BUTTON&refresh=true before "&start" 4 times)
* Run the program via terminal: python ragavan_linkedin.py.
* You will get a CSV file with the top 100 jobs, convert it at this link: https://www.convertcsv.com/csv-viewer-editor.htm#google_vignette.
* Use the top 100 jobs for your convenience.

**By Ragavan**
