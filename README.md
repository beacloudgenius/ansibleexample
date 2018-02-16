Create a droplet in digital ocean and note its IP address and change `IP_ADDRESS` in the `hosts` file.

#### First run of Ansible

When you run this exercise the very first time, keep `root` as the `ansible_user` in the `hosts` file.

#### Subsequent Ansible runs

Please make sure to use `cloudgenius` as the ansible_user not `root`

You need that because the first run of this exercise disables the root user on the target.
