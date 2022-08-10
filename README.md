# SFO_Rental_Analysis

## Background
This project is for Proptech company which wants to provide customers with a broader range of portfolio options for the San Francisco market. I have built a dashboard to display this. 

The goal of this dashboard is to provide charts, maps, and interactive visualizations that help customers explore the data and determine if they want to invest in rental properties in San Francisco.

---
### Rental Analysis

The first step to building the dashboard is to work out all of the calculations and visualizations in an analysis notebook. Once the code is worked out here, it can be copied over to a dashboard code and used with Panel to create the final layout.


#### Housing Units Per Year

Calculated the number of housing units per year and visualize the results as a bar chart using the Pandas plot function.

Default Bar Chart

  ![unscaled-bar.png](Images/Avg-SF-units-peryear.png)

Bar Chart with y-axis limits adjusted

  ![scaled-bar.png](Images/zoomed-housing-units-by-year.png)


#### Average Gross Rent in San Francisco Per Year

Visualized the average gross rent per year to better understand the trends for rental income over time. Visualized the average (mean) gross rent per year and visualized it as a line chart.

1. Calculated the mean `gross` for each year.
2. Visualized the mean gross rent per year as a line chart.

  ![gross-rent.png](Images/avg-sale-px-sq-foot-gross-rent.png)
  
  #### Average Prices By Neighborhood

Compared the average prices by neighborhood.

1. Grouped the data by year and by neighborhood and calculated the average (mean) `sales_price_sqr_foot`.
2. Visualized the mean `sales_price_sqr_foot` per year with the neighborhood as a dropdown selector.

  ![avg-price-neighborhood.png](Images/pricing-info-by-neighborhood.png)
  
  
  #### Neighborhood Map

Read in neighborhood location data and built an interactive map with the average prices per neighborhood. Used a scatter mapbox object from plotly express to create the visualization. I used the mapbox API key for this.

  ![neighborhood-map.png](Images/6-4-geoviews-plot.png)
  
  
  
  
  
  
