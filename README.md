# 🚀 teleport ~ Instantly publish your files over the network, no hosts, no cloud, just magic.

Teleport is a lightweight, peer-to-peer file sharing CLI tool that lets you **send files or folders anonymously** across the internet **without using any central host, public repository, or cloud service**. It uses the power of BitTorrent under the hood to broadcast your content securely and privately — from CLI to anywhere.

---

## ✨ Why Use Teleport?

- 📦 **Send anything** — folders, files, or entire directories.
- 🕵️ **Stay anonymous** — no cloud, no login, no tracking.
- 🔗 **Share with one line** — generate a base64 magic code and send it to your recipient.
- 🛰️ **Peer-to-peer magic** — powered by DHT + Magnet Links + Tracker networks.

---

## 📦 How to Use

```bash
# Send a file or folder
teleport send {file_or_folder_path}
```

# Receive a file or folder using a magic code
```bash
teleport receive {magic_code}
```

# Show version
```bash
teleport version
```

# Show help
```bash
teleport help
```

🧪 Sample Usage
You received a magic code like this:

bWFnbmV0Oj94dD11cm46YnRpaDpiYTU2ZjcwNjQxNzE1NzQ5YWQ2M2FjMDRlYmZiYTcwM2ViYTEwM2MyJmRuPXRlbGVwb3J0JnhsPTg5MyZ0cj11ZHAlM0ElMkYlMkZvcGVuLnN0ZWFsdGguc2klM0E4MCUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIubW9la2luZy5tZSUzQTY5NjklMkZhbm5vdW5jZSZ0cj11ZHAlM0ElMkYlMkZvcGVuLmRlbW9uaWkuY29tJTNBMTMzNyUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIub3BlbnRyYWNrci5vcmclM0ExMzM3JTJGYW5ub3VuY2UmdHI9dWRwJTNBJTJGJTJGdHJhY2tlci5sZWVjaGVycy1wYXJhZGlzZS5vcmclM0E2OTY5JTJGYW5ub3VuY2UmdHI9dWRwJTNBJTJGJTJGdHJhY2tlci5vcGVuYml0dG9ycmVudC5jb20lM0E2OTY5JTJGYW5ub3VuY2UmdHI9dWRwJTNBJTJGJTJGdHJhY2tlci50b3JyZW50LmV1Lm9yZyUzQTQ1MSUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIub3BlbmJpdHRvcnJlbnQuY29tJTNBODAmdHI9dWRwJTNBJTJGJTJGdHJhY2tlci5kbGVyLm9yZyUzQTY5NjklMkZhbm5vdW5jZSZ0cj11ZHAlM0ElMkYlMkZ0cmFja2VyLm9wZW5iaXR0b3JyZW50LmNvbSUzQTgwJTJGYW5ub3VuY2UmdHI9dWRwJTNBJTJGJTJGZXhvZHVzLmRlc3luYy5jb20lM0E2OTY5JnRyPXVkcCUzQSUyRiUyRnB1YmxpYy5wb3Bjb3JuLXRyYWNrZXIub3JnJTNBNjk2OSUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIuY29wcGVyc3VyZmVyLnRrJTNBNjk2OSUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIub3BlbnRyYWNrci5vcmclM0ExMzM3JnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIuYml0dG9yLnB3JTNBMTMzNyUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIuaW50ZXJuZXR3YXJyaW9ycy5uZXQlM0ExMzM3JTJGYW5ub3VuY2Umd3M9aHR0cHM6Ly9naXRodWIuY29tL1B1cndhbmFOZXQvdGVsZXBvcnQv

from:
```bash
teleport send [file path/directory]
```

Now you want to download it?

Just run:
```bash
teleport receive bWFnbmV0Oj94dD11cm46YnRpaDpiYTU2ZjcwNjQxNzE1NzQ5YWQ2M2FjMDRlYmZiYTcwM2ViYTEwM2MyJmRuPXRlbGVwb3J0JnhsPTg5MyZ0cj11ZHAlM0ElMkYlMkZvcGVuLnN0ZWFsdGguc2klM0E4MCUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIubW9la2luZy5tZSUzQTY5NjklMkZhbm5vdW5jZSZ0cj11ZHAlM0ElMkYlMkZvcGVuLmRlbW9uaWkuY29tJTNBMTMzNyUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIub3BlbnRyYWNrci5vcmclM0ExMzM3JTJGYW5ub3VuY2UmdHI9dWRwJTNBJTJGJTJGdHJhY2tlci5sZWVjaGVycy1wYXJhZGlzZS5vcmclM0E2OTY5JTJGYW5ub3VuY2UmdHI9dWRwJTNBJTJGJTJGdHJhY2tlci5vcGVuYml0dG9ycmVudC5jb20lM0E2OTY5JTJGYW5ub3VuY2UmdHI9dWRwJTNBJTJGJTJGdHJhY2tlci50b3JyZW50LmV1Lm9yZyUzQTQ1MSUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIub3BlbmJpdHRvcnJlbnQuY29tJTNBODAmdHI9dWRwJTNBJTJGJTJGdHJhY2tlci5kbGVyLm9yZyUzQTY5NjklMkZhbm5vdW5jZSZ0cj11ZHAlM0ElMkYlMkZ0cmFja2VyLm9wZW5iaXR0b3JyZW50LmNvbSUzQTgwJTJGYW5ub3VuY2UmdHI9dWRwJTNBJTJGJTJGZXhvZHVzLmRlc3luYy5jb20lM0E2OTY5JnRyPXVkcCUzQSUyRiUyRnB1YmxpYy5wb3Bjb3JuLXRyYWNrZXIub3JnJTNBNjk2OSUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIuY29wcGVyc3VyZmVyLnRrJTNBNjk2OSUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIub3BlbnRyYWNrci5vcmclM0ExMzM3JnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIuYml0dG9yLnB3JTNBMTMzNyUyRmFubm91bmNlJnRyPXVkcCUzQSUyRiUyRnRyYWNrZXIuaW50ZXJuZXR3YXJyaW9ycy5uZXQlM0ExMzM3JTJGYW5ub3VuY2Umd3M9aHR0cHM6Ly9naXRodWIuY29tL1B1cndhbmFOZXQvdGVsZXBvcnQv
```


And watch the magic happen. ✨

📂 The received file will be saved under ./downloads.

📡 Under the Hood
Teleport uses:

📡 Support BitTorrent Protocol

🌍 DHT (Distributed Hash Table)

🔁 Peer Exchange (PEX)

📡 Public trackers

The data is never stored on a server. You are the server. You are the cloud.

🔒 Security Notes
Magnet links are encoded in Base64 to prevent direct magnet link sharing over strict channels (e.g., chat apps, URLs).

Anyone with the magic code can access the file — share responsibly.

🧠 Inspired by
magic-wormhole for its simplicity in transfer UX

with BitTorrent for its decentralized resilience

scp and rsync for direct file flows

💡 Roadmap Ideas
 Encrypted transfers with optional passphrase

 GUI/Tray version

 Public file explorer (optional)

 One-time download flag

👨‍💻 Contribute
Feel free to fork and hack it. PRs welcome!

GitHub: https://github.com/PurwanaNet/teleport

🧭 License
MIT License — do whatever you want, but don’t blame us if you teleport something dangerous 😉.

"Teleport is not a protocol, it's a philosophy. Share freely. Transfer simply. No middlemen."


---

Let me know if you want me to localize this README to Bahasa Indonesia or generate a GitHub-compatible
