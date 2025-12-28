\# Jenkins Multi-Cluster Deployment with Argo CD



\## Overview

Deploying different Jenkins versions across two Minikube clusters using Argo CD



\## Clusters

\- \*\*Cluster1\*\*: Jenkins v2.492.3

\- \*\*Cluster2\*\*: Jenkins v2.443.3



\## Git Structure

jenkins-multi-cluster/

├── cluster1/jenkins-2.492.3/

│ ├── namespace.yaml

│ ├── values.yaml

│ └── kustomization.yaml

├── cluster2/jenkins-2.443.3/

│ ├── namespace.yaml

│ ├── values.yaml

│ └── kustomization.yaml

└── README.md



