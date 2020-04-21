# Youtube link: 
https://www.youtube.com/watch?v=1xo-0gCVhTU

# prerequisites
homebrew install minikube
homebrew install kubectl

# start local kubernetes cluster
minikube start

# show kube pods
kubectl get pods

# show kube deployments
kubectl get deployments

# run a deployment from file
kubectl create -f "deployment.yml"

# opened a dashboard in browser window
minikube dashboard 

# get kube cluster public ip
minikube ip

# delete a deployment
kubectl delete deploy/myappdeployment

# delete a service
kubectl delete svc/helloworldservice
