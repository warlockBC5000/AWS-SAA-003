### Analytics

1. **Amazon Athena**: 
   - **Definition**: A serverless interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL.
   - **Use Case**: Athena can be used for quick ad-hoc querying of data stored in S3, such as analyzing web logs for website traffic patterns without the need for complex ETL processes.

2. **AWS Data Exchange**: 
   - **Definition**: A service that makes it easy to find, subscribe to, and use third-party data in the cloud.
   - **Use Case**: Companies can use AWS Data Exchange to access and integrate third-party financial data into their own analytics to enhance market analysis.

3. **AWS Data Pipeline**:
   - **Definition**: A web service for reliably processing and moving data between different AWS compute and storage services, as well as on-premises data sources.
   - **Use Case**: Automating the movement and transformation of data for regular reporting – for instance, daily sales data from various sources to a central analytics platform.

4. **Amazon EMR (Elastic MapReduce)**:
   - **Definition**: A cloud-native big data platform, allowing processing of vast amounts of data quickly and cost-effectively across resizable clusters of Amazon EC2 instances.
   - **Use Case**: Running big data frameworks like Apache Spark or Hadoop to analyze and process large datasets, such as genomic data for scientific research.

5. **AWS Glue**:
   - **Definition**: A fully managed extract, transform, and load (ETL) service that makes it simple and cost-effective to categorize, clean, enrich, and move data.
   - **Use Case**: Automatically discovering, cataloging, and preparing data for analytics, such as integrating data from various databases and S3 buckets for a unified data warehouse.

6. **Amazon Kinesis**:
   - **Definition**: A platform for streaming data on AWS, offering powerful services to make it easy to load and analyze streaming data, and also providing the ability to build custom streaming data applications.
   - **Use Case**: Real-time processing of streaming data, such as monitoring application logs, website clickstreams, or IoT device telemetry.

7. **AWS Lake Formation**:
   - **Definition**: A service that makes it easy to set up a secure data lake in days, managing data access and movement.
   - **Use Case**: Building, securing, and managing a data lake, for instance, to centralize data from various sources and make it available for diverse analytics and machine learning.

8. **Amazon Managed Streaming for Apache Kafka (Amazon MSK)**:
   - **Definition**: A fully managed service that makes it easy to build and run applications that use Apache Kafka to process streaming data.
   - **Use Case**: Running high-throughput message brokers for applications like event-driven microservices, or log aggregation systems.

9. **Amazon OpenSearch Service**:
   - **Definition**: An AWS service for running OpenSearch (formerly known as Elasticsearch) to easily deploy, operate, and scale OpenSearch clusters in the AWS Cloud.
   - **Use Case**: Supporting complex search capabilities on large volumes of data, like log analytics, real-time application monitoring, and clickstream analytics.

10. **Amazon QuickSight**:
    - **Definition**: A fast, cloud-powered business intelligence service that makes it easy to deliver insights to everyone in your organization.
    - **Use Case**: Building visualizations and dashboards to analyze data across your organization, for example, sales performance or operational health.

11. **Amazon Redshift**:
    - **Definition**: A fully managed, petabyte-scale data warehouse service in the cloud, allowing you to efficiently analyze all your data using your existing business intelligence tools.
    - **Use Case**: Conducting complex queries and analytics on large datasets, like historical transaction data for trend analysis and forecasting.

### Applicaiton Integration

1. **Amazon AppFlow**
   - **Definition**: A fully managed integration service that enables secure, automated data flows between AWS services and SaaS applications.
   - **Use Case**: Automating data transfer between Salesforce and Amazon S3 for regular data backup or analytics.
   - **Fact**: Supports many SaaS applications and AWS services, provides data transformation capabilities, and allows for scheduling or event-triggered flows.

2. **AWS AppSync**
   - **Definition**: A managed GraphQL service for building APIs, enabling real-time updates, offline programming, and data synchronization.
   - **Use Case**: Building a real-time collaborative application, like a chat app, where the data (messages, user status) needs to be synchronized across various clients.
   - **Fact**: Integrates with AWS Lambda, Amazon DynamoDB, and Amazon RDS, supporting complex data retrieval with GraphQL.

3. **Amazon EventBridge**
   - **Definition**: A serverless event bus service that connects application data from your own apps, SaaS, and AWS services.
   - **Use Case**: Creating an event-driven architecture, like triggering a Lambda function for image processing when new images are uploaded to S3.
   - **Fact**: Offers scalable event handling without managing underlying infrastructure and supports event filtering and pattern matching.

