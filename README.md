# KubeOperator 3.0 Ansible Playbooks

# 安装 netaddr 模块
pip install --no-cache-dir  netaddr==0.7.19 -i https://mirrors.aliyun.com/pypi/simple/

# 执行安装
ansible-playbook -i hosts 90-init-cluster.yml
