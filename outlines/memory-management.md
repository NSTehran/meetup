# مدیریت حافظه

## تاریخچه

- سگمنتاسیون
- حافظه اجرایی
- زبان غیرساختاریافته و حافظه گلوبال
- زبان سی و استک
  - اسنک فراخوانی
  - مزایا و محدودیت
- هیپ
  - مدیریت دستی، معایب
    - نشت
    - دسترسی خارج محدوده و سوراخ امنیتی
  - کلاس و نمونه سازی
  - Garbage Collector
    - Tracing
      - مزایا (Linked list)
      - معایب
    - Static Analyzed
    - Reference Counting
 
## انواع مدیریت حافظه در پلتفرم اپل

- MRC
  - CoreFoundation
- ARC
  - By refrence
    - Copying
    - Mutable
  - By value
    - Mutation
    - Copy on write

## نکات ARC

- انتقال بین بلاک
  - capture list
- Retain cycle (سیکل رفرنس)
  - Cycle & Closure retaining
  - weak & unowned
  - Escaping
    - تفاوتشان و طریقه مدیریشان توسط سیستم

## اشکال زدایی

- NSZombie
- Instruments
  - Allocations

## پیشرفته

- کش و آزاد سازی
  - Memory Warning
- Memory safty
  - Atomicity
- لی‌آوت مموری
  - Size, Stride, Alignment (CPU)
  - Contiguous allocation
  - Layout of swift Struct, Enum, Array
- Unsafe memory
  - Bit cast
  - Pointer
  - Raw Pointer
  - Buffer Pointer
- Future: Rust style management
