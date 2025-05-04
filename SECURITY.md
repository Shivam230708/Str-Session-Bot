# 🔐 Security Policy

## Supported Versions

| Version | Supported          |
|---------|--------------------|
| 1.x     | ✅ Yes              |
| 0.x     | ❌ No (Deprecated)  |

---

## 📣 Reporting a Vulnerability

We take security seriously. If you find any security-related issue, **please do not open a public GitHub issue**. Instead, follow the steps below:

1. **Email us directly** at: `rajnishmishraaa1@gmail.com`
2. Provide detailed information:
   - Description of the vulnerability
   - Steps to reproduce
   - Affected files or modules
3. We will acknowledge receipt within **24 hours**.
4. A fix will be prioritized and deployed typically within **72 hours**, depending on severity.

---

## 🔍 Common Areas to Review

- Session string generation
- MongoDB data storage
- `.env` file handling
- Broadcast functionality (rate limits, privacy)

---

## 🧷 Best Practices for Users

- Never share your session string publicly.
- Host your bot in a secure, private environment.
- Use `.env` to manage secrets; **never hardcode** API keys.
- Rotate bot tokens periodically if exposed.

---

## 🔐 Bot Session Security

Session strings can grant full access to a user or bot account. This bot:
- Sends user sessions only to their **Saved Messages**
- Never logs session data or API credentials
- Uses Pyrogram & Telethon securely in memory

---

## ✅ Credits

Maintained with ❤️ by [Certified Coders](https://github.com/CertifiedCoders)  
Telegram Support: [@CertifiedCoder](https://t.me/CertifiedCoder)

