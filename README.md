# Analyzing Indonesia's non-oil/gas import-export activities

## Goals
1) Create a model to forecast the Indonesian non-oil/gas import and export monthly time series the year after the end of the available dataset
2) Test for the existence of cointegration on the import and export time series

## Context

### Indonesia's role in the commodity sector
Indonesia is one of the world's largest exporter of raw and agricultural products. Its main exports (besides oil and gas products) include minerals, electrical appliances, and various agricultural goods. It is the world's largest supplier of cloves, and a major supplier of crude palm oil, coffee, and rubber. 

### Cointegration of import and export 
Policies tend to create convergence between imports and exports. This has been tested for 50 countries, where over the quarterly period of 1973 to 1998, where all 50 countries (except for Mexico) show strong signs of cointegration between imports and exports (https://www.sciencedirect.com/science/article/abs/pii/S1059056001001010). 

However, 1998 is the end of the New Order Era in Indonesia. Post 1998, the Indonesian government placed many new trade policies that might changed the long-run relationships between import and export. I would like to check on whether cointegration between import and export is maintained in the post New Order Era.

## Data Source
Indonesia' Badan Pusat Statistik (Central Statistical Body): https://www.bps.go.id/subject/8/ekspor-impor.html#subjekViewTab3

## Technologies Used
1) SARIMA to model and forecast the time series 
2) Augmented Engle-Granger two-step cointegration test 

## Results

## Future Directions
