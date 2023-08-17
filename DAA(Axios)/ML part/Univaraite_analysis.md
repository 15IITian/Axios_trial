# Overview_data->


* There are missing values in all columns , but it because there are some rows which are completely null.

* After removing duplicates, max missing values -> Bathroom


* Target-> Price

_________________________________________________________

# Univariate Analysis->

## Seller Type-> 
#### **(who is responsible for selling the property and what their relationship is to the property.)**

**Owner:** directly owns the property and is selling it

**Builder:** construction company or a developer that is selling properties they have newly constructed or developed.

**Agent:** real estate agent or a realtor who is acting as an intermediary on behalf of the property owner. 

* Agent(87%) >> Owner > Builder

* Missing values =2

## Layout_Type ->
#### **(apartment== flat)**


#### No of rooms in it

**BHK:** (Bedroom, Hall, Kitchen)

**RK:** (Room ,Kitchen) {Hall == Bedroom}

* BHK(94%) >> RK

*  Missing values =1


## Property_type (inc order of luxury)->
* Studio Apartment -> 
  * open  simple room with all features
  * basic type of housing

* Apartment ->
   * Better than Studio 

* Independent Floor ->
   * single floor unit within multi-story building

* Independent House: 

* Villa:
   * larger than Independent House

* Penthouse:
   * most luxurious apartments



* Apartment >>> Studio Apartment >> Independent Floor> Independent House > Villa> Penthouse

* Missing values: 1

## Furnish_type
* **Unfurnish**: no extra furniture 


* **Semi-furnish**: middle

* **furnished**: Extra furniture given 

* Semi-furnish >= Unfurnished >  furnished
* Missing values: 1

## Bathrooms->
* **Categorical**

* More Bathrooms -> More Luxury / area of house 

* 2(50%) >> 1 >> 3 > 4 > other 
* Missing values = 542 (Max in dataset)

## Bedrooms->
* More Bedrooms -> more area/ luxury
* 1 (42%) >= 2(39%) >>3>4>other

_________________________________________________________________________________________

## Area ->
* **Many Many Outlier (Around 4% )** : Some house are very very  as compared to others thus expensive
* Skewness= very High  (due to large scale outliers)
* Many house area come under 2000 (96%) (median =850)

## Price ->
* **Many Outliers(2.5%)** -> really expensive houses(luxury)
* rental_price (inc) -> no of such houses (dec)
* Skewness= 0.9
* Many house rent price come under 83000(98%) (median=25000)
  
