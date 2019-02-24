## Tutorial
$ cd /etc/ansible/roles/ 
$ sudo git clone https://github.com/88K/tutorials.git
$ cd tutorials
$ ansible-playbook install.yaml

## What will be the outcome of this tutorial?

### Applications: 
Grafana (Port: 443), Node-Exporter (Port: 9100), HA-Proxy (Port: 80 > Port: 443)

### SystemD Services:
grafana, node-exporter, haproxy

### Install Location:
/opt/[application]







