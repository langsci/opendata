This directory contains the following files:

- `pdfdownloads.csv`: the downloads of all pdf files associated with books (chapters and whole books) per month. The top row gives the book ID. The downloads are computed from the Apache logs via awstats. Awstats does discount robots and spiders, but is not COUNTER-compliant. In June 2016, the logging went down, hence the numbers are smaller in this month. 

In the future, this directory will contain more `csv` files about :

- hardcover sales
- softcover sales
- GoogleBook views
- OAPEN views
- authors fees
- donations 
