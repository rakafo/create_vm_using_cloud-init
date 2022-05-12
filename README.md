# Overview

Create a VM with cloud-init user-data, without using explicit meta-data .iso file.

Templates: Almalinux 8, CentOS 8, Fedora 35.

# Capabilities

- unatended installation;
- configures user, ssh, hostname;
- configures static ip;

# Requirements

- KVM must be running;
- must have cloud image .qcow2 files ready;

# Sample playbook

examples found in tests/