4. **Amazon MQ**
   - **Definition**: A managed message broker service for Apache ActiveMQ and RabbitMQ.
   - **Use Case**: Migrating existing message brokers to the cloud with minimal code changes in legacy applications.
   - **Fact**: Provides high availability, message durability, and security features, suitable for traditional applications requiring a message broker.

5. **Amazon Simple Notification Service (Amazon SNS)**
   - **Definition**: A fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication.
   - **Use Case**: Sending notifications to end-users via email, SMS, or mobile push notifications, like alerting customers about order status.
   - **Fact**: Supports pub/sub messaging patterns, allowing decoupling of microservices, distributed systems, and serverless applications.

6. **Amazon Simple Queue Service (Amazon SQS)**
   - **Definition**: A fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
   - **Use Case**: Managing a high volume of messages from multiple sources and ensuring their processing in an orderly fashion.
   - **Fact**: Offers two types of message queues: Standard (high-throughput, best-effort ordering) and FIFO (first-in-first-out delivery and exactly-once processing).

7. **AWS Step Functions**
   - **Definition**: A service to coordinate multiple AWS services into serverless workflows.
   - **Use Case**: Orchestrating complex workflows, such as an order fulfillment process that involves multiple steps like payment processing, inventory check, and shipping.
   - **Fact**: Allows visual workflow management, supports error handling, conditional branching, and integrates with various AWS services.


### AWS Cost Management

#### AWS Budgets
- **Definition**: Tool for setting custom budgets to manage AWS costs.
- **Key Facts**: Alerts for cost thresholds; tracks AWS usage and costs.
- **Use Case**: Monitoring monthly AWS spending to stay within budget.

#### AWS Cost and Usage Report
- **Definition**: Detailed report of your AWS costs and usage.
- **Key Facts**: Breaks down costs by service; can be exported to S3.
- **Use Case**: Analyzing detailed cost data to identify cost-saving opportunities.

#### AWS Cost Explorer
- **Definition**: Tool for visualizing and managing AWS costs and usage over time.
- **Key Facts**: Offers interactive charts; forecasts costs; includes RI and Savings Plans recommendations.
- **Use Case**: Identifying trends in AWS spending and optimizing future spending.

#### Savings Plans
- **Definition**: Flexible pricing model offering lower rates on specified usage in exchange for a commitment to a consistent amount of usage (measured in $/hour) for a 1 or 3 year period.
- **Key Facts**: Applicable to EC2, Fargate, and Lambda; offers significant savings over on-demand pricing.
- **Use Case**: Reducing costs for predictable and consistent compute usage.

### Compute

#### AWS Batch
- **Definition**: Fully managed batch processing at any scale.
- **Key Facts**: Automatically provisions resources; integrates with other AWS services.
- **Use Case**: Running hundreds of thousands of batch computing jobs in the cloud.

#### Amazon EC2
- **Definition**: Resizable compute capacity in the cloud.
- **Key Facts**: Offers various instance types; supports Windows and Linux; scalable.
- **Use Case**: Hosting web applications on virtual servers.

#### Amazon EC2 Auto Scaling
- **Definition**: Automatically adjusts EC2 capacity.
- **Key Facts**: Maintains performance; optimizes costs; scales based on demand.
- **Use Case**: Maintaining application availability during demand spikes.

#### AWS Elastic Beanstalk
- **Definition**: Easy-to-use service for deploying and scaling web applications and services.
- **Key Facts**: Supports Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker; automatic scaling and load balancing.
- **Use Case**: Quick deployment of a new web application.

#### AWS Outposts
- **Definition**: Brings native AWS services, infrastructure, and operating models to virtually any data center, co-location space, or on-premises facility.
- **Key Facts**: Fully managed; consistent hybrid experience.
- **Use Case**: Running applications that require low latency access to on-premises systems.

#### AWS Serverless Application Repository
- **Definition**: Managed repository for serverless applications.
- **Key Facts**: Easy to deploy; supports AWS Lambda applications.
- **Use Case**: Deploying serverless applications without needing to worry about infrastructure.

#### VMware Cloud on AWS
- **Definition**: Integrates VMware's software-defined data center software with AWS cloud infrastructure.
- **Key Facts**: Supports existing VMware environments; scalable and secure.
- **Use Case**: Extending on-premises VMware environments to AWS.

