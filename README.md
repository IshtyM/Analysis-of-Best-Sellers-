# Analysis-of-Best-Sellers-

This is a sample dataset of publicly available info on ecommerce sellers in the Garden category in the Amazon marketplace.
Here, work is to sanitize and analyze the data to profile the sellers present, and develop selection criteria to identify the best or most promising sellers in this dataset, that the Acquisitions team should reach out to, and acquire.
Before developing the selection criteria, there is to need to sanitize the data , and parse out usable data from the unstructured text. 

● The column sellerproductcount gives the count of products in the form '1-16 of over 100,000 results'

● sellerratings - this columns gives the % and count of positive ratings (e.g. 88% positive in the last 12 months (118 ratings) ) if parsed correctly

● sellerdetails - using this text to parse out phone numbers, and email IDs of merchants, where available, so our team can reach out to them.

● businessaddress - this gives the business locations of the sellers. You can parse them to identify if a seller is registered in the US , Germany (DE), or China (CN).

● Hero Product 1 #ratings and Hero Product 2 #ratings - these 2 columns give the number of ratings of the 2 'hero products' or best selling products of this seller.

In this python file, plotly is used, therefore to view the graphs, refer this link, https://nbviewer.jupyter.org/github/IshtyM/Analysis-of-Best-Sellers-/blob/main/Analysis%20of%20Best%20Sellers.ipynb

### Libraries Used:
Pandas, Numpy, Matplotlib, Seaborn, Plotly

### Programing Language
Python

### IDE Used
Jupyter Notebook
