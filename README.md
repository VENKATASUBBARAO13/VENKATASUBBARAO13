<h1 align="center">Hi 👋, I'm Venkata Subbarao</h1>

<h3 align="center">
  ☁️ AWS Cloud Engineer | Cloud Computing | DevOps Enthusiast
</h3>

<p align="center">
  Building and deploying AWS infrastructure, cloud applications, networking architectures,
  monitoring solutions, automation workflows, and secure scalable environments through
  hands-on projects.
</p>

<p align="center">
  <a href="https://venkata-subbarao-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/🌐_Portfolio-Visit_Website-2563EB?style=for-the-badge" />
  </a>
  <a href="https://www.linkedin.com/in/ventrapragada-venkata-subbarao">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:venkatasubbarao1305@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 👨‍💻 About Me

🎓 Computer Science Engineering Graduate | Class of 2026

☁️ Aspiring AWS Cloud Engineer focused on cloud infrastructure, networking, monitoring, security, automation, and scalable application deployment.

🔭 Built and deployed multiple hands-on AWS projects covering application hosting, three-tier architecture, infrastructure monitoring, alerting, log automation, and cloud networking.

🌱 Currently strengthening my knowledge in:

- AWS Cloud Architecture
- Linux & Networking
- Infrastructure Monitoring & Observability
- Cloud Security & IAM
- Automation & Event-Driven Services
- DevOps Fundamentals
- Docker

💡 Interested in:

- AWS Cloud Engineer
- Cloud Support Engineer
- Junior DevOps Engineer

⚡ I enjoy learning by building real-world projects, troubleshooting infrastructure, and understanding how cloud technologies work together.

---

## ☁️ AWS & Cloud Skills

### AWS Services

<p>
  <img src="https://skillicons.dev/icons?i=aws" />
</p>

- Amazon EC2
- Amazon VPC
- Amazon S3
- AWS IAM
- Amazon RDS
- Elastic Load Balancing (ALB)
- Auto Scaling Groups
- Amazon CloudWatch
- Amazon Route 53
- AWS Certificate Manager (ACM)
- AWS WAF
- AWS Lambda
- Amazon EventBridge
- NAT Gateway
- Internet Gateway
- AMIs

### Networking & Infrastructure

- VPC Design
- CIDR & Subnetting
- Public & Private Subnets
- Multi-AZ Architecture
- Route Tables
- Internet Gateway
- NAT Gateway
- Security Groups
- Bastion Hosts
- Application Load Balancers
- Target Groups
- Health Checks
- Path-Based Routing
- Host-Based Routing
- Weighted Target Groups
- Sticky Sessions
- Cross-AZ Load Balancing
- Auto Scaling
- Route 53 DNS

### Monitoring & Observability

- Amazon CloudWatch
- CloudWatch Metrics
- CloudWatch Logs
- CloudWatch Alarms
- Prometheus
- Grafana
- Node Exporter
- Infrastructure Monitoring
- Alerting
- PagerDuty
- Incident Testing
- Metrics Visualization

### Automation & Serverless

- AWS Lambda
- Amazon EventBridge
- Boto3
- CloudWatch Logs
- S3 Log Archival
- Event-Driven Automation
- Serverless Automation

### Programming & Development

<p>
  <img src="https://skillicons.dev/icons?i=python,mysql,bash,linux" />
</p>

- Python
- SQL & MySQL
- Linux
- Bash / Shell Scripting
- REST APIs
- Flask
- Django

### Tools & Technologies

<p>
  <img src="https://skillicons.dev/icons?i=git,github,docker,vscode" />
</p>

- Git & GitHub
- Docker
- VS Code
- AWS Management Console

---

# 🚀 Featured AWS Projects

## 🛒 1. AWS E-Commerce Application Deployment

A hands-on AWS deployment project focused on hosting, networking, security, HTTPS, load balancing, database connectivity, and production-style application deployment.

### AWS Technologies

`EC2` `VPC` `RDS` `ALB` `S3` `IAM` `Route 53` `ACM`

`AWS WAF` `CloudWatch` `Lambda` `EventBridge` `Security Groups`

