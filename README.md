<div align="center">

<!-- Animated Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Mohit%20Chandra%20Fulara&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Cloud%20Computing%20%7C%20Networking%20%26%20Security%20%7C%20DevOps%20%7C%20Bioinformatics%20%7C%20AI%20Compliance%20%26%20Infra%20Consultant&descAlignY=58&descSize=15&animation=fadeIn"  />

<!-- Typing Animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&pause=1000&color=4FC3F7&center=true&vCenter=true&width=780&lines=Cloud+Computing+%7C+Networking+%26+Security+%7C+DevOps;AWS+%7C+Kubernetes+%7C+Docker+%7C+Terraform;CI%2FCD+%7C+GitOps+%7C+ArgoCD+%7C+Observability;Bioinformatics+%26+Computational+Biology;AI+Compliance+%26+Infra+Consultant" alt="Typing SVG" />
</a>

<br/>

<!-- Profile Badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohit-chandra-fulara-a20657280)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/2005mohit)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Mohitfulara2005@gmail.com)

</div>

---

## About Me


> Working across **Cloud Computing, Networking & Security, and DevOps**, with a strong focus on **Bioinformatics & Computational Biology** and **AI Compliance & Infra Consulting**. Currently building an **AI Compliance & Governance Automation Platform** that combines a LangGraph multi-agent engine with a full EU AI Act audit workflow, alongside a **Multi-Agent SOC Platform** for automated threat detection and a **Kubernetes-based microservices platform** with full CI/CD, GitOps, and observability. A biotechnology background drives the application of the same cloud-security and pipeline-automation practices to bioinformatics and genomics workloads.

---

## Projects

### AI Compliance & Governance Automation Platform
> Multi-agent, EU AI Act-aligned governance system — from continuous risk detection to consultant-grade audit deliverables

- Designed a **secure, multi-tenant microservices architecture** on AWS (VPC-isolated public/private/data subnets, EKS, ALB, WAF) decoupling synchronous API traffic from async, agentic governance processing via a Redis-backed event bus
- Built a **3-agent LangGraph governance engine** → `Scout Agent (log ingestion & normalization) → Analyst Agent (EU AI Act & NIST AI RMF risk classification) → Fixer Agent (auto-policy & remediation generation)`
- Implemented a **zero-trust IAM model** with IRSA-based least-privilege agent roles, a runtime LLM proxy for prompt-injection/data-leak detection, and a **SHA-256 hash-chained, tamper-proof audit ledger** in PostgreSQL to meet EU AI Act auditability requirements
- Extended the engine into a **consultant workbench**: Evidence Aggregator (cloud API + Git/AST collectors) → PII Scanner (regex + NER) → Rule Engine (Article-mapped compliance checks) → Risk Scorer → Remediation Generator → automated **Technical File / Model Card / Audit Report** generation (WeasyPrint + Jinja2)
- Automated schema-per-tenant data isolation on RDS PostgreSQL, KMS envelope encryption, and cross-account read-only access via AWS STS / Azure Service Principals for client cloud audits
- DevSecOps pipeline with GitHub Actions (SAST, container image scanning, IaC scanning) and ArgoCD GitOps delivery to EKS

`Python` `FastAPI` `LangGraph` `LangChain` `Next.js` `PostgreSQL + pgvector` `Redis / Celery` `AWS (EKS, RDS, KMS, STS, WAF)` `Terraform` `ArgoCD` `GitHub Actions` `Keycloak / OIDC`

---

### Multi-Agent AI SOC Platform
> Automated end-to-end incident response with stateful LangGraph pipeline

- Architected a **4-agent LangGraph pipeline** → `Kafka Stream → Correlation Agent → Intelligence Agent → Risk Agent → Response Agent`, enabling automated end-to-end incident response workflows with stateful checkpointing for failure recovery
- Built threat intelligence layer using **RAG over MITRE ATT&CK** knowledge base — reduced manual incident triage time by **60%**
- Processes **500+ security log events per pipeline run** with automated risk scoring

`Python` `LangChain` `LangGraph` `FAISS` `FastAPI` `Docker` `Kafka` `Ollama` `Llama3`

---

### Cloud-Native Microservices Platform on Kubernetes
> 10+ service microservices platform with full CI/CD, GitOps, and observability

- Built and deployed a **10+ service microservices platform** on Kubernetes (EKS) using Docker, Helm, and Terraform
- Automated **CI/CD and GitOps delivery** with GitHub Actions, ECR, and ArgoCD — enabling fast, reliable rollbacks
- Secured cloud networking with **VPCs, Ingress, TLS, and Route53** for scalable service communication
- Achieved **99% uptime** through full observability with Prometheus, Grafana, and ELK
- Resolved production issues via root-cause analysis across Linux, Kubernetes, and networking layers

`AWS (EKS, ECR, Route53)` `Kubernetes` `Docker` `Terraform` `Helm` `GitHub Actions` `ArgoCD` `Prometheus` `Grafana` `ELK`

