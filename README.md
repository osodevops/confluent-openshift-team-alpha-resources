# confluent-openshift-team-alpha-resources


### Debug
To check this has been added run:
```
kubectl get kustomizations
---
kubectl get GitRepositories -A
```
You should see that the status for both will be set to true, if there are any issues the status will be false and you can see the log to fix the error.