### Key Work

- Deployed an e-commerce application on AWS infrastructure.
- Configured EC2 instances for application hosting.
- Designed AWS networking using VPC and subnets.
- Configured Application Load Balancer and Target Groups.
- Connected the application to Amazon RDS MySQL.
- Configured Route 53 for custom domain access.
- Enabled HTTPS using AWS Certificate Manager.
- Configured AWS WAF for web application protection.
- Configured IAM roles and permissions.
- Used Amazon S3 for cloud storage.
- Used CloudWatch for infrastructure monitoring.
- Worked with Lambda and EventBridge for automation.
- Troubleshot application, networking, and infrastructure issues.

### GitHub Repository

🔗 https://github.com/VENKATASUBBARAO13/AWS_PROJECT_FLIPKART_APPLICATION_WITH_RDS

---

## 📊 2. AWS EC2 Monitoring & Alerting Project

A hands-on infrastructure monitoring project using Prometheus, Grafana, Node Exporter, CloudWatch, Alertmanager, and PagerDuty.

### Technologies

`AWS EC2` `Prometheus` `Grafana` `Node Exporter`

`CloudWatch` `Alertmanager` `PagerDuty`

### Architecture

```text
                         AWS Cloud / VPC

 ┌─────────────────────┐          ┌──────────────────────────────┐
 │    Monitored EC2    │          │       Monitoring EC2         │
 │                     │          │                              │
 │ Linux Server        │          │ Prometheus :9090             │
 │       │             │          │      │                       │
 │ Node Exporter :9100 │─────────▶│      ├── Alert Rules         │
 │                     │ /metrics  │      │        │              │
 └─────────────────────┘          │      ▼        ▼              │
                                  │ Alertmanager  Grafana :3000  │
                                  │      │        │      │       │
                                  └──────┼────────┼──────┼───────┘
                                         │        │      │
                                         ▼        │      ▼
                                     PagerDuty    │  CloudWatch
                                                  │
                                                  ▼
                                            AWS Metrics
```

### Key Work

- Installed and configured Node Exporter.
- Configured Prometheus scraping.
- Monitored Linux EC2 infrastructure.
- Created Prometheus alert rules.
- Configured `InstanceDown` alert.
- Configured high CPU and high disk alerts.
- Built Grafana monitoring dashboards.
- Added Prometheus as a Grafana data source.
- Added CloudWatch as an additional data source.
- Tested infrastructure metrics.
- Simulated infrastructure failure by stopping Node Exporter.
- Verified target health changes in Prometheus.
- Triggered PagerDuty incidents.
- Verified alert resolution and recovery.
- Practiced monitoring troubleshooting and incident handling.

### GitHub Repository

🔗 https://github.com/VENKATASUBBARAO13/AWS-EC2-Monitoring-and-Alerting-Project

---

## 🏗️ 3. AWS Three-Tier Web Application Deployment

A hands-on three-tier AWS architecture demonstrating separation of the presentation, application, and database layers.

### Architecture

```text
                         Users
                           │
                           ▼
                   Route 53 / Domain
                           │
                           ▼
              Application Load Balancer
                           │
              ┌────────────┴────────────┐
              │                         │
              ▼                         ▼
       Frontend EC2                Backend EC2
       Presentation               Application
       Layer                      Layer
                                      │
                                      ▼
                               Amazon RDS MySQL
                                  Data Layer
```

### AWS Technologies

`VPC` `EC2` `RDS` `ALB` `Auto Scaling`

`Route 53` `IAM` `Security Groups` `NAT Gateway`

### Key Work

- Designed a three-tier AWS architecture.
- Created VPC networking and subnet architecture.
- Configured public and private subnets.
- Deployed frontend and backend components on EC2.
- Configured Application Load Balancers.
- Configured Target Groups and health checks.
- Connected backend application to Amazon RDS MySQL.
- Configured Route 53 custom domain access.
- Applied Security Groups between application layers.
- Practiced scalable and highly available architecture concepts.
- Tested application CRUD operations.
- Validated frontend, backend, ALB, and RDS connectivity.

