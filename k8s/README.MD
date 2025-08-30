
# cria uma configmap
kubectl create configmap app-config --from-literal=APP_NAME="teste 123"
kubectl describe configmaps app-config

# criacao de secret
kubectl create secret generic app-secret --from-literal=APP_NAME="teste 123"


