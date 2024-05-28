Welcome to my GitHub portfolio!

I'm a DevOps Engineer with extensive experience in designing, implementing, and maintaining cloud infrastructure and CI/CD pipelines. Below you will find descriptions of some of the key projects I've worked on, along with the technologies and tools used.

Projects :

Project 1: Comprehensive DevOps Automation and Deployment (Capstone DevOps Project - 1)

Description:

This project aimed to streamline the deployment process of the production application by integrating several DevOps practices and tools. The key objectives and tasks included:

Dockerization of the Production Application: Containerized the existing application to ensure consistency across various environments and to simplify the deployment process.

Kubernetes Deployment: Deployed the Dockerized application on Kubernetes, leveraging its orchestration capabilities to manage and scale the application efficiently.

Continuous Integration/Continuous Deployment (CI/CD) Pipeline with Jenkins: Set up a Jenkins freestyle pipeline that automatically deploys the latest version of the application whenever changes are detected in the GitHub repository.

Incorporated testing steps to verify the application's functionality on port 85 before proceeding with the deployment.

NodePort Service for Application Accessibility: Created a Jenkins pipeline to deploy the application on Kubernetes using a custom Docker image stored on Dockerhub.

Ensured the application is exposed as a NodePort Service for external accessibility.

Infrastructure Automation with Terraform: Automated the creation of necessary infrastructure resources using Terraform, ensuring a consistent and reproducible environment setup.

Configuration Management with Ansible: Used Ansible to install Java on the required machines, streamlining the configuration management process and ensuring all dependencies are met.

This project significantly improved the deployment process's efficiency, reliability, and scalability, ultimately enhancing the overall productivity.

Technologies: Docker, Kubernetes, Jenkins, Terraform, Ansible, GitHub, NodePort and DockerHub.

Project 2: Robust and Secure Software Architecture Deployment (DevOps Capstone Project - 2)

Description:

As a Solutions Architect, I led a project to revamp the company's software architecture to enhance robustness and security. Key tasks included:

Regional Deployment: Deployed software in a US AWS region to meet regional requirements.

Private Instances: Ensured instances had no public IPs and no direct internet access for enhanced security.

Scalable Storage Solution: Implemented scalable storage to accommodate unpredictable space requirements.

Shared Storage: Set up real-time shared storage among servers.

Auto Scaling: Configured automatic scaling for CPU usage above 80%.

Managed Database: Migrated the database to a managed AWS service for improved fault tolerance.

Automated Deployment with CodeDeploy: Used CodeDeploy for automatic updates to the Auto Scaling Group.

Kubernetes Integration: Created a container from the GitHub Dockerfile and deployed it to an AWS Kubernetes cluster using a NodePort service for accessibility.

This project provided a secure, scalable, and fault-tolerant architecture to meet the company's evolving needs.

Technologies: AWS (EC2, S3, RDS), Auto Scaling, CodeDeploy, Kubernetes, Docker, GitHub and NodePort.

Project 3: Azure Multi-Region Deployment for Website Architecture (Azure Capstone Project)

Description: As an Azure DevOps Engineer, I implemented a robust and distributed website architecture across two regions. The project involved setting up multiple web pages, configuring an Application Gateway, and managing Azure Storage and VMs. Key tasks included:

Web Page Deployment: Home Page (VM2): Default landing page.

Upload Page (VM1): Interface for file uploads to Azure Blob Storage.

Error Page: Custom 403 and 502 error handling.

Application Gateway Configuration: Route traffic to home page (example.com) and upload page (example.com/upload). Point error pages to a static error.html hosted in Azure Containers.

Multi-Region Deployment: Deployed resources in Central US and West US for optimal traffic distribution using Azure Traffic Manager.

Azure Storage Setup: Hosted error.html as a static website for error handling. Created an "upload" container for file uploads.

VM and VNet Configuration: Deployed VMs inside VNets in both regions.

Cloned the GitHub repository to all VMs and executed deployment scripts:

VM1: Deployed the upload page.

VM2: Deployed the home page.

Edited config.py on VM1 to configure storage account details.

VNet Peering: Connected VNets in both regions using VNet-VNet peering for seamless integration.

This architecture ensured high availability, optimal traffic distribution, and efficient error handling for the company's website.

Technologies: Azure (VMs, VNets, Blob Storage, Application Gateway, Traffic Manager, VNet Peering), GitHub and Python

DevOps Tools Tasks and Case Studies :

I have also uploaded various tasks and case studies to demonstrate my expertise in different DevOps tools and practices :

Ansible: Configuration management and automation tasks. Case studies on efficient software deployment and configuration.

Git: Version control tasks. Case studies on collaborative workflows and branch management.

Kubernetes: Deployment and orchestration tasks. Case studies on scaling and managing containerized applications.

Jenkins: CI/CD pipeline tasks. Case studies on automating build, test, and deployment processes.

Terraform: Infrastructure as Code tasks. Case studies on automating and managing cloud infrastructure.

AWS Tasks and Case Studies :

I have uploaded detailed documentation for various AWS tasks, showcasing my expertise in managing and optimizing AWS services. Below is a list of the tasks with a brief description of each.

Auto Scaling Groups

Detailed steps on creating and configuring Auto Scaling Groups.
Explanation of scaling policies and triggers.

Auto Scaling

In-depth guide on setting up Auto Scaling for applications.
Best practices for ensuring high availability and cost efficiency.

EC2

Documentation on launching and managing EC2 instances.
Various use cases including security, monitoring, and optimization.

ELB (Elastic Load Balancing)

Guide on setting up and configuring Elastic Load Balancers.
Strategies for improving application reliability and performance.

Migration (DMS)

Comprehensive steps for migrating databases using AWS Database Migration Service.
Tips and best practices for a smooth migration process.

RDS (Relational Database Service)

Instructions on setting up and managing RDS instances.
Focus on backup, recovery, and performance tuning.

Route 53

Detailed guide on configuring DNS with Route 53.
Use cases including traffic management and domain registration.

S3 (Simple Storage Service)

Steps for setting up and managing S3 buckets.
Tips for optimizing storage costs and securing data.

VPC (Virtual Private Cloud)

Guide on creating and configuring VPCs.
Best practices for network segmentation and security.

Azure Tasks and Case Studies :

I have also uploaded detailed documentation for various Azure Technology tasks, showcasing my expertise in managing and optimizing Azure services as well. Below is a list of the tasks with a brief description of each.

Azure ARM: Tasks and case studies on Azure Resource Manager.

Storage: Management and optimization of Azure Storage solutions.

App and Container: Deployment and management of Azure App Services and Containers.

Authentication and Authorization: Implementing RBAC and securing resources.

Basic Tasks: Creating resource groups, VMs, and other fundamental Azure services.

Monitoring: Setting up and configuring Azure Monitor and related services.

Networking: Managing VNets, subnets, and network security.

VM and Advanced VM: Deploying and configuring VMs with advanced settings.

Additional Information

Certifications:

1. Advanced Certification in Cloud & DevOps

2. AWS Cerified Solutions Architect Associate

3. AWS Certified Cloud Practitioner

Workshops/Training:

1. Azure 900 Fundamentals Training

2. GCP ACE Training

Contact

If you have any questions or would like to discuss any of the projects or documentation further, feel free to reach out:

Email: umeshrajan633@gmail.com

LinkedIn: linkedin.com/in/umeshkuduwa

Twitter: x.com/UmeshKuduwa

Thank you for visiting my GitHub portfolio!
