# To verify


Check if app pods are running
# RUN

kubectl get pods -n game-2048

Check how the app is exposed inside the cluster
# Run
kubectl get svc -n game-2048

Check if ALB is created and get public URL
# Run

kubectl get ingress -n game-2048   

