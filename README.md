# Ansible Homelab

Exercises and challenges from the **Ansible training** by
[Stéphane Robert](https://blog.stephane-robert.info/), completed on a
Proxmox homelab with LXC containers (Ubuntu 24.04, Debian 13, AlmaLinux 10,
CentOS Stream 9).

## What's covered

Chapters `00` to `13`: inventories (static and dynamic), playbooks, handlers,
Jinja2 templates and filters, conditions, roles, blocks, Vault, custom facts,
lookups and asynchronous tasks. Each chapter keeps its `challenge/` tests.

## Note on Ansible Vault

The Vault password file in `10-Vault/` is committed **on purpose**. It only
protects dummy data from the course exercises, on throwaway test VMs. Never do
this in a real project: real secrets and their passwords must stay out of Git.

## Credits and license

This repository is based on an earlier version of
[stephrobert/ansible-training](https://github.com/stephrobert/ansible-training)
by **Stéphane Robert**. The original project has evolved since, so chapter
names and content may differ from its current state. The course content,
exercise statements and challenge tests are his work, published under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) (see
[LICENSE](./LICENSE)). His original README, as it was at the time, is kept as
[COURSE_README.md](./COURSE_README.md).

Changes: I added my own solutions (playbooks, templates, roles) and a few
extra files. These additions are shared under the same license.
