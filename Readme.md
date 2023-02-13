# AWS courses and Exam preparations

## Learning material

### Core

* [A Cloud Guru AWS **Vision notes**](https://acloudguru.visme.co/view/mxz10wwn-s01-l00-table-of-contents)
* [AWS Cloud Practitioner (CLF-C01) Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)
* [Course presentation](https://acloudguru-content-attachment-production.s3-accelerate.amazonaws.com/1676052837832-1036%20PDF%20Export%202_10_22.pdf)
* [Overview of Amazon
  Web Services **AWS Whitepaper**](https://docs.aws.amazon.com/pdfs/whitepapers/latest/aws-overview/aws-overview.pdf)

### General Basic

* [AWS Terminology Cheat Sheet](https://acloudguru.com/blog/engineering/your-aws-terminology-cheat-sheet)

## Basics

#### Benefits of cloud computing

High availability, elasticity, agility, and durability (data protection).

#### Costs control

* Capital Expenditures (CapEx) - upfront purchases toward fixed assets (equipment, property, software).
* Operating Expenses (OpEx) - funds used to run day-to-day operations (R&D, salaries, rent, marketing)

### Main services and their purpose

* EC2 - Elastic compute cloud (virtual machine as a service)
* SQS - Simple queue service
* RDS - Database as a service
* Route 53 - DNS service
* Dynamo DB - NoSQL database
* Code Pipeline - DevOps orchestration tool
* VPC - Virtual Private cloud where all services exist
* Cloud Front - Content delivery service
* Redshift - Data lake service
* Athena - Query petabytes of data

AWS S3, SQS and EC2 were released in 2006

## Application Lens in AWS

The [AWS Well-Architected Framework](http://aws.amazon.com/architecture/well-architected/) helps you understand the pros
and cons of the decisions you make when building
systems in the cloud. The six pillars of the Framework allow you to learn architectural best practices for designing and
operating reliable, secure, efficient, cost-effective, and sustainable systems. Using
the [AWS Well-Architected Tool](http://aws.amazon.com/well-architected-tool/),
available at no charge in the AWS Management Console, you can review your workloads against these best practices by
answering a set of questions for each pillar.

AWS Lenses and link to AWS 80-page documents for each:  
(_There are also PDFs available on AWS website_)

* In
  the [Serverless Application Lens](https://docs.aws.amazon.com/wellarchitected/latest/serverless-applications-lens/welcome.html),
  we focus on **best practices for architecting your serverless applications** on AWS.

* In
  the [Container Build Lens](https://docs.aws.amazon.com/wellarchitected/latest/container-build-lens/container-build-lens.html),
  we provide **cloud-agnostic best practices for building and managing containers and
  container images**. In addition, _implementation guidance and examples are provided specific to the AWS Cloud_.

* In
  the [Machine Learning Lens](https://docs.aws.amazon.com/wellarchitected/latest/machine-learning-lens/machine-learning-lens.html),
  we focus on how to **design, deploy, and architect your machine learning workloads** in the
  AWS Cloud.

* In the [Data Analytics Lens](https://docs.aws.amazon.com/wellarchitected/latest/analytics-lens/analytics-lens.html),
  we describe a **collection of customer-proven best practices for designing well-architected
  analytics workloads**.

* In
  the [Hybrid Networking Lens](https://docs.aws.amazon.com/wellarchitected/latest/hybrid-networking-lens/hybrid-networking-lens.html),
  we focus on how to **design, deploy, and architect hybrid networking for workloads** in
  the
  AWS Cloud.

* In the [IoT Lens](https://docs.aws.amazon.com/wellarchitected/latest/iot-lens/welcome.html)
  and [IoT Lens Checklist](https://docs.aws.amazon.com/wellarchitected/latest/iot-lens-checklist/overview.html), we
  focus on **best practices for architecting your IoT applications** on AWS.

* In the [SAP Lens](https://docs.aws.amazon.com/wellarchitected/latest/sap-lens/sap-lens.html), we describe a collection
  of customer-proven **design principles and best practices for ensuring SAP
  workloads** on AWS are well-architected.

* In
  the [Games Industry Lens](https://docs.aws.amazon.com/wellarchitected/latest/games-industry-lens/games-industry-lens.html),
  we focus on **designing, architecting, and deploying your games workloads** on AWS.

* In
  the [Streaming Media Lens](https://docs.aws.amazon.com/wellarchitected/latest/streaming-media-lens/streaming-media-lens.html),
  we focus on the **best practices for architecting and improving your streaming media
  workloads** on AWS.

* In
  the [Healthcare Industry Lens](https://docs.aws.amazon.com/wellarchitected/latest/healthcare-industry-lens/healthcare-industry-lens.html),
  we focus on how to **design, deploy, and manage your healthcare workloads**.

* In
  the [Financial Services Industry Lens](https://docs.aws.amazon.com/wellarchitected/latest/financial-services-industry-lens/welcome.html),
  we focus on **best practices for architecting your Financial Services
  Industry
  workloads** on AWS.

* In the [HPC Lens](https://docs.aws.amazon.com/wellarchitected/latest/high-performance-computing-lens/welcome.html), we
  focus on best practices for architecting your **High Performance Computing (HPC) workloads** on
  AWS.

* In the [SaaS Lens](https://docs.aws.amazon.com/wellarchitected/latest/saas-lens/saas-lens.html), we focus on best
  practices for **architecting your software as a service (SaaS) workloads** on AWS.

### Distribution of services

* Compute: Running applications and processing things with compute power
* Storage:
* Database:
* Migration and transfers: Services to move to AWS from traditional server room
* Networking and Content Delivery:
* Management and Governance: Manage AWS and on-premise infrastructure
* Media Services: Services related to media streaming, processing and transcoding (covering audio and media)
* Machine Learning: ML Services
* Analytics: Services to deal with loads of data
* Security: Authentication, password managers, network breaches detection, firewalls
* Application Integration: Help AWS services work together (Step Functions, SQS)
* Cost Management: Cost explore and budgets
* Customer Engagements
* End User Computing: Virtual remote desktop to work on (WorkSpaces)
* Internet of Things:
* Containers:

##

### Regions and availability zone

**Availability zone**: Each region is partitioned into zones.   
Each zone has its own datacenter and own security, connected via high speed network