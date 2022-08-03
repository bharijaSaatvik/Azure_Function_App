# Build API using Azure Function with Python and Azure Cosmos DB
In this tutorial, we’re going to build a Serverless API using HTTP Triggers in Azure Functions that uses a Azure Cosmos DB as database. We’re going to build an API that stores information about products.

# What is Azure Function?
Azure Functions are small pieces of code that we can run in Azure without worrying too much about application infrastructure. One of the great advantage using Azure Function is to save cost, the charges on happen when the functions are executed. Comparing with traditional server based or container based technology, whether or not the functions are executed, the charges is based on the duration that the application servers run.

# What is Azure Cosmos DB?
Azure Cosmos DB is a fully managed globally distributed NoSQL database. It provides schema agnostic capabilities for developers to develop modern applications. Azure Cosmos DB elastically scale the provisioned throughput and storage for your Cosmos databases based on your need and pay only for the throughput and storage you need. This leads to significant cost savings.

# GOAL🎯
In this we shall be following below steps:
1. Create a new Cosmos DB account and container.
2. Create a new Azure Function using Visual Studio Code and test.
3. Develop the two APIs — CreateUser and GetUsers
4. Deploy the two functions to the Azure Function

# Flow-chart
![image](https://user-images.githubusercontent.com/108589568/182418384-ea0fb5df-b2a8-471f-8f56-319c32ece6d5.png)

# 1. Create new Azure Cosmos DB account
Create a Azure Cosmos DB Account on the Azure portal. 
Enter an account name for the Cosmos DB and leave other options as default. 
Click Review + Create.
![image](https://user-images.githubusercontent.com/108589568/182665541-ba3d469d-2ff9-40a3-88f8-9099107c2d51.png)
After the validation is successful, we can click on the Create button.

On the Overview page, click ‘Add Container’ button to create new container.
![image](https://user-images.githubusercontent.com/108589568/182666227-c453acba-9e32-424e-a6dd-b04f2729bd75.png)

Enter the Key in the Database id (serverless-db), Container id(user) and the Partition key (can use the /id as partition key). Remember the Database id and Container Id because we would be using on the later part of the tutorial. Click OK.
![image](https://user-images.githubusercontent.com/108589568/182666783-4989d669-b0eb-4069-9707-e9125502c91d.png)

After the successful creation of the container and database, it should appear on the Data Explorer view.
Step 1 is now completed.


# 2. Create new Azure Function
To create a Function in Azure, there are few ways to do it. One of the simplest way is to create functions on the Azure portal. Also we can do in VS code as well.

# 3. Create NewUser API

# 4. Create Get User API

# 5. Test Function App on Azure Portal


