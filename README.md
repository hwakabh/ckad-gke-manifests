# GKE Manifests

- Repository of GKE manifests for personal developments
- Motivations
  - Personal skill improvements for managing Kubernetes `Resources`
  - Preparations for `CKAD (Certified Kubernetes Application Developer)` exams
  - Stocks of manifests as operational examples

***

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

***

## Envionments

```bash
$ kubectl version
Client Version: version.Info{Major:"1", Minor:"17", GitVersion:"v1.17.0", GitCommit:"70132b0f130acc0bed193d9ba59dd186f0e634cf", GitTreeState:"clean", BuildDate:"2019-12-07T21:20:10Z", GoVersion:"go1.13.4", Compiler:"gc", Platform:"darwin/amd64"}
Server Version: version.Info{Major:"1", Minor:"13+", GitVersion:"v1.13.11-gke.23", GitCommit:"93457f9dac45d5f95c2c609232e1ff2343c72684", GitTreeState:"clean", BuildDate:"2020-01-14T06:01:01Z", GoVersion:"go1.12.11b4", Compiler:"gc", Platform:"linux/amd64"}
```

***

## Licenses and Refernces

- As aligining to the sources under MIT licenses, all of contents in this repository follows to MIT licenses.  
  - The manifests in this repository are solutions for problem-sets of CKAD example questions
  - The links or refs for the example questions
    - <https://github.com/dgkanatsios/CKAD-exercises>
