Minikube

    minikube start - need to start minikube before creating a pod/service

    minikube ip - gets the ip of the virtual machine minikube is running

Kubernetes commands

    Prefix kubectle

    Suffixs

    apply -f <filename> - to create pod

    get pods - print running status of pods

    get services - prints running services

    get deployment

    describe <obj type> <obj name> - print info about obj, events during lifecycle of pod

    delete -f <filename> - used to delete pod or service

Kuberbetes

    - system to deploy containerized apps
    - Nodes , individual machines or vms that run containers
    - Masters - machines or vms with set of program to manage nodes
    - k8 gets images from else where , does not build  images
    - kubernetes (the master) decided where to run each container , each node can run dissimilar set of containers
    - to deploy update the master's state with config file
    -the master works contasntly to meet your desired state

K8 Objects

    Pods - used to run a container, smallest requirement needed to run containers with k8
    for containers that are needed to run together

    ex database, logger and backup manager working together , db is required for other two to work


    Services - sets up networking in k8 cluster

        Node Port - exposes a container to the outside (used for dev purposes)

API Version

    each api defines a  different set  of objects such as a pod to use
    look up the api versions required for the needed objects
