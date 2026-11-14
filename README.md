# Varnix AI 2.0

دستیار هوش مصنوعی فارسی‌زبان سبک و زیبا برای اندروید.

## ویژگی‌ها

- رابط کاربری مدرن تیره با تم بنفش و آبی
- اتصال به OpenRouter
- پنل مالک
- ذخیره امن API Key
- تاریخچه چت، پشتیبان‌گیری و بازیابی
- لینک کانال روبیکا، پرداخت و مایکت قابل تنظیم
- رابط فارسی و راست‌چین
- ساخت APK انتشار با GitHub Actions

## ساخت APK انتشار

1. در GitHub وارد **Settings → Secrets and variables → Actions** شوید.
2. این چهار Secret را تعریف کنید:
   - `KEYSTORE_BASE64`
   - `STORE_PASSWORD`
   - `KEY_PASSWORD`
   - `KEY_ALIAS`
3. از تب **Actions** گردش‌کار **Build Varnix AI Release APK** را اجرا کنید.
4. پس از موفقیت، فایل APK را از بخش **Artifacts** همان اجرا دریافت کنید.

**مهم:** فایل کلید امضا و رمزهای آن نباید در مخزن یا README قرار بگیرند. از GitHub Actions Secrets استفاده کنید.

## نسخه
۲.۰.۰ - Release
