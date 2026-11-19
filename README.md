# Introduction to Argo CD Template

These are the supporting files for [the Introduction to Argo CD tutorial](https://docs.akuity.io/tutorials/intro-to-argo-cd/) in the Akuity docs.

This repository follows an external tutorial. Confirm the tutorial files' reuse terms before adding a repository-wide license. Copy `akuity-platform/argocd-secret.example.yaml` to `akuity-platform/argocd-secret.yaml` and generate a unique admin password hash locally. The local secret file is ignored by Git. Change any admin password used with the old committed example.

This tutorial will walk you through implementing Argo CD with the Akuity Platform, to manage the deployment of the Helm charts in a declarative fashion.

Ultimately, you will have a Kubernetes cluster, with Applications deployed using an Argo CD control plane.