#### AWS Wavelength
- **Definition**: Extends AWS infrastructure to the edge of telecom networks.
- **Key Facts**: Minimizes latency; for applications requiring ultra-low latency

## Containers

### Amazon ECS Anywhere

**Definition:** Run ECS in any environment, including on-premises.
**Key Facts:** Extends ECS to run on customer-managed infrastructure; integrates with AWS for cluster management.
**Use Case:** Running containerized applications on-premises with the same ease as in AWS.

### Amazon EKS Anywhere

**Definition:** Run EKS in your own data center.
**Key Facts:** Provides consistent Kubernetes experience on-premises; easily integrates with AWS.
**Use Case:** Managing Kubernetes clusters on-premises with a need for cloud integration.

### Amazon EKS Distro

**Definition:** Kubernetes distribution used by Amazon EKS.
**Key Facts:** Open-source; allows running Kubernetes clusters on-premises or in the cloud.
**Use Case:** Deploying a scalable and secure Kubernetes cluster compatible with EKS.

### Amazon Elastic Container Registry (Amazon ECR)

**Definition:** Docker container registry for storing, managing, and deploying Docker container images.
**Key Facts:** Fully managed; integrates with ECS and EKS.
**Use Case:** Storing and managing Docker images for containerized applications.

### Amazon Elastic Container Service (Amazon ECS)

**Definition:** Highly scalable, high-performance container management service.
**Key Facts:** Supports Docker containers; integrates with AWS services; can use Fargate for serverless.
**Use Case:** Running and scaling containerized applications on AWS.

### Amazon Elastic Kubernetes Service (Amazon EKS)

**Definition:** Managed service to run Kubernetes on AWS.
**Key Facts:** Automated Kubernetes version upgrades; integrates with AWS services.
**Use Case:** Running Kubernetes applications with the scalability and security of AWS.

## Database

### Amazon Aurora

**Definition:** MySQL and PostgreSQL-compatible relational database with several times the performance.
**Key Facts:** High durability and availability; scales storage automatically.
**Use Case:** Running enterprise-level, high-traffic database applications.

### Amazon Aurora Serverless

**Definition:** Auto-scaling configuration for Amazon Aurora.
**Key Facts:** Scales automatically; pay-per-use; suitable for intermittent or cyclical workloads.
**Use Case:** Operating databases for applications with unpredictable workloads.

### Amazon DocumentDB (with MongoDB compatibility)

**Definition:** Document database service that supports MongoDB workloads.
**Key Facts:** Fully managed; scalable; compatible with MongoDB applications.
**Use Case:** Running, managing, and scaling workloads using MongoDB on AWS.

### Amazon DynamoDB

**Definition:** Fast and flexible NoSQL database service.
**Key Facts:** Fully managed; supports key-value and document data models; single-digit millisecond performance.
**Use Case:** Managing web session data, product catalogs, and gaming leaderboards.

### Amazon ElastiCache

**Definition:** In-memory data store and cache.
**Key Facts:** Supports Redis and Memcached; enhances application performance by retrieving data from fast, managed, in-memory caches.
**Use Case:** Caching frequently accessed data to reduce load on databases.

## Database Services

### Amazon Keyspaces (for Apache Cassandra)

**Definition:** A scalable, highly available, and managed Apache Cassandra-compatible database service.
**Key Facts:** Serverless; pay-per-use model; automatically scales tables.
**Use Case:** Managing large amounts of data with the flexibility of Apache Cassandra without the need for cluster management.

### Amazon Neptune

**Definition:** A fully managed graph database service.
**Key Facts:** Supports popular graph models like Property Graph and RDF; fast and reliable.
**Use Case:** Building recommendation engines, fraud detection systems, and knowledge graphs.

### Amazon Quantum Ledger Database (Amazon QLDB)

**Definition:** A fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log.
**Key Facts:** Owned by a central trusted authority.
**Use Case:** Systems where maintaining a complete and verifiable history of data changes is critical, like supply chain tracking.

### Amazon RDS

**Definition:** Managed relational database service for MySQL, PostgreSQL, Oracle, SQL Server, and MariaDB.
**Key Facts:** Automated backups, patching, and scaling; supports Read Replicas for improved read performance.
**Use Case:** Running traditional relational databases with minimal administrative overhead.

### Amazon Redshift

