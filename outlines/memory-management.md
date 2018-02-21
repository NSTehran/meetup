# مدیریت حافظه

## تاریخچه

  - پیج ها و امضای آن
  -  حافظه اجرایی
- زبان فرترن و حافظه گلوبال
- زبان سی و استک
  - کال استک
  - مزایا و محدودیت
- هیپ
  - مدیریت دستی، معایب
    - لیک
    - دسترسی خارج محدوده و سوراخ امنیتی
  - کلاس و نمونه سازی
  - Garbage Collector
    - Cyclic
      - مزایا (Linked list)
      - معایب
    - Static Analyzed
    - Reference Counting
 
## انواع مدیریت حافظه در پلتفرم اپل

- MRC
- CoreFoundation classes
- ARC
  - By refrence
    - Copying
    - Mutable
  - By value
    - Mutation, Copy on write

## ARC

- Hash Table
- انتقال بین بلاک
- Retain cycle (سیکل رفرنس)
  - closure retain (capture list)
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

## آینده

- Rust style management
