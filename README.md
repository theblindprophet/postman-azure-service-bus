# Postman Azure Service Bus

## Introduction

In my main job I interact with Azure Service Bus queues very often. Usually when I need to build services to send and receive from a queue, I build the "sender" or "receiver" first and have difficulties testing. The Azure Portal has a decent UI called an explorer, but it is extremely simple and doesn't support everything I need. With this Postman collection you can now create, edit, delete queues and then send, receive, peek, and unlock messages.

## What it does

These collections handles three main things: 

1. Azure authentication using a device code method and access tokens
2. Almost all of the REST operations supported for service bus queues including:
    - Create queue
    - Update queue
    - Get queue(s) details
    - Delete queue
    - Send queue message
    - Send queue messages (bulk)
    - Peek queue message
    - Receive and delete message
    - Unlock message
3. Run a **Postman Monitor** for listening to a queue's complimentary deadletter queue
    - Fail **Postman Test** and report error of deadletter reason

## Azure Application Instructions

1. Create Azure Subscription at portal.azure.com
2. Create an Azure App Registration
   ![Create an Azure App Registration](https://github.com/theblindprophet/postman-azure-service-bus/blob/master/images/create_azure_app.png?raw=true)
3. Allow public client flow
   ![Allow public client flow](https://github.com/theblindprophet/postman-azure-service-bus/blob/master/images/add_azure_app_public_client.png?raw=true)
4. Create Azure App platform configuration
   ![Create Azure App platform configuration](https://github.com/theblindprophet/postman-azure-service-bus/blob/master/images/add_azure_app_platform_config.png?raw=true)
5. Add Azure App permissions
   ![Add Azure App permissions](https://github.com/theblindprophet/postman-azure-service-bus/blob/master/images/add_azure_app_permission.png?raw=true)
6. Grant Azure App permissions, if needed
   ![Grant Azure App permissions](https://github.com/theblindprophet/postman-azure-service-bus/blob/master/images/grant_azure_app_permission.png?raw=true)

## Create Service Bus Instructions

1. Create Service Bus Namespace
   ![Create Service Bus Namespace](https://github.com/theblindprophet/postman-azure-service-bus/blob/master/images/create_service_bus_namesplace.png?raw=true)

## Demo

[Demo Video](https://github.com/theblindprophet/postman-azure-service-bus/blob/master/videos/demo.mp4?raw=true)

## Author

Jamie Gross (theblndprophet@gmail.com)

Linked In: https://www.linkedin.com/in/james-l-gross/

I work for [Orange Bees](https://orangebees.com), a software engineering consulting company in Greenville, SC, as a Principal Engineer. I write Angular and .NET applications, architect projects in Azure (Azure Developer Associate certified), and dabble in ElasticSearch and Node.js.