**Definition:** A fully managed, petabyte-scale data warehouse service.
**Key Facts:** Columnar storage for fast analytics; supports SQL querying; integrates with BI tools.
**Use Case:** Analyzing large-scale datasets using existing business intelligence tools.

## Developer Tools

### AWS X-Ray

**Definition:** A service for analyzing and debugging production, distributed applications, such as those built using a microservices architecture.
**Key Facts:** Provides an end-to-end view of requests as they travel through the application; identifies performance bottlenecks.
**Use Case:** Troubleshooting performance and errors in microservice architectures.

## Front-End Web and Mobile

### AWS Amplify

**Definition:** A set of tools and services to build secure, scalable mobile and web applications.
**Key Facts:** Integrates with React, JavaScript, Angular, Vue, Android, and iOS; provides a command-line interface.
**Use Case:** Quickly building and deploying mobile and web applications with authentication, data storage, backend integration.

### Amazon API Gateway

**Definition:** A fully managed service for creating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs.
**Key Facts:** Scalable; supports API caching; throttling and DDoS protection.
**Use Case:** Building API-driven microservice architectures.

### AWS Device Farm

**Definition:** An application testing service that allows developers to test Android, iOS, and web applications on real, physical phones and tablets.
**Key Facts:** Cloud-based; supports automated testing and interactive, manual testing.
**Use Case:** Testing mobile applications across a wide range of devices for compatibility and performance.

### Amazon Pinpoint

**Definition:** A flexible and scalable outbound and inbound marketing communications service.
**Key Facts:** Supports email, SMS, push notifications; provides analytics.
**Use Case:** Engaging and retaining customers with targeted, data-driven messaging campaigns.

## Machine Learning Services

### Amazon Comprehend

**Definition:** Natural language processing (NLP) service that uses machine learning to find insights and relationships in text.
**Key Facts:** Identifies entities, key phrases, language, sentiments; integrates with other AWS services.
**Use Case:** Analyzing customer feedback for sentiment and key themes.

### Amazon Forecast

**Definition:** Time-series forecasting service based on machine learning.
**Key Facts:** No machine learning experience required; integrates with Amazon S3.
**Use Case:** Generating accurate demand forecasts for inventory planning.

### Amazon Fraud Detector

**Definition:** Fully managed service to identify potentially fraudulent online activities.
**Key Facts:** Uses machine learning models; easy to create and deploy models.
**Use Case:** Detecting fraudulent payment transactions in real-time.

### Amazon Kendra

**Definition:** Highly accurate and easy-to-use enterprise search service powered by machine learning.
**Key Facts:** Natural language understanding; indexes content from various sources.
**Use Case:** Creating a search solution for internal document repositories.

### Amazon Lex

**Definition:** Service for building conversational interfaces into any application using voice and text.
**Key Facts:** Powers Alexa; integrates with AWS Lambda for fulfilling requests.
**Use Case:** Building chatbots for customer service or information retrieval.

### Amazon Polly

**Definition:** Text-to-speech service that turns text into lifelike speech.
**Key Facts:** Supports multiple languages and voices; offers
real-time streaming.
**Use Case:** Creating voice responses for virtual assistants or reading out content for visually impaired users.

### Amazon Rekognition

**Definition:** Image and video analysis service using machine learning.
**Key Facts:** Identifies objects, people, text, scenes, and activities; detects inappropriate content.
**Use Case:** Automating image and video analysis for media content curation.

### Amazon SageMaker

**Definition:** Fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning models quickly.
**Key Facts:** Broad machine learning model support; one-click model deployment; integrated Jupyter notebooks.
**Use Case:** Developing, training, and deploying machine learning models for predictive analytics.

### Amazon Textract

**Definition:** Service that automatically extracts text, handwriting, and data from scanned documents.
**Key Facts:** Uses machine learning; processes forms and tables.
**Use Case:** Automating document processing for mortgage applications.

### Amazon Transcribe

**Definition:** Automatic speech recognition (ASR) service that makes it easy to add speech-to-text capability to applications.
**Key Facts:** Supports various languages; offers real-time and batch transcription.
**Use Case:** Transcribing customer service calls for analysis and compliance.

### Amazon Translate

**Definition:** Neural machine translation service for translating text to and from multiple languages.
**Key Facts:** Real-time and batch translation; supports multiple languages and dialects.
**Use Case:** Localizing content for different regions in websites and applications.

