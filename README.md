## Analysis of Subway Crime Complaints with Daily Ridership using NYC Transit Open Data 

- From January 1st to June 30th of 2024, any anomalies in the number of daily complaints at **14 St-Union Sq** and **74 Broadway - Jackson Heights Roosevelt Av** stations compared to other stations with high complaints were likely due to random chance. However, the **anomalies in the average daily ridership were not random**.

- There was **no significant effect of number of daily complaints on the average daily ridership** at these stations, suggesting that deviations in ridership may have been caused by other factors.

- Since the data is stable and free from extreme outliers, statistical thresholding was applied to develop a baseline anomaly detection model. 

- **5.56% and 11.12% of days with complaints were flagged as anomalies in average daily ridership** at the two stations, respectively. This model allows for plugging in new data to identify similar anomalies.
