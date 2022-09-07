# noname-homework

As requested, please find in this repo:

* An Ansible playbook - `pizza.yml` and associated file and directories
  * ansible.cfg
  * files
  * hosts
  * roles
* A Vagrantfile

Though not mandatory, the recommended way to run the project is to use
[vagrant](https://www.vagrantup.com/) with
[VirtualBox](https://www.virtualbox.org/). Alternatively, it can be run from
within any Linux host or virtual machine.

To view the project:

1. Clone this repo

```
https://github.com/V01dDweller/noname-homework.git
```

2. CD into the directory:

```
cd noname-homework
```

3. Issue the `vagrant up` command - A virtual machine will be created with
Ansible installed
4. Once the virtual machine is provisioned, cd to `/vagrant`
5. From there, run the ansible playbook:

```
ansible-playbook pizza.yml
```
