## Tutorial
```
# Please use CentOS-7 for this tutorial

$ cd /etc/ansible/roles/ 

$ sudo git clone https://github.com/88K/tutorials.git

$ cd tutorials

# If you want to install everything
$ ansible-playbook install.yaml

#If you want to execute specific tags
$ ansible-playbook install.yaml -t tag_name

Tags:
ansible-playbook install.yaml --list-tags
[firewall, grafana, haproxy, node_exporter]
```

## What will be the outcome of this tutorial?

### Applications: 
```
Grafana (Port: 443)
Node-Exporter (Port: 9100)
HA-Proxy (Port: 80 > Port: 443)
```
### SystemD Services:
```
grafana 
node-exporter
haproxy
```

### Install Location:
```
/opt/[application]
```


#### [Must] To-Do
```
Add Ansible Tags: https://docs.ansible.com/ansible/2.4/playbooks_tags.html
```



