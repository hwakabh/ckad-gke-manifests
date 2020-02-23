# GKE Manifests

- Repository of GKE manifests for personal developments
- Motivations
  - Personal skill improvements for managing Kubernetes `Resources`
  - Preparations for `CKAD (Certified Kubernetes Application Developer)` exams
  - Stocks of manifests as operational examples

## Launching your Kubernetes environment

- For working out with your manifest, Kubernetes environment should be needed of course.
  - You can choose any of the options to establish the environment:
    - Managed Services
      - GKE: Google Kubernetes Engine
      - EKS: Amazon Elastic Kubernetes Service
      - AKS: Microsoft Azure Kubernetes Service
    - On-Prems
      - Upstream Kubernetes
      - PKS: Pivotal Kubernetes Services
    - For Laptops hosted
      - Minikube

  - Brief procedures booting up your kubernetes cluster in GCP, for example, are:
    - Just run `gcloud container clusters YOUR_K8S_CLUSTER_NAME`

## Envionments

```bash
$ kubectl version --short=True
Client Version: v1.15.2
Server Version: v1.13.12-gke.25
```

## Licenses and Refernces

- As aligining to the sources under MIT licenses, all of contents in this repository follows to MIT licenses.  
  - The manifests in this repository are solutions for problem-sets of CKAD example questions
  - The links or refs for the example questions
    - <https://github.com/dgkanatsios/CKAD-exercises>
