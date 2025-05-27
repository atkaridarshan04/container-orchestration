# 🚀 Automated App Deployment using ECR, ECS (Fargate) & CodePipeline

## Project Overview

This project demonstrates how to **fully automate the deployment** of a containerized **Application** on **Amazon ECS (Fargate)** using **Amazon ECR** for container image storage, and **AWS CodePipeline** with **CodeBuild** for CI/CD.  
The setup ensures that every code change pushed to GitHub triggers a pipeline that builds a Docker image, pushes it to ECR, and seamlessly deploys it to ECS via an Application Load Balancer (ALB).

This project is part of [AWS-Cloud-Labs](https://github.com/atkaridarshan04/AWS-Cloud-Lab) repo, for complete step by step implementation guide, have a look [ecs-cicd-automation](https://github.com/atkaridarshan04/AWS-Cloud-Lab/tree/main/ecs-cicd-automation).
