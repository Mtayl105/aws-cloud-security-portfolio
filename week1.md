## Week 1: AWS Basics

Module 1: Introduction to Amazon Web Services
Cloud Computing Overview

Cloud computing provides on-demand access to computing resources over the internet with no upfront hardware investment. AWS manages the physical infrastructure while customers consume services as needed.

Cloud Service Models

Infrastructure as a Service (IaaS): Customer controls OS, applications, and configurations (e.g., EC2, VPC)

Platform as a Service (PaaS): AWS manages infrastructure and OS while customers deploy applications (e.g., Elastic Beanstalk)

Software as a Service (SaaS): Fully managed applications delivered over the internet (e.g., Amazon WorkSpaces)

Key Benefits of AWS

Elastic scalability based on demand

High availability through distributed infrastructure

Global reach with minimal latency

Reduced operational and maintenance overhead

Shared Responsibility Model (High-Level)

AWS Responsibilities: Physical data centers, networking, hardware, and underlying cloud infrastructure

Customer Responsibilities: Identity and access management (IAM), data protection, operating system patching, and service configuration

Module 2: Compute in the Cloud (EC2 – Conceptual)
Amazon EC2 Overview

Amazon Elastic Compute Cloud (EC2) provides resizable virtual servers that allow customers to run applications in the cloud. EC2 is the core compute service within AWS and a foundational component of IaaS.

Why EC2 Is Used

Host applications and services

Replace or extend on-premises servers

Scale compute resources up or down based on workload

Core EC2 Concepts (Introductory)

Instance: A virtual server running in AWS

Instance Types: Predefined CPU, memory, and performance configurations

Amazon Machine Image (AMI): A template used to launch EC2 instances

Note: EC2 configuration and deployment will be explored hands-on in later weeks.

Module 3: Global Infrastructure and Reliability
AWS Regions

Regions are physical geographic locations that contain multiple Availability Zones. Resources are deployed within regions to meet latency, compliance, and availability requirements.

Availability Zones (AZs)

Independent, isolated data centers within a region

Designed to prevent single points of failure

Enable high availability architectures

Edge Locations

Used by Amazon CloudFront for content delivery

Reduce latency by caching content closer to users

Reliability Principles

High Availability: Systems remain operational during failures

Fault Tolerance: Architectures are designed to withstand component failures

Week 1 Key Takeaways

AWS provides scalable, on-demand infrastructure services

EC2 is the foundational compute service in AWS

Global infrastructure enables reliability, performance, and fault tolerance

Security responsibilities are shared between AWS and the customer
