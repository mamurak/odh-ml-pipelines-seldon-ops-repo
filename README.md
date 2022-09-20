This repository is used to showcase ML model deployment through GitOps.

# How to use

- Fork this repository.
- Update 
- Set up your GitOps agent (e.g. ArgoCD) to sync the target Kubernetes namespace with the `manifest` folder content.
- Set up your ML training pipeline to commit a `SeldonDeployment` manifest to the `manifest` folder after model training (see [ODH ML Pipelines Seldon]()).
