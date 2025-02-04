## Analysis of Subway Crime Complaints with Daily Ridership using NYC Transit Open Data 

**Report** - https://docs.google.com/document/d/1VSnyPdF5qKyDxX0vtyT00O3D3BAZjVbDCybYbiC8NqQ/edit?tab=t.0

- From January 1st to June 30th of 2024, an **average of 2.97 complaints per day were recorded for Grand Larceny amongst other major felonies**.

- Any anomalies in the number of daily complaints at **14 St-Union Sq** and **74 Broadway - Jackson Heights Roosevelt Av** stations compared to other stations with high complaints were likely due to random chance. However, the **anomalies in the average daily ridership were not random**.

- There was **no significant effect of number of daily complaints on the average daily ridership** at those two stations, suggesting that deviations in ridership may have been caused by other factors.

- Since the data is stable and free from extreme outliers, statistical thresholding was applied to develop a baseline anomaly detection model. 

- **8% and 11.12% of days with complaints were flagged as anomalies in average daily ridership** at the two stations, respectively. The model allows for plugging in new data to identify similar anomalies.
