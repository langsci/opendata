This directory contains the following files:

- `pdfdownloads.csv`: the downloads of all pdf files associated with books (chapters and whole books) per month. The top row gives the book ID. The downloads are computed from the Apache logs via awstats. Awstats does discount robots and spiders, but is not COUNTER-compliant. In June 2016, the logging went down, hence the numbers are smaller in this month. 

- `salesBOD2017.csv`: The sales of books via BoD. Quantity and total margin are given. Books are available as hardcover and softcover. Titles are anonymized for legal reasons, but hardcover and softcover have the same code. 

In the future, this directory will contain more `csv` files about :

- hardcover sales
- softcover sales
- GoogleBook views
- OAPEN views
- authors fees
- donations 
