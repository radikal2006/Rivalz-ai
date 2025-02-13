# Rivalz-ai
Daily claim rivalz fragment 

# ربات Rivalz AI

این پروزه ی مشتی شامل یک ربات برای تعامل با “Rivalz Fragmentz claimer” برای گرفتن ایردراپ می‌باشد.

## امکانات

- بررسی موجودی کیف پول
- کلایم کردن فرگمنت‌ها:
  - کلایم خودکار هر ۱۲ ساعت

## شروع نصب

### ۱. دریافت فاست

ابتدا به وبسایت زیر مراجعه کنید و فاست دریافت کنید:

[https://rivalz2.hub.caldera.xyz/](https://rivalz2.hub.caldera.xyz/)

### ۲. نصب Node.js و npm

دستورات زیر را اجرا کنید:

```bash
sudo apt update && apt upgrade -y
sudo apt remove nodejs
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash
source ~/.bashrc
nvm install 22.9.0
nvm use 22.9.0
nvm alias default 22.9.0
```

### ۳. کلون کردن پروژه

مخزن را کلون کنید و به دایرکتوری پروژه بروید:

```bash
git clone https://github.com/radikal2006/Rivalz-ai.git
cd Rivalz-ai
```

### ۴. نصب وابستگی‌ها

دستورات زیر را اجرا کنید:

```bash
npm install
```

### ۵. وارد کردن کیف پول

کلید خصوصی یا ۱۲ کلمه ی کیف پول خود را در فایل‌های زیر ذخیره کنید:

#### الف. وارد کردن کلید خصوصی

فایل `privateKeys.json` را باز کنید:

```bash
nano privateKeys.json
```

سپس اطلاعات را به فرمت زیر وارد کنید:

```json
[
  "پرایوت کی کیف پول اول",
  "پرایوت کی کیف پول دوم"
]
```
پس از وارد کردن اطلاعات، با زدن دکمه‌های زیر فایل را ذخیره کنید:

- `Ctrl + X` برای خروج
- `Ctrl + Y` برای تایید ذخیره
- سپس `Enter`

#### ب. وارد کردن 12 کلمه

فایل `accounts.json` را باز کنید:

```bash
nano accounts.json
```

سپس اطلاعات را به فرمت زیر وارد کنید:

```json
[
  "۱۲ کلمه  کیف پول اول",
  "۱۲ کلمه  کیف پول دوم"
]
```

برای ذخیره، همان مراحل بالا را دنبال کنید.

## استفاده

### ۱. ساخت اسکرین

برای ایجاد یک اسکرین جدید، دستور زیر را اجرا کنید:

```bash
screen -S Rivalz-ai-bot
```

### ۲. راه‌اندازی ربات

برای راه‌اندازی ربات، دستور زیر را اجرا کنید:

```bash
npm start
```

برای خروج از اسکرین بدون بستن آن، کلیدهای زیر را فشار دهید:

- `Ctrl + A + D`

### ۳. تنظیمات ربات

1. **بررسی موجودی کیف پول‌ها**:
   - عدد `0` را وارد کنید تا موجودی کیف پول‌ها بررسی شود.
2. **کلایم کردن فرگمنت‌ها**:
   - عدد `1` را وارد کنید تا کلایم کردن شروع شود.
     - **کلایم دستی**: عدد `1` را وارد کنید.
     - **کلایم خودکار هر ۱۲ ساعت**: عدد `2` را وارد کنید.

## دونیت

اگر خیلی مشتی هستی و میخوای از مرامت هزینه کنی ، فدات بشم حاجی از ادرس های زیر میتونی:

- **Solana**: `CcQ3R38NSSF9BhF8EbctGHqKDjqp8xSqUCJZMdrAr837`
- **EVM**: `0xB3C5b4d238937327C01AeC8908619cEa604D19eA`

##کانال ما
🔸@crypttopiaa 🪂 
🔸@radikal1_2006🪂

## لایسنس

این پروژه تحت لایسنس [MIT](LICENSE) منتشر شده است.

