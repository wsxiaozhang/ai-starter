## 配置本地环境

如果您需要在本地管理或者访问Kubernetes集群，需要做如下配置：
* 安装kubectl。 (安装Kubectl)[https://kubernetes.io/docs/tasks/tools/install-kubectl/]
* 下载集群凭证。在控制台集群详情中获取Kubeconfig。并将集群凭证放置到 `$HOME/.kube/config` 文件


#### 下载凭证
进入容器服务控制台，集群详情页面。 点击复制
![image.png](images/kubeconfig.png)

将内容复制到 `$HOME/.kube/config` 文件。