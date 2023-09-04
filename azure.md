# Azure Exploration

## Storage Services

### 1. Azure Blob Storage
- **Description**: Azure Blob Storage is Microsoft's object storage solution for the cloud. It is optimized for storing massive amounts of unstructured data, such as text or binary data.
- **Python Interaction**: Blobs in Azure Storage are organized into containers. Python can be leveraged to create containers and upload blobs (like files or other data) to the containers using the Azure Storage Blob client library for Python.

### 2. Azure Confidential Ledger
- **Description**: Microsoft Azure Confidential Ledger (ACL) is a new and highly secure service for managing sensitive data records. It runs exclusively on hardware-backed secure enclaves, a heavily monitored and isolated runtime environment that keeps potential attacks at bay. 
- **Python Interaction**: You can create a Python application to write and read data from the Azure Confidential Ledger using the Azure Confidential Ledger Python SDK.

## Compute Services

### 1. Azure Web Apps
- **Description**: Azure App Service enables you to build and host web apps, mobile back ends, and RESTful APIs in the programming language of your choice without managing infrastructure.
- **Python Interaction**: A Python web app can be developed and deployed using Azure App Service, where it can be managed and scaled easily.

### 2. Azure Functions
- **Description**: A serverless solution that allows you to run event-driven code in response to a variety of events.
- **Python Interaction**: Python functions can be created to respond to events like HTTP requests, where they can be deployed as serverless functions on Azure Functions.

## Database Services

### 1. Azure SQL Database
- **Description**: A fully managed platform as a service (PaaS) database engine that handles most of the database management functions such as upgrading, patching, backups, and monitoring without user involvement.
- **Python Interaction**: Python and the Python SQL Driver - pyodbc can be used to connect an application to a database in Azure SQL Database and perform data retrieval and manipulation queries.

### 2. Azure Cosmos DB
- **Description**: Azure Cosmos DB is a fully managed NoSQL and relational database for modern app development. Azure Cosmos DB offers single-digit millisecond response times, automatic and instant scalability, along with guaranteed speed at any scale.
- **Python Interaction**: You can use Python to interact with Azure Cosmos DB in various ways such as creating a database, creating a container, adding items to a container, and querying items in a container using Python SDKs and APIs provided by Azure.


