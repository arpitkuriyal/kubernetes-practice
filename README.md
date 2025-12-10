# Kubernetes Learning Notes

This repository contains my notes and practice manifests while learning Kubernetes through [Boot.dev](https://www.boot.dev/).
I covered the core building blocks of deploying and managing containerized applications in a cluster.

## Concepts Learned

### **Pods**
- Basic unit of deployment  
- Created Pods using YAML and `kubectl`  
- Understood Pod lifecycle and logs  

### **Deployments**
- Managed stateless apps using Deployments  
- Performed rolling updates and rollbacks  
- Learned how ReplicaSets maintain desired state  

### **Services**
- Exposed applications internally and externally  
- Used ClusterIP, NodePort, and LoadBalancer  
- Understood service discovery inside the cluster  

### **Gateway API**
- Modern alternative to Ingress  
- Created Gateways and HTTPRoutes  
- Routed external traffic to backend services  

### **Volumes**
- **Ephemeral volumes** (`emptyDir`, ConfigMap, Secret) for temporary data  
- **PersistentVolume + PVC** for durable storage  
- Learned mounting and storage provisioning  

### **Namespaces**
- Organized resources logically  
- Used namespaces for isolation between environments  

## Tools Used
- Minikube
- kubectl  
- Docker  

## Summary
This project documents my practical understanding of Kubernetes fundamentals:
deploying apps, exposing them, managing storage, and structuring clusters using namespaces.
