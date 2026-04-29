# Kupher Tools
# 🚀 Extend Kubernetes. Empower Platform Engineers. Built with Go.

**Welcome to Kupher Tools** — a growing suite of lightweight tools, controllers, operators, and admission plugins written in idiomatic Go to extend Kubernetes for real-world platform engineering use cases.

> **What is Kupher?**  
> Kupher = Kubernetes + Gopher 🐹  
> Think of it as “Kubernetes by Gophers, for Platform Engineers.”

---

## 🧩 Why Kupher Tools?

Modern platform engineering needs more than vanilla Kubernetes.

You need to **automate governance**, **enforce security policies**, and **customize controllers** to scale internal developer platforms (IDPs). Kupher helps you do just that — the Go way.

Kupher Tools aims to provide:

- 🛠️ **Modular, production-grade Kubernetes extensions** in Go  
- 🔐 **Policy enforcement & automation** via admission controllers and webhooks  
- ⚙️ **Practical utilities** for GitOps, security, developer experience, and more  

---

## 📦 What You'll Find in This Org

Each repository solves a focused problem using **minimal, maintainable Go code**:

- ✅ Kubernetes Operators  
- ✅ Admission Controllers & Webhooks  
- ✅ Custom Controllers & Platform Automations  
- ✅ CLI Tools for Ops & GitOps  
- ✅ Platform Engineering Utilities  

---

## 🤝 Contribute to Kupher

Want to extend Kubernetes?  
Want to solve real-world platform problems with Go?  
Want to build tools you actually use in production?

**Join Kupher** and collaborate with like-minded engineers.

Whether you’re a beginner in writing operators or a pro in Kubernetes internals — we welcome ideas, issues, discussions, and PRs.

> 👉 [Star this repo](#)  
> 👉 [Browse open issues](#)  
> 👉 [Join the community](#)  

Let’s build Kubernetes the Gopher way.

---


## Completed Applications
| Sr. No | App Name                          | App Type             | Description                                                                 |
|--------|-----------------------------------|----------------------|-----------------------------------------------------------------------------|
| 1      | [Auto-mTLS](https://github.com/kupher-tools/auto-mtls)        | K8s Operator | Auto-mTLS is a lightweight Kubernetes operator that enables mutual TLS (mTLS) between services automatically, without requiring a full service mesh.  |
| 2      | [registry-policy-controller](https://github.com/kupher-tools/registry-policy-controller)        | Admission Controller | Admission Controller to enforce image registry policies per namespace and across cluster.               |
| 3      | [kube-tenantctl](https://github.com/kupher-tools/kube-tenantctl)       | CLI| A CLI for tenant management in multi-tenant Kubernetes Cluster               |
| 4      | [namespace-ripper-operator](https://github.com/kupher-tools/namespace-ripper-operator)         | Operator             | A K8s Operator to manage namespace lifecycle based on Time-To-Live (TTL).          |
| 5      | [KupherCD](https://github.com/kupher-tools/KupherCD)                         | Custom Controller    | A lightweight Kubernetes controller that monitors Image Registry for new container image tags and automatically updates Deployments when a newer version is available. |
| 6      | [reloader-operator](https://github.com/kupher-tools/reloader-operator)                 | Operator             | A lightweight Kubernetes operator that automatically restarts deployments when their referenced ConfigMaps change.     |
| 7      | [podcensor-controller](https://github.com/kupher-tools/podcensor-controller)              | Admission Controller |A admission controller to censor naked Pods at the gate — only dressed (i.e., managed) workloads allowed.     |



## Tech Stack
- Go 1.22+

- Controller-runtime

- Kubernetes API Machinery

- Webhooks & AdmissionReview

- Git, REST, YAML
  
- Optionally: OPA, Helm, ArgoCD, etc.

## Stay Connected
Follow Rajesh Deshpande for updates, deep dives, and myth-busting Kubernetes content.
