# Anup Ramachandran

### DevOps Lead · Platform Engineering · AWS · Kubernetes · Terraform · GitLab CI/CD

I build and operate developer platforms and cloud infrastructure with a focus on **automation, reliability, security, and developer experience**.

My current work sits at the intersection of **AWS, Kubernetes, Terraform, GitLab CI/CD and platform engineering**, with a strong focus on infrastructure that other engineering teams can consume safely and repeatedly.

---

## What I work on

| Area | Focus |
|---|---|
| ☁️ Cloud | AWS, EC2, ECS, EKS, IAM, S3, KMS, networking |
| ☸️ Kubernetes | EKS, k3s, Helm, GitOps, Karpenter, workload/platform design |
| 🏗️ Infrastructure | Terraform, reusable modules, immutable infrastructure, AMIs |
| 🚀 CI/CD | GitLab CI/CD, GitLab Runner, Jenkins, GitHub Actions |
| 🧩 Platform Engineering | Self-service infrastructure, developer experience, standardisation |
| 🔐 Security | IAM, least privilege, secrets, supply-chain/security automation |
| 📊 Reliability | Observability, failure modes, incident analysis, capacity and NFRs |
| 🤖 Automation | Python, Go, Bash, PowerShell and infrastructure automation |

---

## Engineering focus

**Platform Engineering × Cloud Infrastructure × Developer Experience × Reliability × Security**

I enjoy problems where the solution is bigger than a single application:

- designing infrastructure used by many engineering teams
- turning manual infrastructure into repeatable self-service workflows
- building scalable CI/CD and runner platforms
- designing Kubernetes platforms and workload scheduling
- improving reliability through observability and failure analysis
- balancing performance, cost, security and operational complexity
- mentoring engineers and turning architecture decisions into practical implementation

---

## Professional experience

### DevOps Lead — MBition / Mercedes-Benz

I work on cloud-native engineering platforms supporting software development workflows, with particular focus on **GitLab Runner infrastructure and AWS-based execution platforms**.

Areas I work across include:

- AWS-based ephemeral and dedicated CI runner infrastructure
- GitLab Runner and Fleeting Runner architecture
- Terraform modules and customer-facing infrastructure onboarding
- EC2, ECS and Auto Scaling based execution capacity
- Kubernetes and EKS platform architecture
- AMI lifecycle and runner image management
- observability, reliability and operational readiness
- infrastructure security and IAM design
- platform limits, non-functional requirements and failure handling
- technical ownership, architecture reviews and engineering mentorship

I approach internal platforms as products: **clear interfaces, safe defaults, useful abstractions, good observability and predictable failure behaviour.**

---

## Selected projects

### [argocd-pi5](https://github.com/anupcoded/argocd-pi5)

My Kubernetes homelab/platform engineering playground.

The environment explores:

- Raspberry Pi + k3s
- Argo CD / GitOps
- Traefik
- Prometheus + Grafana
- Loki
- CloudNativePG
- Immich
- Pi-hole
- Ollama

This is where I experiment with Kubernetes architecture, GitOps, observability, storage, networking and operating a platform end-to-end.

> Repository is currently private.

### [Terraform-NGINX](https://github.com/anupcoded/Terraform-NGINX)

A practical infrastructure-as-code project combining:

**Terraform → AWS EC2 → Ubuntu → Docker → NGINX → Jenkins**

It demonstrates provisioning infrastructure, configuring a workload and validating the deployment through a CI pipeline.

### [html-crawler](https://github.com/anupcoded/html-crawler)

A Go web application that analyses a supplied website and reports:

- HTML version
- page title
- heading structure
- internal/external links
- inaccessible links
- login forms

A small project, but useful evidence of application development alongside infrastructure work.

### [Jenkins-Docker-Deployment](https://github.com/anupcoded/Jenkins-Docker-Deployment)

Jenkins and Docker deployment automation.

### [Upload2SharePoint](https://github.com/anupcoded/Upload2SharePoint)

Python automation for uploading content to SharePoint.

### [svnhook-commit-size-](https://github.com/anupcoded/svnhook-commit-size-)

A Subversion pre-commit hook that prevents commits containing files above a configured size limit.

### [CO2-Calculator](https://github.com/anupcoded/co2-calaculator)

Java application calculating transport-related CO₂ emissions, with Maven/JUnit based build and test workflows.

### [add2files](https://github.com/anupcoded/add2files)

A small Windows automation utility for adding lines to files matching a selected extension.

### [mtask](https://github.com/anupcoded/mtask)

A small API/web deployment exercise using Python, pytest, GitHub Actions, Docker and NGINX.

---

## Earlier engineering work

Some of my older repositories capture the progression of my engineering interests from application development and automation into infrastructure and platform engineering.

One example is **algorand-datastore**, an edge-device research project combining:

**Algorand + RDF + IPFS + Redis + Docker + Raspberry Pi**

The system explored decentralised storage and search for RDF datasets using blockchain-based consensus and distributed services.

I also have repositories covering Java, Python, Go, PowerShell, Docker, Jenkins, AWS, Terraform and CI/CD experiments.

---

## Technology map

```text
                         PLATFORM ENGINEERING
                                │
             ┌──────────────────┼──────────────────┐
             │                  │                  │
          CLOUD              KUBERNETES          CI/CD
             │                  │                  │
       AWS · IAM          EKS · k3s           GitLab
       EC2 · ECS          Helm · GitOps       Jenkins
       S3 · KMS           Karpenter            GitHub Actions
             │                  │                  │
             └──────────────────┼──────────────────┘
                                │
                         INFRASTRUCTURE
                                │
                    Terraform · Packer · AMIs
                                │
             ┌──────────────────┼──────────────────┐
             │                  │                  │
          SECURITY         OBSERVABILITY       AUTOMATION
             │                  │                  │
        IAM · Secrets      Prometheus          Python
        Supply chain       Grafana · Loki      Go
        Least privilege    Metrics · Logs      Bash / PowerShell
```

---

## How I approach engineering

### Build platforms, not snowflakes
Reusable interfaces and automation are more valuable than one-off infrastructure.

### Design for failure
Capacity limits, unhealthy nodes, failed deployments, broken dependencies and partial outages are design inputs, not surprises.

### Make infrastructure observable
If a platform is important, its health, capacity and failure modes should be visible.

### Automate the boring parts
If engineers repeatedly perform the same operational task, there is probably an opportunity to turn it into a product or workflow.

### Keep trade-offs explicit
Performance, cost, reliability, security and developer experience often pull in different directions. Good platform engineering makes those trade-offs visible.

### Prefer practical abstractions
Abstractions should remove unnecessary complexity without hiding the behaviour engineers need to understand when something breaks.

---

## Currently exploring

- Kubernetes platform architecture
- EKS Auto Mode and Karpenter
- KEDA and event-driven autoscaling
- Envoy, Traefik and service-mesh architecture
- cross-account AWS security patterns
- GitOps and internal developer platforms
- build acceleration and remote build execution
- cloud-native security
- AI-assisted infrastructure operations

---

## Beyond the infrastructure

I also enjoy the people side of engineering:

- technical leadership
- architecture discussions
- mentoring engineers
- onboarding and knowledge sharing
- improving engineering processes
- helping teams make better infrastructure decisions

My long-term direction is toward **technical leadership and platform ownership**, while staying close enough to the technology to make sound architectural decisions.

---

## Let's connect

- GitHub: [@anupcoded](https://github.com/anupcoded)
- Email: [anupcoded@gmail.com](mailto:anupcoded@gmail.com)

---

<sub>Building platforms, automating the repetitive, and learning by running things in production — and at home.</sub>
