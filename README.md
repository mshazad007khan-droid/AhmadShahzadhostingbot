<div align="center">

# 🚀 Ahmad Shahzad Hosting Bot

### 🐍 Telegram Python & JavaScript Bot Hosting Platform

<p>
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Telegram-Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  <img src="https://img.shields.io/badge/Railway-Ready-7B61FF?style=for-the-badge&logo=railway&logoColor=white" alt="Railway">
  <img src="https://img.shields.io/badge/License-Personal Use-22C55E?style=for-the-badge" alt="License">
</p>

<p>
  <a href="https://t.me/ahmadteachx">📢 Telegram Channel</a> •
  <a href="https://whatsapp.com/channel/0029VbCx2Sb5q08a3fe3KZ42">🟢 WhatsApp Channel</a> •
  <a href="https://ahmadshahzadmd.vercel.app/">🤖 MD Bot</a>
</p>

</div>

---

## ✨ About the Project

**Ahmad Shahzad Hosting Bot** is a Telegram-based hosting manager that allows users to upload, manage and run Python or JavaScript scripts directly from Telegram.

It includes an admin panel, file management, subscription controls, force-join management, module installation, statistics and a Flask keep-alive endpoint for cloud hosting platforms such as Railway.

> Designed and customized for **Ahmad Shahzad**.

---

## 🌈 Main Features

| Feature | Description |
|---|---|
| 📤 **File Hosting** | Upload `.py`, `.js` and `.zip` files through Telegram |
| ▶️ **Run Scripts** | Start, stop and restart hosted scripts |
| 📜 **Live Logs** | View script logs from the bot |
| 📦 **Module Installer** | Install Python and Node.js packages when needed |
| 👑 **Admin Panel** | Manage users, admins, subscriptions and settings |
| 🔒 **Security Checks** | Scan uploaded scripts and ZIP archives for dangerous patterns |
| 📢 **Force Join** | Manage required Telegram channels or groups |
| 💳 **Subscriptions** | Add, remove and check user subscriptions |
| 📊 **Statistics** | View active users, files and system information |
| 🟢 **Keep Alive** | Flask endpoint included for Railway deployment |
| 🗄️ **SQLite Database** | Stores users, settings, files and subscriptions |

---

## 📁 Project Structure

```text
.
├── AHMEDHOSTING2.py     # Main Telegram bot
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── inf/                  # SQLite database directory (created automatically)
```

---

## ⚙️ Required Environment Variables

For Railway or another hosting platform, add these variables in the service settings:

```env
BOT_TOKEN=your_telegram_bot_token
OWNER_USERNAME=ahmadshahzad804
```

The bot also reads the `PORT` variable automatically. Railway provides this variable by default.

> **Security:** Never publish your real bot token in a public GitHub repository. Store it in Railway Variables or a local `.env` file that is excluded from Git.

---

## 🚂 Deploy on Railway from GitHub

1. Create a private GitHub repository.
2. Upload `AHMEDHOSTING2.py`, `requirements.txt` and this `README.md`.
3. Open [Railway](https://railway.com/) and choose **New Project**.
4. Select **Deploy from GitHub Repo**.
5. Connect your GitHub account and select this repository.
6. Add the variables shown above under **Variables**.
7. Set the start command if Railway does not detect it automatically:

```bash
python AHMEDHOSTING2.py
```

8. Deploy the service and check the deployment logs.

After deployment, push updates to the connected `main` branch. Railway can automatically build, deploy and restart the bot after each update when Auto Deploy is enabled.

---

## 💻 Run Locally

Install the dependencies:

```bash
pip install -r requirements.txt
```

Set your bot token:

```bash
export BOT_TOKEN="your_telegram_bot_token"
export OWNER_USERNAME="ahmadshahzad804"
```

Start the bot:

```bash
python AHMEDHOSTING2.py
```

On Windows PowerShell:

```powershell
$env:BOT_TOKEN="your_telegram_bot_token"
$env:OWNER_USERNAME="ahmadshahzad804"
python AHMEDHOSTING2.py
```

---

## 🔗 Official Links

- 📢 Telegram Channel: [@ahmadteachx](https://t.me/ahmadteachx)
- 🟢 WhatsApp Channel: [Join WhatsApp Channel](https://whatsapp.com/channel/0029VbCx2Sb5q08a3fe3KZ42)
- 🤖 Ahmad Shahzad MD Bot: [Open MD Bot](https://ahmadshahzadmd.vercel.app/)
- 📞 Contact Owner: [@ahmadshahzad804](https://t.me/ahmadshahzad804)

---

## 🛡️ Important Security Notes

- Keep the repository private if the project contains sensitive code.
- Never commit `BOT_TOKEN` to GitHub.
- Use Railway Variables for tokens and other secrets.
- Review uploaded scripts before allowing them to run.
- Keep the SQLite database and uploaded files on persistent storage when required.
- Give the Telegram bot only the permissions it actually needs in channels and groups.

---

## 👨‍💻 Credits

<div align="center">

### Made and customized for Ahmad Shahzad

<p>
  <a href="https://t.me/ahmadshahzad804">
    <img src="https://img.shields.io/badge/Contact-Ahmad%20Shahzad-0EA5E9?style=for-the-badge&logo=telegram&logoColor=white" alt="Contact Ahmad Shahzad">
  </a>
</p>

</div>

---

<div align="center">

⭐ If this project helps you, keep your repository organized and your bot token private.

</div>
