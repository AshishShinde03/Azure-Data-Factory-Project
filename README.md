# Azure-Data-Factory-Project
Project on Azure Data Factory Covid19 Prediction and Reporting

## Solution Architecture
![image](https://github.com/AshishShinde03/Azure-Data-Factory-Project/assets/91445214/9f8f039c-3951-44a8-838c-3d42567d0df9)

## Project Objective
Building a Azure Cloud Data Platform for Data Scientists to Predict the covid19 outbreak and for Data Analyst for reporting and visualiation.

## Step by step Objectives
	1. Data Lake to be built with the following data to aid Data Scientists to predict the spread of the virus/ mortality
		Confirmed cases
		Mortality
		Hospitalization/ ICU Cases
		Testing Numbers
		Country’s population by age group
	2. Data Warehouse to be built with the following data to aid Reporting on Trends
		Confirmed cases
		Mortality
		Hospitalization/ ICU Cases
		Testing Numbers

  

## Data Sources
	1. ECDC Website -> https://www.ecdc.europa.eu/en/covid-19/data
		Confirmed cases
		Mortality
		Hospitalization/ ICU Cases
		Testing Numbers
		
	2. Eurostat Website -> https://ec.europa.eu/eurostat/estat-navtree-portlet-prod/BulkDownloadListing?file=data/tps00010.tsv.gz
		Population by age

## Data Ingestion
1. Population by Age data: Ingestion from Azure Blob Storage to Azure Data Lake using copy activity
   ![image](https://github.com/AshishShinde03/Azure-Data-Factory-Project/assets/91445214/048d98a0-54a7-4a06-b4a2-c518acb7b5b3)

	1. Created Azure Blob Storage and Azure Data Lake Gen2
    	2. Created two Linked Services
