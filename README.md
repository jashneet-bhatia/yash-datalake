# AzureQuickStartDatalake

--------------------------------------------------------------------------
# Overview :
--------------------------------------------------------------------------
The aim of Yash Data lake Walk through guide is build to assist  through the Server less Data Lake reference architecture and the Azure Cloud services used within. 
- Yash Data Lake in Azure Cloud provides following features
	* data ingestion
	* real-time analytics over continuous stream of data
	* batch analytics using the data available in the Data Lake
	* ad-hoc analytics for exploring different data insights and visualization 
<br />
The purpose of a Quick start  is to present an unrefined view of data to the analysts, to help them explore their data refinement and analysis techniques using Azure services.
The deployment  of Quick start Data lake also includes an optional wizard and a sample dataset that is used  to demonstrate data lake capabilities.

![alt text](https://raw.githubusercontent.com/KuldeepShikhare/AzureQuickStartDatalake/sandbox/scripts/images/Step_1_Get_Started.JPG)

--------------------------------------------------------------------------
# Pre-Requisites
--------------------------------------------------------------------------
# Application registration in AAD :
--------------------------------------------------------------------------
1. Service Principal ID
2. Service Principal Key
3. Assign required permissions
4. Set Reply URL :
	https://your-function-app-name.azurewebsites.net/.auth/login/aad/callback
	
	[Note = your-function-app-name : The function name which you would be giving while deploying Yash Data Lake]
	
--------------------------------------------------------------------------
# Visualization :
--------------------------------------------------------------------------
1. Batch Flow - PowerBI Desktop
2. Streaming Flow - PowerBI Online Account
--------------------------------------------------------------------------
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FKuldeepShikhare%2FAzureQuickStartDatalake%2Fsandbox%2FazureDeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
