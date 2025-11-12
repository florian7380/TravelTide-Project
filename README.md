# TravelTide-Project
Customer Segmentation for TravelTide - aligning perks to reduce custoemr retention

## notebooks
The notebooks can be run without any loaded files. The data is loaded by a SQL connection to a the TravelTide data base

- TravelTide EDA - Begin here to get information about the data on different levcels of aggregation
- TravelTide Segmentation - The traditional segmentation with aligned perks
- TravelTide ML - Machine learning approach to find segments and why it's not used (yet)

## reports
Contains the presentation summarizing the insights and results of the segmentation

## data
The connection string to the TravelTide data base can be found in the data folder.

The data base contains the following tables:
- users: Data about the personal information of the customer
- sessions: Data about the sessions the customer had and what was done in them
- flights: Data about the booked flights in a session
- hotels: Data about the booked hotels in a session

## outputs
The most important plots and tables with the key insights and solutions. Since the plots in EDA are confusing and to complex there is a Tableau file with the used data file for the most important outputs from EDA.

## sctipts
The queries from the notebooks to get the data from the TravelTide data base are in the data folder.