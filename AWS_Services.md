### AWS Cost Management

AWS Budgets

Definition: Tool for setting custom budgets to manage AWS costs.
Key Facts: Alerts for cost thresholds; tracks AWS usage and costs.
Use Case: Monitoring monthly AWS spending to stay within budget.

AWS Cost and Usage Report

Definition: Detailed report of your AWS costs and usage.
Key Facts: Breaks down costs by service; can be exported to S3.
Use Case: Analyzing detailed cost data to identify cost-saving opportunities.

AWS Cost Explorer

Definition: Tool for visualizing and managing AWS costs and usage over time.
Key Facts: Offers interactive charts; forecasts costs; includes RI and Savings Plans recommendations.
Use Case: Identifying trends in AWS spending and optimizing future spending.

Savings Plans

Definition: Flexible pricing model offering lower rates on specified usage in exchange for a commitment to a consistent amount of usage (measured in $/hour) for a 1 or 3 year period.
Key Facts: Applicable to EC2, Fargate, and Lambda; offers significant savings over on-demand pricing.
Use Case: Reducing costs for predictable and consistent compute usage.
Compute

AWS Batch

Definition: Fully managed batch processing at any scale.
Key Facts: Automatically provisions resources; integrates with other AWS services.
Use Case: Running hundreds of thousands of batch computing jobs in the cloud.

Amazon EC2

Definition: Resizable compute capacity in the cloud.
Key Facts: Offers various instance types; supports Windows and Linux; scalable.
Use Case: Hosting web applications on virtual servers.

Amazon EC2 Auto Scaling

Definition: Automatically adjusts EC2 capacity.
Key Facts: Maintains performance; optimizes costs; scales based on demand.
Use Case: Maintaining application availability during demand spikes.

AWS Elastic Beanstalk

Definition: Easy-to-use service for deploying and scaling web applications and services.
Key Facts: Supports Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker; automatic scaling and load balancing.
Use Case: Quick deployment of a new web application.

AWS Outposts

Definition: Brings native AWS services, infrastructure, and operating models to virtually any data center, co-location space, or on-premises facility.
Key Facts: Fully managed; consistent hybrid experience.
Use Case: Running applications that require low latency access to on-premises systems.

AWS Serverless Application Repository

Definition: Managed repository for serverless applications.
Key Facts: Easy to deploy; supports AWS Lambda applications.
Use Case: Deploying serverless applications without needing to worry about infrastructure.

VMware Cloud on AWS

Definition: Integrates VMware's software-defined data center software with AWS cloud infrastructure.
Key Facts: Supports existing VMware environments; scalable and secure.
Use Case: Extending on-premises VMware environments to AWS.

AWS Wavelength

Definition: Extends AWS infrastructure to the edge of telecom networks.
Key Facts: Minimizes latency; for applications requiring ultra-low latency.
Use Case: Deploying applications that require ultra-low latency to mobile devices.

### Containers

Amazon ECS Anywhere

Definition: Run ECS in any environment, including on-premises.
Key Facts: Extends ECS to run on customer-managed infrastructure; integrates with AWS for cluster management.
Use Case: Running containerized applications on-premises with the same ease as in AWS.

Amazon EKS Anywhere

Definition: Run EKS in your own data center.
Key Facts: Provides consistent Kubernetes experience on-premises; easily integrates with AWS.
Use Case: Managing Kubernetes clusters on-premises with a need for cloud integration.

Amazon EKS Distro

Definition: Kubernetes distribution used by Amazon EKS.
Key Facts: Open-source; allows running Kubernetes clusters on-premises or in the cloud.
Use Case: Deploying a scalable and secure Kubernetes cluster compatible with EKS.

Amazon Elastic Container Registry (Amazon ECR)

Definition: Docker container registry for storing, managing, and deploying Docker container images.
Key Facts: Fully managed; integrates with ECS and EKS.
Use Case: Storing and managing Docker images for containerized applications.

Amazon Elastic Container Service (Amazon ECS)

