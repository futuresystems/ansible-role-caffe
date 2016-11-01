Ansible-role-caffe
===============================================================================

Ansible Role for Caffe Deep Learning Installation

Requirements
------------

- CUDA for gpu version
- BLAS
- Python (optional)

Role Variables
--------------

- caffe_repo: git repository URL for caffe

Dependencies
------------

n/a

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-role-caffe, type: 'cpu-only' }

License
-------

Apache License v2

Author Information
------------------

Hyungro Lee (hroe.lee@gmail.com)
