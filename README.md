Ingress for minikube steps (https://kubernetes.github.io/ingress-nginx/deploy/)
1- kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/mandatory.yaml
2- \$ minikube addons disable ingress

then run
kubectl apply -f ingress/
