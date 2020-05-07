# Cartier Jewelry 

CARTIER International SNC, or simply [Cartier](https://www.cartier.co.uk/en-gb/collections/jewellery.html), is a French luxury goods conglomerate which designs, manufactures, distributes, and sells jewellery and watches Founded by Louis-François Cartier in Paris in 1847, the company remained under family control until 1964. The company maintains its headquarters in Paris, although it has been a wholly owned subsidiary of the Swiss Richemont Group.Cartier operates more than 200 stores in 125 countries, with three Temples (Historical Maison) in London, New York, and Paris.


### Dataset 
This [dataset](https://www.kaggle.com/marcelopesse/cartier-jewelry-catalog) is available on Kaggle that scraped from orginal Cartier website. this dataset is include six columns .

#### Dataset columns before cleaning:

* ref
* categorie
* title	price
* tags
* description
* image


#### Dataset columns after cleaning:

* categorie
* price
* metal
* gem
* second_gem
* third_gem
* foruth_gem

#### Dataset preparation for machine learning
For machine learning preparation , we have to delete some columns like : 

* categorie
* metal
* gem
* second_gem
* third_gem
* foruth_gem

And add some new columns , for predicting jewels price (new columns are added into data set in MachineLearning notebook)

   * 'amazonite' ,'amethyst', 'amethysts', 'aquamarines',
   * 'aventurine', 'black ceramic', 'black lacquer', 'bracelets',
   * 'brown diamonds', 'carnelian', 'carnelians', 'ceramic',
   * 'chrysoprase', 'chrysoprases', 'citrine', 'coral', 'diamond',
   * 'diamonds', 'earrings', 'emeralds', 'garnets',
   * 'gray mother_of_pearl', 'lacquer', 'lapis lazuli', 'malachite',
   * 'mother_of_pearl', 'necklaces', 'non_rhodiumized white gold',
   * 'obsidians', 'onyx', 'pearl', 'peridots', 'pink gold',
   * 'pink sapphire', 'pink sapphires', 'platinum', 'rings', 'rubies',
   * 'sapphire', 'sapphires', 'spessartite garnet', 'spinels',
   * 'tsavorite garnet', 'tsavorite garnets', 'white gold',
   * 'white mother_of_pearl', 'yellow gold'

All of these column as you can see in top , are dummie variable just for using in machine learning. 
**ready_df_for_ML.csv**  file is ready for running ML algorithm.

### Written By

* [Soroush Ghaderi](https://github.com/SoroushGhaderi)

* [Bahram Jannesar](https://github.com/Bahramjannesar)

### License
See full license on [this](https://opensource.org/licenses/MIT) , Under MIT License
