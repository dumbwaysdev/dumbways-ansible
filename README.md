# ansible-monitoring
Ansible monitoring (Prometheus, Node Exporter, Grafana)

# config
- Update ansible.host with server ip
- Update group_vars/all.yml with your server username / password
- If connect with ssh key, update prometheus-grafana.pem

# how to
Start `ansible-playbook promotheus-grafana.yml`

# access
- Prometheus port : `ip:9090` 
- Grafana port : `ip:3000`
- Node exporter port : `ip:9100`
