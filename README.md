

---

# 📑 Compliance Reports Automation

This repository contains Ansible playbooks and YAML configurations to automate **compliance checks, updates, and reporting** across different environments.

## 📂 Repository Structure

```
compliance_reports/
│── compcheck.yaml         # Compliance check playbook
│── compcheck1.yaml        # Extended compliance checks
│── ftpplaybook.yaml       # Playbook for FTP-related compliance
│── lab1.yaml              # Lab setup - initial compliance test
│── lab2.yaml              # Lab setup - advanced compliance test
│── prepostupdate.yaml     # Pre and post update validation
│── sudouser.yaml          # Compliance checks for sudo users
│── test.yml               # Test playbook for validation
│── update.yaml            # System update compliance check
```

## 🚀 Usage

### Run a compliance check

```bash
ansible-playbook -i inventory.yaml compcheck.yaml
```

### Run pre and post update checks

```bash
ansible-playbook -i inventory.yaml prepostupdate.yaml
```

### Apply sudo user compliance rules

```bash
ansible-playbook -i inventory.yaml sudouser.yaml
```

### Run update compliance

```bash
ansible-playbook -i inventory.yaml update.yaml
```

## 🧪 Lab Playbooks

* `lab1.yaml` → First-level code and compliance testing
* `lab2.yaml` → Extended compliance validation

## 🔒 Compliance Areas Covered

* User and sudo access validation
* System update verification
* FTP configuration compliance
* Pre/post update checks
* General security baselines
