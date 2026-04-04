# AWS Certified Cloud Practitioner (CLF-C02) Revision Sheet

Based on the official AWS exam guide and linked reference pages:

- https://docs.aws.amazon.com/aws-certification/latest/cloud-practitioner-02/cloud-practitioner-02.html
- https://docs.aws.amazon.com/aws-certification/latest/cloud-practitioner-02/clf-technologies-concepts.html
- https://docs.aws.amazon.com/aws-certification/latest/cloud-practitioner-02/clf-02-in-scope-services.html

## 1. Exam Snapshot

- Exam: AWS Certified Cloud Practitioner (CLF-C02)
- Scored questions: 50
- Unscored questions: 15
- Passing score: 700 / 1000

### Domain Weights

- Domain 1: Cloud Concepts = 24%
- Domain 2: Security and Compliance = 30%
- Domain 3: Cloud Technology and Services = 34%
- Domain 4: Billing, Pricing, and Support = 12%

## 2. Official Domain Checklist

### Domain 1: Cloud Concepts

- 1.1 Define the benefits of the AWS Cloud
- 1.2 Identify design principles of the AWS Cloud
- 1.3 Understand the benefits of and strategies for migration to the AWS Cloud
- 1.4 Understand concepts of cloud economics

### Domain 2: Security and Compliance

- 2.1 Understand the AWS shared responsibility model
- 2.2 Understand AWS Cloud security, governance, and compliance concepts
- 2.3 Identify AWS access management capabilities
- 2.4 Identify components and resources for security

### Domain 3: Cloud Technology and Services

- 3.1 Define methods of deploying and operating in the AWS Cloud
- 3.2 Define the AWS global infrastructure
- 3.3 Identify AWS compute services
- 3.4 Identify AWS database services
- 3.5 Identify AWS network services
- 3.6 Identify AWS storage services
- 3.7 Identify AWS AI/ML services and analytics services
- 3.8 Identify services from other in-scope AWS service categories

### Domain 4: Billing, Pricing, and Support

- 4.1 Compare AWS pricing models
- 4.2 Understand resources for billing, budget, and cost management
- 4.3 Identify AWS technical resources and AWS Support options

## 3. Technologies and Concepts AWS Explicitly Calls Out

- APIs
- Benefits of migrating to the AWS Cloud
- AWS Cloud Adoption Framework (AWS CAF)
- AWS Compliance
- Compute
- Cost management
- Databases
- Amazon EC2 purchasing options: On-Demand, Reserved Instances, Spot
- AWS global infrastructure: Regions, Availability Zones
- Infrastructure as code (IaC)
- AWS Knowledge Center
- Machine learning
- Management and governance
- Migration and data transfer
- Network services
- AWS Partner Network (APN)
- AWS Prescriptive Guidance
- AWS Pricing Calculator
- AWS Professional Services
- AWS re:Post
- AWS SDKs
- Security
- AWS Security Blog
- AWS shared responsibility model
- AWS solutions architects
- Storage
- AWS Support Center
- AWS Support plans
- AWS Well-Architected Framework

## 4. High-Yield Revision Notes

### Cloud Benefits

- Trade upfront cost for variable cost
- Benefit from massive economies of scale
- Stop guessing capacity
- Increase speed and agility
- Go global in minutes

### Shared Responsibility Model

- AWS secures the cloud: hardware, software, networking, facilities
- Customer secures what they put in the cloud: data, identities, configuration, guest OS on EC2

### Global Infrastructure

- Region: Geographic area
- Availability Zone: Separate data-center grouping inside a Region
- Edge location: Used for content delivery and low latency

### Pricing Models

- On-Demand: Pay for usage with no long commitment
- Reserved / Savings-style commitment: Lower cost for predictable usage
- Spot: Lowest cost for interruptible spare capacity
- Free Tier: Limited free usage for learning and trials

### Common Comparisons

- EC2: Virtual server you manage
- Lambda: Run code without managing servers
- S3: Object storage
- EBS: Block storage for EC2
- EFS: Shared file storage
- RDS: Managed relational database
- DynamoDB: Managed NoSQL database
- CloudWatch: Metrics, logs, alarms
- CloudTrail: API and account activity history
- IAM: Permissions and access control
- Shield: DDoS protection
- WAF: Filters malicious web traffic

## 5. In-Scope AWS Services With Short Descriptions

### Analytics

