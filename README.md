# About
Ansible playbook to prepare KVM-based hypervisor.

**Supported OS:** Centos/RHEL 7+

Example execution command:
```
ansible-playbook prepare-linux-virt-host.yml -i "localhost," --connection=local --skip-tags "docker, nested_virt"
```