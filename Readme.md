# GCP DevOps Flask Application Deployment on GKE

This repository contains a **Python Flask application** that is deployed on **Google Kubernetes Engine (GKE)** using **Cloud Build** for CI/CD.

---

## Overview

This project demonstrates a complete DevOps workflow on **GCP**, including:

- Containerizing a Flask application using Docker on Github. 
- Setting up **Cloud Build** to automatically build and push Docker images  
- Deploying the application to **GKE** using Kubernetes manifests (`gke.yaml`)  
- Managing resources in a specific **namespace** on the cluster  

---

## Prerequisites

Before running the deployment, ensure you have:

- A **Google Cloud Project**  
- **Cloud Build** enabled  
- **GKE Autopilot Cluster** created  
- **kubectl** installed and configured  
- **Dockerfile** in the project root

---
