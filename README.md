# lobsolution.net
## Inventory Management Solution

I started this project because I wanted to apply all my 20+ years of software development in designing the best product I could.
Everytime I learn a new technology, which can be useful for this, I just use it, even if I have to rewrite a lot of code.
Right now the source code is still not open, but it will probably be soon.
I used all open source technologies with free licence as this is a free version.
For an Enterprise/Custom version, buying licences may be required.

If you want to try it, the demo of the latest version is at: http://demo.lobsolution.net
This user is read-only

Username:
demo@lobsolution.net

Password:
Demo111$

I hope you enjoy it!

This docker compose file is to spin-up the entire infrastructure.

# Prerequisite
- Docker installed (https://www.docker.com/get-started)
- At least 8GB of RAM assigned to Docker

# Usage
- Download the docker-compose.yml file
- Open a Powershell/Bash shell and point to the directory where you downloaded the file
- type: 
    docker-compose up -d
- open the browser and go to http://localhost:5030

As this is a free version, the HTTPS is not enabled. 


# DESIGN
- DDD (Domain Driven Development)
- Microservices
- Event Driven
- State Machine
- SSO (Single Sign On)
- OAuth2/OpenId Connect

# TECHNOLOGIES
- Frontend
  - HTML
  - CSS
  - JQuery
  - TypeScript
  - JavaScript
  - Angular 7
  - Bootstrap 5
  - PrimeNG
  - AdminLTE

- Backend
  - C#
  - .NET CORE 3.1
  - SqlServer 2019

- Infrastructure
  - IdentityServer4
  - Confluent Kafka
  - Elasticsearch
  - Kibana
  - Docker


# FUNCTIONALITIES
  - Dashboard
- INVENTORY
  - Color
  - Size
  - Category
  - Category Group
  - Product
  - Stock Movement
  - Stock Location
- PURCHASE
  - Bill Type
  - Bill
  - Purchase Type
  - Purchase Order
  - Payment Source
  - Purchase Payment
  - Goods Received Note
  - Supplier Type
  - Supplier
- SALES
  - Customer Type
  - Customer
  - Sale Type
  - Shipment Method
  - Sale Order
  - Shipment
  - Invoice Type
  - Invoice
  - Sale Payment
  - Promotion
- ADMINISTRATION
  - User
  - User Roles
  - Custom Roles
  - CONFIGURATION
  - System
  - Company
  - Branch
  - Warehouse
  - Payment Method
  - Currency
  - Unit of Measure
  - Tax Code
- INTEGRATION
  - Import
