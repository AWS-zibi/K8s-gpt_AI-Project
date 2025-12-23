###🧠 Kubernetes AI Debugging with k8sgpt (Minikube + Gemini)###
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
DevOps
   |
   v
kubectl apply
   |
   v
Minikube Cluster
   |__ App/ index.html
   ├── Deployment (NGINX)
   ├── Pod
   └── Service  ClusterIP
   |
   v
k8sgpt
   |
   v
Google Gemini AI
   |
   v
Root Cause Analysis & Fix Suggestions
