# K8s Homelab

A self-hosted 5-node Kubernetes cluster to simulate an on-prem enterprise environment. Built to master Kubernetes fundamentals, Linux, networking, automation, and observability—skills I’m sharpening after reflecting on my Visa Systems Engineer interview.

## Project Overview
- **Purpose**: Deploy a production-like K8s setup at small scale (1 control plane + 4 workers) to prove I can manage and troubleshoot clusters, targeting skills for Visa’s 100-cluster, 5000-node environment.
- **Timeline**: March 15 - April 7, 2025 (24 days, 2-3 hrs/day).
- **Hardware**: Beelink Mini PC (control plane + 2 VMs), 2 Raspberry Pi 4s (workers).

## Goals
1. **K8s Basics**: Pods, services, deployments, namespaces, `kubectl`.
2. **On-Prem**: Node management, failure troubleshooting.
3. **Networking**: Calico CNI, Ingress.
4. **Automation**: Ansible for cluster setup.
5. **Resilience**: Node failure and recovery.
6. **Security**: Container image scanning with Trivy.
7. **Portfolio**: Documented on GitHub for recruiters.

## Progress
- [x] Repository created (Mar 23, 2025).
- [ ] Hardware ordered (Mar 25, 2025).
- [ ] Cluster setup (Mar 29-31, 2025).

## Setup Guide
*(To be completed as hardware arrives and cluster is built.)*

## What I Learned
*(Will document growth—e.g., mastering pod networking with Calico after interview struggles.)*

## Next Steps
- Order hardware (Tuesday, Mar 23).
- Start Ansible playbooks and K8s manifests pre-hardware.
- Update README with setup steps and screenshots.

---
Questions? Ping me or check the [docs/](docs/) folder as I build this out!
