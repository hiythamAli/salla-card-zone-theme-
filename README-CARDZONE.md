# CardZone — Salla Twilight Theme

واجهة CardZone الأصلية محوّلة إلى Theme مبني على Salla Twilight / Theme Raed.

## التشغيل
1. استخدم Node المتوافق مع Raed (Node 22.18+ أو 24.11+).
2. ثبّت pnpm.
3. شغّل `pnpm install`.
4. شغّل `pnpm run development` أثناء التطوير أو `pnpm run production` للإنتاج.
5. اربط المجلد مع Salla CLI ثم نفّذ `salla theme preview`.

## ملاحظات
- الصفحة الرئيسية تستخدم تصميم CardZone وتستبدل البيانات الثابتة بقوائم منتجات Salla.
- السلة، الحساب، البحث، صفحات المنتج، التصنيفات، الطلبات والدفع تعتمد على مكونات Twilight/Salla الأصلية.
- صور CardZone موجودة داخل `src/assets/images/cardzone`.
- اسم الثيم وإعداداته موجودة في `twilight.json`.
