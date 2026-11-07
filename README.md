# سامانه رزرو نوبت درمانگاه (ClinicBook)

پروژه‌ی تحلیلی درس **مهندسی نرم‌افزار** (مرجع: پرسمن و مکسیم، ویرایش ۸ و ۹)

- **نام دانشجو:** علیرضا طاعتی

## فهرست مستندات
| هفته | موضوع | فایل |
|---|---|---|
| ۱ | داستان‌های کاربر و Product Backlog | [week01-user-stories.md](week01-user-stories.md) |
| ۲ | نیازمندی‌ها | [week02-requirements.md](week02-requirements.md) |
| ۳ | Use Case و Activity Diagram | [week03-uml-models.md](week03-uml-models.md) |
| ۴ | ماژول‌ها، Cohesion و Coupling | [week04-modules-cohesion-coupling.md](week04-modules-cohesion-coupling.md) |
| ۵ | معماری لایه‌ای و اینترفیس‌ها | [week05-architecture.md](week05-architecture.md) |
| ۷ | تضمین کیفیت و چک‌لیست بازبینی | [week07-quality-assurance.md](week07-quality-assurance.md) |
| ۸ | کیس‌های تست و BVA | [week08-testing.md](week08-testing.md) |
| ۹ | SCM و فرم درخواست تغییر | [week09-scm.md](week09-scm.md) |
| ۱۰ | تحلیل ریسک و RMMM | [week10-risk-management.md](week10-risk-management.md) |
| ۱۱ | تخمین، زمان‌بندی و نگهداری | [week11-estimation-scheduling-maintenance.md](week11-estimation-scheduling-maintenance.md) |
| ۱۲ | دفترچه‌ی نهایی | [FINAL-booklet.md](FINAL-booklet.md) |

> نمودارها با Mermaid نوشته شده‌اند و در گیتهاب به‌صورت خودکار نمایش داده می‌شوند.

## پروتوتایپ وب‌اپلیکیشن
فایل [clinicbook.html](clinicbook.html) یک پروتوتایپ فرانت‌اند تک‌فایلی است. برای اجرا کافی است آن را در مرورگر باز کنید (نیازی به نصب چیزی نیست).

| قابلیت | داستان کاربر | نیازمندی |
|---|---|---|
| ثبت‌نام و ورود | US-01 | FR-01، FR-02 |
| جستجوی پزشک | US-02 | FR-04 |
| رزرو با قفل ۱۰ دقیقه‌ای و جلوگیری از رزرو تکراری | US-03 | FR-06 تا FR-08 |
| پرداخت آزمایشی | US-06 (شبیه‌سازی) | FR-09 |
| لغو نوبت تا ۲ ساعت قبل و سقف ۲ نوبت در روز | US-04 | FR-10 |

**محدودیت‌ها:** داده‌ها در localStorage مرورگر ذخیره می‌شوند و بک‌اند یا پیامک واقعی وجود ندارد. بخش‌های پزشک، منشی و مدیر در Sprintهای بعدی برنامه‌ریزی شده‌اند.
