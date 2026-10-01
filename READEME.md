# Automated Cloud Data Migration & Backup Governance Strategy

## Project Description
This project implements a production-grade corporate storage architecture on AWS. It focuses on setting up an automated, secure data migration pipeline with multi-region disaster recovery (DR) capabilities and automated lifecycle rules to optimize enterprise storage costs.

## Technical Skills Used
* Amazon S3 & S3 Glacier
* AWS Backup
* Cross-Region Replication (CRR)
* Infrastructure Architecture

## Architecture Setup & Core Features
1. **Disaster Recovery:** Configured AWS S3 Cross-Region Replication between `us-east-1` (Source) and `eu-west-2` (Destination) to achieve high availability.
2. **Cost Optimization (FinOps):** Implemented S3 Lifecycle Policies to automatically transition data to Amazon S3 Glacier Flexible Retrieval after 30 days of inactivity.
3. **Backup Governance:** Integrated AWS Backup with a standard `Daily-35day-Retention` policy to centralize storage snapshots and secure compliance rules.
