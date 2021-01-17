### Overview
This service was developed as part of the [Introduction to Azure Spring Cloud]

Order Service is a pass-through application. It demonstrates the usage of Service Registry provided by the Azure Spring Cloud. 

Order Service receives an order and invokes the [Inventory Service] using Netflix Eureka and OpenFeign, to update the inventory in an Azure Cosmos Database. 

