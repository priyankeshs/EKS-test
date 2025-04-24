# EKS-test
to test EKS and others

to deploy on EKS:
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl apply -f ingress.yaml

We need to have alb setup on aws to expose this to outside world.

