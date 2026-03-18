# Jesutofunmi Ajekola

IT and infrastructure engineer with 7 years across enterprise support, network operations, and cloud environments. Transitioning into DevOps and cloud architecture — building on production AWS experience with hands-on work in Terraform, containers, Kubernetes, and CI/CD pipelines.

---

## Projects

### [terraform_tasks](https://github.com/Jaykol/terraform_tasks) — Infrastructure as Code
Terraform configuration provisioning AWS infrastructure across two iterations. Deploys a t3.micro Ubuntu 22.04 EC2 instance with dynamic AMI lookup, a least-privilege security group, and an SSH key pair — all as code. Iteration 2 refactored hardcoded values into input variables, introduced a `terraform.tfvars.example` pattern for secrets hygiene, and added `.gitignore` to exclude state files and keys.

`Terraform` `AWS EC2` `Security Groups` `HCL` `Variables` `tfvars`

---

### [containerization_project](https://github.com/Jaykol/containerization_project) — Docker + Kubernetes
Containerized a static web application using Docker with Nginx as the base image, pushed to Docker Hub, and deployed to a Kubernetes cluster using Kind. Wrote Kubernetes Deployment and Service YAML manifests, configured a ClusterIP service, and accessed the application via port-forwarding.

`Docker` `Kubernetes` `Kind` `Nginx` `YAML` `kubectl`

---

### [MarketPeak_Ecommerce](https://github.com/Jaykol/MarketPeak_Ecommerce) — AWS EC2 Deployment
Deployed a web application to an AWS EC2 instance running Amazon Linux. Set up Apache HTTP Server, managed the full Git workflow — development branch, pull requests, merge to main — and updated the live server via SSH.

`AWS EC2` `Apache` `Git` `Linux` `SSH`

---

### [hello-world-cicd](https://github.com/Jaykol/hello-world-cicd) — CI/CD Pipeline
Automated build and deploy pipeline using Jenkins and GitHub Actions.

`Jenkins` `GitHub Actions` `CI/CD`

---

### [actionprofile](https://github.com/Jaykol/actionprofile) — GitHub Actions
GitHub Actions workflow configuration and automation.

`GitHub Actions` `YAML`

---

### [kubernetes_1](https://github.com/Jaykol/kubernetes_1) — Kubernetes
Hands-on Kubernetes configuration and orchestration exercises.

`Kubernetes` `kubectl` `YAML`

---

### [yaml_excercises](https://github.com/Jaykol/yaml_excercises) — YAML
Structured YAML practice covering Kubernetes manifests and pipeline configuration.

`YAML` `Kubernetes` `CI/CD`

---

## Production experience

**AWS — Comercio Partners (2023–present)**
- Managed EC2, IAM, S3, CloudWatch, and security groups day-to-day
- Traced a live account compromise to stolen developer credentials via CloudTrail, shut down the attack, locked down IAM, and recovered the full cost from AWS
- Cut monthly AWS spend by 52.4% — EC2 right-sizing, removing idle resources, rewriting storage policies
- Deployed applications to EC2 via CI/CD pipelines using Jenkins, GitHub Actions, and GitLab CI
- Responded to a DoS attack: blocked attacking IPs at the firewall, updated security group rules, activated WAF
- Diagnosed a PM2 failure that took the company website down after an unplanned server restart — restored service and configured PM2 to auto-restart on boot

**Network infrastructure — Tizeti Network Limited (2018–2023)**
- Monitored a 3,000+ node ISP network, responded to outages, rolled out firmware upgrades across the hardware fleet
- Led six engineers to deploy 3,500 cloud-managed public Wi-Fi hotspots across two Nigerian states

**Physical security — Comercio Partners (2023–present)**
- Managed Fortinet firewalls, access control panels, CCTV, and alarm systems
- Set up the full network and physical security stack for a new office with no downtime during cutover

---

## Tools and technologies

| Area | Stack |
|---|---|
| Cloud | AWS (EC2, IAM, S3, RDS, CloudTrail, CloudWatch, WAF, VPC), Azure (fundamentals) |
| IaC | Terraform (EC2, security groups, key pairs, variables, tfvars) |
| Containers | Docker, Kubernetes (Kind, kubectl, Deployment/Service YAMLs) |
| CI/CD | Jenkins (pipeline-as-code), GitHub Actions, GitLab CI |
| Linux | Ubuntu, CentOS, Kali Linux |
| Networking | TCP/IP, DNS, DHCP, VPN, NAT, Fortinet firewalls |
| Security | IAM, security groups, WAF, access control, CCTV, patch management |
| Scripting | Bash, PowerShell, Python (basics) |
| Version control | Git |
| Identity | Active Directory, Office 365, Exchange |

---

## Certifications

- Google Cybersecurity Professional Certificate (2026)
- Google IT Support Professional Certificate (2025)
- Juniper Networks Certified Associate – JNCIA-Junos (2022)
- AWS Solutions Architect Associate – course completed (2025)
- Microsoft AZ-900: Azure Fundamentals – course completed (2025)

---

## Currently building

- Terraform remote state with S3 + DynamoDB locking
- Jenkins pipeline-as-code integrating Terraform for full IaC CI/CD
- Prometheus and Grafana monitoring stack

---

## Education

- MSc Physics (Solid Earth) — University of Ibadan
- BSc Physics — Federal University of Agriculture, Abeokuta

---

## Contact

[LinkedIn](https://www.linkedin.com/in/jesutofunmijohn) · jekola.ajekola@gmail.com
