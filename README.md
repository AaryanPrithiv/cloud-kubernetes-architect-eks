# Cloud & Kubernetes Architect – Amazon EKS Platform Portfolio

Hi 👋  
I’m **Prithivkumar**, a Cloud & Kubernetes Architect with 9+ years of experience
designing, operating, and evolving production-grade Kubernetes platforms on AWS,
with a strong focus on **Amazon EKS**.

This repository represents **how I think and work as a platform architect** —
combining proven open‑source patterns with real‑world operational experience

---

## 🔹 What This Repository Represents

This is **not a demo or tutorial repo**.

It is a **curated architecture portfolio** that demonstrates:
- How I design **EKS blueprint architectures**
- How I own and operate **platform-wide Kubernetes components**
- How I enforce **GitOps, observability, and security**
- How I automate **repeatable platform operations**
- How I separate responsibilities between **platform teams and application teams**

---

## 🔹 Core Skills & Technologies

- **AWS**: EKS, VPC, IAM, EC2, Load Balancers, CloudWatch
- **Kubernetes**: Architecture, RBAC, Networking, Platform Add-ons
- **GitOps**: ArgoCD, Helm, Kubernetes manifests (YAML)
- **Observability**: Prometheus, Grafana, Datadog
- **Security**: Least privilege access, secrets management
- **Automation**: GitHub Actions, Bash-based operational tooling

---

## 🔹 EKS Architecture & Blueprint Design

### ✅ EKS Blueprint Architecture
Located under `architecture/`

- Reference architecture for secure, scalable EKS deployments
- AWS services interlinked with Kubernetes platform components
- Design decisions explained from a **platform ownership perspective**

This section shows how I decide **which AWS services and Kubernetes components**
are appropriate to achieve a business outcome.

---

## 🔹 Shared Responsibility Model

### ✅ Platform vs Application Responsibilities
Located under `architecture/shared-responsibility-model.md`

- Clear delineation between:
  - Platform administrators
  - Application development teams
- Approved deployment patterns for applications targeting EKS
- Guardrails without blocking developer velocity

This reflects how EKS platforms operate in **real enterprise environments**.

---

## 🔹 GitOps & Deployment Patterns

### ✅ GitOps with ArgoCD
Located under `gitops/`

- App‑of‑Apps pattern
- Helm‑based deployments
- Environment promotion via Git
- Declarative Kubernetes manifests (YAML)

This demonstrates **deep familiarity with GitOps workflows** used in production.

---

## 🔹 Platform-Wide Kubernetes Components

### ✅ Lifecycle & Uptime Ownership
Located under `platform-components/`

Platform components owned and operated include:
- AWS VPC CNI
- CoreDNS
- Metrics Server
- Prometheus
- ArgoCD

This section focuses on:
- Upgrade strategies
- Availability considerations
- Platform reliability

---

## 🔹 Security & Least Privilege Access

### ✅ Self‑Service Access Model
Located under `security/`

- Namespace‑scoped RBAC
- Least privilege enforcement
- Secure access patterns for application teams
- Reduced operational overhead for platform admins

---

## 🔹 Observability Strategy

### ✅ Platform & Application Observability
Located under `observability/`

- Metrics, logs, and alerts for EKS platform
- Observability as a **mandatory platform capability**
- Ensuring visibility for both platform and application workloads

---

## 🔹 Automation, Runbooks & Operational Excellence

### ✅ Automated Runbooks & Playbooks
Located under `runbooks/`

- Repeated platform operations automated
- Incident response playbooks
- Operational knowledge captured as documentation

This improves efficiency and reduces manual intervention across the platform.

---

## 🔹 Open‑Source & Real‑World Experience

This repository includes **selected open‑source projects** (AWS, Kubernetes,
ArgoCD, Prometheus) used as **reference implementations**.

My value is in:
- Curating the right patterns
- Applying them to real platforms
- Operating them reliably at scale

---

## ✅ Why This Portfolio

This portfolio reflects how I work as a **Cloud & Kubernetes Architect**:
- Platform ownership over application deployment
- Architecture decisions over tooling hype
- Automation over manual operations
- Reliability and observability by default

📌 **Role Focus**: Cloud & Kubernetes Architect (Amazon EKS)
