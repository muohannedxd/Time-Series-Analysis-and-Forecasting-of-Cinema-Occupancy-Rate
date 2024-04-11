## Analyzing Cinema Occupancy Rates: A Time Series Forecasting Study

### Abstract
Entertainment venues, including cinemas, often suffer from the challenge of high costs and resource wastage due to uncertainties in attendance. This study focuses particularly on addressing these issues by analyzing the occupancy rate in cinema screenings and its high impact on the total sales. By leveraging estimated future values based on time series analysis techniques and comprehensive modeling using $ARIMA$
family models, cinemas can optimize ticket pricing strategies for different days, periods and seasons, thereby reducing costs and maximizing profits. The findings of this research in occupancy rate hold the potential to significantly enhance operational efficiency and financial performance for cinemas in particular and entertainment facilities in general.

### Data Introduction
To fulfill the main goal of this work. We will be using the dataset in cinema.csv that holds daily information about the total sales and occupancy rate captured from several cinemas across several months. Precisely, from March to November of 2023. Total Sales is the average total sales of all the movie theaters in the sample per each day. The occupancy rate or percentage, defines the average of the total number of sold tickets to the maximum capacity of each cinema hall (movie theater) per each day as well. These two features are the most important for this study.
-- added
Note that the time series dataset was drawn from Kaggle. A competition platform and Online Community of data scientists where we can find and publish open datasets. Here is the link: https://www.kaggle.com/datasets/arashnic/cinema-ticket. Of course, in order to be able to conduct the study, we already grouped the data by the mean of occupancy rates and total sales for all cinemas to get one representative value per day.
