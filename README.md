# Coffee-Quality-Analysis-Dashboard
Designed Dynamic Coffee Quality Analysis Dashboard by Using Visualization Tool Power BI After Cleaning the Data by Using Power Query ( ETL Tool ).

![Screenshot (1139)](https://github.com/user-attachments/assets/5292f74a-7a01-4d63-86b9-388599a98f93)

![Screenshot (1136)](https://github.com/user-attachments/assets/23ff3ae6-ec1b-4022-a532-bfc9ddaaac75)
![Screenshot (1137)](https://github.com/user-attachments/assets/74b325db-7739-498d-b7ab-874005ae5f03)
![Screenshot (1138)](https://github.com/user-attachments/assets/f1e644fd-285e-4ab2-8b04-c5343f03d6b2)


## BUSINESS PROBLEM :
The coffee industry thrives on quality, and stakeholders are constantly seeking ways to understand and improve the factors that contribute to it. However, the complexity of coffee quality evaluation involves various sensory attributes, processing methods, origin regions, and defects, making it challenging to pinpoint the key determinants. Therefore, the Coffee Quality Institute (CQI) aims to leverage its dataset to unravel these complexities and provide insights that can guide stakeholders in enhancing coffee quality standards.

## OBJECTIVE :
The primary objective is to delve into the dataset provided by CQI to decipher the factors influencing coffee quality. This involves:

 
  1.Identifying the key determinants of coffee quality, focusing on sensory attributes like aroma, flavor, acidity, etc.

  2.Exploring correlations between processing methods, origin regions, and coffee quality scores.

  3.Analyzing trends or patterns in defect occurrences and their impact on overall coffee quality.

  4.Understanding how different variables interact to influence Total Cup Points, which serve as an overall measure of coffee quality.

## Data:
The data includes a range of information on coffee production, processing, and sensory evaluation. It also contains data on coffee genetics, soil types, and other factors that can affect coffee quality.

**Sensory evaluations (coffee quality scores)** -
   * Aroma: Refers to the scent or fragrance of the coffee.
   * Flavor: The flavor of coffee is evaluated based on the taste, including any sweetness, bitterness, acidity, and other flavor notes.
   *	Aftertaste: Refers to the lingering taste that remains in the mouth after swallowing the coffee.
   *	Acidity: Acidity in coffee refers to the brightness or liveliness of the taste.
   *	Body: The body of coffee refers to the thickness or viscosity of the coffee in the mouth.
   *	Balance: Balance refers to how well the different flavor components of the coffee work together.
   *	Uniformity: Uniformity refers to the consistency of the coffee from cup to cup.
   *	Clean Cup: A clean cup refers to a coffee that is free of any off-flavors or defects, such as sourness, mustiness, or staleness.
   *	Sweetness: It can be described as caramel-like, fruity, or floral, and is a desirable quality in coffee.
   * Overall: A numerical score for the overall quality.


**NOTE**: 'Total Cup Points' is literally the total of 10 features given above. There were some notebooks trying to predict the total cup points given these features. We know the exact 
 function underlying the total cup points.

**Defects**:
 * Defects are undesirable qualities that can occur in coffee beans during processing or storage. Defects can be categorized into two categories: Category One and Category Two defects.
 * Category One defects are primary defects that can be perceived through visual inspection of the coffee beans. These defects include Black beans, sour beans, insect-damaged beans, 
   fungus-damaged beans, etc.
 * Category Two defects are secondary defects that are more subtle and can only be detected through tasting. These defects include Over-fermentation, staleness, rancidness, chemical 
   taste, etc.

**Data Integration , Cleaning or Preparation or Transformation and Load** - Power Query (ETL TOOL)

**Data Visualization & Data Analysis** - PowerBI , Dax , Power Query

## INSIGHTS :

* The overall coffee quality score ( or Total Cup Points) is 83.73 out of 100 based on various sensory evaluations which signify to good coffee quality ( 80 - 85 score considered as good coffee quality) that leads to -
  
                      1. Good aroma and flavor.
                      2.Acceptable balance, body, and acidity.
                      3.Mostly clean cup with some minor defects.
                      4.Noticeable aftertaste and sweetness.
* All sensory evaluations (coffee quality score) are equals to or greater than 7.5 except one sample, which is considered as good .
* The "Double Anaerobic Washed" processing method has the highest total cup points that is 89.33 , compare to other method . 
* "Washed/wet" processing method is most widely used method which are having score more than 80 in most of the cases despite having the maximum defects.
* The country "Colombia" has received the highest total cup points compared to others.
* The harvest year of 2021 has received the maximum total cup points.
* The September months have max quality score occurs compared to other months.
* The country "Brazil" has received the lowest total cup points compared to others which is 78 and processing method used in that is "Semi- Lavado ".  
* Most of the samples 's moisture level is within the ideal range (10-12%) and shows good quality scores in aroma, flavor, acidity, and body which leads to good coffee quality.
  
  
## Conclusion :
Through analysis, key determinants of coffee quality were identified, including aroma, flavor, acidity, body, and cleanliness. Processing methods and origin regions significantly influence quality, highlighting the importance of regional specificity and production techniques. Defect occurrences, both visible and taste-related, underscore the necessity of robust quality control measures. Complex interactions among variables emphasize the multifaceted nature of coffee quality determination. Leveraging data-driven approaches and consumer education can drive continuous quality improvement and sustainability in the coffee industry.


