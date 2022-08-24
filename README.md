# Ansible-k8s-1-master
This is an Ansible Playbook to create a simple Kubernetes cluster


run command:



ansible-playbook main.yml -i inventory --extra-vars "containerd_version='1.6.4-1' kube_ver='1.24.1-00' etcd_ver='v3.4.19' init_ver='1.24.1' calico_ver='v3.21'"
