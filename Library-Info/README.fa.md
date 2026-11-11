[English](README.md) | [فارسی](README.fa.md)

<div dir="rtl">

# اطلاعات کتابخانه

بازگشت به [صفحه‌ی اصلی](../README.fa.md) · مشاهده‌ی قطعات در [Components](../Components/)

## فرمت‌ها

هر قطعه تا جایی که موجود باشد با این فرمت‌ها ارائه می‌شود:

| پوشه‌ی داخل قطعه | فایل‌ها | مناسب برای |
|---|---|---|
| `Altium/` | `.SchLib`، `.PcbLib` | Altium Designer |
| `KiCad/` | `.kicad_sym`، `.kicad_mod` | KiCad |
| `STEP/` | `.step` | هر نرم‌افزار CAD / EDA |

فایل‌های `.step` فرمت عمومی هستند و حتی اگر آلتیوم یا KiCad ندارید، می‌توانید مدل‌های سه‌بعدی را در هر نرم‌افزاری استفاده کنید.

## نحوه‌ی استفاده در Altium Designer

۱. کتابخانه‌ی کامل را از [Releases](https://github.com/africazani/africazani-altium-library/releases/latest) یا یک قطعه را از پوشه‌ی خودش دانلود کنید.
۲. در آلتیوم فایل‌های `.SchLib` و `.PcbLib` (یا `.IntLib`) را از مسیر *Components → File-based Libraries Preferences* اضافه کنید.
۳. مدل سه‌بعدی به فوت‌پرینت وصل است. اگر نمایش داده نشد، فایل `.step` را در پنل PCB Library دوباره لینک کنید.

## نحوه‌ی استفاده در KiCad

نام منوها ممکن است بین نسخه‌های KiCad کمی فرق کند.

۱. **نماد (Symbol):** در Schematic Editor از *Preferences → Manage Symbol Libraries* فایل `.kicad_sym` را به‌عنوان کتابخانه‌ی جدید اضافه کنید.
۲. **فوت‌پرینت:** کتابخانه‌ی فوت‌پرینت در KiCad پوشه‌ای با پسوند `.pretty` است. فایل `.kicad_mod` را داخل چنین پوشه‌ای بگذارید و پوشه را از *Preferences → Manage Footprint Libraries* اضافه کنید.
۳. **مدل سه‌بعدی:** در تنظیمات فوت‌پرینت به تب *3D Models* بروید و فایل `.step` را از پوشه‌ی `STEP/` انتخاب کنید.

## ذکر نام کتابخانه در پروژه‌ی شما

فایل‌ها تحت لایسنس CC BY 4.0 هستند، پس باید نام سازنده را ذکر کنید. لازم نیست روی خود برد نوشته شود؛ یک خط در جایی که پروژه‌تان مستند می‌شود کافی است (README، صفحه‌ی Credits، توضیحات BOM یا توضیحات ویدیو):

</div>

```
Altium/KiCad library and 3D models by africazani – https://github.com/africazani/africazani-altium-library (CC BY 4.0)
```

<div dir="rtl">

اگر فایل‌ها را تغییر داده‌اید، ذکر کنید که تغییر کرده‌اند.

## نکات

- ابعاد طبق دیتاشیت سازنده است؛ قبل از ساخت برد حتماً با آخرین دیتاشیت بررسی کنید.
- لوگوها و علائم تجاری روی مدل‌ها متعلق به صاحبان آن‌هاست.

## تغییرات نسخه‌ها

توضیحات هر نسخه را در صفحه‌ی [Releases](https://github.com/africazani/africazani-altium-library/releases) و فایل [CHANGELOG.md](CHANGELOG.md) ببینید.

</div>
