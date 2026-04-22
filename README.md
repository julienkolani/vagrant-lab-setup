# Vagrant Lab Setup

Environnements de machines virtuelles reproductibles avec Vagrant et VirtualBox.

## Configurations incluses

- `labvm/` — VM Linux avec provisioning Docker automatique (8 Go RAM, 8 vCPUs)
- `vagrant-windows/` — VM Windows pour tests cross-platform

## Stack technique

- Vagrant, VirtualBox, Bash provisioning

## Utilisation

```bash
cd labvm
vagrant up
# La VM démarre et installe Docker automatiquement
```
