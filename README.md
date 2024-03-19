![Testing](https://github.com/albertodescalzo/ansible-role-pangenomics/workflows/Role-Testing/badge.svg)


Pangenomics
=========

(Bioninformatic) pangenomic tools to be installed in any Ubuntu VM: https://diltheylab.github.io/graph-genome-workbench/. For more information about the tools, see the GitHub page.

Requirements
------------

Role was used within the de.NBI Cloud (German Network for Bioinformatics Infrastructure) in a VM with Ubuntu 20.04 and 22.04, but it should work in other cloud suppliers. 

Role Variables
--------------

Adapt the software versions to your preferences. The given variables were used to test the software. Additionally, pay attention to `home_path` and `username`. They should be set up to `/home/runner/work`and `runner` when testing CI.   

Dependencies
------------



Example Playbook
----------------

  - hosts: denbi_vms
  roles:
    - albertodescalzo.pangenomics

License
-------

BSD

Author Information
------------------

Email: Alberto.Descalzo.Garcia@hhu.de
