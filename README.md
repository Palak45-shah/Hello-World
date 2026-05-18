# Python Hello World 🌍

A simple Python project that prints Hello World
to the screen. Built and deployed using GitHub via SSH.

---

## 👤 Author
**PSX0Cipher**

---

## 🛠️ Requirements
- Python 3.x
- Git
- GitHub Account

---

## 🚀 How to Run

### 1. Clone the repo via SSH
```bash
git clone git@github.com:PSX0Cipher/python-hello-world.git
```

### 2. Go into the folder
```bash
cd python-hello-world
```

### 3. Run using Python
```bash
python3 hello.py
```

### 4. Run using Echo
```bash
echo "Hello, World!"
```

### 5. Output

Hello, World!




---

## 💻 Hello World Methods

| Method | Command |
|--------|---------|
| Python | `python3 hello.py` |
| Echo | `echo "Hello, World!"` |
| Python inline | `python3 -c "print('Hello, World!')"` |

---

## 🔐 SSH Setup Guide

### Step 1: Check SSH Key
```bash
ls ~/.ssh/id_ed25519.pub
```

### Step 2: Generate SSH Key
```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

### Step 3: Copy SSH Key
```bash
pbcopy < ~/.ssh/id_ed25519.pub
```

### Step 4: Add to GitHub
1. Go to **github.com → Settings**
2. Click **"SSH and GPG keys"**
3. Click **"New SSH key"**
4. Title: `My Mac`
5. Paste with `Cmd + V`
6. Click **"Add SSH key"**

### Step 5: Test Connection
```bash
ssh -T git@github.com
```
✅ Expected:
