# How to configure this playbook #

1. Add your host machine to the hosts file in `inventory/hosts`
2. Create `host_vars/<host_name>/vars.yml` and alter the default variables discoverable in `roles/<role>/defaults`

# Running the playbook #

Simply run `ansible-playbook setup.yml -i inventory/hosts`
