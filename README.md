# Manual for the patrickstestcontainer-job.yml Job Config

Example Job config file, for applying a workload at a Kubernetes Service

# Sources for the Job Config

I'd like to refer to following to lins, which I've used for for that example:

[kubernetes.io - workloads - job](https://kubernetes.io/docs/concepts/workloads/controllers/job/)


## Applying the Job at a Kubernetes Service

Use following command for applying that job config at a Kubernetes Service - be ware that the Container Image has to exist at a Container Registry - in that case it's an example which I've used for a blog post.

```
kubectl apply -f patrickstestcontainer-job.yml
```