## Management and Governance

### AWS Auto Scaling

**Definition:** Automatically adjusts resources to maintain performance for applications.
**Key Facts:** Supports EC2 instances, ECS tasks, DynamoDB tables, and Aurora replicas.
**Use Case:** Dynamically scaling resources to meet demand for a web application.

### AWS CloudFormation

**Definition:** Infrastructure as Code service to model, provision, and manage AWS resources.
**Key Facts:** Uses templates in JSON or YAML; manages updates to resources.
**Use Case:** Automating the deployment and management of AWS infrastructure for a multi-tier web application.

### AWS CloudTrail

**Definition:** Service that provides a record of actions taken by a user, role, or AWS service.
**Key Facts:** Enables governance, compliance, operational auditing, and risk auditing.
**Use Case:** Tracking changes to AWS resources for security analysis.

### Amazon CloudWatch

**Definition:** Monitoring service for AWS cloud resources and applications.
**Key Facts:** Collects and tracks metrics, collects and monitors log files, sets alarms.
**Use Case:** Monitoring application performance and setting alarms for resource utilization.

### AWS Command Line Interface (AWS CLI)

**Definition:** Unified tool to manage AWS services from the command line.
**Key Facts:** Direct access to the public APIs of AWS services; available on Windows, macOS, and Linux.
**Use Case:** Scripting and automating operations like deploying applications or managing resources.

### AWS Compute Optimizer

**Definition:** Service that recommends optimal AWS resources for your workloads.
**Key Facts:** Provides recommendations for EC2 instances, EBS volumes, and Lambda functions.
**Use Case:** Identifying the most efficient and cost-effective resources for running workloads.

### AWS Config

**Definition:** Service that enables assessing, auditing, and evaluating the configurations of AWS resources.
**Key Facts:** Provides a detailed view of the configuration of AWS resources; supports compliance auditing.
**Use Case:** Ensuring compliance with internal policies and regulatory standards.

### AWS Control Tower

**Definition:** Service to set up and govern a secure, multi-account AWS environment.
**Key Facts:** Automates the setup of a baseline environment; enforces policies with guardrails.
**Use Case:** Managing multiple AWS accounts with standardized security and compliance controls.

### AWS Health Dashboard

**Definition:** Provides relevant and timely information to help manage events in progress.
**Key Facts:** Offers alerts and guidance for AWS service health issues.
**Use Case:** Responding to AWS service disruptions or maintenance.

### AWS License Manager

**Definition:** Service for tracking, managing, and controlling software licenses.
**Key Facts:** Integrates with AWS Marketplace; supports license-included and bring-your-own-license (BYOL) models.
**Use Case:** Managing software license usage to comply with contracts and reduce costs.

### Amazon Managed Grafana

**Definition:** Fully managed service for open-source Grafana to visualize and analyze metrics.
**Key Facts:** Supports multiple data sources; secure and scalable.
**Use Case:** Creating dashboards and visualizations for monitoring application metrics.

### Amazon Managed Service for Prometheus

**Definition:** Fully managed service for Prometheus-compatible monitoring and alerting.
**Key Facts:** Compatible with Prometheus open-source tool; scalable and secure monitoring solution.
**Use Case:** Monitoring containerized applications and microservices architecture.

### AWS Management Console

**Definition:** Web-based interface for managing and monitoring your AWS resources.
**Key Facts:** User-friendly interface; access to a broad range of AWS services.
**Use Case:** Managing AWS resources and services through a graphical interface.

### AWS Organizations

**Definition:** Service for managing and governing multiple AWS accounts.
**Key Facts:** Centralized management; supports policy-based management.
**Use Case:** Structuring and managing AWS accounts for large organizations or enterprise.

### AWS Proton

**Definition:** Fully managed service to automate and manage infrastructure provisioning and code deployments for serverless and container-based applications.
**Key Facts:** Integrates with CI/CD tools; supports infrastructure as code.
**Use Case:** Streamlining the deployment and management of microservices.

### AWS Service Catalog

**Definition:** Service to create and manage catalogs of IT services that are approved for use on AWS
**Key Facts:** Centralized service provisioning; customizable product portfolios.
**Use Case:** Enabling self-service access to approved AWS resources for teams.

### AWS Systems Manager

**Definition:** Service to manage hybrid cloud systems at scale.
**Key Facts:** Provides a unified user interface for operational data; automates tasks.
**Use Case:** Managing and automating operational tasks across AWS resources.

