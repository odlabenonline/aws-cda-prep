# AWS Certified Developer Associate Prep (DVA-C02)

This repository provides a structured 8-week approach for preparing to write the **AWS Certified Developer - Associate** exam in **2026**.

> Before booking the exam, verify the latest AWS exam guide and topic weighting to confirm that **DVA-C02** is still the active version.

## Goal

Build the knowledge and hands-on confidence to:

- understand core AWS developer services
- design and secure cloud-native applications on AWS
- deploy, test, monitor, and troubleshoot serverless and container-based workloads
- pass the AWS Certified Developer - Associate exam

## Recommended Study Approach

Use the same weekly rhythm throughout your preparation:

1. **Learn** the concepts for the week
2. **Build** at least one small hands-on lab
3. **Review** notes, flashcards, and weak areas
4. **Test** yourself with topic-based questions
5. **Reflect** on gaps and revisit unclear services

### Weekly Time Commitment

- **Light plan:** 6-8 hours per week
- **Balanced plan:** 8-12 hours per week
- **Intensive plan:** 12+ hours per week

## 8-Week Preparation Roadmap

### Week 1: AWS Fundamentals for Developers

Focus areas:

- AWS global infrastructure
- IAM users, roles, policies, and least privilege
- AWS CLI, SDKs, and authentication basics
- core services: EC2, S3, CloudWatch, and CloudTrail

Hands-on goals:

- configure the AWS CLI
- create and secure an S3 bucket
- assume an IAM role and call AWS services programmatically

### Week 2: Application Development with AWS Services

Focus areas:

- Lambda fundamentals
- API Gateway integrations
- DynamoDB basics
- SQS, SNS, and EventBridge messaging patterns

Hands-on goals:

- build a small serverless API with Lambda + API Gateway
- store application data in DynamoDB
- publish and consume messages with SQS or SNS

### Week 3: Storage, Databases, and Caching

Focus areas:

- DynamoDB partition keys, sort keys, indexes, and streams
- S3 storage classes, lifecycle rules, and event notifications
- ElastiCache basics and caching patterns
- RDS connectivity concepts relevant to developers

Hands-on goals:

- model a DynamoDB table for a simple app
- trigger a Lambda function from an S3 event
- compare caching vs direct database reads in a sample workload

### Week 4: Security and Access Control

Focus areas:

- IAM policy evaluation logic
- encryption at rest and in transit
- Secrets Manager and Systems Manager Parameter Store
- Cognito basics for application authentication

Hands-on goals:

- store application secrets securely
- add fine-grained permissions to a Lambda execution role
- protect an API with an authentication mechanism

### Week 5: Deployment and CI/CD

Focus areas:

- CloudFormation and AWS SAM basics
- deployment strategies for Lambda and APIs
- CodeCommit, CodeBuild, CodeDeploy, and CodePipeline concepts
- environment configuration and versioning

Hands-on goals:

- package and deploy a serverless application
- create a simple CI/CD flow for build and deploy steps
- practice rollback and safe release concepts

### Week 6: Observability, Debugging, and Troubleshooting

Focus areas:

- CloudWatch logs, metrics, dashboards, and alarms
- X-Ray tracing concepts
- debugging Lambda timeouts, retries, and permissions
- failure handling for asynchronous and event-driven systems

Hands-on goals:

- inspect logs to diagnose a broken Lambda function
- create alarms for latency and error conditions
- trace a request across API Gateway, Lambda, and DynamoDB

### Week 7: Optimization and Architecture Review

Focus areas:

- performance optimization
- cost-aware design decisions
- resiliency and fault tolerance
- choosing between AWS services for a given scenario

Hands-on goals:

- review trade-offs between Lambda, ECS, and EC2 for sample workloads
- optimize a DynamoDB or Lambda-based solution
- document recovery and retry strategies for failures

### Week 8: Final Review and Exam Readiness

Focus areas:

- revisit weak domains
- complete timed practice exams
- memorize common AWS service patterns and limits
- refine elimination strategies for scenario questions

Hands-on goals:

- complete at least 2 full practice exams
- review every missed question by topic
- create a final summary sheet for last-minute revision

## Core Exam Domains to Prioritize

Although AWS may adjust the guide over time, your study should strongly cover:

- **Development with AWS Services**
- **Security**
- **Deployment**
- **Troubleshooting and Optimization**

## Suggested Hands-On Project Path

To make preparation practical, build one small project that evolves over time:

1. Create a serverless REST API
2. Store data in DynamoDB
3. Add authentication and authorization
4. Publish events with SNS, SQS, or EventBridge
5. Add monitoring, alarms, and tracing
6. Deploy through infrastructure as code

This gives repeated exposure to the services and patterns most likely to appear on the exam.

## Study Materials Checklist

- AWS Skill Builder content
- official AWS exam guide
- AWS documentation for core services
- whitepapers and architecture best practices
- hands-on labs in your own AWS account
- topic-based quizzes and full-length practice exams

## Exam Strategy

During the exam:

- identify the AWS service the question is really testing
- eliminate answers that are operationally heavy when a managed service fits better
- prefer secure, scalable, and least-privilege solutions
- watch for keywords about retries, idempotency, decoupling, and monitoring
- flag hard questions and return after answering easier ones

## Success Criteria

You are likely ready to sit the exam when you can:

- explain why one AWS service is a better fit than another in scenario questions
- deploy and debug a basic serverless application without step-by-step guidance
- score consistently well on practice questions under time pressure
- identify secure and cost-conscious implementation choices
