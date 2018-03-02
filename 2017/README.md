This directory contains the following files:

- `pdfdownloads.csv`: the downloads of all pdf files associated with books (chapters and whole books) per month. The top row gives the book ID. The downloads are computed from the Apache logs via awstats. Awstats does discount robots and spiders, but is not COUNTER-compliant. In June 2016, the logging went down, hence the numbers are smaller in this month. 

- `salesBOD2017.csv`: The sales of books via BoD. Quantity and total margin are given. Books are available as hardcover and softcover. Titles are anonymized for legal reasons, but hardcover and softcover have the same code. 

- `salesCreateSpace2017.csv`: The sales of books via CreateSpace. Quantity and total margin are given. Titles are anonymized for legal reasons, but the code is identical between CreateSpace and BOD.

- `GoogleBooksTrafficReport2017.csv`: Books accessed on GoogleBooks with number of pages viewed. The information about "buys" refers to clicks on the link to the LangSci site, from where the book can be downloaded for free.
 
- `OAPENdownloads2017.csv`: Downloads of our titles from the OAPEN platform. Note that the download figures for "A grammar of Pite Saami" are probably an artefact as they are all from Italy, whihch is implausible. Since we have no way to calibrate/correct this, we offer the figures as they are. 

In the future, this directory will contain more `csv` files about :

- GoogleBook views
- OAPEN views
- authors fees
- donations 