Definition: Highly scalable, high-performance container management service.
Key Facts: Supports Docker containers; integrates with AWS services; can use Fargate for serverless.
Use Case: Running and scaling containerized applications on AWS.

Amazon Elastic Kubernetes Service (Amazon EKS)

Definition: Managed service to run Kubernetes on AWS.
Key Facts: Automated Kubernetes version upgrades; integrates with AWS services.
Use Case: Running Kubernetes applications with the scalability and security of AWS.

### Database

Amazon Aurora

Definition: MySQL and PostgreSQL-compatible relational database with several times the performance.
Key Facts: High durability and availability; scales storage automatically.
Use Case: Running enterprise-level, high-traffic database applications.

Amazon Aurora Serverless

Definition: Auto-scaling configuration for Amazon Aurora.
Key Facts: Scales automatically; pay-per-use; suitable for intermittent or cyclical workloads.
Use Case: Operating databases for applications with unpredictable workloads.

Amazon DocumentDB (with MongoDB compatibility)

Definition: Document database service that supports MongoDB workloads.
Key Facts: Fully managed; scalable; compatible with MongoDB applications.
Use Case: Running, managing, and scaling workloads using MongoDB on AWS.

Amazon DynamoDB

Definition: Fast and flexible NoSQL database service.
Key Facts: Fully managed; supports key-value and document data models; single-digit millisecond performance.
Use Case: Managing web session data, product catalogs, and gaming leaderboards.

Amazon ElastiCache

Definition: In-memory data store and cache.
Key Facts: Supports Redis and Memcached; enhances application performance by retrieving data from fast, managed, in-memory caches.
Use Case: Caching frequently accessed data to reduce load on databases.

### Database Services

Amazon Keyspaces (for Apache Cassandra)

Definition: A scalable, highly available, and managed Apache Cassandra-compatible database service.
Key Facts: Serverless; pay-per-use model; automatically scales tables.
Use Case: Managing large amounts of data with the flexibility of Apache Cassandra without the need for cluster management.

Amazon Neptune

Definition: A fully managed graph database service.
Key Facts: Supports popular graph models like Property Graph and RDF; fast and reliable.
Use Case: Building recommendation engines, fraud detection systems, and knowledge graphs.

Amazon Quantum Ledger Database (Amazon QLDB)

Definition: A fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log.
Key Facts: Owned by a central trusted authority.
Use Case: Systems where maintaining a complete and verifiable history of data changes is critical, like supply chain tracking.

Amazon RDS

Definition: Managed relational database service for MySQL, PostgreSQL, Oracle, SQL Server, and MariaDB.
Key Facts: Automated backups, patching, and scaling; supports Read Replicas for improved read performance.
Use Case: Running traditional relational databases with minimal administrative overhead.

Amazon Redshift

Definition: A fully managed, petabyte-scale data warehouse service.
Key Facts: Columnar storage for fast analytics; supports SQL querying; integrates with BI tools.
Use Case: Analyzing large-scale datasets using existing business intelligence tools.
### Developer Tools

AWS X-Ray

Definition: A service for analyzing and debugging production, distributed applications, such as those built using a microservices architecture.
Key Facts: Provides an end-to-end view of requests as they travel through the application; identifies performance bottlenecks.
Use Case: Troubleshooting performance and errors in microservice architectures.

### Front-End Web and Mobile

AWS Amplify

Definition: A set of tools and services to build secure, scalable mobile and web applications.
Key Facts: Integrates with React, JavaScript, Angular, Vue, Android, and iOS; provides a command-line interface.
Use Case: Quickly building and deploying mobile and web applications with authentication, data storage, backend integration.

Amazon API Gateway

Definition: A fully managed service for creating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs.
Key Facts: Scalable; supports API caching; throttling and DDoS protection.
Use Case: Building API-driven microservice architectures.

AWS Device Farm

