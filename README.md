# ACTUAL-APP

DevOps Capstone Case Study – Fitness Tracker Application Deployment on AWS EKS
You are part of a DevOps Engineering team for a health and wellness organization. The company plans to modernize its Fitness Tracker application and deploy it using cloud-native technologies on AWS. Your responsibility is to transform the existing application into a production-ready deployment using enterprise DevOps practices.
Application Repository
https://github.com/Msocial123/Fitness_Tracker.git

The application source code is already available. Analyze the codebase and prepare all deployment assets required for production deployment.
Business Requirement
Business expects:
• Application deployed on AWS EKS
• Application accessible externally through Load Balancer
• Production-grade deployment architecture
• Secure access mechanisms
• Persistent storage for application data
• Standardized deployments using Helm
• Git-based collaboration and approval workflows
• Agile project tracking using Jira
Your Role
As a DevOps Engineer you are responsible for:
• Source code governance
• Containerization
• Infrastructure setup
• Kubernetes deployment
• Configuration management
• Release workflow
• Documentation
Phase 1: Jira Planning
Before implementation begins:

1. Create one Epic for the overall Fitness Tracker initiative
2. Break the Epic into User Stories
3. Create Subtasks for implementation activities
4. Assign work items to yourself
5. Track progress throughout execution

Examples:
- Source Control Setup
- Docker Build Activities
- EKS Setup
- Kubernetes Deployment
- Helm Packaging
- Storage Configuration
Phase 2: Source Code Governance
Create and maintain GitHub repository structure.
Maintain all artifacts in source control:
• Docker assets
• Kubernetes manifests
• Helm charts
• Documentation

Implement Pull Request workflow.
Direct commits to the main branch are not permitted.
Phase 3: Containerization
Analyze the Fitness Tracker application.
Create Dockerfile(s).
Build production-ready container image(s).
Follow naming, tagging, and versioning conventions.
Phase 4: Docker Registry
Push generated images into Docker Hub.
Maintain image repository standards and tagging strategy.
Phase 5: Production AWS EKS Setup
Create a production-style Kubernetes environment.
Consider:
• Cluster architecture
• Worker node strategy
• Networking
• Security
• High availability
• Scalability
Phase 6: Bastion Host Access
Cluster administration should not happen directly.
Design secure access using a Bastion Host.
Administrative activities should occur through the Bastion architecture.
Phase 7: Kubernetes Deployment
Create Kubernetes resources:
• Deployments
• Services
• LoadBalancer
• ConfigMaps
• Secrets

Application must be accessible externally.
Phase 8: Persistent Storage
Application data should survive:
• Pod restart
• Pod deletion
• Application upgrades
• Node failures

Implement persistent storage architecture.
Phase 9: Helmification
Convert Kubernetes manifests into reusable Helm charts.
All configurable parameters must be externalized into values.yaml.
No hardcoded values should exist.
Phase 10: Release Workflow
Expected workflow:
Developer Change → Commit → Pull Request → Review → Approval → Merge → Deployment
Expected Deliverables
1. GitHub Repository
2. Docker Hub repository
3. EKS Cluster
4. Kubernetes manifests
5. Helm charts
6. Documentation
7. Jira tracking
Important Instructions
Do not search for ready-made solutions.
Design your own implementation.
Follow production and enterprise practices.
Document architecture decisions and assumptions.



DevOps Capstone Case Study – Hospital Application Deployment on AWS EKS
Case Study Goal
You are part of a DevOps Engineering team in a healthcare organization. The organization wants to modernize its Hospital Application and deploy it on AWS using production-grade DevOps practices. Your team is responsible for taking the source code, creating deployment artifacts, building infrastructure, and releasing the application into Kubernetes.

This is an end-to-end enterprise assignment. You must plan, collaborate, and deliver the complete solution using industry best practices.
Application Repository
Repository URL:
https://github.com/Msocial123/Hospital-Application.git

The application source code is already available. You need to analyze the application and prepare deployment assets.
Business Requirement
The organization wants:
• Application deployed on AWS EKS
• External users should access application through Load Balancer
• Secure production access model
• Persistent application data
• Reusable deployment process
• Git-based approvals
• Agile project tracking
Your Role
Act as a DevOps Engineer responsible for:
• Application packaging
• Infrastructure setup
• Kubernetes deployment
• Configuration management
• Release management
• Documentation
Phase 1: Jira Planning
Before implementation starts:

Create Jira work items:
1. Create one Epic for the complete initiative
2. Break Epic into Stories
3. Create Subtasks for implementation activities
4. Assign tasks to yourself
5. Track work progress

Examples:
- Source code management
- Docker implementation
- EKS setup
- Helm implementation
- Kubernetes deployment
- Persistent storage
Phase 2: Source Code Governance
Create a GitHub repository structure.
Maintain all project assets in source control:
• Docker assets
• Kubernetes manifests
• Helm charts
• Documentation

Implement Pull Request workflow.
No direct commits into main branch.
Phase 3: Containerization
Analyze the application.
Create Dockerfile(s).
Build production-ready Docker image.
Follow naming and versioning standards.
Phase 4: Image Registry
Push generated Docker image into Docker Hub.
Maintain image repository and tagging strategy.
Phase 5: Production EKS Setup
Create a production-style AWS EKS environment.
Students should think about:
• Cluster design
• Worker nodes
• Networking
• Security
• Availability
• Scalability
Phase 6: Bastion Host Access
Direct access to cluster is not allowed.
Design secure administrative access using Bastion Host architecture.
All administrative activities should happen through Bastion.
Phase 7: Kubernetes Deployment
Create Kubernetes resources:
• Deployment
• Services
• LoadBalancer
• ConfigMaps
• Secrets

Application must be accessible externally.
Phase 8: Persistent Storage
Application data should survive:
• Pod deletion
• Restart
• Upgrade
• Node failure

Implement persistent storage architecture.
Phase 9: Helmification
Convert Kubernetes deployment into Helm charts.
Move configurable parameters into values.yaml.
No hardcoded values allowed.
Phase 10: Release Workflow
Expected process:
Developer change → Commit → Pull Request → Review → Approval → Merge → Deploy

