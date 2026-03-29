<div align="center">

```
██████╗ ██╗   ██╗███████╗██╗  ██╗██╗   ██╗ █████╗ ███╗   ██╗████████╗
██╔══██╗██║   ██║██╔════╝██║  ██║╚██╗ ██╔╝██╔══██╗████╗  ██║╚══██╔══╝
██║  ██║██║   ██║███████╗███████║ ╚████╔╝ ███████║██╔██╗ ██║   ██║   
██║  ██║██║   ██║╚════██║██╔══██║  ╚██╔╝  ██╔══██║██║╚██╗██║   ██║   
██████╔╝╚██████╔╝███████║██║  ██║   ██║   ██║  ██║██║ ╚████║   ██║   
╚═════╝  ╚═════╝ ╚══════╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝   
```

**`~/devops`** · **`Noida, India`** · **`2+ yrs`**

🟢 &nbsp;*Available for collaboration*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/dushyant-kumar-dk)
[![Hashnode](https://img.shields.io/badge/Hashnode-2962FF?style=flat-square&logo=hashnode&logoColor=white)](https://dushyantkumark.hashnode.dev)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kumardushyant545@gmail.com)

</div>

---

> Building production-grade cloud-native systems on **AWS & GCP** —
> from Terraform-provisioned infra to secure, GitOps-driven Kubernetes deployments.

---

## `▸ focus areas`

| | Area | Stack |
|---|---|---|
| ☁ | **Cloud Infrastructure** | AWS · GCP · EKS · Terraform · IAM · VPC · Lambda |
| ⟳ | **CI/CD & GitOps** | Jenkins · GitHub Actions · GitLab CI · AWS CodePipeline · Argo CD |
| ◎ | **Containers & Kubernetes** | Docker · Kubernetes · Helm · Gateway API |
| ⬡ | **DevSecOps & Observability** | SonarQube · Trivy · GuardDuty · Prometheus · Grafana |

---

## `▸ deployment pipeline`

```
  code push
      │
      ▼
  ┌─────────────────────────────────┐
  │  Jenkins · GitHub Actions       │  ← CI trigger
  │  GitLab CI · AWS CodePipeline   │
  └──────────────┬──────────────────┘
                 │
                 ▼
  ┌─────────────────────────────────┐
  │  SonarQube · Trivy scan         │  ← security gate
  └──────────────┬──────────────────┘
                 │
                 ▼
  ┌─────────────────────────────────┐
  │  Docker build → ECR / GCR push  │  ← artifact
  └──────────────┬──────────────────┘
                 │
                 ▼
  ┌─────────────────────────────────┐
  │  Argo CD GitOps → EKS deploy  ✓ │  ← production
  └─────────────────────────────────┘
```

---

## `▸ tech stack`

**Cloud & Infra**
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-%234285F4.svg?style=flat-square&logo=google-cloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-%231A1918.svg?style=flat-square&logo=ansible&logoColor=white)

**CI/CD & GitOps**
![Jenkins](https://img.shields.io/badge/Jenkins-%232C5263.svg?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-%23FC6D26.svg?style=flat-square&logo=gitlab&logoColor=white)
![CodePipeline](https://img.shields.io/badge/AWS_CodePipeline-%23FF9900.svg?style=flat-square&logo=amazonaws&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-%23EF7B4D.svg?style=flat-square&logo=argo&logoColor=white)

**Containers & Orchestration**
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-%230F1689.svg?style=flat-square&logo=helm&logoColor=white)

**Security & Observability**
![SonarQube](https://img.shields.io/badge/SonarQube-%234E9BCD.svg?style=flat-square&logo=sonarqube&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-%231904DA.svg?style=flat-square&logo=aqua&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=flat-square&logo=grafana&logoColor=white)
![GuardDuty](https://img.shields.io/badge/GuardDuty-%23FF9900.svg?style=flat-square&logo=amazonaws&logoColor=white)

**MLOps & Scripting**
![MLflow](https://img.shields.io/badge/MLflow-%23d9ead3.svg?style=flat-square&logo=numpy&logoColor=blue)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/Bash-%23121011.svg?style=flat-square&logo=gnu-bash&logoColor=white)

---

## `▸ recent commits`

```
a3f9c21  [feat]   manage production EKS clusters for microservices workloads
b12e4d7  [feat]   optimize Jenkins/GHA/GitLab CI pipelines + Argo CD GitOps
c8a1f03  [infra]  provision AWS + GCP infrastructure with Terraform IaC
d45b9e0  [sec]    integrate SonarQube + Trivy + GuardDuty into CI pipeline
e67c2a8  [ops]    deploy Prometheus + Grafana observability stack on EKS
f90d1b4  [learn]  MLOps PoC — model packaging + Kubernetes-based serving
g23f5e9  [learn]  GenAI automation with AWS Bedrock + Lambda
```

---

## `▸ currently learning`

```yaml
2025:
  - Advanced Kubernetes internals & Gateway API
  - DevSecOps security automation & compliance
  - MLOps fundamentals — model lifecycle & CI/CD for ML
  - GenAI automation — AWS Bedrock & Lambda
```

---

## `▸ open to collaborate on`

- DevOps & Cloud automation projects
- Kubernetes & GitOps-based platform engineering
- Knowledge sharing & learning-driven MLOps experiments

---

<div align="center">

`⚙️ converting manual infrastructure tasks into fully automated pipelines since 2022 🚀`

[![](https://visitcount.itsvg.in/api?id=dushyantkumark&icon=6&color=1)](https://visitcount.itsvg.in)

</div>