- Amazon Athena: Query data in Amazon S3 using SQL.
- Amazon EMR: Managed big data platform for frameworks like Hadoop and Spark.
- AWS Glue: Managed data integration and ETL service.
- Amazon Kinesis: Real-time data streaming and processing service.
- Amazon OpenSearch Service: Managed search, log analytics, and observability service.
- Amazon QuickSight: Cloud business intelligence and dashboard service.
- Amazon Redshift: Managed cloud data warehouse for analytics.

### Application Integration

- Amazon EventBridge: Serverless event bus for connecting applications and services.
- Amazon Simple Notification Service (Amazon SNS): Pub/sub messaging and notifications.
- Amazon Simple Queue Service (Amazon SQS): Managed message queue for decoupling applications.
- AWS Step Functions: Workflow orchestration service for coordinating tasks and services.

### Business Applications

- Amazon Connect: Cloud contact center service.
- Amazon Simple Email Service (Amazon SES): Scalable email sending and receiving service.

### Cloud Financial Management

- AWS Budgets: Set custom cost and usage budgets with alerts.
- AWS Cost and Usage Reports: Detailed raw billing and usage reports.
- AWS Cost Explorer: Visualize and analyze AWS costs and usage.
- AWS Marketplace: Catalog for buying third-party software and services.

### Compute

- AWS Batch: Managed batch job scheduling and execution service.
- Amazon EC2: Resizable virtual servers in the cloud.
- AWS Elastic Beanstalk: Platform service for deploying and scaling applications.
- Amazon Lightsail: Simplified virtual private server service.
- AWS Outposts: AWS infrastructure and services delivered on premises.

### Containers

- Amazon Elastic Container Registry (Amazon ECR): Managed container image registry.
- Amazon Elastic Container Service (Amazon ECS): Managed container orchestration service.
- Amazon Elastic Kubernetes Service (Amazon EKS): Managed Kubernetes service.

### Customer Enablement

- AWS Support: Technical support plans and guidance from AWS.

### Database

- Amazon Aurora: High-performance managed relational database compatible with MySQL and PostgreSQL.
- Amazon DocumentDB: Managed document database with MongoDB compatibility.
- Amazon DynamoDB: Fully managed NoSQL key-value and document database.
- Amazon ElastiCache: Managed in-memory caching service.
- Amazon Neptune: Managed graph database service.
- Amazon RDS: Managed relational database service.

### Developer Tools

- AWS CLI: Command line tool for managing AWS services.
- AWS CodeBuild: Managed build and test service.
- AWS CodePipeline: Continuous delivery orchestration service.
- AWS X-Ray: Distributed tracing and application analysis service.

### End User Computing

- Amazon AppStream 2.0: Stream desktop applications to users.
- Amazon WorkSpaces: Managed virtual desktop service.
- Amazon WorkSpaces Secure Browser: Managed secure browser for web-based workloads.

### Frontend Web and Mobile

- AWS Amplify: Tools and hosting for building full-stack web and mobile apps.
- AWS AppSync: Managed GraphQL API service with real-time features.

### Internet of Things (IoT)

- AWS IoT Core: Connect and manage IoT devices securely at scale.

### Machine Learning

- Amazon Comprehend: Natural language processing service for text insights.
- Amazon Kendra: Intelligent enterprise search service.
- Amazon Lex: Build conversational chatbots and voice bots.
- Amazon Polly: Convert text to lifelike speech.
- Amazon Q: Generative AI assistant for business and AWS use cases.
- Amazon Rekognition: Image and video analysis service.
- Amazon SageMaker AI: Build, train, and deploy machine learning models.
- Amazon Textract: Extract text and data from documents.
- Amazon Transcribe: Speech-to-text service.
- Amazon Translate: Neural machine translation service.

### Management and Governance

- AWS Auto Scaling: Automatically adjust capacity to match demand.
- AWS CloudFormation: Define and provision infrastructure as code.
- AWS CloudTrail: Record AWS API activity for auditing.
- Amazon CloudWatch: Monitor metrics, logs, and alarms.
- AWS Compute Optimizer: Recommends better-sized AWS resources.
- AWS Config: Track resource configuration and compliance status.
- AWS Control Tower: Set up and govern a multi-account AWS environment.
- AWS Health Dashboard: View AWS service and account health events.
- AWS License Manager: Manage software licenses across AWS resources.
- AWS Management Console: Web interface for AWS management.
- AWS Organizations: Centrally manage multiple AWS accounts.
- AWS Service Catalog: Govern approved IT services for organizations.
- Service Quotas: View and manage AWS service limits.
- AWS Systems Manager: Operational management for AWS resources.
- AWS Trusted Advisor: Recommendations for cost, security, performance, and resilience.
- AWS Well-Architected Tool: Review workloads against AWS best practices.

