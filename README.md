# Serverless architecture

Litware, Inc. is rapidly expanding their toll booth management business to operate in a much larger area. As this is not their primary business, which is online payment services, they are struggling with scaling up to meet the upcoming demand to extract license plate information from a large number of new tollbooths, using photos of vehicles uploaded to cloud storage. Currently, they have a manual process where they send batches of photos to a 3rd-party who manually transcodes the license plates to CSV files that they send back to Litware to upload to their online processing system. They want to automate this process in a way that is cost effective and scalable. They believe serverless is the best route for them, but do not have the expertise to build the solution.

## Target Audience

Application Developers & Technical Architects

## Abstract

### Workshop

In this workshop, you will work as a group to setup and configure a serverless architecture within Azure using a combination of Azure Functions, Logic Apps, Event Grid, Cosmos DB, and Azure Storage. The focus is on removing server management from the equation, breaking down the solution into smaller components that are individually scalable, and allowing the customer to only pay for what they use.

Learning Objectives:

- Use a series of Azure Functions that independently scale and break down business logic to discrete components.

- Use computer vision algorithms within an Azure Function to accurately detect license plates in car images at scale.

- Provision and use Cosmos DB as a highly available NoSQL data store for processed data.

- Create a Logic App that contains a workflow to export processed license plates and conditionally send alerts based on successful or unsuccessful operation.

- Use App Insights to monitor the serverless topology, observing how well the solution scales when under load.

- Implement a Continuous Deployment DevOps process to automatically publish changes to Function Apps.

### Hands-on Lab

The Serverless architecture hands-on lab is an exercise that will challenge you to implement an end-to-end scenario using a supplied sample that is based on Microsoft Azure Functions, Azure Cosmos DB, Event Grid, and related services. The scenario will include implementing compute, storage, workflows, and monitoring, using various components of Microsoft Azure. The hands-on lab can be implemented on your own, but it is highly recommended to pair up with other members at the lab to model a real-world experience and to allow each member to share their expertise for the overall solution.

## Azure services and related products

- Azure Functions
- Azure Cognitive Services
- Azure Event Grid
- Application Insights
- AzureCosmos DB
- Logic Apps
