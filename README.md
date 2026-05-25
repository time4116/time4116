# André Perrot

**Senior Platform / DevOps Engineer**  
AWS · Kubernetes · CI/CD · Developer Productivity · AI-assisted platform tooling

I build and operate delivery platforms, infrastructure automation, and internal tooling that help engineering teams ship without waiting on DevOps.

## Selected proof

- Cut CI/CD repository onboarding from 1–2 DevOps engineer-days to under an hour with a Claude Code CLI plugin that encodes build patterns, standards, and project archetypes.
- Supported CI/CD systems handling 317+ daily builds across services.
- Reduced compute costs about 20% through ARM64 build and Kubernetes runtime work.
- Built build-agent automation that eliminates about 365 idle agent-days of compute annually.
- Built EKS upgrade automation with preflight checks for API deprecations, capacity validation, mixed Fargate/Karpenter clusters, and Velero backup gating.

## Projects

### [bedrock-pr-agent](https://github.com/time4116/bedrock-pr-agent)

AI-assisted GitHub PR review harness on AWS Bedrock.

Routes GitHub App events through API Gateway, SQS, Lambda, and Bedrock AgentCore, then updates a single idempotent PR comment with review findings, CI diagnosis, Terraform context, and policy checks.

**Stack:** Python · AWS Bedrock · AgentCore · LangGraph · Lambda · SQS · API Gateway · CDK · GitHub Apps

### [repocaster](https://github.com/time4116/repocaster)

GitHub App that converts repository context into AI-generated audio briefings.

A LangGraph pipeline scans the repo, generates a script with Bedrock, synthesizes audio with OpenAI TTS, and delivers a playable MP3 briefing through GitHub comments and S3.

**Stack:** Python · AWS Bedrock · LangGraph · OpenAI TTS · S3 · GitHub Apps

## Core stack

AWS · EKS · Kubernetes · Terraform · CloudFormation · CDK · GitHub Actions · Jenkins · ArgoCD · Karpenter · Helm · Python · Bash · Datadog · OpenTelemetry · ELK · AWS Bedrock · LangGraph · Claude Code

## Links

- [LinkedIn](https://www.linkedin.com/in/andré-perrot-174b4b31)
