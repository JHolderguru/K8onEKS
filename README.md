## commands to run kubernetes using the cmd

## Prerequisite

#### Install kubctl and eksctl com

#### kubectl version to verify

#### on fargate
#### eksctl create cluster

#### on ec2 for more granularity

####   example of provision 2 t2 nodes
```eksctl create cluster --name Test-Cluster --version 1.17 --region eu-west-1 --nodegroup-name linux-nodes --node-type t.2 micro --nodes 2```

#### ```
kubectl get node

kubectl get pod

kubectl get ns ```
####
