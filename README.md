# Alteryx-Web-Scraping

Alteryx provides you the ability to scrap any website and extract the data you need. Most times, it can be a challenging task if you are dealing with a website with complex HTML scripting. 

In the workbook named: City Data Web Scraping, the data from this site was extracted, https://in.pcmag.com/software-services/37661/20-high-tech-cities-youll-want-to-call-home
This site contains 3 fields that we want to extract, City Name, Salary and Description. 

In the workbook named: COVID Data Scraping, the data from this site was extracted, https://www.mygov.in/corona-data/covid19-statewise-status/
From this site the fields extracted are, State Name, Total Confirmed, Death, State Code, Last Confirmed Covid Cases, Last Cured Discharged, Last Deaths

For web scraping in Alteryx, you will have to use Regular Expressions to extract the data from the HTML Script. Since people struggle with RegEx very often, one technique that can help in easing the problems is to use the following RegEx: (.*?)

Thanks.
