# KubeOperator Ansible 脚本

[KubeOperator](https://github.com/KubeOperator/KubeOperator) 是一个开源的轻量级 Kubernetes 发行版，专注于帮助企业规划、部署和运营生产级别的 K8s 集群。

该项目为 KubeOperator 安装包相关内容，包含了 KubeOperator 的安装脚本及默认配置文件等。

## 安装 netaddr 模块
```
pip install --no-cache-dir netaddr==0.7.19 -i https://mirrors.aliyun.com/pypi/simple/
```

## 执行安装
```
ansible-playbook -i hosts.hostname.ini -e @variables.yml 90-init-cluster.yml
```

## 问题反馈

如果您在使用过程中遇到什么问题，或有进一步的需求需要反馈，请提交 GitHub Issue 到 [KubeOperator 项目的主仓库](https://github.com/KubeOperator/KubeOperator/issues)