Definition: An application testing service that allows developers to test Android, iOS, and web applications on real, physical phones and tablets.
Key Facts: Cloud-based; supports automated testing and interactive, manual testing.
Use Case: Testing mobile applications across a wide range of devices for compatibility and performance.

Amazon Pinpoint

Definition: A flexible and scalable outbound and inbound marketing communications service.
Key Facts: Supports email, SMS, push notifications; provides analytics.
Use Case: Engaging and retaining customers with targeted, data-driven messaging campaigns.

### Machine Learning Services

Amazon Comprehend

Definition: Natural language processing (NLP) service that uses machine learning to find insights and relationships in text.
Key Facts: Identifies entities, key phrases, language, sentiments; integrates with other AWS services.
Use Case: Analyzing customer feedback for sentiment and key themes.

Amazon Forecast

Definition: Time-series forecasting service based on machine learning.
Key Facts: No machine learning experience required; integrates with Amazon S3.
Use Case: Generating accurate demand forecasts for inventory planning.

Amazon Fraud Detector

Definition: Fully managed service to identify potentially fraudulent online activities.
Key Facts: Uses machine learning models; easy to create and deploy models.
Use Case: Detecting fraudulent payment transactions in real-time.

Amazon Kendra

Definition: Highly accurate and easy-to-use enterprise search service powered by machine learning.
Key Facts: Natural language understanding; indexes content from various sources.
Use Case: Creating a search solution for internal document repositories.

Amazon Lex

Definition: Service for building conversational interfaces into any application using voice and text.
Key Facts: Powers Alexa; integrates with AWS Lambda for fulfilling requests.
Use Case: Building chatbots for customer service or information retrieval.

Amazon Polly

Definition: Text-to-speech service that turns text into lifelike speech.
Key Facts: Supports multiple languages and voices; offers real-time streaming.
Use Case: Creating voice responses for virtual assistants or reading out content for visually impaired users.

Amazon Rekognition

Definition: Image and video analysis service using machine learning.
Key Facts: Identifies objects, people, text, scenes, and activities; detects inappropriate content.
Use Case: Automating image and video analysis for media content curation.

Amazon SageMaker

Definition: Fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning models quickly.
Key Facts: Broad machine learning model support; one-click model deployment; integrated Jupyter notebooks.
Use Case: Developing, training, and deploying machine learning models for predictive analytics.

Amazon Textract

Definition: Service that automatically extracts text, handwriting, and data from scanned documents.
Key Facts: Uses machine learning; processes forms and tables.
Use Case: Automating document processing for mortgage applications.

Amazon Transcribe

Definition: Automatic speech recognition (ASR) service that makes it easy to add speech-to-text capability to applications.
Key Facts: Supports various languages; offers real-time and batch transcription.
Use Case: Transcribing customer service calls for analysis and compliance.

Amazon Translate

Definition: Neural machine translation service for translating text to and from multiple languages.
Key Facts: Real-time and batch translation; supports multiple languages and dialects.
Use Case: Localizing content for different regions in websites and applications.

### Management and Governance

AWS Auto Scaling

Definition: Automatically adjusts resources to maintain performance for applications.
Key Facts: Supports EC2 instances, ECS tasks, DynamoDB tables, and Aurora replicas.
Use Case: Dynamically scaling resources to meet demand for a web application.

AWS CloudFormation

Definition: Infrastructure as Code service to model, provision, and manage AWS resources.
Key Facts: Uses templates in JSON or YAML; manages updates to resources.
Use Case: Automating the deployment and management of AWS infrastructure for a multi-tier web application.

AWS CloudTrail

Definition: Service that provides a record of actions taken by a user, role, or AWS service.
Key Facts: Enables governance, compliance, operational auditing, and risk auditing.
Use Case: Tracking changes to AWS resources for security analysis.

Amazon CloudWatch

Definition: Monitoring service for AWS cloud resources and applications.
Key Facts: Collects and tracks metrics, collects and monitors log files, sets alarms.
Use Case: Monitoring application performance and setting alarms for resource utilization.

AWS Command Line Interface (AWS CLI)

