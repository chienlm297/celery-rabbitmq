
### Install Rabbitmq

```
helm install rabbitmq --set auth.username=xxx,auth.password=xxxx,persistence.size=5Gi,persistence.storageClass=linode-block-storage-retain bitnami/rabbitmq --namespace converter
```