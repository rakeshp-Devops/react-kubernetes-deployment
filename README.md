# Start Minikube
minikube start

# Deploy app
kubectl apply -f deployment.yaml

# Expose service
kubectl apply -f service.yaml

# Check resources
kubectl get pods
kubectl get svc

# Access application
minikube service react-webapp-service