Definition: Unified tool to manage AWS services from the command line.
Key Facts: Direct access to the public APIs of AWS services; available on Windows, macOS, and Linux.
Use Case: Scripting and automating operations like deploying applications or managing resources.

AWS Compute Optimizer

Definition: Service that recommends optimal AWS resources for your workloads.
Key Facts: Provides recommendations for EC2 instances, EBS volumes, and Lambda functions.
Use Case: Identifying the most efficient and cost-effective resources for running workloads.

AWS Config

Definition: Service that enables assessing, auditing, and evaluating the configurations of AWS resources.
Key Facts: Provides a detailed view of the configuration of AWS resources; supports compliance auditing.
Use Case: Ensuring compliance with internal policies and regulatory standards.

AWS Control Tower

Definition: Service to set up and govern a secure, multi-account AWS environment.
Key Facts: Automates the setup of a baseline environment; enforces policies with guardrails.
Use Case: Managing multiple AWS accounts with standardized security and compliance controls.

AWS Health Dashboard

Definition: Provides relevant and timely information to help manage events in progress.
Key Facts: Offers alerts and guidance for AWS service health issues.
Use Case: Responding to AWS service disruptions or maintenance.

AWS License Manager

Definition: Service for tracking, managing, and controlling software licenses.
Key Facts: Integrates with AWS Marketplace; supports license-included and bring-your-own-license (BYOL) models.
Use Case: Managing software license usage to comply with contracts and reduce costs.

Amazon Managed Grafana

Definition: Fully managed service for open-source Grafana to visualize and analyze metrics.
Key Facts: Supports multiple data sources; secure and scalable.
Use Case: Creating dashboards and visualizations for monitoring application metrics.

Amazon Managed Service for Prometheus

Definition: Fully managed service for Prometheus-compatible monitoring and alerting.
Key Facts: Compatible with Prometheus open-source tool; scalable and secure monitoring solution.
Use Case: Monitoring containerized applications and microservices architecture.

AWS Management Console

Definition: Web-based interface for managing and monitoring your AWS resources.
Key Facts: User-friendly interface; access to a broad range of AWS services.
Use Case: Managing AWS resources and services through a graphical interface.

AWS Organizations

Definition: Service for managing and governing multiple AWS accounts.
Key Facts: Centralized management; supports policy-based management.
Use Case: Structuring and managing AWS accounts for large organizations or enterprise.

AWS Proton

Definition: Fully managed service to automate and manage infrastructure provisioning and code deployments for serverless and container-based applications.
Key Facts: Integrates with CI/CD tools; supports infrastructure as code.
Use Case: Streamlining the deployment and management of microservices.

AWS Service Catalog

Definition: Service to create and manage catalogs of IT services that are approved for use on AWS.
Key Facts: Standardizes resource provisioning; integrates with AWS resources.
Use Case: Enabling organizations to manage a catalog of IT services for their users.

AWS Systems Manager

Definition: Service for viewing and controlling infrastructure on AWS.
Key Facts: Centralized operational hub; automates operational tasks.
Use Case: Managing and automating routine operations tasks across AWS resources.

AWS Trusted Advisor

Definition: Online resource to help reduce cost, increase performance, and improve security.
Key Facts: Provides best practice recommendations; covers cost optimization, security, fault tolerance, and performance.
Use Case: Optimizing AWS environment performance and security.

AWS Well-Architected Tool

Definition: Tool to review the state of your workloads and compares them to the latest AWS architectural best practices.
Key Facts: Provides guidance to implement designs that scale over time; based on five pillars.
Use Case: Assessing workloads against AWS best practices to ensure efficient and effective use of AWS resources.

### Media Services

Amazon Elastic Transcoder

Definition: Media transcoder in the cloud, converting media files into different formats.
Key Facts: Easy to use; scalable; supports various media formats; integrates with other AWS services like S3.
Use Case: Converting video files into multiple formats for streaming on different devices.

Amazon Kinesis Video Streams

