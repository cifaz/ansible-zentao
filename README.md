cifaz.ansible-zentao
========================
  
本实例使用的tar解压安装
```
ansible-galaxy install cifaz.ansible-zentao
```
  
### 运行
```
- hosts: local
  remote_user: root
  roles:
    - {role: "ansible-zentao", tag: "zentao"}

```
  
### 未完事项
自定义配置, 可配置httpd mysql等相关事项

