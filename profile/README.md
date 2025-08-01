# Kupher Tools
Extend Kubernetes. Empower Platform Engineers. Built with Go.

**Welcome to Kupher Tools — a collection of purpose-built tools, controllers, operators, and admission plugins written in Go to extend Kubernetes capabilities and solve real-world platform engineering challenges.**

By the way, what is Kupher ? ---> Its **Ku**bernetes by Go**pher**

## Why Kupher Tools?
Modern platform engineering demands more than vanilla Kubernetes.

From automating governance to enforcing security policies, scaling developer platforms to customizing controllers — Kubernetes extensibility is key.

## Kupher Tools enables:

- Seamless Kubernetes extension using idiomatic Go

- Practical solutions for internal developer platforms (IDPs)

- Production-grade patterns for GitOps, policy enforcement, automation, and more

## What You'll Find Here
Each repository in the org solves a specific problem with a focused and minimal Go-based Kubernetes extension.

✅ Kubernetes Operators

✅ Admission Controllers

✅ Webhooks

✅ Custom Controllers

✅ CLI tools for automation

✅ GitOps tools & platform plumbing utilities

## Completed Applications
| Sr. No | App Name                          | App Type             | Description                                                                 |
|--------|-----------------------------------|----------------------|-----------------------------------------------------------------------------|
| 1      | registry-policy-controller        | Admission Controller | Blocks naked Pods and enforces controller-backed workloads.                |
| 2      | namespace-ripper-operator         | Operator             | Auto-updates Deployments using latest image tags from Docker Hub.          |
| 3      | KupherCD                          | Custom Controller    | Restarts Deployments on ConfigMap changes using annotation-based triggers. |
| 4      | reloader-operator                 | Operator             | Periodically checks and syncs Deployment image tags across registries.     |
| 5      | podcensor-controller              | Admission Controller | Enforces namespace-level policies (e.g., allowed registries, labels).      |



## Tech Stack
- Go 1.22+

- Controller-runtime

- Kubernetes API Machinery

- Webhooks & AdmissionReview

- Git, REST, YAML
  
- Optionally: OPA, Helm, ArgoCD, etc.

## Stay Connected
Follow Rajesh Deshpande for updates, deep dives, and myth-busting Kubernetes content.
