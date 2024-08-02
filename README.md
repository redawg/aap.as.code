# ansible.platform.as.code
ansible.platform.as.code
```
export CONTROLLER_CONFIGS_DIR=/home/$logname/git-repos/seed

ansible-playbook -i inventory ansible.containerized_installer.install -e@ames_vault.yml --vault-password-file ~/.ssh/secret
ansible-playbook -i inventory  infra.controller_configuration.configure_controller.yml -e@ames_vault.yml --vault-password-file ~/.ssh/secret

```