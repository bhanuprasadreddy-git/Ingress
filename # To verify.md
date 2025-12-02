# To verify

# RUN

kubectl get pods -n game-2048  -  Check if app pods are running

kubectl get svc -n game-2048   - Check how the app is exposed inside the cluster

kubectl get ingress -n game-2048  - Check if ALB is created and get public URL

