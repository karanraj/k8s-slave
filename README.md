k8s-slave
=========

This role will configure slave node of kubernetes multi node cluster on AWS Amazon linux

Requirements
------------

To successfully configure slave node you must have an Amazon linux ec2-instance launched on AWS whose public IP uploaded on your inventory file under group-name slave..

Example Playbook
----------------

    - hosts: slave
      roles:
         - { role: karanraj.k8s_slave }

* See Also
  [k8s-master-node-setup](https://galaxy.ansible.com/karanraj/k8s_master)

