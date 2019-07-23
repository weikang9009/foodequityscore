# Project

## Elements of food environment

* Food retail
    * supermarkets
    * small grocery and corner stores
    * convenience stores
        * include chain convenience stores, drug stores or pharmacies, and discount or dollar stores.
    * public markets
        * historic City-owned indoor markets that feature diverse vendors selling a variety of food (mostly prepared) and non-food products
    * food assistance sites: 
        * Nutrition assistance programs: 
            * After School Meal Sites   
                * typically operated by non-profit organizations, churches and schools
                * funded through the USDA’s Child and Adult Care Food Program
            * Summer Meal Sites (Summer Food Service Program (SFSP))
                * federally-funded, state administered program
            * Senior Meal Sites
                * federally funded, congregate nutrition program
            * Food Pantry and Meal Sites
                * Locations may be homeless shelters, emergency pantries, schools or churches.
                * 425 sites operating during 2016 (affiliated with the Maryland Food Bank. could be additional sites)
            * urban agriculture sites
                * Urban Farms
                * community gardens


## Data collection of food retail

### Place APIs 
* [Foursquare venues](https://developer.foursquare.com/docs/resources/categories)
    * [search for venues](https://developer.foursquare.com/docs/api/venues/search)
    * categories
        * hierarchical structure (up to four layers)
        * categories relevant to food environment
            * Convenience Store 4d954b0ea243a5684a65b473
                * in second layer under 
                    * first layer: Shop & Service 4d4b7105d754a06378d81259
            * Farmers Market: 4bf58dd8d48988d1fa941735
                * in third layer under 
                    * first layer: Shop & Service 4d4b7105d754a06378d81259
                    * second layer: Food & Drink Shop: 4bf58dd8d48988d1f9941735
            * Grocery Store 4bf58dd8d48988d118951735
                * in third layer under 
                    * first layer: Shop & Service 4d4b7105d754a06378d81259
                    * second layer: Food & Drink Shop: 4bf58dd8d48988d1f9941735
            * Health Food Store 50aa9e744b90af0d42d5de0e
                 * in third layer under 
                    * first layer: Shop & Service 4d4b7105d754a06378d81259
                    * second layer: Food & Drink Shop: 4bf58dd8d48988d1f9941735
            * Supermarket 52f2ab2ebcbc57f1066b8b46
                * in third layer under 
                    * first layer: Shop & Service 4d4b7105d754a06378d81259
                    * second layer: Food & Drink Shop: 4bf58dd8d48988d1f994173 
            * Organic Grocery 52f2ab2ebcbc57f1066b8b45
                * in third layer under 
                    * first layer: Shop & Service 4d4b7105d754a06378d81259
                    * second layer: Food & Drink Shop: 4bf58dd8d48988d1f994173  
    * Places API
        * intro https://developer.foursquare.com/docs/terms-of-use/overview
        * Daily Call Quota https://developer.foursquare.com/docs/api/troubleshooting/rate-limits
        * account https://developer.foursquare.com/
        * python package https://github.com/mLewisLogic/foursquare
            * example https://github.com/v-iashin/FoursquareAPI/blob/master/Examples/venues.ipynb
            * [nice tutorial](http://www.bgoncalves.com/download/finish/5-teaching/91-data-mining-foursquare.html)
            * [another example of Classification of Moscow Metro stations using Foursquare data](https://towardsdatascience.com/classification-of-moscow-metro-stations-using-foursquare-data-fb8aad3e0e4)
        * API explorer https://foursquare.com/developers/explore
* [Google Place API](https://developers.google.com/places/web-service/supported_types#table3)
    * support very coarse Place types/categories
        * related to food retail
            * supermarket
            * store
    * [Place details/data fields](https://developers.google.com/places/web-service/place-data-fields) 
