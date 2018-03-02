This directory contains the following files:

- `pdfdownloads.csv`: the downloads of all pdf files associated with books (chapters and whole books) per month. The top row gives the book ID. The downloads are computed from the Apache logs via awstats. Awstats does discount robots and spiders, but is not COUNTER-compliant. In June 2016, the logging went down, hence the numbers are smaller in this month. 

- `OAPENdownloads2017.csv`: Downloads of our titles from the OAPEN platform. Note that the download figures for "A grammar of Pite Saami" are probably an artefact as they are all from Italy, which is implausible. Since we have no way to calibrate/correct this, we offer the figures as they are. 

- `GoogleBooksTrafficReport2017.csv`: Books accessed on GoogleBooks with number of pages viewed. The information about "buys" refers to clicks on the link to the LangSci site, from where the book can be downloaded for free.

- `salesBOD2017.csv`: The sales of books via BoD. Quantity and total margin are given. Books are available as hardcover and softcover. Titles are anonymized for legal reasons, but hardcover and softcover have the same code. 

- `salesCreateSpace2017.csv`: The sales of books via CreateSpace. Quantity and total margins per currency are given. Titles are anonymized for legal reasons, but the code is identical between CreateSpace and BOD.

- `authorfees2017.csv`: Information about the author fees we collected in 2017. Titles are anonymized. The codes do not correspond to the codes used for sales figures.

- `donations2017.csv`: Information about the donations we received in 2017. Donors are anonymized. The codes do not correspond to the codes used for sales figures or the author fees. This information is still incomplete as of 2018-03-01. 

We have no access statistics for Zenodo, where our books are also hosted. 

 