[English](README.md) | [فارسی](README.fa.md)

<div dir="rtl">

# کتابخانه آلتیوم

مجموعه‌ای از کتابخانه‌های **Altium Designer** همراه با مدل‌های سه‌بعدی **STEP** با جزئیات بالا (شامل نوشته‌های روی IC ها): نماد شماتیک، فوت‌پرینت و بدنه‌ی سه‌بعدی برای ماژول‌ها، آی‌سی‌ها، کانکتورها، قطعات پسیو و بسیاری قطعات دیگر.

---

## دسته‌بندی‌ها

| پوشه | محتوا |
|---|---|
| [`Resistors`](Resistors/) | مقاومت‌ها |
| [`Capacitors`](Capacitors/) | خازن‌ها |
| [`Inductors-Relays-Chokes`](Inductors-Relays-Chokes/) | سلف، رله و چوک |
| [`Diodes-LEDs`](Diodes-LEDs/) | دیود و LED |
| [`Transistors`](Transistors/) | ترانزیستور و ماسفت |
| [`ICs`](ICs/) | آی‌سی‌ها |
| [`MCUs`](MCUs/) | میکروکنترلرها |
| [`Modules`](Modules/) | ماژول‌ها (ESP32-WROOM-32U و ...) |
| [`Connectors`](Connectors/) | کانکتورها |
| [`Sensors`](Sensors/) | سنسورها |
| [`Crystals-Oscillators`](Crystals-Oscillators/) | کریستال و اسیلاتور |
| [`Switches-Buttons`](Switches-Buttons/) | کلید و دکمه |
| [`Displays`](Displays/) | نمایشگرها |
| [`Protection`](Protection/) | فیوز، TVS، وریستور و قطعات حفاظتی |
| [`Mechanical`](Mechanical/) | قطعات مکانیکی (سوراخ، پایه، قاب) |
| [`Misc`](Misc/) | سایر قطعات |

## ساختار پوشه‌ها

هر قطعه داخل دسته‌ی خودش یک پوشه‌ی جدا دارد:

</div>

```
<Category>/
└── <Part-Name>/
    ├── <Part-Name>.step
    ├── <Part-Name>.SchLib
    ├── <Part-Name>.PcbLib
    └── preview.png
```

<div dir="rtl">

## دانلود

**روش اول – کتابخانه‌ی کامل (پیشنهادی)**
همه‌ی قطعات در یک بسته: به صفحه‌ی [**Releases**](https://github.com/africazani/africazani-altium-library/releases/latest) بروید و آخرین فایل `.zip` را از بخش *Assets* دانلود کنید. هر نسخه توضیحاتی دارد که می‌گوید چه چیزی اضافه یا تغییر کرده است.

**روش دوم – یک قطعه‌ی مشخص**
در همین ریپو پوشه‌ی دسته‌ها را باز کنید، قطعه‌ی موردنظر را پیدا کنید و فایل‌هایش را دانلود کنید:

۱. پوشه‌ی قطعه را باز کنید (مثلاً `Modules/ESP32-WROOM-32U/`).
۲. روی فایل کلیک کنید و دکمه‌ی **Download raw file** را بزنید (یا با *Code → Download ZIP* کل ریپو را دانلود کنید).

## نحوه‌ی استفاده در Altium Designer

۱. کتابخانه‌ی کامل را از [Releases](https://github.com/africazani/africazani-altium-library/releases/latest) یا یک قطعه را از پوشه‌ی خودش دانلود کنید.
۲. در آلتیوم فایل‌های `.SchLib` و `.PcbLib` (یا `.IntLib`) را از مسیر *Components → File-based Libraries Preferences* اضافه کنید.
۳. مدل سه‌بعدی به فوت‌پرینت وصل است. اگر نمایش داده نشد، فایل `.step` را در پنل PCB Library دوباره لینک کنید.

## نکات

- ابعاد طبق دیتاشیت سازنده است؛ قبل از ساخت برد حتماً با آخرین دیتاشیت بررسی کنید.
- لوگوها و علائم تجاری روی مدل‌ها متعلق به صاحبان آن‌هاست.

## لایسنس

این اثر تحت لایسنس [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) منتشر شده است.
استفاده، تغییر و انتشار این فایل‌ها (حتی تجاری) آزاد است، به شرط ذکر نام سازنده:

> مدل‌های سه‌بعدی و کتابخانه‌ی آلتیوم توسط **africazani** – https://github.com/africazani/africazani-altium-library

## ارتباط

اشتباهی دیدید یا قطعه‌ی جدیدی می‌خواهید؟ Issue بسازید یا در تلگرام پیام بدهید: **@africazani**

</div>