Definition: Service to capture, process, and store video streams.
Key Facts: Real-time and batch video processing; securely streams video to AWS from connected devices.
Use Case: Streaming live video feeds from surveillance cameras for real-time analysis.

### Migration and Transfer

AWS Application Discovery Service

Definition: Service that helps enterprise customers plan migration projects by gathering information about their on-premises data centers.
Key Facts: Automatically collects configuration and usage data; supports planning for migration.
Use Case: Gathering data about on-premises servers to assist in planning a migration to AWS.

AWS Application Migration Service

Definition: Service that simplifies and expedites the migration of applications to AWS.
Key Facts: Minimizes downtime to applications; automates re-platforming; works closely with AWS Database Migration Service.
Use Case: Migrating web applications from an on-premises environment to AWS.

AWS Database Migration Service (AWS DMS)

Definition: Service that helps migrate databases to AWS quickly and securely.
Key Facts: Supports homogeneous and heterogeneous migrations; minimal downtime.
Use Case: Migrating a legacy SQL database to Amazon RDS or Aurora.

AWS DataSync

Definition: Data transfer service that simplifies, automates, and accelerates moving data between on-premises storage and AWS services.
Key Facts: Faster than open-source tools; integrates with S3, EFS, and FSx for Windows File Server.
Use Case: Moving large datasets to AWS storage for analysis.

AWS Migration Hub

Definition: Central location to track and manage migrations from on-premises to AWS.
Key Facts: Provides migration status at a glance; integrates with other AWS migration tools.
Use Case: Tracking the progress of application migrations across multiple AWS and partner solutions.

AWS Snow Family

Definition: A suite of physical devices to transfer large volumes of data into and out of AWS.
Key Facts: Includes Snowcone, Snowball, and Snowmobile; secure data transfer; suitable for environments with limited connectivity.
Use Case: Transferring petabytes of data into AWS without relying on network bandwidth.

AWS Transfer Family

Definition: Fully managed service enabling secure file transfers into and out of S3.
Key Facts: Supports SFTP, FTPS, and FTP; integrates with existing authentication systems.
Use Case: Migrating file transfer workflows to AWS while maintaining compatibility with existing clients.

### Networking and Content Delivery

AWS Client VPN

Definition: A managed client-based VPN service.
Key Facts: Enables secure connections to AWS or on-premises networks; supports OpenVPN clients.
Use Case: Providing secure remote access to an AWS VPC for a mobile workforce.

Amazon CloudFront

Definition: A fast content delivery network (CDN) service.
Key Facts: Securely delivers data, videos, applications, and APIs; integrates with AWS services.
Use Case: Speeding up distribution of static and dynamic web content.

AWS Direct Connect

Definition: A cloud service solution that links your network directly to AWS.
Key Facts: Bypasses the internet for more reliable and consistent network experience.
Use Case: Establishing a dedicated network connection from an on-premises data center to AWS.

Elastic Load Balancing (ELB)

Definition: Automatically distributes incoming application traffic across multiple targets.
Key Facts: Types include Application Load Balancer, Network Load Balancer, and Classic Load Balancer.
Use Case: Distributing web traffic across multiple EC2 instances to optimize application performance.

AWS Global Accelerator

Definition: A service that improves the availability and performance of applications.
Key Facts: Directs traffic to optimal endpoints over the AWS global network.
Use Case: Enhancing the performance of a global application for users around the world.

AWS PrivateLink

Definition: Provides private connectivity between VPCs, AWS services, and on-premises applications.
Key Facts: Securely access services while keeping network traffic within the AWS network.
Use Case: Accessing a third-party service or SaaS application securely from within a VPC.

Amazon Route 53

Definition: A scalable and highly available Domain Name System (DNS) web service.
Key Facts: Offers domain registration, DNS routing, and health checking.
Use Case: Routing users to Internet applications by translating domain names (like www.example.com) into IP addresses.

AWS Site-to-Site VPN

