We can create a k8s cluster using GKE. Using Google cloud CLI or Google Cloud SDK we can create a k8s cluster. 

Creating cluster from CLI
- Install Google cloud SDK https://cloud.google.com/sdk/docs/install
- `gloud container cluster create test-cluster`
  - GKE creates a managed headnode and 3 worker nodes by default
  - It also configures local kubectl to connect to the cluster
- `gcloud container clusters list`
- `kubectl get nodes`
