## Flipkart_Best_Laptop_Analysis

I Scraped all Laptops details from flipkart website using Python BeautifulSoup and Requests library and used pandas and matplotlib for Data Analysis

In This Project I have used requests library to send a GET request to the e-commerce website and retrieve the HTML content of the webpage. It then uses Beautiful Soup to parse the HTML and find all the elements with the class "product", which are assumed to be the products on the webpage. The code then loops through each product and extracts the ProductName, Stars, Ratings, Reviews, CurrentPrice, MRP, Processor, Ram, Storage using the find() method of Beautiful Soup. The extracted information is appended to a list and print at the end.

Created CSV file with the extracted information and verifies information of CSV file by reading them back using Pandas. 
