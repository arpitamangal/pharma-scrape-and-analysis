# Pharma Scrape & Analysis
### Scraping, cleaning, processing, and analysing pharmaceutical data.

Context: The healthcare industry in India is rapidly growing. Customers now have a popular and convenient option to get healthcare products and services through online pharmacies and healthcare platforms like 1mg. These platforms provide a wide selection of products at affordable costs, as well as the ease of home delivery and online consultations with medical specialists. The objective of project to: 
* Perform market research (descriptive analytics) and answer the questions:
  * Who are the top manufacturers that adopted to online pharmacies?
  * Medicines related to which disease are mostly available online?
  * Medicines of which disease is most expensive?
  * Medicines of which therapeutic_class are most?
* Build classification model to classify medicines and healthcare products according to the list of 40 general categories of medicines as listed by the FDA.
* Build a pricing model which would allow small pharmacies to accurately predict market prices of medicines and decide on a competitive selling point.
* Build an algorithm which can provide substitute recommendations for medicines based on their description and features, for better inventory management.


The data for the analysis is scraped from the 1mg website using Beautiful Soup library in Python. The information scraped: 

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
  
The scraped data is stored in a MongoDB database due to its flexibility and ability to handle data.

Pharma Analysis
With small pharmacies facing increased competition from multinational pharmacy chains and online pharmacy platforms, to remain competitive they need to be highly organized and use resources more efficiently. To support this we have developed several Proof-of-Concept algorithms which would allow small pharmacies to improve inventory management and develop competent pricing strategies. These algorithms have shown promising results and can be significantly improved upon with more resources. We are tackling 3 Objectives -

Build an algorithm which can 

* This is a proof of concept developed for 500 medicines starting with each alphabet. 
* Currently scraping rest of the data to extend the analysis.

