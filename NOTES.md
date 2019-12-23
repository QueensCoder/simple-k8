Minikube

    minikube start - need to start minikube before creating a pod/service

    minikube ip - gets the ip of the virtual machine minikube is running

Kubernetes commands

    Prefix kubectle

    Suffixs

    apply -f <filename> - to create pod

    get pods - print running status of pods

    get services - prints running services

K8 Objects

    Pods - used to run a container, smallest requirement needed to run containers with k8
    for containers that are needed to run together

    ex database, logger and backup manager working together , db is required for other two to work


    Services - sets up networking in k8 cluster

        Node Port - exposes a container to the outside (used for dev purposes)

API Version

    each api defines a  different set  of objects such as a pod to use
    look up the api versions required for the needed objects
