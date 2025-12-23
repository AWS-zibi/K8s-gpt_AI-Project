🧠 Kubernetes AI Debugging with k8sgpt (Minikube + Gemini) 

#Project Overview# 

This project demonstrates how to deploy a simple Kubernetes application on Minikube and use k8sgpt with Google Gemini AI to automatically analyze, detect, and explain real Kubernetes issues. 

The focus of this project is AI-assisted Kubernetes troubleshooting, not just deployment. 

#Project Highlights# 

Kubernetes running locally using Minikube 

Application deployed using Deployment + ClusterIP Service 

Automated cluster analysis using k8sgpt 

AI-powered explanations using Google Gemini 

Real-world Kubernetes errors detected and resolved 

#Tech Stack# 

Kubernetes: Minikube 

Application: NGINX 

Service Type: ClusterIP 

AI Tool: k8sgpt 

AI Provider: Google Gemini 

OS: Ubuntu (Local) 


###Kubernetes Architecture###  

 Developer
   |
   v
kubectl apply
   |
   v
Minikube Cluster
   |
   ├── Deployment (NGINX)
   ├── Pod
   └── ClusterIP Service
   |
   v
k8sgpt
   |
   v
Google Gemini AI
   |
   v
Root Cause Analysis & Fix Suggestions


<img width="346" height="259" alt="Screenshot from 2025-05-19 10-52-41" src="https://github.com/user-attachments/assets/29ac76e3-f8f7-4318-9250-0c2865090e8a" />
<img width="1509" height="757" alt="Screenshot from 2025-12-23 14-32-33" src="https://github.com/user-attachments/assets/5a781d84-8e45-486d-a279-861cf00871a5" />

