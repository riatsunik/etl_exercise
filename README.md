# Data Engineer Assessment
### Exercise proposed by a German company for a data engineer position.

`That was my solution; it's not a complex exercise and is suitable for anyone who wants to learn a little about data engineering. Do you have ways to improve my solution? Or another way to do it? Feel free to download and enjoy.`

### Prerequisites
  ```sh
  - Jupyter Notebook 8.12 or superior.
  - Python 3.10.12 or superior.
  - PostgreSQL 15 or superior.
  - etl_exercise DB created.
  ```

You are given three different files, each corresponding to the output of 3 different sources, namely:

* User.csv
* Company.csv
* Bookings.csv

As part of the assessment, we would like you to process the three files and take any necessary steps to ensure further processing will yield correct results. Then ingest those files and build a data model in a database of your choice (e.g., PostgreSQL). It is expected of you to introduce testing for those ingested data points. Once the data model is built, please answer the following questions using your data model:

1. What is the monthly count of unique Users (headcount) who have made a booking for the last six months?
2. How many users need more than 30 days to make their first booking, and from which company are those users?
3. What is the daily 7-day rolling total booking amount for March 2023?
   
Lastly, also answer the following questions:
- Which principles should you follow when building pipelines, and are there any anti-patterns you would avoid? How would you improve your current solution further if you had more time?

  
