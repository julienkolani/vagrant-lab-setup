# Vagrant Lab Setup

Reproducible virtual machine environments using Vagrant and VirtualBox. Contains two configurations: a Linux lab VM provisioned with Docker (8 GB RAM, 8 vCPUs), and a Windows VM setup for cross-platform testing.

## Features

- Linux lab VM with automated Docker provisioning (8 GB RAM, 8 vCPUs)
- Windows VM configuration for cross-platform development and testing
- Fully reproducible environments via `vagrant up`

## Tech Stack

- Vagrant
- VirtualBox
- Docker (provisioned inside Linux VM)
- Shell provisioning

## Setup

Requirements: [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/) installed.

**Linux lab VM:**

```bash
cd labvm
vagrant up
```

**Windows VM:**

```bash
cd vagrant-windows
vagrant up
```

## Project Structure

```
labvm/
  Vagrantfile    # Linux lab VM: Docker provisioning, 8 GB RAM, 8 vCPUs
vagrant-windows/
  Vagrantfile    # Windows VM configuration
```
