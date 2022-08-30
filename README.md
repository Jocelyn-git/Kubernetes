# ingress-nginx

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.1.1/deploy/static/provider/baremetal/deploy.yaml  

kubectl port-forward service/ingress-nginx-controller -n ingress-nginx 8888:80

kubectl apply -f ingress1.yaml

http://myhost.local    (set Host by ModHeader)  
