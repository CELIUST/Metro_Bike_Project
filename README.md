# Metro_Bike_Project
# Metro Bike Share Trip Analysis


## Introduction
This project is about constructing a data pipeline and establishing data architecture. This project will display data sourcing to visualization, integrating key components of data collection, storage, transformation, and presentation. For this project, both tech skills for handling data and for organizing it well (data architecture) and making it look good (data visualization) are needed. My main goal is to create an efficient data pipeline so to showcase this I've chosen to explore and work with Metro Bike Share Data for this project. 

## Commpany's Background
Metro Bike Share is a public bicycle-sharing system operated by Metro, in collaboration with partners like Bicycle Transit Systems. Designed to provide convenient and sustainable transportation options, Metro Bike Share allows users to rent bicycles for short trips in urban areas. The system aims to enhance mobility, reduce traffic congestion, and promote a healthier and more eco-friendly mode of transportation. With bike stations strategically located throughout cities, Metro Bike Share offers an accessible and efficient means of commuting, contributing to the overall accessibility and sustainability of urban transportation systems.

##Files image

## Data Sourcing
Source: https://bikeshare.metro.net/about/data/
Data Dictinoary: Data_Dictionary_Metro_Bike.xlsx
Tools: Google Colab and Python
After getting fimilair with the data, I then procced to scarpe the website using these python code in Google Colab: [Extraction_Metro_Bike.ipynb](path/to/Extraction_Metro_Bike.ipynb)

Once the links were successfully downloaded from the source, I noticed the links were zip file, which meant they were compressed files, therefore I used the following codes to unzip the files: [Unzip_Metro_Bike.ipynb](path/to/Unzip_Metro_Bike.ipynb)

## Storage
Data Store: Azure, often referred to as Microsoft Azure, is a cloud computing platform and service provided by Microsoft.
This is the python script I used to upload the unzip files into Azure containers: 

## Modeling



