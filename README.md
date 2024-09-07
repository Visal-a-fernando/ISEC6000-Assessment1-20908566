# ISEC6000-Assessment1-20908566

## Project Overview
ISEC6000-Assessment 1 is a microservices-based e-commerce application deployed using the Saleor platform. This project demonstrates modern DevOps practices such as containerization with Docker, orchestration with Kubernetes, and deployment on Google Kubernetes Engine (GKE). The focus is on securing and scaling the application to handle real-world workloads.

## Tech Stack
- **Kubernetes (GKE):** Container orchestration and management.
- **Docker:** Containerization of microservices.
- **Saleor:** Open-source, Python-based e-commerce platform with API, Dashboard, and Storefront components.
- **Google Cloud SDK:** Managing GKE and other cloud resources.
- **PostgreSQL:** Database management for persistent data storage.
- **Redis:** In-memory data caching for optimized performance.

## Architecture
The application is built on a microservices architecture, including the following components:

- **Saleor API:** Backend services handling core e-commerce functionality.
- **Saleor Dashboard:** Admin interface for managing store operations.
- **Saleor Storefront:** Frontend for customer interactions.
- **PostgreSQL Database:** Persistent storage for application data.
- **Redis Cache:** Caches frequently accessed data for faster response times.

### Architecture Diagram
Will be added later **************

## Deployment Instructions

### Prerequisites
Before you start, ensure you have the following tools installed:

- [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)
- [Docker](https://docs.docker.com/get-docker/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/)
- [gke-gcloud-auth-plugin](https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-access-for-kubectl#install_plugin)

### Steps to Deploy
Will be added later **************

## Security Considerations
- **Container Security:** All containers are run as non-root users to reduce attack surfaces.
- **Vulnerability Scanning:** Trivy has been used to scan container images for vulnerabilities. Any detected issues have been remediated.
- **Network Policies:** Network policies have been implemented to restrict unnecessary traffic between services, enhancing security.
- **Runtime Security:** Continuous monitoring and logging are set up to detect and mitigate potential threats.

## Monitoring and Logging
- **Monitoring:** Prometheus and Grafana are configured for monitoring the application’s health and performance.
- **Logging:** ELK Stack (Elasticsearch, Logstash, Kibana) is used for centralized logging.

## Future Enhancements
- **CI/CD Integration:** Implement a continuous integration/continuous deployment pipeline using GitHub Actions or Jenkins for automated builds and deployments.
- **Auto-scaling:** Set up horizontal pod auto-scaling (HPA) to automatically adjust the number of pods based on resource usage.

## Contributors
- Visal Fernando (GitHub: [Visal-a-fernando](https://github.com/Visal-a-fernando))
