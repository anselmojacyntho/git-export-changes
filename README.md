# 🧩 git-export-changes

A lightweight Bash tool to **export all files modified since a specific commit** in a Git repository — perfect for incremental deployments, FTP uploads, or quick change packaging.

---

## 🚀 Features

✅ Export files changed since a specific commit
✅ Preserve directory structure
✅ Optional ZIP packaging (`--zip`)
✅ Works in any Git repo
✅ No external dependencies (only `git` and `zip`)
✅ Simple to install globally

---

## ⚙️ Installation

You can install it in two easy ways:

### 🪣 Option 1 — Clone the repository

```bash
git clone https://github.com/anselmobarbosa/git-export-changes.git
cd git-export-changes
chmod +x git-export-changes
sudo cp git-export-changes /usr/local/bin/git-export-changes
```

### 🪣 Option 2 — Wget

```bash
sudo wget -O /usr/local/bin/git-export-changes \
https://raw.githubusercontent.com/anselmobarbosa/git-export-changes/main/git-export-changes
sudo chmod +x /usr/local/bin/git-export-changes
```
