# Kafka template yaml
kafka and zookeeper using docker image from bitnami

### How to run:
1. Deploy zookeeper 
``` 
kubectl apply -f zookeeper-deployment.yaml

kubectl create -f zookeeper-service.yaml

```
2. Deploy kafka
```
kubectl apply -f kafka-deployment.yaml

kubectl create -f kafka-service.yaml
```