### AWS Trusted Advisor

**Definition:** Service that provides real-time guidance to help you provision your resources following best practices.
**Key Facts:** Offers recommendations in cost optimization, security, fault tolerance, and performance improvement.
**Use Case:** Optimizing resource usage and cost-effectiveness.

### AWS Well-Architected Tool

**Definition:** Service that provides a consistent approach to evaluating architectures.
**Key Facts:** Offers guidance on best practices and improvements.
**Use Case:** Assessing and improving the architecture of applications.

## Media Services

### AWS Elemental MediaConnect

**Definition:** Secure, transport-grade live video transfer service.
**Key Facts:** Low-latency, high-quality video transfer; supports encryption.
**Use Case:** Reliable and secure live video streaming for broadcasting and events.

### AWS Elemental MediaConvert

**Definition:** File-based video transcoding service with broadcast-grade features.
**Key Facts:** Supports a wide range of video formats; integrates with other AWS services.
**Use Case:** Converting video files into different formats for playback on various devices.

### AWS Elemental MediaLive

**Definition:** Broadcast-grade live video processing service.
**Key Facts:** Supports multiple input formats and streaming protocols; integrates with AWS services.
**Use Case:** Encoding and streaming live video for broadcasting and events.

### AWS Elemental MediaPackage

**Definition:** Video origination and packaging service.
**Key Facts:** Supports multiple streaming formats; integrates with CDN services.
**Use Case:** Preparing and delivering video content for OTT and online streaming.

### AWS Elemental MediaStore

**Definition:** Video origination and storage service.
**Key Facts:** Reliable and low-latency storage for video assets; scalable.
**Use Case:** Storing and serving video assets for streaming applications.

### AWS Elemental MediaTailor

**Definition:** Personalized ad insertion service for streaming video.
**Key Facts:** Supports targeted advertising; improves viewer engagement.
**Use Case:** Monetizing video streaming services with personalized ads.

## Migration and Transfer

### AWS DataSync

**Definition:** Online data transfer service that simplifies, automates, and accelerates moving data between on-premises storage and Amazon S3, EFS, or FSx for Windows File Server.
**Key Facts:** Supports data migration, data synchronization, and data distribution.
**Use Case:** Migrating data to the AWS Cloud and keeping it in sync with on-premises storage.

### AWS Data Pipeline

**Definition:** Web service for orchestrating and automating the movement and transformation of data between different AWS services and on-premises data sources.
**Key Facts:** Supports data transfer, data processing, and scheduling.
**Use Case:** Automating data workflows across multiple AWS services.

### AWS Data Transfer

**Definition:** Services for transferring data into and out of AWS.
**Key Facts:** Includes AWS DataSync, AWS Snow Family, and AWS Storage Gateway.
**Use Case:** Securely and efficiently transferring large volumes of data to and from AWS.

### AWS Snow Family

**Definition:** Edge computing and data transfer devices for rugged or disconnected environments.
**Key Facts:** Includes Snowcone, Snowball, and Snowmobile.
**Use Case:** Transferring large data sets to and from remote or challenging locations.

### AWS Transfer Family

**Definition:** Managed file transfer service for SFTP, FTPS, and FTP.
**Key Facts:** Fully managed; integrates with Amazon S3 and EFS.
**Use Case:** Securely transferring files to and from AWS.

## Mobile

### AWS Mobile Hub

**Definition:** Integrated console for building, testing, and monitoring mobile applications.
**Key Facts:** Supports iOS, Android, React Native; integrates with AWS services.
**Use Case:** Developing and managing mobile app backend services.

## Networking and Content Delivery

### AWS App Runner

**Definition:** Fully managed service for building containerized web applications.
**Key Facts:** Automatically builds and deploys web applications from source code or Docker images.
**Use Case:** Quickly deploying web applications without managing infrastructure.

### AWS CloudFront

**Definition:** Content delivery network (CDN) service.
**Key Facts:** Low-latency content delivery; integrates with other AWS services.
**Use Case:** Accelerating content delivery to users worldwide.

### AWS Direct Connect

**Definition:** Dedicated network connection from on-premises to AWS.
**Key Facts:** Private and dedicated network connection; reduces network costs.
**Use Case:** Establishing a dedicated and high-speed network connection to AWS.

### AWS Global Accelerator

