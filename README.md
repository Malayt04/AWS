# AWS for devops

These are the notes and link to resources that I am creating while learning aws. 
Also these notes are based on a youtube playlist. You can checkout the lectures with this link (https://www.youtube.com/playlist?list=PLRAV69dS1uWSj3ltu0ym1LwWg4509PZ0N)

# Day 1:

# On premise vs Cloud Infrastructre:
So starting of, you must be wondering what is cloud and how is it diffrent from On Premise infrastructure which means having your own physical servers at a place. So lets discuss about it: 

![Cloud vs On Premise Infrastructure](https://uploads-ssl.webflow.com/5f9497b13bcbdc738e5867c5/61e866fd5c6c47040c2f51c6_Zs3pHSWcULrsP9enPJHSt46HbcIonuBTv--rgoaRXnoWB6p0EAYFEku9S-Tzrvtk2_-u4Vyr6wDLDB7JW5TXWt-f4D6uEtpVgORKqrdasuNXFOWmyyfdHqSa1PQBBLZ1ufzAXjbK.png)

Lets discuss the points given in the above image:

## On premise Infrastructure:

Since we are setting up our own physical servers in this infrastructure, it requires high investment firstly to find a place and to purchase servers as well. Although the resources are deployed in-house which means you have complete control over the data. But one of the major issue with this infrastructure is that it is very tough to scale this system because of physical servers. You can imagine how tough it would be to purchase new servers everytime and also keep the maintainance of the old one's which is also very important.

## Cloud Infrastructure:

Now as we go through this part you will find many advantages of using cloud over physical servers. Firstly it works on pay as you go model which means we have to pay according to the storage or technology we require and also the amount of users we are handelling which is better that making huge starting investment for buying physical servers. Although the deployment takes place on a third party platform which can create loss of authority of data which reduces the crediblity. But one of the biggest advantage of moving in cloud is scalability and elasticity. You have seen live streams on diffrent platform reaching 1 to 2 crore viewership sometimes. These numbers are managed by the flexibility of cloud infrastructure which helps us to upscale when users are more and even scale down when viewrs are less which is a game changer.


# Types Of Cloud Services:
Okay so by the above information, you have understood why are we moving towards cloud and why not (depends on your requirement), now lets discuss about the different cloud services:

## Infrastructure as a Service (IaaS):

IaaS provides virtualized computing resources over the internet. It allows users to rent infrastructure components like virtual machines, storage, and networking resources on a pay-per-use basis.<br>
Example: Amazon Web Services (AWS) EC2 (Elastic Compute Cloud).<br>
Explanation: AWS EC2 allows users to launch and manage virtual servers (EC2 instances) in the cloud. Users can choose the instance type, operating system, and other configurations based on their requirements.


## Platform as a Service (PaaS):

PaaS provides a platform allowing customers to develop, run, and manage applications without dealing with the underlying infrastructure. It offers development and deployment environments with built-in tools and services.<br>
Example: Heroku, netlify etc.<br>
Explanation: Heroku is a cloud platform that allows developers to deploy, manage, and scale web applications easily. It supports various programming languages and frameworks, providing a seamless deployment experience without worrying about infrastructure management.


## Software as a Service (SaaS):

SaaS delivers software applications over the internet on a subscription basis. Users can access these applications via a web browser without needing to install or maintain any software locally.<br>
Example: Youtube<br>
Explanation:YouTube exemplifies the SaaS model by providing users with access to a software application  over the internet, without requiring installation or maintenance, and offering continuous update.


## Function as a Service (FaaS):

FaaS is a cloud computing service that allows developers to deploy individual functions or pieces of code in the cloud and execute them in response to events or triggers without managing server infrastructure.<br>
Example: AWS Lambda.<br>
Explanation: AWS Lambda allows developers to run code in response to events such as changes to data in Amazon S3 buckets, updates to DynamoDB tables, HTTP requests via Amazon API Gateway, etc. Developers upload their code and Lambda automatically scales and executes it in response to events.



# Control Over Cloud

In cloud computing, control over the cloud refers to the degree of authority and management a user or organization has over their cloud infrastructure and resources. Control can vary based on several factors, including the type of cloud deployment (private, public, hybrid, or multi-cloud) and the level of service provided by the cloud provider. Let's define each type of cloud deployment in the context of control:

## Private Cloud

You own the hardware
You own the software
Only you use it 
Security complaince


## Public Cloud:

Cloud resources are shared over a group of people
Cloud service provider is involved
Control is in the hand of the cloud service provider 
Users have access to virtual machines through web based console

## Hbyrid Cloud

Best of both private and public 
Connection through internet and shared link

## Multicloud

Use multiple cloud service providers to manage the workload of your organisation
eg: aws, azure both together



# AWS (Amazon Web Services)

![AWS](https://repost.aws/static/images/aws.png)

An Amazon company <br>
On demand cloud <br>
Pay what you use <br>
Compute Storage Access data transfer


# AWS global infrastructure 

Amazon Web Services (AWS) is known for its extensive and robust global infrastructure, which enables customers to deploy their applications and services with low latency, high availability, and scalability across the globe. Here's a brief overview of the AWS global infrastructure:

## Regions:
   - AWS operates a global network of data centers known as regions. A region is a geographical area that consists of multiple Availability Zones (AZs).<br>
   - Each region is isolated from other regions to provide fault tolerance and stability. AWS currently has multiple regions worldwide, including regions in North America, South America, Europe, Asia Pacific, and the Middle East.<br>

## Availability Zones (AZs):
   - Availability Zones are distinct data centers within a region that are engineered to be isolated from failures in other Availability Zones.<br>
   - Each AZ is equipped with independent power, cooling, and networking infrastructure to ensure high availability and fault tolerance.<br>
   - By deploying resources across multiple AZs within a region, customers can achieve redundancy and improve the resilience of their applications.<br>

## Edge Locations:
   - In addition to regions and Availability Zones, AWS has a global network of edge locations that are used for content delivery and caching through the Amazon CloudFront service.<br>
   - Edge locations are distributed worldwide and are strategically located to deliver content to end-users with low latency and high data transfer speeds.<br>

## Global Network Backbone:
   - AWS operates a high-speed global network backbone that interconnects its regions and edge locations.<br>
   - This network backbone ensures fast and reliable communication between AWS services, regions, and edge locations, enabling customers to transfer data and access resources efficiently.<br>

## AWS Direct Connect:
   - AWS Direct Connect provides dedicated network connections between customer data centers, office locations, or colocation environments and AWS.<br>
   - By using AWS Direct Connect, customers can establish private and secure connections to AWS, bypassing the public internet, and achieve predictable network performance and reduced latency.<br>

## AWS Local Zones and Wavelength Zones:
   - AWS has introduced Local Zones and Wavelength Zones to bring AWS services closer to end-users and specific geographic locations.<br>
   - Local Zones are extensions of AWS regions that are located closer to metropolitan areas, enabling customers to run latency-sensitive applications with single-digit millisecond latency.<br>
   - Wavelength Zones are deployed at the edge of telecommunication networks and are optimized for ultra-low latency applications, such as mobile edge computing and 5G-enabled services.<br>

![AWS global infrastructure](https://digitalcloud.training/wp-content/uploads/2022/02/aws-regions-availability-zones.png)



