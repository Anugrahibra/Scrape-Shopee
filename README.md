#README
This script is used to scrape data from the Shopee website for laptops and store the data in an excel file. It uses the following libraries:

pandas
selenium
bs4 (BeautifulSoup)
time
It opens a headless chrome browser and navigates to the Shopee website for laptops. The script then scrolls down the page multiple times to load all the laptops on the page. After this, the script takes a screenshot of the page and saves it as "home.png". It then uses BeautifulSoup to parse the page source and extract the relevant information such as name, price, link, number sold and location.

The extracted data is then stored in a pandas dataframe and saved as an excel file "Result/Laptop.xlsx" with one sheet named "Sheet1". The script also prints the progress of the scraping and processing of data to the console.
