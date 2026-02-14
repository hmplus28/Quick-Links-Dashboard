
# 🚀 داشبورد مدیریت لینک (Quick Links Dashboard) [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://www.w3.org/html/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://www.javascript.com/)


یک داشبورد مدرن، واکنش‌گرا و سریع برای مدیریت دسترسی سریع به لینک‌های پرتال، ابزارهای کار و وب‌سایت‌های مورد علاقه. این ابزار جایگزینی قدرتمند برای بوک‌مارک‌های پیش‌فرض مرورگر است که امکان سازماندهی رنگی و جستجوی پیشرفته را فراهم می‌کند.

## ✨ ویژگی‌های کلیدی

- 🎨 **دسته‌بندی‌های رنگی:** امکان ایجاد دسته‌های نامحدود و اختصاص رنگ به هر دسته برای سازماندهی بصری لینک‌ها.
- 🔍 **جستجوی آنی:** دسترسی فوری به لینک‌های مورد نظر با تایپ کردن نام، دسته یا آدرس.
- 💾 **مدیریت کامل (CRUD):** امکان افزودن، ویرایش، حذف لینک‌ها و دسته‌ها با رابط کاربری ساده.
- 🔄 **پشتیبان‌گیری و بازیابی (Backup/Restore):** خروجی گرفتن از تمام لینک‌ها به صورت فایل JSON و امکان بازگردانی آن‌ها در سیستم‌های دیگر.
- 🌙 **پشتیبانی از تم تاریک (Dark Mode):** جلوگیری از خستگی چشم در محیط‌های کاری تاریک.
- 📱 **طراحی واکنش‌گرا (Responsive):** نمایش عالی در دسکتاپ، تبلت و موبایل.
- 🚫 **بدون نیاز به سرور:** تمام داده‌ها در مرورگر کاربر (LocalStorage) ذخیره می‌شوند.

## 🚀 تکنولوژی‌های استفاده شده

- **HTML5:** ساختار معنایی و یکپارچه.
- **CSS3:** طراحی مدرن، استفاده از Flexbox/Grid و متغیرهای CSS برای تم‌ها.
- **JavaScript (Vanilla):** مدیریت داده‌ها (CRUD)، جستجو، و دستکاری DOM بدون هیچ فریم‌ورک.
- **LocalStorage API:** پایگاه داده محلی مرورگر.

## 📋 پیش‌نیازها

این پروژه کاملاً Front-end است و نیاز به نصب هیچ پکیجی ندارد.
- یک مرورگر وب مدرن.

## 🛠️ نصب و راه‌اندازی

1.  **دریافت کد:**
    ```bash
    git clone https://github.com/hmplus28/Quick-Links-Dashboard.git
    cd Quick-Links-Dashboard
    ```

2.  **اجرا:**
    کافیست فایل `index.html` را با مرورگر خود باز کنید.

## 📖 نحوه استفاده

1.  **ایجاد دسته:**
    -   روی دکمه "+ دسته" کلیک کنید.
    -   نام دسته را وارد کرده و یک رنگ برای آن انتخاب کنید.

2.  **افزودن لینک:**
    -   روی "+ لینک" کلیک کنید.
    -   عنوان، آدرس (URL)، توضیحات کوتاه و دسته مربوطه را مشخص کنید.

3.  **مدیریت داده‌ها:**
    -   برای ویرایش یا حذف هر آیتم، از دکمه‌های موجود روی کارت‌ها استفاده کنید.
    -   برای جابجایی لینک بین دسته‌ها، هنگام ویرایش، دسته مورد نظر را تغییر دهید.

4.  **بک‌آپ‌گیری:**
    -   از دکمه "Backup" در هدر برای دانلود فایل `quicklinks-backup.json` استفاده کنید.

## 🎨 تصاویر پروژه

نمای کلی از داشبورد مدیریت لینک‌ها:

![نمای داشبورد مدیریت لینک](https://s8.uupload.ir/files/screenshot_from_2026-02-14_21-28-31_vg10.png)

## 🧠 ساختار داده (JSON)

داده‌ها در قالب زیر ذخیره می‌شوند که برای توسعه‌دهندگان جهت گسترش پروژه مفید است:

```json
[
  {
    "id": "unique-id-1",
    "category": "Dev Tools",
    "color": "#6ea8fe",
    "items": [
      {
        "id": "unique-id-2",
        "title": "GitHub",
        "url": "https://github.com",
        "note": "کد منبع پروژه‌ها"
      }
    ]
  }
]
```

## 🤝 مشارکت (Contributing)

اگر ایده‌ای برای بهبود رابط کاربری یا افزودن ویژگی‌های جدید دارید، خوشحال می‌شوم Pull Request دریافت کنم.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 👨‍💻 توسعه‌دهنده

**حمیدرضا مهرآبادی**

- [LinkedIn](https://linkedin.com/in/hamidreza-mehrabadi-6a6439322)
