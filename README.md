# Data-Engineer-Project-using-Microsoft-Fabric
This is End of End Data Engineer project using Microsoft Fabric in ingesting data from Bing API to Fabric, then the data is transformed, and visualized. Below are steps performed in the project for your reference: 

1/ Data Engestion: Used Data Factory in Fabric to connect to Bing API, and copy all latest news data under json format to  One Lake in Fabric. These json will be stored in Lake Database in One Lake (the json data is stored as file structure)

2/ Data Transformation: The raw data in json will be transformed by using notebook in Synapse Data Engineering, and then saved under delta table in the Lake Database as well (these delta table is stored as table structure).

3/ Sentiment analysis: run sentiment analysis on cleaned data using Synapse Data Science.

4/ Data visualization: the result obtained from sentiment analysis is used to create dashboard by using Power BI.

5/ Data alert: using Data Activator for sending data alert to email. 