### GitHub Repository

🔗 https://github.com/VENKATASUBBARAO13/AWS-Three-Tier-Web-Application-Project

---

## 📦 4. AWS EC2 Log Automation & S3 Archival Project

A serverless AWS log automation project that collects EC2 logs through CloudWatch and automates log processing and archival using Lambda, EventBridge, and Amazon S3.

### Architecture

```text
Amazon EC2
    │
    ▼
CloudWatch Agent
    │
    ▼
CloudWatch Logs
    │
    ▼
AWS Lambda
    ▲
    │
EventBridge
    │
    ▼
Amazon S3
    │
    ▼
Log Archive
```

### AWS Technologies

`EC2` `CloudWatch` `CloudWatch Logs` `Lambda`

`EventBridge` `S3` `IAM` `Python` `Boto3`

### Key Work

- Created an EC2-based log collection workflow.
- Installed and configured the CloudWatch Agent.
- Collected EC2 log files into CloudWatch Logs.
- Created CloudWatch Log Groups and Log Streams.
- Configured IAM permissions for AWS services.
- Created an S3 bucket for centralized log archival.
- Configured S3 bucket policies.
- Used Lambda for serverless log automation.
- Configured EventBridge for scheduled automation.
- Tested log processing and S3 archival.
- Verified uploaded and downloaded log files.
- Practiced event-driven cloud automation.

### GitHub Repository

🔗 https://github.com/VENKATASUBBARAO13/AWS-EC2-Log-Automation-and-S3-Archival-Project

---

# 🧰 DevOps & Cloud Hands-On Experience

### AWS Infrastructure

- EC2 provisioning and configuration
- VPC and subnet design
- Public and private networking
- CIDR and subnetting
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Bastion Host architecture
- Application Load Balancer
- Target Groups
- Health Checks
- Auto Scaling Groups
- Launch Templates
- AMIs
- Route 53
- ACM and HTTPS
- AWS WAF

### Monitoring & Observability

- CloudWatch
- CloudWatch Logs
- CloudWatch Metrics
- Prometheus
- Grafana
- Node Exporter
- Alert Rules
- Alertmanager
- PagerDuty
- Infrastructure Monitoring
- Incident Testing
- Troubleshooting

### Automation

- AWS Lambda
- EventBridge
- Boto3
- Serverless Automation
- Log Processing
- S3 Archival

### DevOps Fundamentals

- Linux administration
- Git & GitHub
- Docker fundamentals
- Application deployment
- Infrastructure troubleshooting
- Cloud security fundamentals
- IAM
- Automation fundamentals

---

# 📚 Certifications & Learning

- Microsoft Azure Fundamentals
- Microsoft Introduction to AI
- Google: Innovating With Google Cloud AI
- TCS iON Career Edge – Young Professional
- GeeksforGeeks Python Programming
- Tata Data Visualisation – Forage
- Tata GenAI Powered Data Analytics – Forage

---

# 🎯 Currently Working On

- Strengthening AWS core services and cloud architecture.
- Practicing Linux administration and networking.
- Building real-world AWS infrastructure projects.
- Improving monitoring and observability skills.
- Learning Docker and DevOps practices.
- Improving cloud security and IAM knowledge.
- Practicing infrastructure troubleshooting and automation.
- Preparing for AWS Cloud Engineer and Cloud Support Engineer roles.

---

# 📫 Connect With Me

<p>
  <a href="https://www.linkedin.com/in/ventrapragada-venkata-subbarao">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>

  <a href="https://venkata-subbarao-portfolio.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-Visit-2563EB?style=for-the-badge" />
  </a>

  <a href="mailto:venkatasubbarao1305@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

🐙 GitHub: https://github.com/VENKATASUBBARAO13

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=VENKATASUBBARAO13&label=Profile+Views&color=2563EB&style=for-the-badge" />
</p>

<h3 align="center">
  ☁️ Learning. Building. Deploying. Monitoring. Automating. Troubleshooting. Growing. 🚀
</h3>

<p align="center">
  ⭐ Thanks for visiting my GitHub profile! ⭐
</p>
