# kubernetes-using-minikube-example

##Using minikube with .yaml config files

###Create pods
minikube start
kubectl create -f [yourfile]

###Check pods and services
kubectl get pods
kubectl get services

###Open your service in the host
####Get ip
minikube ip
####Open your service
type ip of minikube:[nodePort] in browser
