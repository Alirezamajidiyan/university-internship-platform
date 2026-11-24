# Docker Compose

فایل `compose.production.yml` فقط الگوی اولیه است. قبل از استقرار باید موارد زیر تکمیل شوند:

- نام دامنه و تنظیمات Reverse Proxy.
- متغیرهای اتصال دیتابیس.
- تنظیمات Storage و مسیر فایل‌ها.
- Secretهای احراز هویت و OTP.
- Healthcheck متناسب با Backend و PWA.
- سیاست Backup و Migration.

هیچ Secret واقعی را در این پوشه یا Git ذخیره نکنید. مقادیر محیط Production فقط روی سرور و با Permission محدود نگهداری شوند.
