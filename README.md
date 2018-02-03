Simple kubernetes setup for raspberry pi cluster.


-Uses weave network
-Install kubernetes Dashboard


TODO:
Setup ingress controller
autoscaler
scaling kube-dns


Usage:
Update inventory file
Run bootstrap.yml playbbok and then restart your hardware
Run site.yml

Warning:
This setup does not deal with security issues with kubeadm token. Would advice not to have it in yoaur ansible playbook.
Installs an unsupprted docker version > 17.03

Based on information from
https://kubecloud.io/setup-a-kubernetes-1-9-0-raspberry-pi-cluster-on-raspbian-using-kubeadm-f8b3b85bc2d1
