[English](README.md) | [فارسی](README.fa.md)

<div dir="rtl">

# کتابخانه آلتیوم

مجموعه‌ای از کتابخانه‌های **Altium Designer** و **KiCad** همراه با مدل‌های سه‌بعدی **STEP** با جزئیات بالا (شامل نوشته‌های روی IC ها): نماد شماتیک، فوت‌پرینت و بدنه‌ی سه‌بعدی برای ماژول‌ها، آی‌سی‌ها، کانکتورها، قطعات پسیو و بسیاری قطعات دیگر.

---

## دسته‌بندی‌ها

| پوشه | محتوا |
|---|---|
| [`Resistors`](Components/Resistors/) | مقاومت‌ها |
| [`Capacitors`](Components/Capacitors/) | خازن‌ها |
| [`Inductors-Relays-Chokes`](Components/Inductors-Relays-Chokes/) | سلف، رله و چوک |
| [`Diodes-LEDs`](Components/Diodes-LEDs/) | دیود و LED |
| [`Transistors`](Components/Transistors/) | ترانزیستور و ماسفت |
| [`ICs`](Components/ICs/) | آی‌سی‌ها |
| [`MCUs`](Components/MCUs/) | میکروکنترلرها |
| [`Modules`](Components/Modules/) | ماژول‌ها (ESP32-WROOM-32U و ...) |
| [`Connectors`](Components/Connectors/) | کانکتورها |
| [`Sensors`](Components/Sensors/) | سنسورها |
| [`Crystals-Oscillators`](Components/Crystals-Oscillators/) | کریستال و اسیلاتور |
| [`Switches-Buttons`](Components/Switches-Buttons/) | کلید و دکمه |
| [`Displays`](Components/Displays/) | نمایشگرها |
| [`Protection`](Components/Protection/) | فیوز، TVS، وریستور و قطعات حفاظتی |
| [`Mechanical`](Components/Mechanical/) | قطعات مکانیکی (سوراخ، پایه، قاب) |
| [`Misc`](Components/Misc/) | سایر قطعات |

## ساختار ریپو

</div>

```
/
├── Components/     همه‌ی قطعات، دسته‌بندی‌شده (هر قطعه یک پوشه)
├── Library-Info/   راهنمای استفاده، نکات و تغییرات
├── LICENSE
├── README.md
└── README.fa.md
```

<div dir="rtl">

- دنبال یک قطعه‌ی مشخص هستید؟ پوشه‌ی [`Components`](Components/) را باز کنید و دسته‌ی آن را انتخاب کنید.
- می‌خواهید بدانید کتابخانه چطور نصب و استفاده می‌شود؟ به [`Library-Info`](Library-Info/) بروید.

هر قطعه داخل دسته‌ی خودش یک پوشه‌ی جدا دارد:

</div>

```
Components/<Category>/<Part-Name>/
├── Altium/    (.SchLib, .PcbLib)
├── KiCad/     (.kicad_sym, .kicad_mod)
├── STEP/      (.step – works in any CAD/EDA tool)
└── preview.png
```

<div dir="rtl">

## دانلود

**روش اول – کتابخانه‌ی کامل (پیشنهادی)**
همه‌ی قطعات در یک بسته: به صفحه‌ی [**Releases**](https://github.com/africazani/africazani-altium-library/releases/latest) بروید و آخرین فایل `.zip` را از بخش *Assets* دانلود کنید. هر نسخه توضیحاتی دارد که می‌گوید چه چیزی اضافه یا تغییر کرده است.

**روش دوم – یک قطعه‌ی مشخص**
در همین ریپو پوشه‌ی [`Components`](Components/) را باز کنید، قطعه‌ی موردنظر را پیدا کنید و فایل‌هایش را دانلود کنید:

۱. پوشه‌ی قطعه را باز کنید (مثلاً `Components/Modules/ESP32-WROOM-32U/`).
۲. روی فایل کلیک کنید و دکمه‌ی **Download raw file** را بزنید (یا با *Code → Download ZIP* کل ریپو را دانلود کنید).

مراحل نصب و نکات: [Library-Info](Library-Info/) را ببینید.

## لایسنس

این اثر تحت لایسنس [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) منتشر شده است.
استفاده، تغییر و انتشار این فایل‌ها (حتی تجاری) آزاد است، به شرط ذکر نام سازنده:

> کتابخانه‌های Altium/KiCad و مدل‌های سه‌بعدی توسط **africazani** – https://github.com/africazani/africazani-altium-library

روش ذکر نام کتابخانه در پروژه‌ی خودتان: [Library-Info](Library-Info/README.fa.md) را ببینید.

## ارتباط

اشتباهی دیدید یا قطعه‌ی جدیدی می‌خواهید؟ Issue بسازید یا در تلگرام پیام بدهید: **@africazani**

</div>
