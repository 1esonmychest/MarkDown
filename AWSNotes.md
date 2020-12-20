# Week 7 Day 4: Introduction - Cloud Foundations
## Introduction to Cloud Foundations on AWS
### Module 0: Welcome to Cloud Foundations on AWS
#### Part 1 

> What you will learn
```
At the core of the lesson
```
You will learn how to:
* Describe the course objectives and overview
* Create your AWS Training Portal account
* Access course materials

You will discuss:
* The origins of cloud computing

You will build:
* Project - Creating the AWS Training Portal Account

# Cloud Foundations on AWS: Course objectives and overview
> Prerequisites
```
General required knowledge
```
* IT technical knowledge
* IT business knowledge
```
Preferred knowledge
```
* Familiarity with cloud computing concepts
* Working knowledge of distributed systems
* Familiarity with general networking concepts
* Working knowledge of multi-tier architectures
> Course objectives
```
Define the AWS Cloud concepts
```
Explain cloud economics
* Define pricing models
* Describe the AWS cloud value proposition

Describe core AWS services
* Describe characteristic of deployment/operation
* Review common use cases

Explain AWS Cloud security
* Review the shared responsibility model: security "in" the cloud and "of" the cloud
* Review basic security and compliance

Describe basic AWS Cloud architecture principles

Review cloud billing and support services
> Course outline

Module 0: Welcome to Cloud Foundations on AWS

Module 1: Introduction to Cloud Computing

Module 2: Cloud Economics

Module 3: AWS Core Services
* Compute
* Storage
* Virtual Private Cloud (VPC)
* Database
* Load Balancing, Monitoring, Automatic Scaling

Module 4: AWS Cloud Security

Module 5: Cloud Architecting

Module 6: Cloud Billing and Support Services
# Module details
> Module 1 details: Introduction to Cloud Computing
```
Module 1: Introduction to Cloud Computing
```
Part 1: What is Cloud Computing?

Part 2: Six Advantages of Cloud Computing

Part 3: What is Amazon Web Services (AWS)?

Part 4: AWS Cloud Adoption Framework (AWS CAF)
> Module 2 details: Cloud Economics
```
Module 2: Cloud Economics
```
Part 1: Fundamentals of AWS Pricing

Part 2: Total Cost of Ownership (TCO)

Part 3: AWS Infrastructure Overview
>Module 3 details: AWS Core Services
```
Module 3, Section 1: AWS Core Services-Compute
```
Part 1: Compute Services Overview and Amazon EC2

Part 2: AWS Lambda and AWS Elastic Beanstalk
```
Module 3, Section 2: AWS Core Services-Storage
```
Part 1: Amazon Elastic Block Store (Amazon EBS)

Part 2: Amazon Simple Storage Service (Amazon S3)

Part 3: Amazon Elastic File System (Amazon EFS)

Part 4: Amazon Simple Storage Service Glacier
> Module 3 details: AWS Core Services, cont'd
```
Module 3, Sections 3: AWS Core Services-Virtual Private Cloud (VPC)
```
Part 1: Amazon Virtual Private Cloud (Amazon VPC)

Part 2: AWS Security Groups
```
Module 3, Section 4: AWS Core Services-Database
```
Part 1: Amazon Relational Database Systems (Amazon RDS)

Part 2: Amazon DynamoDB

Part 3: Amazon Redshift

Part 4: Amazon Aurora
> Module 3 details: AWS Core Services, cont'd
```
Module 3, Section 5: Load Balancing, Monitoring, Automatic Scaling
```
Part 1: Elastic Load Balancing

Part 2: Amazon CloudWatch

Part 3: Amazon EC2 Auto Scaling
> Module 4 details: AWS Cloud Security
```
Module 4: AWS Cloud Security
```
Part 1: AWS Shared Responsibility Model

Part 2: AWS Identity and Access Management (IAM)

Part 3: AWS Trusted Advisor

Part 4: AWS CloudTrail

Part 5: AWS Config

Part 6: AWS Day One Best Practices

Part 7: AWS Security and Compliance Program

Part 8: AWS Security Resources
> Module 5 details: Cloud Architecting
```
Module 5: Cloud Architecting
```
Part 1: Introduction to the AWS Well-Architected Framework

Part 2: Deep Dive - Well-Architected Design Principles

Part 3: Understanding Reliability and High Availability

Part 4: Example of Transitioning a Data Center to the Cloud
> Moduel 6 details: Cloud Billing and Support Services
```
Module: Cloud Billing and Support Services
```
Part 1: AWS Organizations

Part 2: AWS Billing and Cost Management

Part 3: AWS Support Services
# Week 7 Day 4: Introduction to Cloud Computing
## What is Cloud Computing
### Module 1: Introduction to Cloud Computing
#### Part 1
> What you will learn

**At the core of the lesson**

You will learn how to:
* Describe cloud computing
* Define different models of cloud computing
* Distinguish between deployment methods and determine the difference between on-premises and cloud

You will discuss:
* The origings of cloud computing
```
Key Terms:
* High availability:
* Fault tolerance:
* Low latency:
* Scalability:
* Elasticity:
```
> Important cloud terminology
* High availability (highly available)
    * Accessible when you need it
* Fault tolerance (fault tolerant)
    * Ability to withstand a certain amount of failure and still remain functional
* Scalability (scalable)
    * Ability to easily grow in size, capacity, or scope when required
    * Growth is (usually) based on demand
* Elasticity (elastic)
    * Ability to grow (scale) when required and to reduce in size when resources are no longer needed
### Understanding cloud computing
> What is cloud computing?

Cloud computing is the *on-demand* delivery of compute power, database storage, applications, and other IT resources. These resources are delivered through a cloud services platform *via the internet* with *pay-as-you-go* pricing
>Before cloud computing

**Infrastructure as software**
Hardware solutions are physical, and they require:
* Space
* Staff
* Physical security
* Planning
* Capital expenditure

You must guess at theoretical maximum peaks:
* Is there enough resource capacity?
* Do we have sufficient storage?

What if your needs change?
* You must go through the time, effort, and cost required to change all these
>Using cloud computing

**Software is flexible**

If your needs change, your software can change much more *quickly, easily, and cost-effectively* than your hardware
### Models of cloud computing
> Three example models of cloud computing

IaaS-Infrastructure as a service

PaaS-Platform as a service

SaaS-Software as a service

