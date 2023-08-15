# prometheus-cicd

Passo a passo:
https://devopscube.com/setup-prometheus-monitoring-on-kubernetes/

kubectl create namespace monitoring
kubectl create -f clusterRole.yaml
kubectl create -f config-map.yaml
kubectl create -f deployment.yaml