# Let's GitOps!  A semi-opinionated tutorial for those just getting into GitOps.

## Introduction

GitOps is a large topic that covers can include a number of different tools and techniques.  There is no "wrong" or "right" way to build out your own GitOps practices, but there are certainly a few tools and techniques that come up frequently.  Obviously, there is [git](https://git-scm.com/) and [Kubernetes](https://kubernetes.io/).  In between, there are a lot of different tools you can use to manage the "Ops", and more are appearing each day.  The key to a good GitOps practice is having a way to *template* your Kubernetes manifests in order to reduce copy/paste, and a way to manage the lifecycle of these manifests on your Kubernetes clusters.

This tutorial will focus on two of the most popular tools for the job:
* [Kustomize](https://github.com/kubernetes-sigs/kustomize) for templating, and
* [Argo CD](https://argoproj.github.io/argo-cd/) for Lifecycle / Continuous Deployment


