# Project 22: S3 Log Archive with Lifecycle

## Goal
Reduce AWS storage costs using S3 lifecycle management.

## Tasks Completed
1. Created an S3 bucket.
2. Uploaded Ubuntu system logs to S3.
3. Configured lifecycle expiration.
4. Enabled automatic deletion after 30 days.

## AWS Configuration
- Service: Amazon S3
- Region: ap-south-1
- Bucket: project22-s3-log-archive-590507089733-1795581285
- Folder: logs/
- Lifecycle Rule: Project22-Log-Expiration
- Expiration: 30 days

## Verification
Lifecycle configuration verified using AWS CLI.