Definition: A secure connection between an on-premises network and an Amazon VPC.
Key Facts: Uses IPsec VPN connections; integrates with existing network architecture.
Use Case: Extending on-premises networks to the cloud securely.

AWS Transit Gateway

Definition: A service that enables you to connect your Amazon VPCs and on-premises networks to a single gateway.
Key Facts: Simplifies network topology; integrates with AWS Direct Connect and Site-to-Site VPN.
Use Case: Centralizing and managing multiple VPCs and VPN connections.

Amazon VPC

Definition: A service that lets you launch AWS resources in a logically isolated virtual network.
Key Facts: Customizable IP address ranges, subnets, route tables, and network gateways.
Use Case: Hosting a secure and scalable web application.

### Security, Identity, and Compliance

AWS Artifact

Definition: A portal for on-demand access to AWS compliance documentation and AWS agreements.
Key Facts: Provides audit artifacts; manages compliance reports.
Use Case: Obtaining compliance reports for auditing purposes.

AWS Audit Manager

Definition: Helps continuously audit AWS usage to simplify how you assess risk and compliance.
Key Facts: Automates evidence collection; integrates with AWS services.
Use Case: Streamlining audit preparation for compliance with regulations.

AWS Certificate Manager (ACM)

Definition: Manages the deployment, renewal, and management of SSL/TLS certificates.
Key Facts: Integrates with AWS services; supports public and private TLS certificates.
Use Case: Securing website domains with SSL/TLS certificates.

AWS CloudHSM

Definition: A cloud-based hardware security module (HSM) that enables secure key storage and cryptographic operations.
Key Facts: Supports industry standards; dedicated hardware within AWS environment.
Use Case: Managing cryptographic keys for regulatory compliance.

Amazon Cognito

Definition: Provides authentication, authorization, and user management for web and mobile applications.
Key Facts: Supports social identity providers; integrates with SAML 2.0.
Use Case: Adding user sign-up, sign-in, and access control to apps.

Amazon Detective

Definition: Automatically analyzes and visualizes security data to investigate and identify security issues.
Key Facts: Integrates with AWS security services; provides visual analysis.
Use Case: Investigating potential security issues or suspicious activities.

AWS Directory Service

Definition: Offers multiple options to set up and run Microsoft Active Directory (AD) in AWS.
Key Facts: Includes AWS Managed Microsoft AD, AD Connector, and Simple AD.
Use Case: Running Windows workloads that require Active Directory.

AWS Firewall Manager

Definition: Centralized management of AWS WAF rules across multiple accounts and resources.
Key Facts: Automates firewall rule management; integrates with AWS Organizations.
Use Case: Implementing consistent firewall rules across an organization's AWS environment.

Amazon GuardDuty

Definition: A threat detection service that continuously monitors for malicious activity.
Key Facts: Uses machine learning, anomaly detection, and integrated threat intelligence.
Use Case: Detecting unexpected and potentially unauthorized activity in AWS accounts.

AWS IAM Identity Center (AWS Single Sign-On)

Definition: Centrally manage single sign-on (SSO) access to multiple AWS accounts and business applications.
Key Facts: Integrates with existing identity sources; supports SAML 2.0.
Use Case: Streamlining user access to multiple AWS accounts and applications.

AWS Identity and Access Management (IAM)

Definition: Manages access to AWS services and resources.
Key Facts: Supports identity federation; fine-grained access controls.
Use Case: Controlling user and group access to AWS resources.

Amazon Inspector

Definition: Automated security assessment service to improve the security and compliance of applications.
Key Facts: Assesses applications for vulnerabilities and deviations from best practices.
Use Case: Running automated security assessments on EC2 instances.


AWS Key Management Service (AWS KMS)

Definition: Managed service to create and control cryptographic keys.
Key Facts: Integrates with other AWS services; supports key rotation and management.
Use Case: Encrypting data stored in S3 buckets using managed keys.

Amazon Macie

