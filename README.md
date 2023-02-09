Kata Containers
=========

An Ansible role to deploy Kata Containers on Kubernetes clusters (containerd specific)

Requirements
------------

* A Kubernetes cluster, using containerd, up and running.
* `kubectl` binary in the localhost $PATH
* An admin configuration for kubernetes, exported as KUBECONFIG

Example Playbook
----------------

```sh
ansible-playbook -i /path/to/inventory/file tasks/main.yml
```

License
-------

Apache

Author Information
------------------

* Chelsea Mafrica <chelsea.e.mafrica@intel.com>
* Fabiano Fidêncio <fabiano.fidencio@intel.com>
