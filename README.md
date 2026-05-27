# Guestbook Application: Containerization & Orchestration

This project documents the containerization and deployment of a Guestbook web application. It demonstrates the full lifecycle of an application from local development using **Docker** to production-grade orchestration using **Kubernetes**.

## 🔗 Portfolio
- **Website:** [frankfru.com](https://frankfru.com)
- **LinkedIn:** [Insert your LinkedIn profile link here]
- **GitHub:** [chifru19](https://github.com/chifru19)

## 🛠 Project Highlights
- **Containerization:** Built and containerized a Node.js web application.
- **Orchestration:** Implemented Kubernetes **Deployments** for scalable instances and **DaemonSets** for cluster-wide node coverage.
- **Scaling:** Configured **Horizontal Pod Autoscaler (HPA)** to dynamically scale replicas based on CPU demand.
- **Version Control:** Managed rolling updates and rollbacks to ensure zero-downtime deployments.
- **Security:** Integrated secret management and configuration maps for secure environment variable handling.

## 📸 Lab Evidence
Detailed evidence of the lab progress can be found in the [screenshots/](screenshots/) folder.
- **Registry & Build:** Images verified in the IBM Cloud Container Registry.
- **Deployment Status:** Verification of Pods, Services, and HPA configuration.
- **Rolling Update:** Transitioning from v1 to v2 application versions.

## 📂 Project Structure
```text
├── screenshots/          # Evidence of lab completion
├── Dockerfile            # Container definition
├── deployment.yml        # Deployment configuration
├── daemonset.yaml        # DaemonSet configuration
├── service.yaml          # Service routing
├── volume-and-pvc.yaml   # Storage configuration
└── deployment_evidence.txt # CLI log output