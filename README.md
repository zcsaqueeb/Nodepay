- Register Here : [Nodepay](https://app.nodepay.ai/register?ref=MvmY9WUkNAq7vN9) -
- Use Code : MvmY9WUkNAq7vN9

# Nodepay BOT

**Automate tasks effortlessly with Nodepay BOT!**

## 📌 Features

- Retrieve account information automatically.
- Run with **Monosans Proxy** (Option 1).
- Run with **Private Proxy** (Option 2).
- Run **Without Proxy** (Option 3).
- Complete available tasks autonomously.
- Send pings every 55 minutes automatically.
- Multi-account support with threading.

_Note:_ Using proxies enables up to 3 connections; without proxies, only 1 connection is allowed.

---

## ⚙️ Requirements

- Python **3.9+** installed with `pip`.

---

## 🚀 Installation

1. **Clone Repository:**
   ```bash
   git clone https://github.com/vonssy/Nodepay-BOT.git
   cd Nodepay-BOT
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🔧 Configuration

### `tokens.txt`
Add tokens in the following format:
```text
eyjxxxx1
eyjxxxx2
```

### `proxy.txt`
Add proxies in one of these formats:
```text
ip:port           # Default Protocol HTTP.
protocol://ip:port
protocol://user:pass@ip:port
```

---

## 💡 Usage

Run the script:
```bash
python bot.py
```

---

## 🔎 Additional Notes

To fetch the token manually, open your browser console and execute:
```js
localStorage.getItem('np_token')
```

---
