# 🛠️ fix-centos-repos.sh

Script to fix and restore the default CentOS 7 repositories using the [CentOS Vault](https://vault.centos.org/).  
Useful when the original mirrors are no longer available or you're getting repository errors during package installation or updates.

---

## 📋 Description

This script automatically:
- Creates a backup of your current CentOS repository file.
- Replaces it with the official CentOS Vault 7.9.2009 repository URLs.
- Cleans and rebuilds the YUM cache.

---

## ⚡ Quick Usage

You can run it directly with:

```bash
bash <(curl -s https://raw.githubusercontent.com/0LB-i/fix-centos-repos/main/fix-centos-repos.sh)
