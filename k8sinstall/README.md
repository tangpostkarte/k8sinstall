# 使用说明

## basic_config role

### defaults中的main.yaml为当前role的变量, k8s_hosts为当前安装的主机列表，需要把自己安装的主机定义在里面

## install_containerd 为安装containerd的role

## install_runc 为安装runc的role

## install_cni_plugin为安装cni plugin的role

## install_k8s_binaries 为安装kubeadm kubelet kubectl的role

## kubeadm_init 为初始化master节点的role

## install_flannel 为部署flannel的role

### default中的main.yaml定义的变量为kubeadm初始化配置文件里面的一些变量

- masterHostName master节点主机名
