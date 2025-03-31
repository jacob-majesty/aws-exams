### **AWS Cloud Computing Cheat Sheet – Quick Learning Bullet Points**  

#### **1. Cloud Computing & Types**  
- **Cloud Computing**: On-demand access to computing resources over the internet.  
- **Types**:  
  - **IaaS** (Infrastructure as a Service) – Compute, storage, networking (e.g., AWS EC2).  
  - **PaaS** (Platform as a Service) – Managed runtime environments (e.g., AWS Elastic Beanstalk).  
  - **SaaS** (Software as a Service) – Fully managed applications (e.g., Gmail, Dropbox).  

#### **2. Shared Responsibility Model**  
- **AWS**: Secures the cloud infrastructure (hardware, networking, data centers).  
- **Customer**: Secures data, applications, OS configurations, and access management.  

#### **3. IAM (Identity and Access Management)**  
- **Users, Groups, Policies**:  
  - **Users** – Individual accounts.  
  - **Groups** – Collection of users with shared permissions.  
  - **Policies** – JSON documents defining access rules.  
  - **IAM Roles** – Temporary permissions for AWS services.  

#### **4. Compute Services**  
- **EC2 (Elastic Compute Cloud)** – Virtual servers with flexible configurations.  
- **EBS (Elastic Block Store)** – Persistent storage for EC2 instances.  
- **EFS (Elastic File System)** – Scalable shared storage for multiple instances.  
- **ELB (Elastic Load Balancer)** – Distributes traffic across instances.  
  - **ALB (Application Load Balancer)** – Layer 7 routing.  
  - **NLB (Network Load Balancer)** – Layer 4 performance.  
  - **ASG (Auto Scaling Group)** – Adjusts EC2 instances based on demand.  

#### **5. Storage & Data Transfer**  
- **S3 (Simple Storage Service)** – Object storage with high durability.  
  - Policies & Encryption: S3 bucket policies, IAM policies, SSE encryption options.  
- **AWS Snow Family** – Data transfer appliances for offline migrations.  
  - **Snowball Edge** – Storage & compute processing.  
  - **Storage Gateway** – Hybrid cloud storage integration.  

#### **6. Databases & Analytics**  
- **RDS** – Managed relational databases (MySQL, PostgreSQL, etc.).  
- **ElastiCache** – In-memory caching (Redis, Memcached).  
- **DynamoDB** – NoSQL key-value database.  
- **Redshift** – Data warehouse for analytics.  
- **EMR (Elastic MapReduce)** – Big data processing with Hadoop & Spark.  
- **Athena** – Query S3 data using SQL.  
- **DocumentDB** – Managed MongoDB-compatible NoSQL.  
- **Neptune** – Managed graph database.  
- **Timestream** – Time-series database.  
- **QLDB** – Immutable ledger database.  
- **Managed Blockchain** – Create & manage blockchain networks.  
- **Glue** – ETL service for data integration.  
- **DMS (Database Migration Service)** – Migrate databases to AWS.  

#### **7. Containers & Serverless**  
- **ECS (Elastic Container Service)** – Docker container orchestration.  
- **Fargate** – Serverless compute for containers.  
- **ECR (Elastic Container Registry)** – Docker image repository.  
- **Amazon EKS (Elastic Kubernetes Service)** – Managed Kubernetes.  
- **Lambda** – Serverless compute (event-driven).  
- **API Gateway** – Manage & secure APIs.  
- **Batch** – Process batch computing workloads.  
- **Lightsail** – Simple cloud hosting for small applications.  

#### **8. DevOps & Infrastructure as Code**  
- **CloudFormation** – Infrastructure as code (YAML/JSON).  
- **CDK (Cloud Development Kit)** – Programmatic IaC using TypeScript/Python.  
- **Elastic Beanstalk** – PaaS for deploying applications.  
- **CodeDeploy** – Automate deployments.  
- **CodeCommit** – Managed Git repository.  
- **CodeBuild** – Continuous integration.  
- **CodePipeline** – CI/CD workflow automation.  
- **CodeArtifact** – Managed package repository.  
- **SSM (AWS Systems Manager)** – Fleet management & automation.  

