# Amazon SageMaker AI — Introduction

## Summary
Amazon SageMaker has been rebranded as Amazon SageMaker AI. Older docs may use “SageMaker” while newer docs use “SageMaker AI”; they refer to the same platform.

SageMaker AI is a unified, end-to-end ML platform that supports training, pipelines, deployment/serving, and inference in one place via SageMaker Studio. Organizations typically create domains (often one per team) and user profiles to provide controlled access to Studio applications.

## Key Capabilities
- Unified platform for ML lifecycle: training → deployment → inference
- SageMaker Studio provides apps such as notebooks, canvas, pipelines, and serving tools
- MLOps admins create domains and user profiles to onboard users and manage access

## Pros
- Single platform improves collaboration
- Managed infrastructure reduces ops overhead
- Lower learning curve for data scientists/ML engineers (one toolset)

## Cons
- Cost can increase significantly (managed platform + infra usage)
- Vendor lock-in makes migrations difficult
- Governance burden for MLOps: RBAC, permissions, and cost controls are critical

## Lab Guide (Next Lecture)
1. Choose AWS region and confirm permissions
2. Open SageMaker AI in AWS Console
3. Create SageMaker Studio Domain (networking + roles)
4. Create user profiles (data scientist, ML engineer, MLOps roles)
5. Launch Studio and verify access
6. Implement RBAC and guardrails
7. Implement cost controls (budgets, tagging, shutdown habits)
8. Proceed to training/pipelines/serving labs
