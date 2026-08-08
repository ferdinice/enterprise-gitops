# Enterprise GitOps Repository

This repository contains the Kubernetes manifests monitored by ArgoCD.

## Workflow

Developer
↓
Application Repository

Jenkins CI

Docker Build

Amazon ECR

Update GitOps Repository

ArgoCD Sync

Kubernetes Cluster

## Structure

applications/
ArgoCD Applications

base/
Base Kubernetes manifests

overlays/
Environment-specific manifests