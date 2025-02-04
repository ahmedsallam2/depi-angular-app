# depi-angular-app

---

# **k8s-lab: Kubernetes and Docker Compose Lab Setup on CentOS 9**

## **Project Overview**
This project sets up a **Kubernetes cluster (one master, one worker node) and Docker Compose environment** on CentOS 9. The goal is to experiment with containerized applications using both **Docker Compose** for local development and **Kubernetes** for orchestration.

---

## **Steps to Set Up the Project**

### **1. Install and Configure Git**
- Install Git on CentOS 9.
- Configure Git with a username and email.
- Generate an SSH key and add it to GitHub.

### **2. Set Up GitHub Repository**
- Create a GitHub repository.
- Clone the repository to the local machine.
- Install and authenticate GitHub CLI (`gh`).

### **3. Install Docker and Docker Compose**
- Install Docker for container management.
- Enable and start the Docker service.
- Install Docker Compose for multi-container applications.

### **4. Set Up Docker Compose Environment**
- Create a `docker-compose.yaml` file defining services.
- Deploy services using Docker Compose.
- Verify running containers.

### **5. Prepare the System for Kubernetes**
- Disable swap for Kubernetes.
- Install `kubeadm`, `kubelet`, and `kubectl`.
- Enable the `kubelet` service.

### **6. Configure Firewall for Kubernetes**
- Open required ports for Kubernetes communication.
- Reload firewall rules.

### **7. Initialize Kubernetes Cluster**
- Initialize Kubernetes on the master node using `kubeadm`.
- Configure `kubectl` for cluster administration.

### **8. Install a Networking Plugin**
- Deploy a networking solution like Calico for pod communication.

### **9. Join Worker Node to the Cluster**
- Use the `kubeadm join` command to connect the worker node.
- Verify cluster status.

### **10. Deploy a Sample Application with Kubernetes**
- Define a deployment and apply it using `kubectl`.
- Verify that pods are running.

### **11. Expose the Application Using a Kubernetes Service**
- Create a service definition.
- Deploy and check the service status.

### **12. Validate Setup**
- List running containers, pods, and services.
- Debug any issues encountered.

### **13. Commit and Push Project Files**
- Add all changes to Git.
- Commit and push the files to GitHub.

### **Future Enhancements**
- Automate deployments with Helm.
- Implement CI/CD pipelines.
- Add monitoring tools like Prometheus and Grafana.
- Use Terraform for infrastructure automation.

---

This documentation covers both **Docker Compose** and **Kubernetes** setups, allowing for flexible container management. Adjust as needed based on additional configurations.