**Definition:** Service that improves the availability and performance of applications.
**Key Facts:** Anycast IP addresses; automatic failover; integrates with AWS services.
**Use Case:** Load balancing and improving the availability of applications.

### AWS Transit Gateway

**Definition:** Service that simplifies network connectivity between VPCs and on-premises networks.
**Key Facts:** Hub-and-spoke architecture; centralize network routing.
**Use Case:** Simplifying network architecture in a multi-VPC or hybrid cloud environment.

### Elastic Load Balancing

**Definition:** Automatically distributes incoming application traffic across multiple targets.
**Key Facts:** Supports Application Load Balancers, Network Load Balancers, and Classic Load Balancers.
**Use Case:** Ensuring high availability and fault tolerance for applications.

## Robotics

### AWS RoboMaker

**Definition:** Service for developing, testing, and deploying intelligent robotics applications.
**Key Facts:** Integrates with ROS (Robot Operating System); simulates robot behavior.
**Use Case:** Developing and deploying robotics applications for various industries.

## Satellite

### AWS Ground Station

**Definition:** Service for controlling satellites and ingesting satellite data.
**Key Facts:** Global network of ground stations; integrates with AWS services.
**Use Case:** Ingesting and processing satellite data for various applications.

## Security, Identity, and Compliance

### Amazon Cognito

**Definition:** Identity management service that enables developers to add user sign-up, sign-in, and access control to web and mobile apps.
**Key Facts:** User pools and identity federation; supports multi-factor authentication.
**Use Case:** Adding user authentication and access control to applications.

### AWS Artifact

**Definition:** On-demand access to AWS compliance reports.
**Key Facts:** Provides compliance documentation for AWS services.
**Use Case:** Accessing compliance reports for auditing and regulatory purposes.

### AWS Certificate Manager

**Definition:** Service that lets you easily provision, manage, and deploy public and private SSL/TLS certificates for use with AWS services.
**Key Facts:** Automated certificate renewal; supports HTTPS for web applications.
**Use Case:** Securing web applications with SSL/TLS certificates.

### AWS CloudHSM

**Definition:** Cloud-based hardware security module (HSM) for generating and storing cryptographic keys.
**Key Facts:** FIPS 140-2 compliant; integrates with other AWS services.
**Use Case:** Protecting sensitive data and cryptographic operations.

### AWS Directory Service

**Definition:** Managed Microsoft AD in the AWS Cloud.
**Key Facts:** Integrates with AD-aware workloads; supports single sign-on (SSO).
**Use Case:** Integrating AWS resources with existing Active Directory environments.

### AWS Firewall Manager

**Definition:** Centralized management of AWS WAF rules across multiple accounts and resources.

**Key Facts:** 
- Automates firewall rule management
- Integrates with AWS Organizations.

**Use Case:** Implementing consistent firewall rules across an organization's AWS environment.

### Amazon GuardDuty

**Definition:** A threat detection service that continuously monitors for malicious activity.

**Key Facts:** 
- Uses machine learning, anomaly detection, and integrated threat intelligence.

**Use Case:** Detecting unexpected and potentially unauthorized activity in AWS accounts.

### AWS IAM Identity Center (AWS Single Sign-On)

**Definition:** Centrally manage single sign-on (SSO) access to multiple AWS accounts and business applications.

**Key Facts:** 
- Integrates with existing identity sources
- Supports SAML 2.0.

**Use Case:** Streamlining user access to multiple AWS accounts and applications.

### AWS Identity and Access Management (IAM)

**Definition:** Manages access to AWS services and resources.

**Key Facts:** 
- Supports identity federation
- Fine-grained access controls.

**Use Case:** Controlling user and group access to AWS resources.

### Amazon Inspector

**Definition:** Automated security assessment service to improve the security and compliance of applications.

**Key Facts:** 
- Assesses applications for vulnerabilities and deviations from best practices.

**Use Case:** Running automated security assessments on EC2 instances.

### AWS Key Management Service (AWS KMS)

**Definition:** Managed service to create and control cryptographic keys.

**Key Facts:** 
- Integrates with other AWS services
- Supports key rotation and management.

**Use Case:** Encrypting data stored in S3 buckets using managed keys.

### Amazon Macie

**Definition:** Machine learning-powered security service to discover, classify, and protect sensitive data.

**Key Facts:** 
- Automatically identifies and classifies sensitive data in AWS
- Supports GDPR compliance.

