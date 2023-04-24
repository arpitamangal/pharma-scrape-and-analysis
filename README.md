# Pharmaceutical Data: Scraping & Analysis

This project involves end-to-end processes, including scraping, storing, cleaning, exploring, and analyzing pharmaceutical data. The objective of the project is to: 
* develop a pricing model for pharmacies, **Linear Regression**
* predict substitutes for a medicine using descriptions, **Word2Vec Model**
* classify medicines into FDA categories, **K-means Clustering**
* market research on online pharmaceutical market, **Exploratory Data Analysis**

## Inspiration

One of the most prominent issues during the COVID-19 pandemic was the unavailability of medicines. A few suppliers dominate the pharmaceutical industry, and patients often pay more for medicines due to lack of knowledge. This project identifies substitutes from lesser-known brands and develops a pricing model based on product information. The project also classifies medicines and healthcare products into FDA's list of 40 categories. These models would help pharmacies improve inventory management and pricing strategies.

## Scraping 

Scraped over 13K pages from the [1mg](https://www.1mg.com/), an online pharmacy. The information scraped: 

  * Name
  * Price
  * Description
  * Manufacturer information 
  * Product information
  * Dosage form
  * Active ingredient
  * Mechanism of action
  * Benefits
  * Side effects
  * Factbox 
     - Habit Forming
     - Therapeutic Class
     - Chemical Class
     - Action Class
  
## Storing 
The data is stored in a MongoDB database due to its flexibility and ability to handle unstructured data.

## Exploratory Data Analysis

* Which manufacturers have successfully adopted online pharmacy sales channels?
* What types of medicines are commonly available for purchase online?
* Which disease's medicines are typically the most expensive?
* Which therapeutic classes of medicines are most frequently available for purchase online?

## Tool & Technologies
* Scraping: BeautifulSoup
* Storing: Pymongo
* Cleaning & Exploring: Pandas, Numpy, Matplotlib, Seaborn, NLTK
* Model Building: Gensim (Word2Vec), Sklearn (Kmeans Clustering, LinearRegression)

[![My Skills](https://skillicons.dev/icons?i=py,mongodb)](https://skillicons.dev) 

## Fact
Indian healthcare sector is expected to grow rapidly, with a market value of around $280 billion and a predicted CAGR of 16-17%. Digital health technologies, such as telemedicine, electronic health records, and mobile health applications, are likely to play a key role in improving access to healthcare services and managing patient care. It becomes important to improve access to quality healthcare, reduce costs, and address financing and regulatory issues.
 
*This is a work in progress (proof of concept developed for 13K medicines and health care products)*
