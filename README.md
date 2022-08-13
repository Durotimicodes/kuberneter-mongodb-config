#To deploy you application using the Kubectl command line tool use this commands
1. kubectl apply -f mongo-secret.yaml
2. kubectl apply -f mongo-config.yaml
3. kubectl apply -f mongo.yaml
4. kubectl apply webapp.yaml

#To get all component
kubectl get all

#To get config and secret
kubectl get config
kubectl get secret
kubectl get pod

#To get other sub commands
kubectl --help
kubectl describe
kubectl logs "name of the pod"
