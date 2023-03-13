```
kubeadm init --kubernetes-version=v1.25.6 \
     --control-plane-endpoint=kubeadm-vip.linux.io \
     --apiserver-advertise-address=0.0.0.0 \
     --pod-network-cidr=10.244.0.0/16 \
     --service-cidr=10.96.0.0/12 \
     --image-repository=registry.cn-hangzhou.aliyuncs.com/google_containers \
     --ignore-preflight-errors=Swap | tee kubeadm-init.log
```