![Cloud Models](https://www.rividium.com/images/cloudmodels.png "Cloud Models")
### Cloud deployment models
> Three cloud deployment models

All-in cloud

Hybrid

Private cloud (on-premises)
>All-in cloud versus on-premises

* All-in cloud
    * No upfront investment
    * Low ongoing costs
    * Focus on innovation
    * Flexible capacity
    * Speed and agility
    * Global reach on demand
* Private cloud
    * Large initial purchase
    * Labor, patches, and upgrade cycles
    * Systems administration
    * Fixed capacity
    * Long procurement cycle and setup
    * Limited geographic regions

[Cloud Deployment Models](https://blog.dbdigger.com/basics-of-cloud-technology/ "Link to Cloud Models")
>What can you do in the cloud?

**You can use cloud computing for:**

Application hosting

Backup and storage

Content delivery

Websites

Enterprise IT

Databases
### Section wrap-up

**What is Cloud Computing?**
* On-demand delivery of IT resources online with pay-as-you-go pricing
* Three models of cloud computing are:
    * Infrastructure as a service (IaaS)
    * Platform as a service (PaaS)
    * Software as a service (SaaS)
* All-in cloud, hybrid, and private cloud are three cloud deployment models
* Cloud services are available to replace traditional on-premises computing activities
### Up next:

**Six Advantage of Cloud Computing**
# Week 7 Day 4: Introduction - Six Advantages
> Advantage 1: Capex to variable expense

> Captial expense versus variable expense

**Capital expense (capex):**
* Funds that a company uses to acquire, upgrade, and maintain physical assets such as property, industrial buildings, or equipment

**Variable expense**
* An expense that the person who bears the cost can easily alter or avoid
>Advantage 2: Economies of scale

Benefit from massive economies of scale
> Economies of scale

Hardware solutions are physical and require:
* Space
* Staff
* Physical security

Significant cost to procure and house these resources:
* No purchasing power
* Cloud providers use hundreds of thousands of customers to achieve economies of scale
> Advantage 3: Capacity planning

Eliminate guessing about your capacity needs
> Guessing about capacity
1. What are the potential maximum peaks in usage?
0. Is there enough resource capacity at peak?
3. Is the amount of storage sufficient?
> Advantage 4: Speed and agility

> Increase speed and agility

Rapid availability of new resources
* Provision resources in minutes, not weeks 

Increase innovation
* Quick, low cost experimentation
* Use prefabricated functionality without requiring in-house expertise (date warehousing, analytics)

Increase experimentation
* Explore new avenues of business with minimal risk and expense
* Test with different configurations
> Advantage 5: Spend strategically

Stop spending money on running and maintaining data centers
> Stop spending money on data centers

* Focus on customers
* Focus on projects that differentiate the business
* Delegate the ranking, stacking, and powering of servers to the cloud provider
> Advantage 6: Ease of deployment

Go global in minutes

![Go global!](https://images.wallpaperscraft.com/image/planet_sphere_globe_124700_1920x1080.jpg "Go global in minutes!!!")
> AWS Infrastructure

Regions, Availability Zones (AZ's) and Edge Locations
![Regions and AZ's](https://image.slidesharecdn.com/2-150706192311-lva1-app6892/95/aws-govcloud-us-an-overview-2-638.jpg?cb=1436214432 "Regions and AZ's")
> Amazon customer success case studies

Visit AWS Customer Success Page @:

[AWS Customer Success](https://aws.amazon.com/solutions/case-studies/)
# What is Amazon Web Services (AWS)
## Module 1: Introduction to Cloud Computing
### Part 3
> What you will learn

**At the core of the lesson**

You will learn how to:
* Explain in general what a web service is
* Explore services that Amazon Web Services (AWS) offers
* Examine ways to access AWS services

You will discuss:
* What web services are
```
Key Terms:
* AWS Core Services
* AWS Foundational Services
* Software development kits (SDK's)
* AWS Command Line Interface (AWS CLI)
```
> On premise vs AWS comparison

![Table](https://www.cloverinfotech.com/wp-content/uploads/2019/09/Infographics-Cloud-based-vs-On-premise-IT-Systems.png "Comparison scale")
> What are web services?

A web service is any piece of software that makes itself available over the internet.
It uses a standardized format, either Extensible Markup Language (XML) or JavaScript Object Notation (JSON), for the request and the response of an API interaction.

![Demo](https://image.slidesharecdn.com/windowsazuretoolkitios-110727123833-phpapp02/95/windows-azure-toolkit-for-ios-55-728.jpg?cb=1311771077 "Device request/Cloud response")
> What is AWS?

**AWS is a secure cloud services provider with many different services that include solutions for:**

|Compute |Storage |End user computing |
|--------|--------|------------------|
|Management and governance |Media services |Migration and transfer |
|Mobile |Developer tools |Networking and content delivery |
|Analytics |Customer engagement |Application integration |
|AWS Billing and Cost Management |Robotics |Database |
|Game tech |Machine learning |Internet of Things |
|Blockchain |AR & VR |Satellite
> AWS by category: Core services

|Amazon EC2|AWS Lambda|AWS Fargate|
|----------|----------|-----------|
|Auto Scaling|AWS Elastic Beanstalk|AWS Outposts|
|Amazon Elastic Container Registry|Amazon Elastic Container Service|VMware Cloud on AWS|
|Amazon Lightsail|AWS Batch|AWS Serverless Application Repository|
|           |**Compute**|               |

|Amazon VPC|Amazon Route 53|AWS Direct Connect|
|----|-----|----|
|Elastic Load Balancing|AWS PrivateLink|AWS Client VPN|
|   |**Networking**|    |

|Amazon S3|Amazon EBS|Amazon CloudFront|
|-|-|-|
|Amazon S3 Glacier|Amazon Elastic File System|AWS Snowball
|Storage Gateway|   |AWS Snowmobile|
|   |**Storage**|   |

|Amazon RDS|Amazon DynamoDB|Redshift|
|-|-|-|
|AWS Database Migration|    |Amazon ElastiCache|
|   |**Database**|  |
> AWS by category: Foundational services

|Amazon EMR|AWS Data Pipeline|Amazon Elasticsearch|
|-|-|-|
|Amazon Kinesis|Amazon Machine Learning|Amazon QuickSight|
|Amazon Redshift|   |Amazon Athena|
|   |**Analytics**| |

|Amazon WorkSpaces|Amazon WorkLink|Amazon WorkDocs|
|-|-|-|
|Amazon AppStream 2.0|  |   |
|   |**End user computing**|    |

|Amazon Pinpoint|AWS Device Farm|AWS Amplify|
|-|-|-|
|AWS Mobile SDK's|AWS AppSync|Amazon API Gateway|
|Amazon Mobile Analytics|AWS Mobile HUB|Amazon SNS|
|Amazon Cognito|    |   |
|   |**Mobile services**|   |

|Amazon FreeRTOS|AWS IoT 1-Click|AWS IoT Analytics|
|-|-|-|
|AWS IoT Core|AWS IoT Device Defender|AWS IoT Button|
|AWS IoT Events|AWS IoT Device Management|AWS IoT Greengrass|
|AWS IoT SiteWise|  |AWS IoT Things Graph|
|   |**Internet of Things**| |
> AWS by category: Developer and operations services

|AWS CodeCommit|AWS CodeDeploy|AWS CodePipeline|
|-|-|-|
|AWS CodeBuild|AWS X-Ray|AWS CodeStar|
|AWS CLI|   |   |
|   |**Developer tools**|   |

|Amazon CloudWatch|AWS CloudFormation|AWS CloudTrail|
|-|-|-|
|AWS Config|AWS Trusted Advisor|AWS Organizations|
|   |**Management and governance**| |

|AWS Identity and Access Management|AWS Directory Service|Amazon Inspector|
|-|-|-|
|AWS CloudHSM|AWS Key Management Service|AWS WAF|
|AWS Certificate Manager|   |AWS Shield|
|   |**Security, identity, and compliance**|    |

|Amazon API Gateway|Amazon AppStream|Amazon CloudSearch|
|-|-|-|
|Amazon Elastic|Amazon SES|Amazon SNS|
|Amazon SQS|    |Amazon SWF|
|   |**Application integration**|   |
> Core services: Focus on key services

|Amazon EC2|AWS Lambda|AWS Elastic Beanstalk|
|-|-|-|
|   |**Compute**|   |

|Amazon VPC|    |Amazon Route 53|
|-|-|-|
|   |**Networking**|    |

|Amazon S3|Amazon CloudFront|Amazon S3 Glacier|
|-|-|-|
|   |**Storage**|   |

|Amazon RDS|    |Amazon DynamoDB|
|-|-|-|
|   |**Database**| |
> Core Services: Developer and operations

|Amazon CloudWatch| |AWS CloudFormation|
|-|-|-|
|   |**Management and governance**| |

|   |AWS Identity and Access Management|    |
|-|-|-|
|   |**Security, identity, and compliance**|    |
> Access to AWS services

AWS Management Console
* Access on the go with AWS Console Mobile App

AWS Command Line Interface (AWS CLI)

Software development kits (SDK)
# AWS Cloud Adoption Framework (AWS CAF)
## Module 1: Introduction to Cloud Computing
### Part 4
> What you will learn

**At the core of the lesson**

You will learn how to:
* Describe the AWS Cloud Adoption Framework (AWS CAF)
* Explore the six core perspectives of the AWS CAF

You will discuss:

* The six core perspectives of the AWS CAF
```
Key Terms:
* AWS Cloud Adoption Framework (AWS CAF)
* Core perspectives
```
> AWS Cloud Adoption Framework (AWS CAF)

**AWS CAF provides:**
* Perspectives in planning, creating, managing, and supporting a modern IT service
* Guidelines for establishing, developing, and running AWS environments
* Structure for business and IT teams to work together
> Six Core Perspectives

    1. Business Perspective: How do your architectural approaches align technical delivery to business imperatives?

    2. People Perspective: What skills are needed to adopt the AWS cloud platform? Examples include guiding processes of role descriptions, training, certification, and mentoring

    3. Governance Perspective: How do you update the staff skills and organizational processes necessary to ensure business governance in the cloud? How do you manage and measure cloud investments to evaluate business outcomes?

    4. Platform Perspective: What patterns, guidance, and tools are necessary to optimize your use of technology services on AWS? 

    5. Security Perspective: How do you define and implement the required levels of security, governance, and risk management to achieve compliance?

    6. Operations Perspective: How do you provide process, guidance, and tools for optimum operational service management of the AWS environment?

![Six Core Perspectives](https://image.slidesharecdn.com/howtobuildasuccessfulawsconsultingpractice-caminchley-150429111026-conversion-gate02/95/how-to-build-a-successful-aws-consulting-practice-40-638.jpg?cb=1430438451 "CAF core perspectives")
## Section wrap-up
**AWS CAF**
* The AWS CAF helps organizations develop efficient and effective plans for their cloud adoption journey
* The AWS CAF breaks down the complex process of planning a move to the cloud into manageable pieces called perspectives
* The AWS CAF provides guidelines for establishing, developing, and running AWS environments
* This framework provides a structure for business and IT teams to work together
# Fundamentals of AWS Pricing
## Module 2: Cloud Economics
### Part 1
> What you will learn

**At the core of the lesson**

You will learn how to:
* Describe the AWS pricing model
* Explain the advantages of the AWS pricing model
* Explain the concept of total cost of ownership
* Describe the AWS Free Tier, its services, and its limitations
```
Key Terms:
* Aggregated outbound data
* Tiered pricing
* Consolidated Billing
* AWS Identity and Access Management (IAM)
* AWS Elastic Beanstalk
* Amazon EC2 Auto Scaling
* AWS OpsWorks
```
> AWS fundamentals

Pay for AWS fundamentals:
* Compute
* Storage
* Outbound data transfer

No charge:
* Inbound data transfer
* Data transfer between services within the same region

Charge for aggregated outbound
> AWS pricing model

**AWS pricing model:**

While the number and types of services offered by AWS have increased, the AWS philosophy on pricing has not changed

At the end of each month, you pay for what you use. You can start or stop using a product at any time. No long-term contracts are required

**Advantages of the model:**
* Pay for what you use
* Pay less when you reserve
* Pay less when you use more
* Pay less as AWS grows
> First advantage: AWS pricing model

**Pay for what you use**

Pay only for the services you consume, with no large upfront expenses

Lower variable costs adapt to changing business needs
**Benefits**

* Adapt to changing business needs
* Redirect focus on innovation and invention
> Second advantage: Pay less when you reserve

**Reserved instances are available in three options:**

1. All Upfront Reserved Instance (AURI) > largest dicount
3. Partial Upfront Reserved Instance (PURI) > lower discounts
555. No Upfront Payments Reserved Instance (NURI) > smaller discount

**The benefits are:**
* Minimize risk
* Predictably manage budgets
* Comply with policies that require longer-term commitments
> Third advantage: Pay less when you use more

**Pay less by using more**

Realize volume-based discounts:
* Savings as usage increases
* Tiered pricing for services, such as Amazon S3, Amazon Elastic Block Store (Amazon EBS), or Amazon Elastic File System (Amazon EFS) > the more you use, the less you pay per GB
* Data transfer in is always free
* Multiple storage services deliver lower storage costs based on needs

Benefits:
* Choosing the right combination of storage options helps you reduce costs, while perserving performance, security, and durability
> Fourth advantage: Pay even less as AWS grows

**Pay even less as AWS grows:**

AWS is focused on lowering cost of doing business
* Results in AWS passing savings from economies of scale to you
* Since 2006, AWS has lowered pricing 78 times
* Future higher performing resources replace current resources for no extra charge
> Custom pricing

Meet varying needs through custom pricing

Available for high-volume projects with unique requirements
> AWS Free Tier

**The AWS Free Tier hepls customers**
* AWS Free Tier helps customers get started in the cloud
* If you are a new AWS customer, you can use a free usage tier for Amazon S3, Amazon EBS, Elastic Load Balancing, and other AWS services
> Limitations:
* Only new customers
* Up to 1 year
* Applicable to only certain services and options

To learn more, see [AWS Free Tier](https://www.aws.amazon.com/free)

> AWS services included with an AWS Free Tier charge

**AWS services for no additional charge:**
* Amazon Virtual Private Cloud (Amazon VPC)
* AWS identity and Access Management (IAM)
* Consolidated Billing
* AWS Elastic Beanstalk**
* AWS CloudFormation**
* Amazon EC2 Auto Scaling**
* AWS OpsWorks**

##### **Note: There may be changes associated with other AWS services used with these services
## Summary
### Fundamentals of Pricing
* There is no charge for:
    * Inbound data transfer
    * Data transfer between services within the same Region
* Pay for what you use
* Start and stop any time
* No long-term contracts required
* Some services are free, but AWS services used with these services are not free
# Total Cost of Ownership (TCO)
## Module 2: Cloud Economics
### Part 2
> What you will learn

**At the core of the lesson**

You will learn how to:
* Determine the total cost of ownership (TCO)
* Identify the costs associated with a cloud service
* Use the AWS Totcal Cost of Ownership (TCO) Calculator
```
Key Terms:
* Total cost of ownership
```
## Total cost of ownership (TCO)

> On-premises versus the cloud

**Traditional infrastructure**
* Equipment
* Resources and Administration
* Contracts
* Cost

            Not equal to

**Cloud**
* Pay for what you use
* Improve Time to Market & Agility
* Scale Up and Down
* Self-service infrastructure
> Total cost of ownership (TCO) defined

**Total cost of ownership (TCO)**

A financial estimate to help identify direct and indirect costs of a system

Why use TCO?
* To compare the costs of running an entire infrastructure environment or specific workload on premises versus the AWS Cloud
* To budget and build the business case for moving to the cloud

|   |Server costs|  |
|-|-|-|
|Hardware-server,rack,chassis PDUs,ToR switches(and maintenance)|Software-OS,virtualization licenses(+maintenance)|Facilities cost-Space,power,cooling|

|   |Storage costs| |
|-|-|-|
|Hardware-Storage disks,SAN and FC switches|Storage admin costs|Facilities cost-Space,power,cooling|

|   |Network costs| |
|-|-|-|
|Network hardware-LAN switches,load balancer,badnwidth costs|Network admin costs|Facilities cost-Space,power,cooling|

|   |IT Labor costs|    |
|-|-|-|
|   |Server admin|  |
> On premises versus all-in cloud

You could save 96 percent a year by moving your infrastructure to AWS. Your 3-year total savings would be $159,913

|   |3-year total cost of ownership|    |
|-|-|-|
|   |On premises|AWS|
|Server|$91,922|$2,547|
|Storage|$67,840|$4,963|
|Network|$7,660|$-------|
|IT-labor|$-------|$-------|
|**Total**|$167,422|$7,509|

AWS costs includes business-level support
> AWS Simple Monthly Calculator

**AWS Pricing Calculator**
* Estimate monthly costs
* Identify opportunities to reduce monthly costs
* Use templates to compare services and deployment models

**Access the AWS Pricing Calculator:**

[AWS Pricing Calculator](https://calculator.aws/#/)
> AWS Total Cost of Ownership (TCO) Calculator

**The AWS TCO Calculator**
* Estimate cost savings
* Detailed reports
* Modify assumptions

**Accessing the TCO Calculator:**

[TCO Calculator](https://awstcocalculator.com)
> Additional cloud benefit considerations

**Hard benefits**
* Reduced spending on compute, storage, networking, security
* Avoidance of hardware and software purchases (capex)
* Reduction in operations costs, backup and disaster recovery
* Reduction in operations personnel

**Soft savings**
* Reuse of service and appilcations using the same cloud service
* Increased developer productivity
* Improved customer satisfaction
* Imporved employee morale
* Agile business processes that respond quickly to opportunities
* Increase global reach
>Case study: Delaware North TCO--1

**Background:**
* Growing global company, more than 200 locations
* 500 million customers, $3 billion annual revenue

**Challenge:**
* Meet demand to rapidly deploy new solutions
* Constantly upgrade aging equipment

**Criteria:**
* Broad solution to handle all workloads
* Ability to modify processes to improve efficiency and lower costs
> Case study: Delaware North TCO--2

![Case study TCO 2](https://d1.awsstatic.com/diagrams/DelawareNorth-TCO-chart-091815.2a72b1f6615b74b08bd204a9593328cb969478cc.jpg "Delaware North TCO case study 2")
>Case sutdy: Delaware North TCO--3

**Background**
* Growing global company with over 200 locations
* 500 million customers, $3 billion annual revenue

**Challenge**
* Meet demand to rapidly deploy new solutions
* Constantly upgrade aging equipment

**Criteria**
* Broad solution to handle all workloads
* Ability to modify processes to improve efficiency and lower costs

**Solution**
* Moved its on-premises data center to AWS
* Eliminate busy work (e.g. patching software)
* Achieve a positive return on investment (ROI)
> Case study: Delaware North TCO--4

|   |Business Goals|    |
|-|-|-|
|Growth|Enhanced 24/7 business|Operational efficiency

| |Resource optimization|   |
|-|-|-|
|Robust security compliance|Enhanced disaster revoery|Increased computing capacity|

| |Speed to market| |
|-|-|-|
|One day to provision new businesses| |Minutes to push out a service|

| |Operational efficiency| |
|-|-|-|
| |Continuous cost optimization and reduction| |
> Resources

[AWS Economics Center](http://aws.amazon.com/economics/)

[AWS TCO Calculator](https://awstcocalculator.com)

[Simple Monthly Calculator](https://calculator.s3.amazonaws.com/index.html)

[Case studies and research](http://aws.amazon.com/economics/)

# Section wrap-up
## Total Cost of Ownership
* TCO is a financial estimate to help identify direct and indirect costs of a system-
    * Can use to compare costs of environments or workloads on premises versus the cloud
    * Can use for budgets and building the case to move to cloud
* AWS TCO Calculator-
    * Detailed reports with 3-year TCO comparison by cost categories
    * Executive reports
    * Assumptions can be tailored to business needs
# AWS Infrastructure Overview
## Module 2: Cloud Economics
### Part 3
> What you will learn

**At the core of the lesson**

You will learn how to:
* Understand the AWS Global Infrastructure and the types of services that are available
* Examine the AWS Global Infrastructure
* Understand the difference between AWS Regions, Availability Zones, and edge locations
```
Key Terms:
* Elastic infrastructure
* Scalable infrastructure
* Fault-tolerant
```
## AWS Global Infrastructure
![Three elements](https://image.slidesharecdn.com/understandingawsstorageoptions-150330042057-conversion-gate01/95/understanding-aws-storage-options-6-638.jpg?cb=1466107086 "Compute,Networking,Storage")
> AWS data centers

**The foundation for the AWS infrastructure are the data centers**

Data centers usually have characteristics such as:
* A data center is a location where actual physical data resides
* A data center typically has 50,000 to 80,000 physical servers
* All data centers are online. No data center is cold (or not being used)

Also, data centers contain AWS custom network equipment, such as:
* Multi-ODM (Original Design Manufacturer) sourced hardware
* Amazon custom network protocol stack
> AWS Regions

**An AWS Region is a geographical area**
* Each Region is made up of two or more Availability Zones
* AWS has 18 Regions worldwide
* You enable and control data replication across Regions
* Communication between Regions uses AWS backbone network connections infrastructure

![AWS Regions](https://smarttechways.files.wordpress.com/2020/06/aws-region-and-availability-zones.jpg?w=625 "AWS Region,AZs,data centers")
> AWS Global Infrastructure: Current Regions

![Current Regions](https://d1u7j79bg1ays7.cloudfront.net/blog/wp-content/uploads/2016/03/AWS-EC2-Regions.png "Current Regions/Orange-New Regions/Green")
> AWS Availability Zones

**Availability Zones
* Each Availability Zone is:
    * Made up of one or more data centers
    * Desinged for fault isolation
    * Interconnected with other Availability Zones using high-speed private links
* You choose your Availability Zones
* AWS recommends replicating across Availability Zones for resiliency

![Data Center](https://www.datacenterknowledge.com/sites/datacenterknowledge.com/files/azure-availability-zones_0.jpg "Data Center example")
> AWS edge locations

**An edge location is where users access AWS services

* As of November 2019, the global network of AWS edge locations comprises 210 points of presence (199 edge locations and 11 Regional edge caches) in 78 cities across 37 countries
* Specifically used with Amazon CloudFront, a global content delivery network (CDN), to delivery content to end users with reduced latency
* Regional edge caches are used for content with infrequent access 

![Edge Locations](https://media.amazonwebservices.com/blog/2017/cf_map_2017_locs_1.png "Edge Locations & Caches")
> AWS infrastructure features

Elastic and scalable:
* Elastic infrastructure, dynamic adaption of capacity
* Scalable infrastructure, adapts to accommodate growth

Fault-tolerant:
* Continues operating properly in the presence of a failure
* Built-in redundancy of components

High availability:
* High level of operational performance with minimized downtime

[AWS Infrastructure info](https://aws.amazon.com/about-aws/global-infrastructure/)

> AWS foundational services

![](https://image.slidesharecdn.com/hsbcandawsday-awsfoundations-170709164032/95/hsbc-and-aws-day-aws-foundations-7-638.jpg?cb=1499618785 "AWS foundational services")

## Section wrap-up:
### AWS Infrastructure Overview
* Examined the AWS Global Infrastructure to understand:
    * Data centers
    * Regions
    * Availability Zones
    * Edge locations
* Reviewed AWS service categories and their organization
## Module 2 wrap-up
### Module 2: Cloud Economics
* Explored the fundamentals of AWS pricing
* The AWS Simple Monthly Calculator can be used to provide accurate cost estimates
* The AWS TCO Calculator can be used to estimate cost savings
* Introduced the AWS Simple Monthly Calculator and the TCO Calculator
<!-- Week 7/Day 5/Core Services-Compute does not launch. Continuing on to Compute-Lambda for now-->
# Week 7/Day 5/Core Services-Compute-Lambda
## AWS Lambda and AWS Elastic Beanstalk
### Module 3, Section 1: AWS Core Services-Compute
#### Part 2
> What you will learn

**At the core of the lesson**

You will learn how to:
* Describe details of AWS Lambda and serverless computing
* Describe AWS Elastic Beanstalk
```
Key Terms:
* Amazon Elastic Compute Cloud
* AWS Lambda
* Elastic Load Balancer
* AWS Elastic Beanstalk
* Amazon Machine Image (IAM)
```
### Introduction to AWS Labmda
> What is AWS Lambda?

**AWS Lambda**
* Fully managed serverless compute
* Event-driven execution
* Sub-second metering
* Function execution limited to a maximum of 5 minutes
* Multiple languages supported

[AWS Lambda wiki](https://en.wikipedia.org/wiki/AWS_Lambda)
> Lambda key benefits
* No servers to manage
* Continuous scaling
* Sub-second metering
> Getting started with Lambda

**AWS Lambda**
* Upload your code to AWS Lambda
* Set up your code to trigger from other AWS services, Hypertext Transfer Protocol (HTTP) endpoints, or in-application activity
* Lambda runs your code only when triggered, by using only the compute resources needed
* Pay only for the compute time that you use
* Multiple languages are supported
> Lambda

**Use cases:**
* Run code in response to an event
* For example:
    * Changes to an Amazon Simple Storage Service (Amazon S3) bucket
    * Changes to an Amazon DynamoDB table
    * Respond to an HTTP request
    * Invoke code with application programming interface (API) calls
* Build serverless applicatoins triggered by Lambda functions
* Deploy with AWS CodePipeline and AWS CodeDeploy
> Lambda example
* Users capture an image for their property listing
* The mobile app uploads the new image to Amazon S3
* A Lambda function is triggered and calls Amazon Recognition
* Amazon Recognition retrieves the image from Amazon S3 and returns labels for the detected property
### Section wrap-up
#### AWS Lambda
* Fully managed serverless compute
* Event-driven execution
* Executes code only when needed and scales automatically
* Multiple languages supported
### Introduction to AWS Elastic Beanstalk
> What is Elastic Beanstalk?
* Platform as a service (PaaS)
* Quickly deploys, scales, and manages web applications
* Reduces management complexity
* Keeps controly in your hands
    * Choose your instance type
    * Choose your database
    * Set and adjust Amazon EC2 Auto Scaling
    * Update you application
    * Access server log files
    * Enable Secure HTTP (HTTPS) on a load balancer

**Supports a large range of platforms and languages:**
* Packer Builder
* Single container, multi-container, or pre-configured Docker
* Go
* Java SE
* Java with Tomcat
* .NET on Windows Server with IIS
* Node js
* PHP
* Pyton
* Ruby

No charge for Elastic Beanstalk, pay only for the underlying services used
> Elastic Beanstalk components

**Elastic Beanstalk provides all the services that you need:**

![Elastic Beanstalk Components](https://i.ytimg.com/vi/nRLZZefLDqU/maxresdefault.jpg)

### Section wrap-up
#### AWS Elastic Beanstalk
* Enhances developer productivity by simplifying the process of deploying your application
* Reduces management complexity
* There is no charge for Elastic Beanstalk. You pay only for the services you use
### Module wrap-up
#### In summary
* Reviewed AWS compute services including Amazon EC2, Lambda, and Elastic Beanstalk
* Discussed Amazon EC2 cost optimization

[AWS Elastic Beanstalk wiki](https://en.wikipedia.org/wiki/AWS_Elastic_Beanstalk)
# Week 7/Day 5-Networking
## Networking
### Practicing network skills

**In this lesson, you will learn how to network. You will also practice networking with your peers**
> What you will learn

**At the core of the lesson**

You will learn how to:
* Network with people you don't know
* Start conversations
* Join conversations
```
Key Word:
* Networking
```
> Tips for building a professional network

**Dont's**
* Don't dismiss another person
    * Take other people seriously, regardless of their status
* Don't be rude
    * Treat other people with respect
* Don't rush
    * Take time to listen to other people

**Do's**
* Try to have interesting conversations
* Ask who might be good people for you to meet
* Be generous with your time
> Conversation skills

**How to start or join conversations**

Tips and tricks for starting a conversation with one person
* Introduce yourself
* Ask a question about the event
* Ask a question about the other person
* Ask a question about an event-related topic

Tips and tricks for joining a group conversation
* Listen carefully
* Make eye contact
* Wait for a natural break and ask a question
* Show interest
> Company scenarios

**Practice your networking skills in the following scenarios**

Scenario 1:

Two former students visit your Amazon Web Services (AWS) class. During a short break, they both start a conversation with your instructor. The three of them stand in the hallway, and talk about a job interview that one of the former students had recently

You goal:
1. Participate in the conversation

Scenario 2:

Two former students visit your AWS class. During a short break, they both start a conversation with your instructor. The three of them stand in the hallway, and talk bout a job interview that one of the former students had recently.

You goals:
1. Participate in the conversation
3. Get the phone number or email address of one former student

Scenario 3:

You attend an IT event. You are seated and waiting for the next speaker, whose presentation starts in 15 minutes. Not many people are in the room. A few seats away, you see one other person, who is checking their mobile phone.

Your goal:
1. Start a conversation

Scenario 4:

You attend an IT event. You are seated and waiting for the next speaker, whose presentation starts in 15 minutes. Not many people are in the room. A few seats away, you see one other person, who is checking their mobile phone.

Your goals:
1. Start a conversation
5. Ask for tips about which sessions are interesting

Scenario 5:

Your company gives a workshop on cloud security. A senior cloud security engineer leads the workshop. As a new hire, this event is your chance to introduce yourself to them. After the workshop, you stay to talk to the senior engineer. Unfortunately, they don't have much time to stay after the workshop.

Your goal:
1. Start a conversation

Scenario 6:

Your company gives a workshop on cloud security. A senior cloud security engineer leads the workshop. As a new hire, this event is your chance to introduce yourself to them. After the workshop, you stay to talk to the senior engineer. Unfortunately, they don't have much time to stay after the workshop.

Your goals:
1. Start a conversation
2. Ask if you can schedule a 20-minute meeting with them

# Week 8/Day 1/Core Services-EBS
## Amazon Elastic Block Store (Amazon EBS)
### Module 3, Section 2: AWS Core Services-Storage
#### Part 1
> What you will learn

**At the core of the lesson**

You will learn how to:
* Compare and contrast the different types of storage services
* Explain the basic pricing that differentiates the storage solutions
```
Key Terms:
* Instance store
* Amazon Elastic Block Store (Amazon EBS)
```
### Introduction to storage services
> AWS services
* Amazon Virtual Private Cloud (Amazon VPC)
* Amazon Elastic Compute Cloud (Amazon EC2)
* Amazon Identity and Access Management (IAM)

|Database| |
|-|-|
|Amazon Relational Database Service (Amazon RDS)|Amazon DynamoDB|

|Storage| | | |
|-|-|-|-|
|Amazon EBS|Amazon S3|Amazon Elastic File System (Amazon EFS)|Amazon S3 Glacier
### Amazon Elastic Block Store (Amazon EBS)
> Storage

**Amazon EBS provides persistent block-storage volumes**
> Block-level versus object-level storage

**Block storage**

Change one block (piece of the file) that contains the character
* With block storage, you change only the block that contains the character

**Object storage**

Entire file must be updated
* With object storage, the entire file must be updated

**Difference**

This difference has a major impact on the throughput, latency, and cost of your storage solution

![File v Block v Object](https://image.slidesharecdn.com/ceph-as-sds-170508191216/95/ceph-as-software-define-storage-6-638.jpg?cb=1494270752 "File vs Block vs Object")
> Amazon EBS

**Amazon EBS offers block-level storage**

You can use Amazon EBS to create individual storage volumes and attach them to an Amazon EC2 instance
* Volumes are automatically replicated within its Availability Zone
* Can be backed up automatically to Amazon S3
* Uses:
    * Boot volumes and storage for Amazon EC2 instances
    * Data storage with a file system
    * Database hosts
    * Enterprise applications

| |Solid State Drives (SSD)| |
|-|-|-|
|Volume|General Purpose|Provisioned IOPS|
|Max volume size|16 TB|16 TB|
|Max IOPS/volume|10,000|32,000|
|Max throughput/volume|160 MB/s|500 MB/s|

| |Hard Disk Drives (HDD)| |
|-|-|-|
|Volume|Throughput-Optimized|Cold|
|Max volume size|16 TB|16 TB|
|Max IOPS/volume|500|250|
|Max throughput/volume|500 MB/s|250 MB/s|
> Amazon EBS volume types

**Use cases**

|Solid State Drives (SSD)| |Hard Disk Drives (HDD)| |
|-|-|-|-|
|General Purpose|Provisioned IOPS|Throughput-optimized|Cold|
|Recommended for most workloads|I/O-intensive workloads|Streaming workloads that require consistent, fast throughput at a low price|Throughput-oriented storage for large volumes of data that is infrequently accessed|
|System boot volumes|Relational Databases|Big data|Scenarios where the lowest storage cost is important|
|Virtual desktops|NoSQL Databases|Data warehouses|Cannot be a boot volume|
|Low-latency interactive apps| |Log processing| |
|Development and test environments| |Cannot be a boot volume|
> Amazon EBS

**Snapshots, encrytion, elasticity**

Snapshots:
* Point-in-time snapshots
* Re-create a new volume at any time

Encryption:
* Encrypted Amazon EBS volumes
* No additional cost

Elasticity:
Increase capacity
Change to different types
> Amazon EBS

**1. Volumes**
* Amazon EBS volumes persist independently from the instance
* All volume types are charged by the amount provisioned per month

**2. IOPS**
* General Purpose (SSD)
    * Charged by the amount your provision in GB per month until storage is released
* Magnetic
    * Charged by the number of requests to volume
* Provisioned IOPS (SSD)
    * Charged by the amount you provision in IOPS (by percentage of day or month that is used)

**Snapshots and data transfer**

**3. Snapshots:**
* Added cost of Amazon EBS snapshots to Amazon S3 is per GB-month of data stored

**4. Data transfer:**
* Inbound data transfer is free
* Outbound data tansfer changes are tiered
### Amazon EBS demonstration
### Section wrap-up
#### Storage-Amazon EBS
* Persistent and customizable block storage for Amazon EC2
* HDD and SSD types
* Replicated in the same Availability Zone
* Easy and transparent encryption
* Elstic volumes
* Back up by using snapshots
# Week 8/Day 1/Core Services-Storage-S3
## Amazon Simple Storage Service (Amazon S3)
### Module 3, Section 2: AWS Core Services-Storage
#### Part 2
> What you will learn

**At the core of the lesson**
You will learn how to:
* Explore the fundamentals of Amazon Simple Storage Service (Amazon S3)
* Compare and contrast Amazon S3 to Amazon EBS
* Explain the basic pricing that differentiates the storage solutions
```
Key Terms:
* Amazon Simple Storage Service (Amazon S3)
* Amazon Elastic Block Store (Amazon EBS)
```
### Amazon Simple Storage Service (Amazon S3)
> Amazon S3

**Amazon S3 offers:**

Managed cloud storage solution that is designed to scale seamlessly and provide 11 9s of durability
* Store as many objects as you want
* Bucket names must be unique across all existing bucket names in Amazon S3
* Amazon S3 cannot be used as a bootable drive
* Data is stored redundantly
> Amazon S3 storage classes

**Amazon S3 offers four classes of object-level storage:**
* Amazon S3 Standard
* Amazon S3 Standard-IA
* Amazon S3 One Zone-IA
* Amazon S3 Glacier

**To upload your data (photos, videos, documents)**
1. Create a bucket in one of the AWS Regions
7. Upload any number of objects to the bucket
> Access the data anywhere

**Three ways to access the data anywhere**
1. AWS Management Console
2. AWS CLI
3. AWS SDKs
> Amazon S3 and objects

**An object lifecycle**

Bucket:

https://**s3-ap-northest-1**.amazonaws.com/**[bucket name]**/
* Region code = s3-ap-northeast-1
* Bucket name = [bucekt name]

Object:

https://s3-ap-northeast-1.amazonaws.com/[bucket name]/**[Preview2.mp4]**
* Key = [Preview2.mp4]
> Redundancy in Amazon S3

[Amazon S3 redundancy](https://www.eweek.com/storage/amazon-s3-launches-cheaper-level-of-online-backup#:~:text=Amazon%20S3%20Reduced%20Redundancy%20Storage%20is%20designed%20to,in%20the%20S3%20data%20center-than%20Amazon.com%27s%20standard%20storage.)
> Seamless scaling

**Amazon S3 designed for seamless scaling**
* Bucket and object can be backed up across all Availability Zones per Region
> Amazon S3

**Common use cases**
* Storing application assets
* Static web hosting
* Backup and disaster recovery (DR)
* Staging area for big data
* Many more...
> Amazon S3: Storage pricing

**Consider the following:**
1. Types of storage classes:
* Standard Storage
    * 11 9s of durability
    * Four 9s of availability
* Standard-Infrequent Access (SIA)
    * 11 9s of durability
    * Three 9s of availability
2. Amount of storage:
* The number and size of objects
* Type of storage
> Amazon S3 pricing

**Pay only for what you use:**
* GBs per month
* Transfer OUT to other regions
* PUT, COPY, POST, LIST, and GET requests

**You do NOT have to pay for:**
* Transfers IN to Amazon S3
* Transfers OUT from Amazon S3 to Amazon CloudFront or Amazon EC2 in the same Region
### Section wrap-up
#### Amazon S3
* Amazon S3 is a fully managed cloud storage service
* Store a virtually unlimited number of objects
* Pay for only what you use
* Access at any time, from anywhere
* Amazon S3 offers rich security controls)

[Amazon S3 link](https://docs.aws.amazon.com/AmazonS3/latest/dev/Welcome.html)
# Week 8/Day 1/Core Services-Storage-Glacier
## Amazon Simple Storage Service Glacier
### Module 3, Section 2: AWS Core Services-Storage
#### Part 4
> What you will learn

**At the core of the lesson

You will learn to:
* Explore Amazon Simple Storage Service Glacier
* Compare and contrast Amazon S3 Glacier to Amazon Simple Storage Service (Amazon S3)
```
Key Terms:
* Amazon Simple Storage Service Center
* Amazon S3 Glacier Archive
* Amazon S3 Glacier Vault
* Amazon S3 Glacier Vault Access Policy
```
### Amazon S3 Glacier

**Designed for security, durability, and low cost**
* Amazon S3 Glacier is a data archiving service designed for security, durabilit, and an extremely low cost
* Designed for **11 9s** of durability for objects
* Supports Secure Sockets Layer (SSL)/Transport Layer Security (TLS) **encryption of data in transit and at rest**
* The **Vault Lock** feature **enforces** compliance via a **lockable policy**
* Extremely low-cost design is ideal for long-term archiving
    * Provides three options for access to archives (**Expedited, Standard,** and **Bulk**) from a few minutes to several hours
> Using Amazon S3 Glacier
* RESTful web services
* Java or .NET software development kits (SDKs)
> Amazon S3 with lifecycle policies

**Policies allow you to delete or move objects based on age**
* Amazon S3 Standard
    * 30 Days to delete
* Amazon S3 Standard-Infrequent Access
    * 60 Days to delete
* Amazon Glacier
    * 365 Days to delete
> Storage comparison

| |Amazon S3|Amazon S3 Glacier|
|-|-|-|
|Data Volume|No limit|No limit|
|Average Latency|ms|Minutes or hours|
|Item Size|5 TB max|40 TB mxx|
|Cost/GB Per Month|centscents|cents|
|Billed Requests|PUT,COPY,POST,LIST, and GET|UPLOAD and retrieval|
|Retrieval Pricing|cents Per request|centscents Per request and per GB|
> Server-side encryption

![Server-side encryption](https://image.slidesharecdn.com/02encryptiontalkv3-150707140155-lva1-app6891/95/protecting-your-data-with-aws-kms-and-aws-cloudhsm-10-638.jpg?cb=1436277834 "Server-side encryption")
> Security with Amazon S3 Glacier
* Control access with AWS Identity and Access Management (IAM)
* Amazon S3 Glacier encrypts your data with AES-256
* Amazon S3 Glacier manages your keys for you
> How Amazon S3 Glacier stores data
* Amazon S3 Glacier stores data in an archive
    * A basic unit of data in Amazon Glacier (document, video, image, etc)
* A vault is a collection of archives

**API application > Vault > Archive**
> Interact with Amazon S3 Glacier

**Interact with Amazon S3 Glacier using:**

Amazon S3 lifecycle policies
* Archived files are accessed via the Amazon S3 console or Amazon S3 API

Amazon S3 Glacier API
* Directly add files
* To retrieve files:
    1. Initiate a job request
    2. Select the archive retrieval operation
    5. Optionally specify a date range or a byte range filter
    4. Poll for job completion, or receive SNS notification
    > Archive retrieval options

    | |Archive retrieval options| |
    |-|-|-|
    |Expedited 1-5 minutes|Standard 3-5 hours|Bulk 5-12 hours|

### Section wrap-up
#### Amazon S3 Glacier
* Amazon S3 Glacier is a data archiving service designed for security, durability, and an extremely low cost
* Amazon S3 Glacier pricing is Region-based
* Extremely low-cost design is ideal for long-term archiving
* The service is designed for 11 9s of durability for objects
### Unit wrap-up
#### Module 3, Section 2:
##### AWS Core Services-Storage
* Reviewed the characteristics of Amazon Elastic Block Store (Amazon EBS), Amazon S3, Amazon Elastic File Systme (Amazon EFS), and Amazon S3 Glacier
* Identified appropriate uses for each storage option
* Briefly looked at the pricing differences for various storage options
# Week 8/Day 2/Core Services-VPC-Virtual Private Cloud
## Amazon Virtual Private cloud (Amazon VPC)
### Module 3, Section 3: AWS Core Services-Virtual Private Cloud (VPC)
#### Part 1
> What you will learn

**At the core of the lesson**

You will learn how to:
* Describe key concepts related to Amazon Virtual Private Cloud (Amazon VPC) and security groups
* Explain virtual networking in the cloud with Amazon VPC
* Describe how to create virtual firewalls with security groups
```
Key Terms:
* Amazon Virtual Private Cloud (Amazon VPC)
```
![Amazon VPC](https://i0.wp.com/jayendrapatil.com/wp-content/uploads/2016/03/AWS-VPC-Components.png "Amazon VPC")
> Network environment in the cloud

**Amazon VPC**
* Use to create a VPC, or a private virtual network in the AWS Cloud
* VPCs are logically isolated from other virtual networks
* Many AWS resources such as Amazon Elastic Compute Cloud (Amazon EC2) instances, are launched into VPCs

**Control of network configuration**
* Allows complete control of network configuration, including:
    * Internet Protocol (IP) address ranges
    * Subnet creation
    * Route table creation
    * Network gateways
    * Security settings
> Amazon VPC

**Deployment**
* Offers several layers of security controls:
    * Ability to allow and deny specific internet and internal traffic
* Other AWS services deploy into Amazon VPC
    * Service inherits security built into network

**Integration**

| |Amazon VPC| |
|-|-|-|
|AWS OpsWorks|Amazon DynamoDB|AWS Elastic Beanstalk|
|AWS Data Pipeline|Amazon EC2 Auto Scaling|Amazon RDS|
|Amazon DynamoDB|Elastic Load Balancing|Amazon Elastic File System|
|Amazon ElastiCache|Amazon Simple Storage Service|Amazon WorkSpaces|
|Amazon EMR| | |

**Features**
* Builds on the high availability of AWS Regions and Availability Zones
    * Each VPC lives in a single Region
    * Multiple VPCs per account
* Subnets
    * Used to divide VPC
    * Enables Amazon VPC to span multiple Availability Zones

**Classless Inter-Domain Routing (CIDR)**
* Each Amazon VPC must specify the IPv4 address range by choosing a Classless Inter-Domain Routing (CIDR) block, like 10.0.0.0/16
> Amazon VPC components

**Components**
1. Subnets-Segment of a VPC's IP address range where you can launch AWS services
    * Subnets in an Availability Zone cannot span Availability Zones > one subnet equal one Availability Zone
    * Can be classified as public, private, or VPN only
    * Default VPCs contain one public subnet in every Availability Zone within the Region with a netmask of /20
2. Route tables: Used to control traffic going out of the subnets
3. Dynamic Host Configuration Protocol (DHCP) option sets: Provides a standard for passing configuration information to hosts on a TCP/IP network
4. Security groups: A virtual, stateful firewall
5. Network access control lists (network ACLs): Control access to subnets; and stateless
6. Internet gateway: Allows access to the internet from the VPC
7. Elastic IP address: Static, public IP address that can be pulled from a pool for use on a temporary basis
8. Elastic network interface: Virtual network interface
9. Endpoints: Direct connection to another AWS service
10. Peering: Allows two VPCs to communicate
11. Network Address Translation (NAT) instances and NAT Gateways: Accepts, translates, and forward traffic within a private subnet
![Amazon VPC Components](https://docs.aws.amazon.com/vpc/latest/userguide/images/default-vpc-diagram.png "VPC Components")
> Amazon VPC Connections

**Connections**

|VPN Connectivity Options|Description|
|-|-|
|AWS Hardware VPN|You can create an IPsec hardware VPN connection between your VPC and your remote network|
|AWS Direct Connect|AWS Direct Connect provides a dedicated private connection from a remote network to your VPC|
|AWS VPN Cloud-Hub|You can create multiple AWS hardware VPN connections via your VPC to enable communications between various remote networks|
|Software VPN|You can create a VPN connection to your remote network by using an Amazon EC2 instance in your VPC that's running a software VPN appliance
> Design a VPC

**Part 01:**
* First, you create the VPC and give it a name, Test VPC
* Give your VPC any IP addresses in the following CIDR block: 10.0.0.0/16

**Part 02:**
* Next, you create a subnet named Subnet A1 and assign an IP address space that contains 256 IP addresses

**Part 03:**
* Finally, you create another subnet called Subnet B1 and assign an IP address space to it

**Part 04:**
* To accomplish this, add an internet gateway called Test IGW
* Subnet A1 now becomes a public subnet where non-local traffic is routed through the internet gateway
* Subnet B1 will be your private subnet that is isolated from the internet
### Section wrap-up

**Amazon VPC**
* You learned key concepts related to Amazon Virtual Private Cloud (Amazon VPC) and security groups
* You learned about virtual networking in the cloud with Amazon VPC
* You walked through a process that showed how to create virtual firewalls with security groups
# Core Services-VPC-CloudFront
## Module 3, Section 3: AWS Core Services
### Part 3
> What you will learn

**At the core of the lesson**

You'll learn:
* Global, Growing Content Delivery Network
* Secure Content at the Edge Location
* Programmable Content Delivery Network (CDN)
```
Key Term:
* Amazon CloudFront-is a web service for content delivery or Content Delivery Network (CDN)
```
> Amazon CloudFront

**What is Amazon CloudFront**
* Amazon CloudFront is a web service that speeds up distribution of your static and dynamic web content, such as .html, .css, .js, and image files, to your users
* CloudFront delivers your content through a worldwide network of data centers called edge locations
> AWS Global Infrastructure

**Edge Locations and Regional Edge Caches**

![AWSGlobal](https://media.amazonwebservices.com/blog/2017/cf_map_2017_locs_1.png "Edge Locations & Regional Edge Caches")
> Amazon CloudFront

**Key Features**
* Global, Growing Content Delivery Network
* Secure Content at the Edge Location
* Programmable Content Delivery Network (CDN)
* High Performance:
    * Low latency
    * High data transfer speeds
* Cost Effective:
    * Pay for data transfer and requests to deliver content to customers
    * No upfront or minimum commitments
* Deep Integration with other AWS services

**Cost Estimation**

Traffic Distribution:
* Pricing varies across geographic regions
* Based on the edge location

Requests:
* Number/type of requests
* Geographic region

Data Transfer Out:
* The amount of data transferred out of Amazon CloudFront edge locations
> Section Wrap-up

**AWS CloudFront**
* Global, Growing Content Delivery Network
* Secure Content at the Edge Location
* Programmable Content Delivery Network (CDN)
> Module Review

**Virtual Private Cloud (VPC)
* Explored the features of the Amazon Virtual Private Cloud (Amazon VPC)
* Reviewed Amazon VPC Security Groups
* Discussed Amazon CloudFront
# Core Services-VPC-Security Groups
## Module 3, Section 3: AWS Core Services-Virtual Private Cloud (VPC)
### Part 2
> What you will learn

**At the core of the lesson**

You will learn how to:
* Explain security groups and how they help secure your data
```
Key Terms:
* Security group
* Network access control lists (network ACLs)
* Key pairs
```
> Aws security groups

**Key features**
* Security groups act like a built-in firewall for your virtual servers
* Security group rules determine who has access to instances
* Security groups are stateful
> Amazon VPC and security groups
* Security group: Acts as a firewall for Amazon Elastic Compute Cloud (Amazon EC2) instances
* Network access control lists (network ACLs): Acts as a firewall for associated subnets
* Key pairs: Cryptography used to encrypt and decrypt login information

![Amazon VPC & Security Groups](https://image.slidesharecdn.com/20161213-ec2mastermorning-slideshare-161213075647/95/amazon-ec2-vpc-hol-56-638.jpg?cb=1481616046 "Amazon VPC & Security Groups")
> Multi-tier security groups

**AWS multi-tier security group**
* This example is of a classic AWS multi-tier security group
* In this architecture, notice that multiple different security group rules were created to accommodate this multi-tiered web architecture

![Architecture](https://image.slidesharecdn.com/hsbcandawsday-securityidentityandaccessmanagement-170709164101/95/hsbc-and-aws-day-security-identity-and-access-management-8-638.jpg?cb=1499618791 "Multi-tier Architecture")
> Section wrap-up

**AWS Security Groups**
* Security groups act like a built-in firewall for your virtual servers
* Security group rules determine who has access to instances
* Security groups are stateful
# Core Services-Database Overview
## Amazon Database Services Overview
### Module 6: Computing (Database)
#### Part 0
> What you will learn

**At the core of the lesson**

You will learn how to:
* Explain some of the challenges of relational databases
* Explore the available database options offered by AWS
* Examine the difference between unmanaged and managed database solutions
* Describe the differences between a structured query language (SQL) database and a NoSQL database
* Explain how to choose an AWS database that meets the needs of different business scenarios
```
Key Terms:
* SQL
* NoSQL
* Database instance
* Relational database
* Managed services
* Unmanaged services
```
> Challenges of relational databases
* Server maintenance and energy footprint
* Software installation and patches
* Database backups and high availability
* Limits on scalability
* Data security
* Operating system (OS) installation and patches
> AWS database options

| |SQL|NoSQL|
|-|-|-|
|Transactional databases|Amazon RDS|Amazon DynamoDB|
|Data analytics or relationships|Amazon Redshift|Amazon Neptun|
|In-memory data store and cache| |Amazon Elasticache|
> SQL and noSQL databases

| |SQL|NoSQL|
|-|-|-|-|
|Data Storage|Rows and Columns|Key-value|
|Schemas|Fixed|Dynamic|
|Querying|Uses SQL|Focuses on collection of documents|
|Scalability|Vertical|Horizontal|

|SQL| | | |
|-|-|-|-|
|ISBN|Title|Author|Format|
|9182932465265|Cloud Computing Concepts|Jackson, Mateo|Paperback|
|3142536475869|The Database Guru|Garcia, Maria|Ebook|
```
NoSQL
{
        "ISBN": 9182932465265,
        "Title": "Cloud Computing Concepts",
        "Author": "Jackson, Mateo",
        "Format": "Paperback"
}
```
### Managed Services
> Unmanaged vs. Managed Services

**Unmanaged:**
* Unmanaged services are typically provisioned by you. Scaling, fault tolerance, and availability are managed by you

**Managed:**
* Managed services require the user to configure them. Scaling, fault tolerance, and availability are typically built in to the service
> Deep Dive on Managed Services

**Managed Services On-Premises | Managed Services on AWS**

|Database On-premises|Database in Amazon EC2|Amazon RDS or Amazon Aurora|
|-|-|-|
|App optimization| |AWS Cloud|
|Scaling| |Scaling|
|High availability| |High availability|
|Database backups| |Database backups|
|DBs/w patches| |DBs/w patches|
|DBs/w installs| |DBs/w installs|
|OS patches|AWS Cloud|OS patches|
|OS installation|OS installation|OS installations|
|Server Maintenance|Server Maintenance|Server Maintenance|
|Rack and Sack|Rack and Sack|Rack and Sack|
|Power, HAVAC, net|Power, HAVAC, net|Power, HAVAC, net|
> Managed Services Responsibilities

**You Manage:**
* Applicatoin optimization

**AWS Manages:**
* OS installation and patches
* Database software install and patches
* Database backups
* High availability
* Scaling
* Power and rack & stack
* Server maintenance
> Choosing a database service

![AWS Database Services](https://image.slidesharecdn.com/choosingtherightdatabaseservice-160502082116/95/choosing-the-right-database-service-aws-db-day-10-638.jpg?cb=1462177360 "AWS Database Services")
> AWS database recommendations

|If You Need|Product Type|Consider Using|
|-|-|-|
|Managed relational database hat is launched with a choice of six popular database engines|Relational database|Amazon RDS|
|MySQL-and PostgreSQL-compatible relational database built for the cloud|Relational database|Amazon Aurora|
|Fully managed NoSQL database|NoSQL database|Amazon DynamoDB|
|Managed graph database|NoSQL database|Amazon Neptune|
|Managed Redis key-value store|NoSQL database|Amazon ElastiCache|
|Columnar storage SQL data warehouse|Relational database|Amazon Redshift|
> AWS database usage scenarios

|Database Name|Best Used For|
|-|-|
|Amazon RDS Amazon Aurora|*Transactional applications like ERP, CRM, and ecommerce to log transactions and store structured data *Amazon Aurora differentiator: Open source, high performance, and low cost|
|Amazon Redshift|*Analytic applications for operational reporting and querying terabyte-to exabyte-scale data|
|Amazon ElastiCache|*Real time application use cases that require submillisecond latency, like gaming leaderboards, chat or messaging, streaming, and IoT|
|Amazon Neptune|*Applications with use cases that require the navigation of highly connected data like social news feeds, recommendations, and fraud detection|
|Amazon DynamoDB|*Internet-scale applications like hospitality, dating, and ridesharing that need to serve content and store structured and unstructured data|
### Section wrap-up

**Amazon Database Services Overviewd**
* Managed databases simplify and automate many operational and management tasks
* The choice of AWS managed database to use is based on application requirements
* Each database offering has a primary use case--make sure you are familiar with it
* Unsupported database engines or database versions can be hosted on Amazon EC2
# Week 8/Day 2/Core Services-Database-RDS
## Amazon Relational Database Service (RDS)
### Module 3, Section 4: AWS Core Services-Database
#### Part 1
> What you will learn

**At the core of the lesson**

You'll learn to:
* Dive deep into one type of data services, Amazon Relational Database Service (RDS)
```
Key Terms:
* Amazon Relational Database Service (Amazon RDS)
* Database instance
```
> Amazon RDS
* Managed service that sets up and operates a relational database in the cloud

Users > Application Servers <> Amazon RDS
> Amazon RDS backup

**Amazon RDS backup options include:**

|Automatic:|Creates automated backups (full daily snapshot and transaction logs) of DB instance during the backup window|
|-|-|
|Manual:|Creates a storage volume snapshot of your DB instance|
> Amazon RDS DB Instances

Amazon RDS supports six database types:

1. MySQL
2. Amazon Aurora
3. Microsoft Sequel Server
4. PostgreSQL
5. MariaDB
6. Oracle
<!-- Week 8/Day 2/Core Services/Database-RDS/pg 4/slide 7 -->