# Automated Cost Governance

## 🌟 Overview
**Scenario**<br/>
AWS accounts often have **unused or forgotten resources** like idle EC2 instances, unattached EBS volumes, outdated snapshots, or load balancers with no traffic. These resources **accumulate over time** and silently increase your monthly AWS bill.

In this project, you’ll **intentionally deploy a wasteful AWS environment** using a **CloudFormation template**, and then simulate the role of a Solutions Architect tasked with identifying and fixing these cost leaks. You’ll build a workflow that detects unused resources, recommends cleanup actions, and removes them safely with proper governance.

**Your Role**<br/>
As a **Solutions Architect focusing on cost optimization**, your goal is to **identify and eliminate unnecessary AWS costs** using enterprise-grade automation. You will use AWS native tools to:

* Deploy intentionally wasteful infrastructure with proper tagging for tracking.
* Implement multi-tier detection workflows (immediate, data-driven, advanced analytics).
* Build SSM automation documents with embedded Python cleanup logic and approval workflows.
* Create IAM-secured governance processes with role separation and audit trails.
* Apply S3 lifecycle policies for ongoing storage cost optimization.

## 🛠️ Services used
* **Amazon EC2**: Over-provisioned instances and unattached EBS volumes.
* **Amazon S3**: Static website hosting without lifecycle cost optimization.
* **AWS CloudFormation**: Infrastructure as Code for consistent wasteful deployment.
* **AWS Systems Manager (SSM)**: Automation documents with Python cleanup scripts and approval workflows.
* **AWS IAM**: Role-based access control for automation execution and approvals.
* **Amazon SNS**: Email notifications for approval requests and completion status.
* **AWS Cost Explorer**: Historical spend analysis and savings validation.
* **AWS Trusted Advisor**: Automated waste detection recommendations.

## ☁️ AWS Architecture

## &rarr; Final Result

<!-- ![alt text](design/igw.png) -->
