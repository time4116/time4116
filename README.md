# André Perrot

**Platform Engineering Leader | Hands-On IC | AWS | Kubernetes | DevOps**

I build the systems and tooling that let engineering teams ship without waiting on DevOps.

## Selected proof

- **PR Review Automation:** Built an AI-powered PR review bot (AWS Bedrock + AgentCore) that automates Jira criteria validation and Terraform security scans, consolidating manual review cycles into a single live feedback loop.
- **Infrastructure-as-Code Agents:** Built IaC Smith, a Bedrock/LangGraph controller that turns GitHub issues into validated Terraform/Terragrunt PRs with repo-pattern scanning, static/runtime validation, and bounded repair loops.
- **Self-Service Migration:** Engineered a Claude Code CLI plugin for autonomous CI/CD bootstrapping, enabling teams to scaffold and migrate repos without DevOps intervention.
- **Cluster Modernization:** Led a zero-downtime KOPS-to-EKS migration across multiple production clusters, including a VPC redesign to eliminate legacy CIDR collision risks.
- **Cost Optimization:** Eliminated ~365 agent-days of idle compute annually by architecting an on-demand CI build agent manager, significantly reducing overhead while maintaining developer speed.

## Projects

### [iac-smith](https://github.com/time4116/iac-smith)

AI infrastructure controller that turns freeform GitHub issues into validated Terraform/Terragrunt pull requests.

Uses AWS Bedrock and LangGraph to infer infrastructure intent, scan target repo conventions, generate IaC, run static and runtime validation, apply bounded self-repair loops, and open reviewable GitOps PRs without directly applying infrastructure.

**Stack:** Python · AWS Bedrock · LangGraph · Terraform · Terragrunt · GitHub Actions · AWS OIDC

### [bedrock-pr-agent](https://github.com/time4116/bedrock-pr-agent)

AI-assisted GitHub PR review harness on AWS Bedrock.

Routes GitHub App events through API Gateway, SQS, Lambda, and Bedrock AgentCore, then updates a single idempotent PR comment with Claude review synthesis and deterministic security scan findings.

**Stack:** Python · AWS Bedrock · AgentCore · LangGraph · Lambda · SQS · API Gateway · CDK · GitHub Apps

### [repocaster](https://github.com/time4116/repocaster)

GitHub App that converts repository context into AI-generated audio briefings.

A LangGraph pipeline scans the repo, generates a script with Bedrock, synthesizes audio with OpenAI TTS, and delivers a playable MP3 briefing through GitHub comments and S3.

**Stack:** Python · AWS Bedrock · LangGraph · OpenAI TTS · S3 · GitHub Apps

## Core stack

AWS · EKS · Kubernetes · Terraform · Terragrunt · CloudFormation · CDK · GitHub Actions · Jenkins · ArgoCD · Karpenter · Helm · Python · Bash · Datadog · OpenTelemetry · ELK · AWS Bedrock · LangGraph · Claude Code

## Links

- [LinkedIn](https://www.linkedin.com/in/andré-perrot-174b4b31)
