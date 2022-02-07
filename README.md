# Overview

Create VM with cloud-init user-data, without using explicit meta-data .iso file.

vm.template options:

1. centos-8
2. fedora-34
3. fedora-34-kde

# Capabilities

- configures user, ssh, hostname;
- configures static ip;

# Requirements

- KVM must be running;
- must have cloud image .qcow2 files ready;

# Sample playbook

examples found in tests/
