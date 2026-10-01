# Douglas García Jiménez

### AWS · Kubernetes · SRE troubleshooting

I build hands-on labs to strengthen my skills in infrastructure automation, observability, and incident investigation. My focus is understanding **why a system fails**, gathering evidence, and validating recovery.

## Featured projects

### [AWS Cloud Engineering Lab](https://github.com/douglas0311/eks-learning-lab)
A reproducible AWS Kubernetes lab for practicing SRE workflows—from provisioning infrastructure to investigating controlled failures.

- **Infrastructure:** Terraform, Amazon EKS, ECR, and versioned S3 remote state.
- **Automation:** GitHub Actions with AWS OIDC authentication, application deployment, and infrastructure teardown.
- **Observability:** Prometheus and Grafana dashboards connecting workload health, resource requests, and node scheduling.
- **Troubleshooting:** Progressive exercises covering container startup failures, insufficient schedulable CPU, and node scheduling constraints.

[Engineering notes and RCA portfolio](https://github.com/douglas0311/eks-learning-lab/tree/main/docs) · [Explore the repository](https://github.com/douglas0311/eks-learning-lab) · [Application playbook](https://github.com/douglas0311/eks-learning-lab/blob/main/docs/simple-test/playbook.md) · [Kubernetes walkthrough](https://github.com/douglas0311/eks-learning-lab/blob/main/docs/simple-test/kubernetes-explained.md)

### [Elias](https://github.com/douglas0311/Elias)
An engineering companion project exploring how guided questions, context, and evidence can support troubleshooting and stronger engineering judgment.

## How I approach an incident

**Observe → Collect evidence → Compare → Form a hypothesis → Validate → Document**

I use logs, Kubernetes events, resource configuration, and metrics together. A healthy workload provides a useful comparison, and a recovery is only complete once its behavior has been checked.

## Current learning focus

- Kubernetes scheduling, workloads, and service connectivity
- Distinguishing symptoms from root causes
- Using observability to separate useful signals from noise
- Building repeatable labs and documenting what I learn

These repositories document hands-on learning projects and controlled lab scenarios.
