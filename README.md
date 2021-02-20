## datou-k8-calico
---

#### Overview

By default, Kubernetes uses a flat network topology. This doesn't follow conventional security practices to segment networks to reduce impact if any part of the network was compromised. Calico helps to 

#### Pre-requisites

- Minikube - see [datou-k8](https://github.com/datou-tech/datou-k8)
- Install calicoctl - `brew install calicoctl`

#### Setting up

- Start minikube - `minikube start --network-plugin=cni --cni=calico  --driver=hyperkit`

#### Set Up a Network Policy