### Migration and Transfer

- AWS Application Discovery Service: Discover on-premises workloads for migration planning.
- AWS Application Migration Service: Lift-and-shift server migration to AWS.
- AWS Database Migration Service (AWS DMS): Migrate databases to AWS with minimal downtime.
- Migration Evaluator: Build data-driven migration business cases.
- AWS Migration Hub: Track and manage migration progress across tools.
- AWS Schema Conversion Tool (AWS SCT): Convert database schemas to new engines.
- AWS Snow Family: Physical devices for edge computing and large-scale data transfer.

### Networking and Content Delivery

- Amazon API Gateway: Create, publish, and manage APIs.
- Amazon CloudFront: Content delivery network for low-latency global delivery.
- AWS Direct Connect: Dedicated private network connection to AWS.
- AWS Global Accelerator: Improve global application availability and performance.
- AWS PrivateLink: Private connectivity to services without public internet exposure.
- Amazon Route 53: DNS and domain routing service.
- AWS Transit Gateway: Central hub for connecting VPCs and networks.
- Amazon VPC: Isolated virtual network in AWS.
- AWS VPN: Secure encrypted network connectivity to AWS.
- AWS Site-to-Site VPN: Connect on-premises networks to AWS over encrypted tunnels.
- AWS Client VPN: Managed VPN for remote user access.

### Security, Identity, and Compliance

- AWS Artifact: On-demand access to AWS compliance reports and agreements.
- AWS Audit Manager: Helps automate evidence collection for audits.
- AWS Certificate Manager (ACM): Provision and manage SSL/TLS certificates.
- AWS CloudHSM: Dedicated hardware security modules for key operations.
- Amazon Cognito: User sign-up, sign-in, and app authentication service.
- Amazon Detective: Investigate and analyze security findings.
- AWS Directory Service: Managed Microsoft Active Directory and directory options.
- AWS Firewall Manager: Centrally manage firewall and security rules.
- Amazon GuardDuty: Threat detection and continuous security monitoring.
- AWS Identity and Access Management (IAM): Manage users, roles, and permissions.
- AWS IAM Identity Center: Centralized workforce access to AWS accounts and apps.
- Amazon Inspector: Automated vulnerability and exposure scanning.
- AWS Key Management Service (AWS KMS): Managed encryption key service.
- Amazon Macie: Discover and protect sensitive data in S3.
- AWS Resource Access Manager (AWS RAM): Share AWS resources across accounts.
- AWS Secrets Manager: Store and rotate secrets securely.
- AWS Security Hub: Centralize and prioritize security findings.
- AWS Shield: Managed DDoS protection.
- AWS WAF: Filter malicious traffic to web applications.

### Serverless

- AWS Fargate: Serverless compute for containers.
- AWS Lambda: Run code in response to events without managing servers.

### Storage

- AWS Backup: Centralized backup management across AWS services.
- Amazon Elastic Block Store (Amazon EBS): Persistent block storage for EC2.
- Amazon Elastic File System (Amazon EFS): Managed shared file storage for Linux workloads.
- AWS Elastic Disaster Recovery: Disaster recovery service for rapid recovery to AWS.
- Amazon FSx: Managed file systems for specialized workloads.
- Amazon S3: Durable, scalable object storage.
- Amazon S3 Glacier: Low-cost archival storage.
- AWS Storage Gateway: Hybrid storage service linking on-premises environments with AWS.

## 6. Last-Minute Memorization List

- IAM = who can do what
- CloudTrail = who did what
- CloudWatch = what is happening now
- S3 = object storage
- EBS = block storage
- EFS = shared file storage
- EC2 = virtual machine
- Lambda = serverless code
- RDS = relational database
- DynamoDB = NoSQL database
- VPC = private network
- Route 53 = DNS
- CloudFront = CDN
- SNS = fan-out notifications
- SQS = queued messages

## 7. Exam Strategy

- If the question asks for the least operational effort, prefer managed or serverless services.
- If it asks for elasticity, think Auto Scaling, serverless, or managed scaling.
- If it asks for audit logs, think CloudTrail.
- If it asks for monitoring, metrics, or alarms, think CloudWatch.
- If it asks for permissions, think IAM or IAM Identity Center.
- If it asks for DDoS protection, think Shield.
- If it asks for web request filtering, think WAF.
- If it asks for low-cost archive, think S3 Glacier.
- If it asks for global content delivery, think CloudFront.
