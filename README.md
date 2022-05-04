# Scraping Natural Gas Futures with Python, GS, Tableau
 
Welcome to my first GitHub project!

This is where I practice my Data Science skills. 

With my expertise in the Natural Gas industry, I am utilizing my programming skills on projects. In my first personal data science project, I created a Tableau Public workbook that displays a price for Natural Gas in Henry Hub, Louisiana for every month through 2026. Prices are in dollars per one million cubic feet of gas. There are four charts: the first chart is the current futures curve; the second chart provides historical context to the most recent prices. In the last two charts I aggregated historical daily futures prices into Summer (Apr-Oct) and Winter (Nov-Mar) seasons. Below is the Tableau Public link. Please click “Request Data Refresh” for an update.

The data is updated every 30 minutes by a Python script I wrote. The script goes to a web site, collects the prices, sorts them, and then inserts them into the first blank row of a Google Sheet. Then, Tableau pulls the time series data as the Google Sheet is updated.

https://public.tableau.com/app/profile/dmitrybrown/viz/NYMEX-HenryHub-ForwardCurves/Strips

These charts are updated every 30 minutes using this Python script. I am using a Batch file with Windows scheduler to run this process. My next step is to redo the scheduling with Powershell. 

Thank you for visiting my personal project!

Dmitry
