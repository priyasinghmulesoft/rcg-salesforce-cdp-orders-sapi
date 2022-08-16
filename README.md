# rcg-salesforce-cdp-orders-sapi
Orders API to send order data from source to Salesforce CDP

Anypoint Studio Project Asset for Sending Orders to Salesforce CDP

Use Case : 
Collect order headers and order details from API request body in given valid JSON schema format and send it to Salesforce CDP using Streaming API

Salesforce authentication used : 
OAuth Username/password

Pre-requisite : 
Salesforce CDP credentials including consumer key, consumer secret, username, password
Salesforce CDP Ingestion API setup with object source and data stream created
RAML Schema used in Salesforce CDP to create data stream to create JSON request emulating source data
