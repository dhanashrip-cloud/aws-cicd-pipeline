# aws-cicd-pipeline
# AWS CI/CD Pipeline Project

## Architecture
GitHub → CodePipeline → CodeBuild → S3 (Live Website)

## AWS Services Used
- **CodePipeline** – Orchestrates the pipeline
- **CodeBuild** – Builds and tests the application
- **S3** – Hosts the static website
- **CloudWatch** – Monitors pipeline health
- **SNS** – Sends deployment notifications
- **IAM** – Manages secure permissions

## How It Works
1. Developer pushes code to GitHub
2. CodePipeline detects the change automatically
3. CodeBuild runs the buildspec.yml instructions
4. Built artifacts are deployed to S3
5. Website is live within minutes

## Live Demo
[Link to your S3 website URL here]
