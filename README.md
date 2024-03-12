# PDF-scraper-bot
A Robotic Process Automation (RPA) bot that automatically extracts and filters important data from PDF files using scraping techniques. It will then input the filtered data into Excel.

## Build Process
This Robotic Process Automation (RPA) was created using [Uipath](https://www.uipath.com/) and uses [Adobe Acrobat](https://get.adobe.com/reader/) to open PDF documents. Using scraping techniques, the Robotic Process Automation (RPA) will retrieve data and enter it into a predefined Excel (ScrapedInvoiceOutput.xlsx). The data to be retrieved from the PDF are **Invoice Number**, **Invoice Date**, **Customer Name**, **Total Amount**, and **Customer ID**. The creation of the RPA can be seen in the following image:
![Build Process Robotic Process Automation (RPA)](https://github.com/AlvinOctaH/PDF-scraper-bot/blob/main/Images/Scrape.png?raw=true)

## Results
The results of the data scraping that has been done, can be seen in the following figure:
![Results of the data scraping](https://github.com/AlvinOctaH/PDF-scraper-bot/blob/main/Images/Excel.png?raw=true)
