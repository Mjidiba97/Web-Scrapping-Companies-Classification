# Web Scrapping and Companies Classification
Web Scrapping and Companies Classification

The first task is <b>Entities Classification</b>. The excel file contains a sheet named 'Data', which is an export of startups from the Dealroom database. Each row corresponds to one five entities: startups, mature companies, universities/schools, government/non-profit and unclassified. The goal is to use the data in order to classify each entity into one these five categories. The result is to be exported into two sheets in the Excel file.

The second task is <b>Web Scrapping</b>. The goal is to retreive the information about companies in the <a href='https://www.ycombinator.com/companies/'>YCombinator website</a>. The results are also to be exported to the Excel file.

The <b>main.py</b> file contains all the code for the assignment. You simply have to have the Excel file on the same repository and run the python file. The code will get the results and put them automatically in the Excel file.

Note: Before running the file, you need to download <a href="https://chromedriver.chromium.org/">chromedriver</a> (for scrapping) and change its path in the beginning of the code (DRIVER_PATH constant).
