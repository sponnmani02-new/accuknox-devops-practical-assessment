# Accuknox DevOps Trainee Practical Assessment

This repository contains the completed practical assessment for the **Accuknox DevOps Trainee** position.

---

##  Problem Statement 1 – Containerisation and Deployment of Wisecow Application

**Objective:**  
Containerize and deploy the [Wisecow App](https://github.com/nyrahul/wisecow) on a Kubernetes cluster (e.g., Minikube/Kind) with TLS support and CI/CD automation.

**Included Files:**
- `Dockerfile` – Container image definition for Wisecow.
- `deployment.yaml` – Kubernetes Deployment and Service manifests.
- `.github/workflows/ci.yml` – GitHub Actions workflow for CI/CD pipeline.

**Pipeline Actions:**
- Build and push Docker image on every commit to `main`.
- Deploy updated container automatically to the Kubernetes environment.

---

##  Problem Statement 2 – Automation Script (Bash/Python)

Two scripts are included:

1. **System Health Monitor** – Monitors CPU, Memory, and Disk usage. Logs alerts when thresholds are exceeded.  
   File: `system_health_monitor.sh`

2. **Application Health Checker** – Checks if a web application is up or down based on HTTP response codes.  
   File: `app_health_checker.py`

---

##  Problem Statement 3 – KubeArmor Zero-Trust Policy

**Objective:**  
Implement a basic KubeArmor zero-trust security policy for the deployed Wisecow app.

**Included Files:**
- `kubearmor-policy.yaml` – Example policy that blocks access to `/etc/passwd` for the Wisecow pod.
- `screenshot-kubearmor-violation.png` – Sample (placeholder) screenshot showing a simulated policy violation.

---

##  Repository Structure


