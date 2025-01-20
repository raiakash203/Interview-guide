# Interview-guide

## 1. How do you approach issues with data accuracy and data quality in your projects?

Effective data management practices start with establishing strict data validation rules to check the data’s accuracy, consistency, and completeness. Here are some strategies candidates might mention: 

Implement automated cleansing processes using scripts or software to correct errors 

Perform regular data audits and reviews to maintain data integrity over time

Collaborate with data source providers to understand the origins of potential issues and improve collection methodologies 

Design a robust data governance framework to maintain the high quality of data

## 2. How do you ensure the scalability of a data pipeline?

Scalability in data pipelines is key for handling large volumes of data without compromising performance. 

Here are some of the strategies experienced candidates should mention: 

Using cloud services like AWS EMR or Google BigQuery, as they offer the ability to scale resources up or down based on demand. 

Perform data partitioning and sharding to distribute the data across multiple nodes, reducing the load on any single node

Optimizing data processing scripts to run in parallel across multiple servers

Monitoring performance metrics with the help of monitoring tools and making adjustments to scaling strategies

## 3.How would you handle event duplication in an Event-Driven system?

Event duplication can occur due to network retries, system failures, or bugs. Handling duplication ensures data consistency and reliability. Strategies include:

Idempotency: Design event handlers to have the same effect when processing an event multiple times.
Unique Event Identifiers: Assign unique identifiers to events and check for duplicates before processing.
Event Sourcing: Store a log of all events to detect and ignore duplicates.
Deduplication Queues: Filter out duplicates before they reach event handlers.
Database Constraints: Use unique keys or indexes to prevent duplicate entries.

## 4. What are the steps involved in a CloudFormation Solution?

Create or use an existing CloudFormation template using JSON or YAML format.
Save the code in an S3 bucket, which serves as a repository for the code.
Use AWS CloudFormation to call the bucket and create a stack on your template. 
CloudFormation reads the file and understands the services that are called, their order, the relationship between the services, and provisions the services one after the other.

## 5. what are the limitation of lambda functions?


## 6. how would you over come the scenario of cold start in case of lambda?


## 7. what are different ways you can deploy your lambda functions


## 8. How would you use a shared library in different lambda function wotuout duplicating the code in each functions

## 9. suppose you have files in s3 bucket and you need to process them as they are uploaded in the bucket. How would you achieve this?


## 10. And a follow up question in the above scenario what would happen if you get millions of files in one go in the bucket. how woild you handle the scenario
