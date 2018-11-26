# QuickStartDatalake

--------------------------------------------------------------------------
# Overview :
--------------------------------------------------------------------------
The aim of Yash Azure Quick start solution is to showcase the capabilities of Server less Data Lake in the Azure Cloud. 
- Yash Data Lake in Azure Cloud showcases features such as
	* data ingestion
	* real-time analytics over continuous stream of data
	* batch analytics using the data available in the Data Lake
	* ad-hoc analytics for exploring different data insights and visualization 
	* data governanace 
<br />
The purpose of a Quick start  is to present an unrefined view of data to the analysts, to help them explore their data refinement and analysis techniques using Azure services.
The deployment  of Quick start Data lake also includes an optional wizard and a sample dataset that is used  to demonstrate data lake capabilities.

![alt text](https://raw.githubusercontent.com/KuldeepShikhare/AzureQuickStartDatalake/sandbox/scripts/images/Step_1_Get_Started.JPG)

--------------------------------------------------------------------------
# Pre-Requisites
--------------------------------------------------------------------------
- Application registration in AAD :
	1. Service Principal
	2. App Secret Key
	3. Assign required permissions
	4. Set Reply URL :https://your-function-app-name.azurewebsites.net/.auth/login/aad/callback
		[Note = your-function-app-name : The function name which you would be giving while deploying Yash Data Lake]
	
- Open Elasticsearch function app to load data to Elasticsearch for first time
	
--------------------------------------------------------------------------
The following section provide steps for running the Quickstart.
# Run and monitor the deployment:
After you deploy the template, to run Quickstart, do the following steps:
1. Go to the Output section of ARM template deployment services.
2. Copy URL from output section.
3. Open this URL in new tab

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FKuldeepShikhare%2FAzureQuickStartDatalake%2Fsandbox%2FazureDeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
