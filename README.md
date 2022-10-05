# kubernetes-efk
EFK Kubernetes manifests



# install

Create Fluentd Cluster Role
kubectl create -f https://raw.githubusercontent.com/truanguyenvan/kubernetes-efk/main/fluentd/fluentd-role.yaml

Create Fluentd Service Account 
kubectl create -f https://raw.githubusercontent.com/truanguyenvan/kubernetes-efk/main/fluentd/fluentd-sa.yaml

Creste Fluentd Cluster Role Binding
kubectl create -f https://raw.githubusercontent.com/truanguyenvan/kubernetes-efk/main/fluentd/fluentd-rb.yaml

Deploy Fluentd DaemonSet

kubectl create -f https://raw.githubusercontent.com/truanguyenvan/kubernetes-efk/main/fluentd/fluentd-ds.yaml

https://devopscube.com/setup-efk-stack-on-kubernetes/
