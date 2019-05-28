# Ansible Role for Docker Registry on Kubernetes

## 3.1.0 - TBC

### Major Changes

  - Always use `become: true` with molecule, especially for vagrant
  - Replace `inventory_hostname` with `ansible_hostname`

## 3.0.0 - 2019-05-20

  - Initial release for Ansible 2.8 or higher
  - Support both Ubuntu 16.04/18.04 or RHEL/CentOS 7 or openSUSE Leap 15
