پروژه فروشگاه NOÉR — نسخه آماده
-------------------------------
مسیرها:
  frontend/  -> پروژه React + Vite + Tailwind
  backend/   -> پروژه Node.js + Express + MongoDB + Zarinpal

دستورالعمل سریع اجرا (لوکال):
1) Backend:
   cd backend
   cp .env.example .env
   # مقدار MERCHANT_ID و CALLBACK_BASE را در .env قرار دهید (برای تست از ngrok)
   npm install
   npm run dev

2) Frontend:
   cd frontend
   npm install
   npm run dev
   نمایش: http://localhost:5173

نکات:
- لوگوی برند در frontend/public/logo.jpg قرار دارد.
- برای پرداخت واقعی از MERCHANT_ID زرین‌پال استفاده کنید و CALLBACK_BASE را آدرس عمومی سرور قرار دهید.
- به نکات امنیتی در مستند قبلی توجه کنید.