Definition: Machine learning-powered security service to discover, classify, and protect sensitive data.
Key Facts: Automatically identifies and classifies sensitive data in AWS; supports GDPR compliance.
Use Case: Protecting sensitive customer data stored in S3.

AWS Network Firewall

Definition: Managed firewall service for VPC.
Key Facts: Provides flexible rules for traffic inspection, intrusion detection, and prevention.
Use Case: Implementing network-level security controls for inbound and outbound traffic in a VPC.

AWS Resource Access Manager (AWS RAM)

Definition: Service to share AWS resources across accounts.
Key Facts: Supports sharing of Subnets, Transit Gateways, etc.; integrates with AWS Organizations.
Use Case: Sharing Subnets with other AWS accounts within an organization.

AWS Secrets Manager

Definition: Manages, retrieves, and rotates database credentials, API keys, and other secrets.
Key Facts: Integrates with RDS, Redshift, and DocumentDB; supports secret rotation.
Use Case: Managing database credentials securely and automating their rotation.

AWS Security Hub

Definition: Comprehensive view of security alerts and security posture across AWS accounts.
Key Facts: Aggregates security findings from AWS services and partner tools.
Use Case: Centralizing and prioritizing security alerts and compliance status.

AWS Shield

Definition: Managed Distributed Denial of Service (DDoS) protection service.
Key Facts: AWS Shield Standard and AWS Shield Advanced options; integrates with CloudFront and Route 53.
Use Case: Protecting websites and applications against DDoS attacks.

AWS WAF

Definition: Web application firewall that helps protect web applications from common web exploits.
Key Facts: Offers rules to control bot traffic and block common attack patterns.
Use Case: Protecting a web application from SQL injection and Cross-Site Scripting (XSS) attacks.

### Serverless Services

AWS AppSync

Definition: A managed service that uses GraphQL to make it easy to build collaborative mobile and web applications.
Key Facts: Real-time data synchronization; offline data access.
Use Case: Building a real-time chat application that syncs across devices.

AWS Fargate

Definition: A serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS).
Key Facts: Eliminates the need to manage servers; scales containers.
Use Case: Running containerized applications without managing underlying infrastructure.

AWS Lambda

Definition: A compute service that lets you run code without provisioning or managing servers.
Key Facts: Automatic scaling; pay only for the compute time you consume.
Use Case: Automatically resizing images uploaded to S3.

### Storage Services

AWS Backup

Definition: A centralized backup service that makes it easier to manage and automate backups across AWS services.
Key Facts: Supports EBS, RDS, DynamoDB, EFS, and Storage Gateway.
Use Case: Automating and centralizing backup of AWS cloud resources.

Amazon Elastic Block Store (Amazon EBS)

Definition: Provides block-level storage volumes for use with EC2 instances.
Key Facts: High-performance volumes; snapshots for backup.
Use Case: Providing persistent block storage for an EC2 instance running a database.

Amazon Elastic File System (Amazon EFS)

Definition: A scalable, elastic, cloud-native file system for Linux-based workloads.
Key Facts: Can be used with AWS Cloud services and on-premises resources; scales automatically.
Use Case: Storing and sharing files across multiple EC2 instances.

Amazon FSx

Definition: Provides fully managed third-party file systems with native compatibility and feature sets.
Key Facts: Includes FSx for Windows File Server and FSx for Lustre.
Use Case: Running a high-performance computing (HPC) workload that requires fast data processing.

Amazon S3

Definition: Object storage built to store and retrieve any amount of data from anywhere.
Key Facts: Scalable; data availability; secure; supports web-based applications.
Use Case: Hosting static website content and media files.

Amazon S3 Glacier

Definition: A secure, durable, and low-cost storage service for data archiving and long-term backup.
Key Facts: Offers retrieval options from minutes to hours; highly durable.
Use Case: Archiving old but important data at low cost.

AWS Storage Gateway

Definition: A hybrid cloud storage service that provides on-premises access to virtually unlimited cloud storage.
Key Facts: Supports file, volume, and tape storage interfaces; integrates with S3.
Use Case: External file transfer