**Use Case:** Protecting sensitive customer data stored in S3.

### AWS Network Firewall

**Definition:** Managed firewall service for VPC.

**Key Facts:** 
- Provides flexible rules for traffic inspection, intrusion detection, and prevention.

**Use Case:** Implementing network-level security controls for inbound and outbound traffic in a VPC.

### AWS Resource Access Manager (AWS RAM)

**Definition:** Service to share AWS resources across accounts.

**Key Facts:** 
- Supports sharing of Subnets, Transit Gateways, etc.
- Integrates with AWS Organizations.

**Use Case:** Sharing Subnets with other AWS accounts within an organization.

### AWS Secrets Manager

**Definition:** Manages, retrieves, and rotates database credentials, API keys, and other secrets.

**Key Facts:** 
- Integrates with RDS, Redshift, and DocumentDB
- Supports secret rotation.

**Use Case:** Managing database credentials securely and automating their rotation.

### AWS Security Hub

**Definition:** Comprehensive view of security alerts and security posture across AWS accounts.

**Key Facts:** 
- Aggregates security findings from AWS services and partner tools.
**Use Case:** Centralizing and prioritizing security alerts and compliance status.

### AWS Shield

**Definition:** Managed Distributed Denial of Service (DDoS) protection service.
**Key Facts:** 
- AWS Shield Standard and AWS Shield Advanced options
- Integrates with CloudFront and Route 53.
**Use Case:** Protecting websites and applications against DDoS attacks.

### AWS WAF

**Definition:** Web application firewall that helps protect web applications from common web exploits.
**Key Facts:** 
- Offers rules to control bot traffic and block common attack patterns.
**Use Case:** Protecting a web application from SQL injection and Cross-Site Scripting (XSS) attacks.

## Serverless Services

### AWS AppSync

**Definition:** A managed service that uses GraphQL to make it easy to build collaborative mobile and web applications.
**Key Facts:** 
- Real-time data synchronization
- Offline data access.
**Use Case:** Building a real-time chat application that syncs across devices.

### AWS Fargate

**Definition:** A serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS).
**Key Facts:** 
- Eliminates the need to manage servers
- Scales containers.
**Use Case:** Running containerized applications without managing underlying infrastructure.

### AWS Lambda

**Definition:** A compute service that lets you run code without provisioning or managing servers.
**Key Facts:** 
- Automatic scaling
- Pay only for the compute time you consume.
**Use Case:** Automatically resizing images uploaded to S3.

## Storage Services

### AWS Backup

**Definition:** A centralized backup service that makes it easier to manage and automate backups across AWS services.
**Key Facts:** 
- Supports EBS, RDS, DynamoDB, EFS, and Storage Gateway.
**Use Case:** Automating and centralizing backup of AWS cloud resources.

### Amazon Elastic Block Store (Amazon EBS)

**Definition:** Provides block-level storage volumes for use with EC2 instances.
**Key Facts:** 
- High-performance volumes
- Snapshots for backup.
**Use Case:** Providing persistent block storage for an EC2 instance running a database.

### Amazon Elastic File System (Amazon EFS)

**Definition:** A scalable, elastic, cloud-native file system for Linux-based workloads.
**Key Facts:** 
- Can be used with AWS Cloud services and on-premises resources
- Scales automatically.
**Use Case:** Storing and sharing files across multiple EC2 instances.

### Amazon FSx

**Definition:** Provides fully managed third-party file systems with native compatibility and feature sets.
**Key Facts:** 
- Includes FSx for Windows File Server and FSx for Lustre.
**Use Case:** Running a high-performance computing (HPC) workload that requires fast data processing.

### Amazon S3

**Definition:** Object storage built to store and retrieve any amount of data from anywhere.
**Key Facts:** 
- Scalable
- Data availability
- Secure
- Supports web-based applications.
**Use Case:** Hosting static website content and media files.

### Amazon S3 Glacier

**Definition:** A secure, durable, and low-cost storage service for data archiving and long-term backup.
**Key Facts:** 
- Offers retrieval options from minutes to hours
- Highly durable.
**Use Case:** Archiving old but important data at low cost.

### AWS Storage Gateway

**Definition:** A hybrid cloud storage service that provides on-premises access to virtually unlimited cloud storage.
**Key Facts:** 
- Supports file, volume, and tape storage interfaces
- Integrates with S3.
**Use Case:** External file transfer
