# DevOps Project: Kubernetes Application Deployment with GitOps

## Project Overview

This repository contains all the necessary code and configurations to deploy a multi-component application on a local Kubernetes cluster using GitOps principles with Argo CD. The application consists of:
* Three distinct NGINX servers serving static content.
* A Python Flask/FastAPI application that acts as a routing layer, forwarding requests to the appropriate NGINX backend based on a `cellID`.
* An observability stack (Prometheus, Grafana, Alertmanager) to monitor the cluster and applications.

The goal of this project is to demonstrate modern DevOps practices, including:
* Local Kubernetes cluster setup with Kind.
* GitOps workflow with Argo CD.
* Containerization of applications.
* Service discovery and routing within Kubernetes.
* Comprehensive observability for application health and performance.
* Consideration of security best practices.

## Project Goals

* Establish a robust local Kubernetes environment.
* Implement a GitOps flow for infrastructure and application deployment.
* Develop and deploy a Python routing application integrated with NGINX backends.
* Set up a complete observability stack.
* Document security considerations and best practices.

## Getting Started

More detailed instructions will be provided in subsequent sections, including prerequisites, setup steps, and testing procedures.

## Repository Structure