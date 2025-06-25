# 🚀 Email Validator & Risk Classifier

A smart, scalable tool to clean, validate, and classify 140K+ emails — just like top product-based companies do.

---

## 🔍 What it does

- ✅ Validates email syntax (username, domain)
- ⚠️ Detects risky emails from disposable domains
- 🧹 Cleans duplicates and malformed IDs
- 📊 Tags each email as: `valid`, `invalid`, or `risky`

---

## 🔧 Tech Used

- Python 🐍  
- Pandas 📊  
- Regex 💡  

---

## 📁 Output Format

| E-Mail Address         | Domain       | Status   | Reason                     |
|------------------------|--------------|----------|----------------------------|
| user@gmail.com         | gmail.com    | valid    | syntactically valid        |
| .invalid@live.com      | live.com     | invalid  | username starts with dot   |
| abc@tempmail.com       | tempmail.com | risky    | disposable email domain    |

---

## 🧠 Behind the Scenes

- Regex-based format checks  
- Custom list of 1000+ disposable domains  
- Smart filters for username errors & duplicate entries  
- Clean CSV output ready for analytics or integration

---

## ▶️ Run It

```bash
python validate_emails.py
