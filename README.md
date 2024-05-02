# Build-your-OWN-Database-Programming-Interface-GraphQL-REST-API-Neurelo

https://www.youtube.com/watch?v=SmyV-yJxgIM 

https://raw.githubusercontent.com/RodrigoMvs123/Build-your-OWN-Database-Programming-Interface-GraphQL-REST-API-Neurelo/main/README.md

Neurelo 
https://www.neurelo.com/cloud-data-apis?utm_campaign=Coding%20with%20Ania&utm_source=youtube&utm_medium=paidsocial&utm_content=Cloud-data-API 
Dashboard
https://dashboard.neurelo.com/projects 

Start Project 
New
Organization
Rodrigo M.V.S.´s Organization
Name
movies
Database Engine
MongoDB
Language
Javascript
Create

Add a Data Source - MongoDB
Connect Data Source
New Data Source
Name
sample_data
Connection String
…/sample_mflix ( Past )
Password
Ip Access Details List
Region 
…
Test Connection
Submit 
MongoDB
https://www.mongodb.com/ 
Create Project
Name Your Project
demo
Next
rodrigomvsrodrigo@gmail.com     Project Owner 
Create Project
Create a Deployment
M0
Name 
cluster0
Provider
AWS
Region
São Paulo(sa-east-1)
Create Deployment
Add a connection IP address ( Copy ) 
Create a database user
name and password ( Copy )
Create Database User
Choose a Connection Method
Connect to your Application
Drivers
Connection to Cluster
Review Setup Steps
Connection String ( Copy and Past )
Ip Access List
Add Ip Address
Allow Access from Anywhere
Confirm

Database UI
Browser Collections
sample_mflix ( Add to Connection String …/sample_flix )

Neurelo UI
Projects
Movies
Dashboard
Create an Environment 
New Environment 
Environment Name
default
Region
…
Observability 
On
Create

Create an API Key
New API Key
API Key Name
demo_key
Create
Generated API Key
… ( Copy )

Start Runners

API Playground
users
Find my users
Headers
X-API-KEY      Value …
Send
Response
Users ( Object )

Neurelo UI
Projects
Movies
Definitions
Custom Queries
New
Endpoint Name
1960-movies
Submitted
Custom Query AI Assistant
get movies by year and make sure year is 1960
{ 
	“find”: “movies”,
	“filter”: {
		“year”: 1960	
		}
}
Use This
Test Query
API KEY
…
Run
Commit
Commit Message
add 1960-movies custom query
Commit

Docs
Custom Queries
GET 1960-movies






