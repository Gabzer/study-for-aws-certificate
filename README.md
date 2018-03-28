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

-Cloud9: is a place where you can develop your code inside the AWS console so you do not even do it on your desktop but in a browser.


_Management Tools_

-CloudWatch: monitoring service.

-CloudFormation: to work as a solution architect. Way to create infrastructure scripts. Important for the solution architect.

-CloudTrail: is used to record changes in your AWs environment.

-Config: monitors the configuration of your entire AWS environment. Possibility to view your environment in the state it was in the past.

-OpsWorks: similar to Elastic Beanstalk. Way to automate your environment.

-Service Catalog: way to manage i.t. services that are proof of use in AWS.

-Systems Manager: is an interface manage your AWS features.

-Trusted Advisor: will give you advice in several different disciplines. It also tells you if you are not using your AWS services as much as you can and how to save money on using AWS.

Managed Services: helps manage cloud services.

---------------------------------------------------------------------------------

**EXAM TIPS**

CloudWatch is very important to the exam

---------------------------------------------------------------------------------


_Media Services_

-Elastic Transcoder:

-MediaConvert: can be a file-based video transcoding service with broadcast capabilities. Allows you to create videos and require content for broadcast and multi-media display.

-MediaLive: is a broadcast grade of a live video processing service. Create high-quality video streams for you to stream to broadcast TVs and connected to the internet.

-MediaPackage: prepares and protects your videos for delivery over the Internet.

-MediaStore: great place to store your media which offers excellent performance, good consistency and low latency.

-MediaTailor: allows you to do targeted advertising on video streams without sacrificing the level of transmission quality of service.


_Machine Learning_

-SageMaker: it is very easy for developers to use Deep Learning when they basically encode the environments.

-Comprehend: is a kind of analysis of feeling around data, to tell whether people say good things or not about their products.

-DeepLens: is artificially a web camera that discovers what it is that you are looking at. Dublin is a physical piece of hardware.

-Lex: asrtificially intelligent way of communicating with customers.

-Machine Learning: the difference between Deep Learning and Machine Learning is that Deep Learning is connected to neural networks while Machine Learning is still very kind of entry level for learning to be smarter. Machine Learning is the best way to describe Deep Learning. Machine Learning is basically a set of data in the AWS cloud. It will then analyze that data set and provide some results and determine whether or not it bases any data on any new data that you know or do not know. It will predict a result with uncertain Machine Learning terms.

-Polly: takes Lex and turns it into speech.

-Rekognition: make videos and images. You upload a file and it tells what's in that file.

-Amazon Translate: translator.


_Analytics_

-Athena: allows you to run sequel core theories against things in your first three buckets.

-EMR: for Big Data. Has a lot of different servers and hacks your data for analysis.

-CloudSearch: for the AWS.

-ElasticSearch Service: for the AWS.

-Kinesis:

-Kinesis Video Streams:

-QuickSight: Amazon business intelligence tool.

-Data Pipeline: way to move your data between different AWS services.

-Glue: news service. Extracts and transforms data into a data transfer