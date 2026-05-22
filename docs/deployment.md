# Deployment

kubectl apply -f kubernetes/

Verify:

kubectl get pods -n nexoryx-vpn
kubectl get svc -n nexoryx-vpn
kubectl get ingress -n nexoryx-vpn
