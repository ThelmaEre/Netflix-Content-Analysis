# Netflix-Content-Analysis
This project explores Netflix's content library using Tableau.
It analyzes:
- The growth of Netflix titles (shows and movies) added per year
- The top genres on Netflix
- The top countries producing content on Netflix

## Dashboard Preview
<img width="999" height="799" alt="Netflix Content Analysis Dashboard" src="https://github.com/user-attachments/assets/2a04467f-5834-4c52-afc3-d5c6385a82e3" />

## Tools Used
- Tableau Public
- Excel (*for data cleaning*)

## Key Insights
- The amount of content released on Netflix grew rapidly between 2015 and 2019.
- There was a dip in content release in 2021.
- Dramas and Comedies are the top 2 genres that dominate the platform.
- The United States, India, United Kingdom, Japan and South Korea are the top 5 countries which contribute the highest number of movies/shows

## About the Dataset 
The dataset was downloaded from Kaggle. It includes Netflix titles (i.e movies and shows) released between 2008 and 2021. It is accompanied with fields such as genre, country, release year, and date added. 

## My Process
- **Step 1**: Data sourcing from online dataset platform **Kaggle**
- **Step 2**: Data cleaning in Excel
  - Ensured there were no duplicates in the show_id field by using the ‘remove duplicates’ function in excel. 
  - Ensured all dates were properly formatted in date format and not text by using the 'Text to Columns' function.
  - Ensured there were no weird values or spaces in the text columns (i.e title, director, country)
  - Eradicated mislabeled ratings (The original data had a mixup where some show duration values ended up in the ratings tab e.g 66mins instead of PG/R18+/TV-MA)
- **Step 3**: Data Visualization in Tableau
  - Imported Excel workbook into Tableau
  - Created 3 worksheets to analyze; top genres, top countries producing content, number of titles released per year
  - Assembled worksheets into dashboard to reveal patterns
- **Step 4**: Project documentation in GitHub

## Author
Created by **Thelma Eremionkhale (2026)**

*Link to dashboard*: https://public.tableau.com/app/profile/thelma.eremionkhale/viz/NETFLIXContentAnalysisDashboardbyThelmaEremionkhale/NetflixContentAnalysisDashboard?publish=yes 

*View individual worksheets here (Tableau Story)*: https://public.tableau.com/app/profile/thelma.eremionkhale/viz/NETFLIXContentAnalysisDashboardbyThelmaEremionkhale/Story1?publish=yes&showOnboarding=true
