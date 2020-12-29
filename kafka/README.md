# Kafka template yaml
kafka and zookeeper using docker image from bitnami. This template for local development.

### How to run:
1. Deploy zookeeper 
``` 
kubectl apply -f zookeeper-deployment.yaml

kubectl create -f zookeeper-service.yaml

```
2. Deploy kafka
```
kubectl create -f kafka-service.yaml
```
replace IP 10.64.140.43 to your EXTERNAL IP kafka-service on kafka-deployment.yaml
```
kubectl apply -f kafka-deployment.yaml
```
