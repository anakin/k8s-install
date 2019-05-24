# Kubernetes集群快速搭建指南
## 软件版本
- Etcd:3.3.13
- Kubernetes:v1.13.3
- calico:release-v2.6

## 环境准备
### 环境介绍
三台虚拟主机<br>
- IP地址：192.168.32.131-133
- 操作系统：Ubuntu-19.04

其中，131作为master节点，部署etcd,calico,apiserver,controller-manager,scheduler服务；其他两台作为worker，部署calico,proxy,kubelet服务。

所有操作使用root用户完成。

### 二进制文件下载地址
[网盘](https://pan.baidu.com/s/1mGt4nPJHfQs6Zjdi1xvFTg) 提取码: uz1n 

## 操作步骤
请参考我的[Blog](https://anakin.github.io/tags/kubernetes/)