---

### Secure Cloud-Native Genomics Pipeline *(Bioinformatics × Cloud Security)*
> Scalable, compliant sequence-analysis pipeline built on the same infra-automation and zero-trust practices used in the governance platform

- Designed a **containerized NGS pipeline** (Nextflow/Snakemake orchestration) covering raw read QC, alignment, variant calling, and annotation — packaged as reproducible Docker images per pipeline stage
- Deployed pipeline execution on **AWS Batch / EKS** with Terraform-provisioned compute, auto-scaling worker pools, and S3-backed data lake for FASTQ/BAM/VCF artifacts
- Applied the governance platform's security patterns to genomic data: **KMS envelope encryption at rest, IRSA least-privilege roles per pipeline stage, and immutable S3 Object Lock storage** for HIPAA/GxP-aligned handling of sensitive sequencing data
- Automated pipeline CI with GitHub Actions (container scanning, workflow linting) and GitOps-style versioned pipeline releases

`Nextflow / Snakemake` `Biopython` `GATK` `BWA / Bowtie2` `Samtools` `AWS Batch` `AWS S3 + KMS` `Docker` `Terraform`

---

## Tech Arsenal

### Cloud & DevOps
<div align="center">

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white) ![ArgoCD](https://img.shields.io/badge/ArgoCD_(GitOps)-EF7B4D?style=flat&logo=argo&logoColor=white) ![CI/CD](https://img.shields.io/badge/CI%2FCD_Pipeline_Design-2C3E50?style=flat&logo=githubactions&logoColor=white)

</div>

### Infrastructure & Automation
<div align="center">

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Bash](https://img.shields.io/badge/Bash_Scripting-4EAA25?style=flat&logo=gnubash&logoColor=white) ![Networking](https://img.shields.io/badge/Networking-1A1A2E?style=flat&logo=cisco&logoColor=white) ![IaC](https://img.shields.io/badge/Infrastructure_as_Code-7B42BC?style=flat&logo=terraform&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white) ![Observability](https://img.shields.io/badge/Monitoring_%26_Observability-2C3E50?style=flat&logo=grafana&logoColor=white)

</div>

### Agentic AI & Governance
<div align="center">

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-FF6B35?style=flat&logo=python&logoColor=white) ![Multi-Agent](https://img.shields.io/badge/Multi--Agent_Systems-6C3483?style=flat&logo=amazonwebservices&logoColor=white) ![Agent Orchestration](https://img.shields.io/badge/Agent_Orchestration-1A1A2E?style=flat&logo=python&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-FF4B4B?style=flat&logo=databricks&logoColor=white) ![AI Governance](https://img.shields.io/badge/AI_Governance_%26_Compliance-0f2027?style=flat) ![EU AI Act](https://img.shields.io/badge/EU_AI_Act_%2F_NIST_AI_RMF-2C3E50?style=flat)

</div>

### Backend & Data
<div align="center">

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)

</div>

### Programming
<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

</div>

### Bioinformatics & Computational Biology
<div align="center">

![Biopython](https://img.shields.io/badge/Biopython-3776AB?style=flat&logo=python&logoColor=white) ![BLAST](https://img.shields.io/badge/BLAST-005C99?style=flat&logo=biorxiv&logoColor=white) ![NGS](https://img.shields.io/badge/NGS_Data_Analysis-2C3E50?style=flat) ![GATK](https://img.shields.io/badge/GATK_(Variant_Calling)-4EAA25?style=flat) ![Samtools/BWA](https://img.shields.io/badge/Samtools_%2F_BWA_%2F_Bowtie2-1A1A2E?style=flat) ![Nextflow](https://img.shields.io/badge/Nextflow_%2F_Snakemake-24B26B?style=flat) ![R/Bioconductor](https://img.shields.io/badge/R_%2F_Bioconductor-276DC3?style=flat&logo=r&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas_%2F_NumPy-150458?style=flat&logo=pandas&logoColor=white) ![Genomics](https://img.shields.io/badge/Genome_Assembly_%26_Annotation-2C3E50?style=flat) ![Phylogenetics](https://img.shields.io/badge/Phylogenetics-7B42BC?style=flat)

</div>

## GitHub Statistics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=2005mohit&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=4FC3F7&icon_color=4FC3F7&text_color=c9d1d9" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=2005mohit&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=4FC3F7&text_color=c9d1d9" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=2005mohit&theme=tokyonight&hide_border=true&background=0d1117&ring=4FC3F7&fire=4FC3F7&currStreakLabel=4FC3F7)](https://git.io/streak-stats)

</div>

---

## 📬 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohit-chandra-fulara-a20657280)
[![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Mohitfulara2005@gmail.com)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/2005mohit)

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer&animation=fadeIn" />

*⭐ From [2005mohit](https://github.com/2005mohit) — If something caught your eye, drop a star!*

</div>
