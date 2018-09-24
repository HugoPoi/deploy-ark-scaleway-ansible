# Ark Manager Deploy in Scaleway with Ansible

## 1. Deploy some instance
`SCW_API_KEY=xxxxx ansible-playbook deploy_ark.yml`
## 2. Setup the machine
`SCW_API_KEY=xxxxx ansible-playbook -i scaleway_inventory.yml setup_ark.yml`
