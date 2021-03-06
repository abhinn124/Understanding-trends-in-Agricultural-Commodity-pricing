# Understanding-trends-in-Agricultural-Commodity-pricing
Understanding trends in APMC (Agricultural produce market committee)/mandi price &amp; quantity arrival data for different commodities in Maharashtra.

You are presented with a data set around Agriculture and your aim is to understand trends in APMC (Agricultural produce market committee)/mandi price & quantity arrival data for different commodities in Maharashtra.

Objective:
1. Test and filter outliers. 
2. Understand price fluctuations accounting the seasonal effect 
    1. Detect seasonality type (multiplicative or additive) for each cluster of APMC and commodities 
    2. De-seasonalise prices for each commodity and APMC according to the detected seasonality type 
3. Compare prices in APMC/Mandi with MSP(Minimum Support Price)- raw and deseasonalised 
4. Flag set of APMC/mandis and commodities with highest price fluctuation across different commodities in each relevant season, and year.

Variable description:
* msprice- Minimum Support Price 
* arrivals_in_qtl- Quantity arrival in market (in quintal) 
* min_price- Minimum price charged per quintal 
* max_price- Maximum price charged per quintal 
* modal_price- Mode (Average) price charged per quintal 
