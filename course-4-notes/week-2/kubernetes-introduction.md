# 🤖 Kubernetes - Introduction

**For detailed information check the** [**Kubernetes Basics tutorial**](https://kubernetes.io/docs/tutorials/kubernetes-basics/)**.**

### General Idea

![Kubernetes Main Steps](<../../.gitbook/assets/image (11) (1).png>)

Key concepts

* **Kubernetes -** _production-grade, open-source platform that orchestrates the placement (scheduling) and execution of application containers within and across computer clusters._
* **Cluster -** _manage the cluster and the nodes that are used to host the running applications._
* **Node** - _worker machine in Kubernetes and may be either a virtual or a physical machine, depending on the cluster. Each Node is managed by the control plane._
* **Control Pane -** _responsible for managing the cluster_
* **Deployment** - _responsible for creating and updating instances of your application_
* **Pod** - _a group of one or more application containers (such as Docker) and includes shared storage (volumes), IP address, and information about how to run them._
* **Service** _- abstraction layer which defines a logical set of Pods and enables external traffic exposure, load balancing, and service discovery for those Pods._

![Cluster Diagram: See details](<../../.gitbook/assets/image (9) (1).png>)

`kubectl` main commands:

* `kubectl version`
* `kubectl get nodes`
* `kubectl create deployment`
* `kubectl get deployments`
* `kubectl describe`
* `kubectl logs`
* `kubectl exec`
* `kubectl proxy`
* `kubectl expose`
* `kubectl label`
* `kubectl scale`
* `kubectl set image` (to perform updates)
* `kubectl rollout undo`

For a complete list of commands, you can check the kubectl commands [cheat sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/) and the [getting started](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands) site.

![Node overview. See details in Kubenetes site](<../../.gitbook/assets/image (7) (1).png>)

