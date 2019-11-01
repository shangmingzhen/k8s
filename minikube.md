minikube start --vm-driver=none
* minikube 1.5.2 is available! Download it: https://github.com/kubernetes/minikube/releases/tag/v1.5.2
* To disable this notice, run: 'minikube config set WantUpdateNotification false'

! minikube v1.4.0 on Centos 7.7.1908
* Running on localhost (CPUs=2, Memory=7821MB, Disk=40938MB) ...
* OS release is CentOS Linux 7 (Core)
* Preparing Kubernetes v1.16.0 on Docker 19.03.3 ...
* Pulling images ...
* Unable to pull images, which may be OK: running cmd: sudo env PATH=/var/lib/minikube/binaries/v1.16.0:$PATH kubeadm config images pull --config /var/tmp/minikube/kubeadm.yaml: running command: sudo env PATH=/var/lib/minikube/binaries/v1.16.0:$PATH kubeadm config images pull --config /var/tmp/minikube/kubeadm.yaml: exit status 1
* Launching Kubernetes ... 
* Configuring local host environment ...
* 
! The 'none' driver provides limited isolation and may reduce system security and reliability.
! For more information, see:
  - https://minikube.sigs.k8s.io/docs/reference/drivers/none/
* 
! kubectl and minikube configuration will be stored in /root
! To use kubectl or minikube commands as your own user, you may need to relocate them. For example, to overwrite your own settings, run:
* 
  - sudo mv /root/.kube /root/.minikube $HOME
  - sudo chown -R $USER $HOME/.kube $HOME/.minikube
* 
* This can also be done automatically by setting the env var CHANGE_MINIKUBE_NONE_USER=true
* Waiting for: apiserver proxy etcd scheduler controller dns
* Done! kubectl is now configured to use "minikube"
