Study for AWS certificate
=========================

**The AWS Platform**

|                        |                          |                     |
|------------------------|--------------------------|---------------------|
|                        | Game Development         |                     |
| Business productivity  | Desktop & App Streaming  | Internet Of Things  |
|       AR / VR          | Application integration  | Customer Engagement |
|      Analytics         |Security & Identity & Compliance|Mobile Services|
|    Management Tools    |      Media Services      |  Machine Learning   |
|       Migration        |Networking & Content Delivery|  Developer Tools |
|        Compute         |           Storage        |      Database       |
|                        |AWS Global Infrastructure |                     |


_What is a Region? What is an AZ ?_

A Region is a geographical area. Each Region consists of 2 (or more) Availability Zones. An Availability Zone(AZ) is simply a Data Center.

An AZ is one or more discrete data centers, each with redundant power, networking and connectivity, housed in separate facilities.


_What is an Edge Location ?_

Edge Location are endpoints for AWS which are used for caching content. Typically this consists of CloudFront, Amazon's Content Delivery Network (CDN).

---------------------------------------------------------------------------------

**EXAM TIPS**

Understand the difference between a Region, an Availability Zone(AZ) and an Edge Location.

---------------------------------------------------------------------------------

_Compute_

-EC2: virtual machines into AWS platform.

-EC2 Container Service: manage the conteiners Dockers at scale.

-Elastic Beanstalk: is an easy-to-use service for deployment and scalability of web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go and Docker on known servers such as Apache, Nginx, Passenger and IIS.

-Lambda: is the code uploaded in the cloud and you control when execute.

-Lightsail: includes everything you need to quickly start your project: a virtual machine, SSD-based storage, data transfer, DNS management and a static IP.

-Batch: use for the batch computing in the cloud.


_Storage_

-S3 (Simple Storage Service): object based storage.

-EFS: storage connected at a network.

-Glacier: archiving all of you data.

-Snowball: way to bring large amounts of data to the AWS data center.

-Storage Gateway: are the virtual machines that you install in your data center or your headquarters.


_Databases_

-RDS (Relational Data service): database relational.

-DynamoDB: non-relational database.

-Elasticache: way to store in cache.

-Red Shift: for data warehousing or business intelligence.


_Migration_

-AWS Migration Hub: basically a tracking service that allows you to track your apps as you migrate them to AWS and integrates with other services within the migration framework that will come in a second.

-Application Discovery Service: automated tool set and not only detects which apps you have but its dependencies.

-Database Migration Service: very easy way to migrate your local data to AWS.

-Server Migration Service: very easy way to migrate your local server to AWS.

-Snowball: way to bring large amounts of data to the AWS data center.


_Networking & Content Delivery_

-VPC (Amazon Virtual Private Cloud): virtual data center. You configure firewalls, availability zones, a network side range varies, you set up a route table. **Very important for the exam.**

-CloudFront: amazon content distribution network. If you think of media assets or things like video files or image files, the CloudFront allows you to access them from a nearest endpoint.

-Route53: Amazon DNS service.

-API Gateway: way to create your own API to talk to your other services. **Very important for the exam.**

-Direct Connect: makes it easy to establish a dedicated network connection between the local environment and AWS.


_Developer Tools_

-CodeStar: way to collaborate with other developers who are working on a project.

-CodeCommit: Amazon repository.

-CodeBuild: compiles your code or runs tests and produces ready-to-deploy software packages.

-CodeDeploy: deployment services. Automates deployments of apps to two instances but can also do so in local instances.

-CodePipeline: continuous delivery service, use some kind of model and visualize and automates the steps required to free up your software.

-X-Ray: is used to debug and analyze your serveless application. It has order tracking in which you can actually log in and find the causes of the performance bottlenecks.

-Cloud9: is a place where you can develop your code inside the AWS console so you do not even do it on your desktop but in a browser
