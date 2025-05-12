
### 🔧 سورس ربات ریموت | پنل | مدیریت اکانت | اکانت گیر  
**Remote Bot Panel | Account Manager | Telegram Multi-Client**

---

## 🇮🇷 فارسی

این سورس یک ربات **ریموت تلگرامی** است که قابلیت مدیریت چندین اکانت تلگرام (با استفاده از سشن‌های IP + ID + Hash) را دارد. با این ربات می‌توانید از طریق یک رابط ساده تلگرامی تمام تنظیمات لازم را انجام دهید.

### ✅ ویژگی‌ها:
- ✅ افزودن / حذف / مشاهده لیست اکانت‌ها
- ✅ جوین و لفت خودکار از گروه/کانال
- ✅ تنظیم پیام خشاب (Bio)
- ✅ تنظیم / حذف کپشن پیشفرض
- ✅ تنظیم سرعت ارسال پیام
- ✅ روشن/خاموش کردن حالت اسپم
- ✅ تغییر نام و عکس پروفایل

### 🛠️ راهنمایی نصب:

1. **فایل `remote.py`:**
   - توکن ربات خود را وارد کنید.
   - عددی ادمین را وارد کنید.
   - مقادیر `ip_id` و `ip_hash` را تنظیم کنید.

2. **فایل `accounts.txt`:**
   - چند خط از داده‌های `ip_id`, `ip_hash` را به صورت جداگانه اضافه کنید.

3. **نصب دیپندنسی‌ها:**
```bash
pip install telethon python-dotenv
```

4. **اجرای ربات:**
```bash
python remote.py
```

> ⚠️ این سورس فقط جهت آموزش و تست شخصی طراحی شده است. استفاده از آن برای اهداف غیرقانونی ممنوع است.

---

## 🇬🇧 English

### 🔧 Remote Telegram Bot | Account Manager | Spam Panel

This is a **Telegram remote bot panel** that allows you to manage multiple Telegram accounts using session-like data (`IP_ID` + `IP_HASH`). You can control everything from your Telegram chat interface.

### ✅ Features:
- ✅ Add / Remove / List accounts
- ✅ Auto join and leave groups/channels
- ✅ Set/Delete bio (status)
- ✅ Set/Delete default caption
- ✅ Adjust send speed
- ✅ Enable/disable spam mode
- ✅ Change name and profile photo

### 🛠️ Installation Guide:

1. **Edit `remote.py`:**
   - Insert your bot token.
   - Set the admin user ID.
   - Configure `ip_id` and `ip_hash`.

2. **Add accounts in `accounts.txt`:**
   - Each line should contain an `ip_id` and `ip_hash` pair.

3. **Install dependencies:**
```bash
pip install telethon python-dotenv
```

4. **Run the bot:**
```bash
python remote.py
```

> ⚠️ This source code is for educational purposes only. Do not use it for illegal activities.

---

## 📁 Project Structure

```
├── remote.py         # Main bot logic
├── accounts.txt      # Accounts list (ip_id, ip_hash)
└── README.md         # Documentation
```

---

## 🤝 Support & Contribution

If you'd like to contribute or report bugs, feel free to open an issue or pull request!

---

## ⚠️ Disclaimer

Use this project responsibly. I am not responsible for any misuse or damage caused by this tool.

---

