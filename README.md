# Ansible Hybrid Cloud Automation

This repository contains Ansible playbooks for automating services across a hybrid cloud environment managed from a central Proxmox host.

## 📁 Folder Structure

- `playbooks/` – Individual automation playbooks

## ✅ Playbooks Included

- `deployapache.yml` – Installs and starts Apache2 on the `ubuntuweb` VM

## 🔧 Inventory Targets

- `ubuntuweb` (10.0.0.79)
- `ubuntuk8s` (10.0.0.75)
- `Taha-OCI` (Oracle Cloud Ubuntu)
- `WindowsCore01` (via WinRM)
