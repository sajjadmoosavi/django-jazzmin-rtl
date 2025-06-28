
# django-jazzmin-rtl

A complete, corrected, and production-ready **RTL stylesheet** for the Django **Jazzmin admin panel**, based on **AdminLTE v3.1**.

## 💡 Why this file?

After searching extensively for a stable and reliable RTL solution for Jazzmin, this was the most complete and accurate implementation I could find — fully corrected and enhanced.  
It is specifically built for `AdminLTE.io` and works flawlessly with Jazzmin.

## 🚀 Installation

1. Copy the CSS file to your Django static directory:
   ```
   static/css/jazzmin-rtl.css
   ```

2. Link it in your Django settings:

```python
JAZZMIN_SETTINGS = {
    "custom_css": "css/jazzmin-rtl.css",
}
```

3. Make sure your project language is set to Farsi (`fa-ir`) and compile messages:
```bash
django-admin makemessages -l fa
django-admin compilemessages
```

4. Add your Persian font (e.g., `IranSans`) in `static/font/` directory.

## ✅ License

MIT — Free for personal and commercial use.

---

## django-jazzmin-rtl (فارسی)

فایل CSS کامل، اصلاح‌شده و پایدار برای **راست‌چین‌سازی پنل مدیریت جنگو Jazzmin** بر پایه **AdminLTE نسخه ۳.۱**.

## 💡 چرا این فایل؟

من مدت‌ها به‌دنبال یک فایل سالم و دقیق برای راست‌چین‌کردن Jazzmin بودم و کامل‌ترین چیزی که پیدا کردم همین فایل بود.  
تمام اجزای مهم AdminLTE را اصلاح کرده‌ام تا با خیال راحت در پروژه‌های راست‌چین از آن استفاده کنید.

در واقع این فایل همان قالب رسمی [AdminLTE.io](https://adminlte.io) است که به‌طور کامل راست‌چین شده و بدون هیچ مشکلی روی Jazzmin اجرا می‌شود.

## 🚀 آموزش نصب

۱. فایل CSS را در مسیر `static/css/` پروژه کپی کنید.  
۲. فونت فارسی مثل `IranSans` را در مسیر `static/font/` قرار دهید.  
۳. در فایل `settings.py` تنظیم زیر را اضافه کنید:

```python
JAZZMIN_SETTINGS = {
    "custom_css": "css/jazzmin-rtl.css",
}
```

۴. زبان پروژه را روی `fa-ir` قرار دهید و دستورات زیر را اجرا کنید:

```bash
django-admin makemessages -l fa
django-admin compilemessages
```

## ✅ مجوز استفاده

مجوز MIT — استفاده رایگان برای پروژه‌های شخصی و تجاری.
