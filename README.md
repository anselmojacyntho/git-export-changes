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

## 🧠 Why use it?

When you need to:

Deploy only changed files to a server
Generate incremental updates for a legacy system
Quickly inspect what changed since a certain commit
This tool saves you from manually diffing and copying files
Generating high value for when you still need to deploy via FTP, for example.

## ⚙️ Installation

You can install it in two easy ways:

### 🪣 Option 1 — Clone the repository

```bash
git clone https://github.com/anselmobarbosa/git-export-changes.git
cd git-export-changes
chmod +x git-export-changes
sudo cp git-export-changes /usr/local/bin/git-export-changes
```

### 🌐 Option 2 — Direct Install

```bash
sudo wget -O /usr/local/bin/git-export-changes \
https://raw.githubusercontent.com/anselmobarbosa/git-export-changes/main/git-export-changes
sudo chmod +x /usr/local/bin/git-export-changes
```

### 🧰 Usage

```bash
git-export-changes --help
git-export-changes --from <commit_hash> --out <output_dir> [--zip]
```

### 🧰 Examples

```bash
git-export-changes --from a1b2c3d --out ../ftp_upload
git-export-changes --from a1b2c3d --out ../ftp_upload --zip
```

## 💡 Tips

If you want to remove it later:

```bash
sudo rm /usr/local/bin/git-export-changes
```

## 🪪 License

MIT License © 2025 [Anselmo Barbosa](https://github.com/anselmobarbosa)

You are free to use, modify, and distribute this script as long as the original author and license notice are preserved.
