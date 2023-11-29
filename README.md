# adventcalendar2023-deploy-ayame-ansible
アドベントカレンダー2023向けの SEIL/x86 Ayame を Ansible でデプロイするためのサンプルです。

# 必要なモジュール
- community.libvirt
- linux-system-roles.network


# 依存モジュールのインストール
```shell
ansible-galaxy collection install community.libvirt
ansible-galaxy install linux-system-roles.network
```

# 実行
```shell
ansible-playbook -i ./inventory.yml Ayame-deploy.yml

```