# Hi, I'm Nihar Landge

<img align="right" src="https://unavatar.io/linkedin/nihar-landge?label=PROFILE+VIEWS&color=0e7c7b&style=flat" />

```yaml
role:      Cloud & DevOps Engineer
focus:     Infrastructure as Code · Observability · CI/CD
location:  India
status:    shipping every sat and sunday
```

---

### Currently

- Building cloud-native platforms with **Terraform**, **Kubernetes**, and **Go**.
- Going deep on **OpenTelemetry**, **ELK**, and **EKS** deployment patterns.
- Contributing to **open-source** observability tooling.
- Open to collaborating on infra, automation, and developer-experience projects.

---

### Tech Arsenal

**Cloud & Infrastructure**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![EKS](https://img.shields.io/badge/Amazon_EKS-FF9900?style=flat&logo=amazoneks&logoColor=black)

**Observability & CI/CD**
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat&logo=opentelemetry&logoColor=white)
![Elastic Stack](https://img.shields.io/badge/ELK-005571?style=flat&logo=elasticstack&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)

**Languages**
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat&logo=gnubash&logoColor=white)

---

### Stack I Run

A snapshot of the cloud-native platform I build and operate. Source-to-prod, fully observable, fully automated.

```mermaid
flowchart LR
    subgraph Source
        DEV([Developer])
        GIT[Git Push]
    end

    subgraph CI/CD
        GHA[GitHub Actions]
        ARGO[ArgoCD]
        HELM[Helm]
    end

    subgraph Runtime
        EKS[Amazon EKS]
        EC2[EC2 Workers]
        S3[S3 State]
    end

    subgraph Observability
        OTel[OpenTelemetry]
        ELK[ELK Stack]
        PROM[Prometheus]
    end

    subgraph IaC
        TF[Terraform]
        K8S[Kubernetes Manifests]
    end

    DEV -->|commit| GIT
    GIT --> GHA
    GHA -->|build + test| HELM
    HELM --> ARGO
    ARGO -->|sync| EKS
    EKS --> EC2
    TF -.->|provision| EKS
    TF -.->|state| S3
    EKS --> OTel
    OTel --> ELK
    OTel --> PROM
    K8S --> EKS

    classDef src fill:#0e7c7b,color:#fff,stroke:#0e7c7b
    classDef cicd fill:#2088FF,color:#fff,stroke:#2088FF
    classDef rt fill:#FF9900,color:#000,stroke:#FF9900
    classDef obs fill:#425CC7,color:#fff,stroke:#425CC7
    classDef iac fill:#7B42BC,color:#fff,stroke:#7B42BC

    class DEV,GIT src
    class GHA,ARGO,HELM cicd
    class EKS,EC2,S3 rt
    class OTel,ELK,PROM obs
    class TF,K8S iac
```

> _Live in production. Traced end-to-end. Provisioned by code._

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=14&duration=3000&pause=1000&color=0E7C7B&center=true&vCenter=true&multiline=true&repeat=false&width=500&lines=git+comm[...]" />
</p>

<p align="center">
  <sub>Find me elsewhere as <code>@niharlandge</code>.</sub>
</p>

<!--
nihar-landge/nihar-landge
-->
