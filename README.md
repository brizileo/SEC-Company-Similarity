# Overview
In this project I extract Form 10-K reports from the SEC API in XBRL format and analyse the dataset to identify similarities between companies.  
The documenation of the SEC API can be found at the following location:  

- https://www.sec.gov/search-filings/edgar-application-programming-interfaces.  
  
The similarity scores is defined between all Companies-FiscalYear pairs. It is obtained as the inverse of the mean absolute error times Jaccard similarity.   
Jaccard similarity is included to account for the fact that companies do not have the same number of features.  
