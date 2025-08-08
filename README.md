# 🤖 Telegram Personal Helper Bot

A fun side project that turns Telegram into your own personal assistant — built for quick commands, lightweight automation, and a touch of nerdy joy.

---

## 🚀 Features

- `/whoami` — Get info about the user who sent the command  
- `/ping` — Check if the bot is alive and responsive  
- `/weather` — (Coming soon) Get weather updates for your location  
- Adding more with time
---

## 🛠️ Tech Stack

- **Scala** — Functional and expressive  
- **sttp** — HTTP client for Telegram API  
- **Circe** — JSON decoding  
- **Cats Effect** — For safe and composable side effects  

---

## ⚙️ Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/xDavidRTx/telegram-scala-bot.git
   cd telegram-helper-bot
   ```

2. **Set your Telegram bot token**

   ```bash
   export TELEGRAM_BOT_TOKEN=your_token_here
   ```

3. **Run the bot**

   ```bash
   sbt run
   ```

---

## 🧪 Example Commands

Send these to your bot in Telegram:

```
/whoami
/ping
```

---

## 🧠 Why?

Because sometimes you just want to type `/whoami` and get a real answer. This bot is a playground for personal automation, command-line nostalgia, and Scala experimentation.

---

## 📬 Contributing

Open to ideas, PRs, and weird command suggestions. Feel free to fork and make it your own!

---

## 📄 License

MIT — do whatever you want, just don’t blame the bot if it becomes sentient.
```
