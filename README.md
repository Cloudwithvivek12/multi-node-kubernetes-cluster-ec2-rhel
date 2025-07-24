# How to Setup Multi-Node Kubernetes Cluster in EC2 RHEL

This documentation helps you set up a high-availability Kubernetes cluster using multiple EC2 instances running on RHEL (Red Hat Enterprise Linux).

## 🧰 Requirements
- AWS EC2 account
- 2+ EC2 RHEL instances
- SSH access
- Docker, kubeadm, kubectl installed

## 🛠️ Steps

1. Launch EC2 instances (master & worker nodes)
2. Set hostname and update `/etc/hosts`
3. Install Docker and Kubernetes tools
4. Initialize Kubernetes master node using `kubeadm init`
5. Join worker nodes using `kubeadm join`

## 📂 Directory Structure
