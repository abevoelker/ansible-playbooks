ansible-playbooks
=================

Ansible playbooks and an example Vagrantfile in the pattern I typically use.
Typically, I'd put all these files (except the Vagrantfile) under a root
`ansible` directory inside the application source.

Vagrant use requires a relatively recent Linux kernel and some extra packages
as it uses [`vagrant-lxc`](https://github.com/fgrehm/vagrant-lxc).
