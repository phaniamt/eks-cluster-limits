# eks-cluster-limits

### Install weave net in EKS cluster ###
    kubectl apply -f "https://cloud.weave.works/k8s/net?k8s-version=$(kubectl version | base64 | tr -d '\n')"
