# Scraping-Immoweb

## Collecting Data

Website: https://www.immoweb.be/en

### Description:

Project001:	Code for making the scraping the Price, subtype the property, immocode, this variable is used as ID for verifying not have duplicate data. Output: FINAL.cvs  

Project002:	Code for collecting the specific requirement variables. I add the level the energy variable because I consider it a relevant variable for estimating 
the price sale. Output: FINAL2.csv  

Links:	Code for scraping the websites.  Output: URL1000.csv  

CleanData	Code for cleaning data with pandas.	The expected output is Data_Base_Immo.cvs  
  
### Installation  

My version Python 3.9.7  
Pandas '1.4.2'  
Selenium  

### What is there left to do?
Generate the Data_Base_Immo.cvs 
Clean the variables with extension in m2 square meter.
I want to create some conditions, with the variables. For example I noticed that if the house has garden is a NaN value in this specific variable but the variable ‘Garden extension’ has the extension in square meter. I can notice this because I quicky examined the data, but I think I can make a better analysis.

### Main problems:
I have the idea that I want to encode. I'm starting to do it but I still don't have the ability to order it sequentially. For example I wanted to create a list of list, I made the code, I tried it, it didn't work, I tried another code with the same idea, it took a long time.
At the end the couch helped me, I placed the empty list in the right place, in this case outside the loop.

### Personal situation:
Happy because the code worked.  
I learned a lot and enjoyed it.  
Motivated to continue learning