#### **9. Global Applications & Networking**  
- **Route 53** – Scalable DNS & domain management.  
- **CloudFront** – CDN for content delivery.  
- **S3 Transfer Acceleration** – Faster global S3 uploads.  
- **AWS Outposts** – Extend AWS infrastructure on-premises.  
- **AWS WaveLength** – Low-latency apps at telco edge.  
- **AWS Local Zones** – Deploy apps closer to users.  

#### **10. Messaging & Streaming**  
- **SQS (Simple Queue Service)** – Message queuing.  
- **SNS (Simple Notification Service)** – Push notifications.  
- **Kinesis** – Real-time data streaming.  
- **Amazon MQ** – Managed message broker service.  

#### **11. Monitoring & Logging**  
- **CloudWatch Metrics** – Collect & monitor AWS resource metrics.  
- **CloudWatch Logs** – Store & analyze logs.  
- **EventBridge** – Serverless event bus.  
- **CloudTrail** – Logs AWS API activity.  
- **X-Ray** – Distributed tracing for applications.  
- **CodeGuru** – AI-powered code review & performance insights.  
- **AWS Health** – Service status & operational health monitoring.  

#### **12. Networking & Security**  
- **VPC (Virtual Private Cloud)** – Isolated network for AWS resources.  
- **Subnets** – Public/private subnet separation.  
- **Internet Gateway** – Allows public internet access.  
- **NAT Gateway** – Enables outbound internet for private subnets.  
- **VPC Flow Logs** – Capture network traffic logs.  
- **VPC Peering** – Connect VPCs privately.  
- **VPC Endpoints** – Private connection to AWS services.  
- **PrivateLink** – Secure internal service access.  
- **Client VPN & Transit Gateway** – VPN & multi-VPC networking.  

#### **13. Security & Compliance**  
- **DDoS Protection**:  
  - **WAF (Web Application Firewall)** – Blocks malicious traffic.  
  - **AWS Shield** – DDoS protection.  
- **AWS Network Firewall** – Managed firewall service.  
- **Encryption & Key Management**:  
  - **KMS (Key Management Service)** – Manage encryption keys.  
  - **CloudHSM** – Hardware security module for encryption.  
- **Certificate & Secret Management**:  
  - **AWS Certificate Manager (ACM)** – Manage SSL/TLS certificates.  
  - **Secrets Manager** – Store & retrieve secrets securely.  
- **Security Monitoring**:  
  - **GuardDuty** – Threat detection & monitoring.  
  - **Inspector** – Automated security assessment.  
  - **Config** – Compliance tracking for AWS resources.  
  - **Macie** – Data security & sensitive data discovery.  
  - **Security Hub** – Centralized security compliance.  
- **IAM Access Analyzer** – Detects overly permissive policies.  

#### **14. AI & Machine Learning**  
- **Rekognition** – Image & video analysis.  
- **Transcribe** – Speech-to-text service.  
- **Polly** – Text-to-speech service.  
- **Lex** – Chatbot & conversational AI.  
- **Comprehend** – NLP (Natural Language Processing).  
- **SageMaker** – Build & deploy ML models.  
- **Kendra** – AI-powered enterprise search.  
- **Personalize** – Recommendation engine.  
- **Textract** – OCR & document analysis.  

#### **15. AWS Organizations & Cost Management**  
- **AWS Organizations** – Manage multiple AWS accounts.  
- **Consolidated Billing** – Unified billing for multiple accounts.  
- **AWS Control Tower** – Set up & govern multi-account AWS environments.  
- **AWS Service Catalog** – Manage approved AWS service configurations.  
- **Pricing Models** – On-demand, reserved, spot instances, savings plans.  
- **AWS Compute Optimizer** – Cost & performance recommendations.  
- **Billing & Costing Tools** – AWS Cost Explorer, Budgets, Trusted Advisor.  
- **Service Quotas** – Track AWS service limits.  
- **AWS Support Plans** – Basic, Developer, Business, Enterprise.  

---

