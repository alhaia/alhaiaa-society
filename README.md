# جمعية الحياة الفلسطينية الخيرية

واجهة ويب عربية ثابتة ومتجاوبة لإعادة تقديم موقع جمعية الحياة الفلسطينية الخيرية، مبنية باستخدام React وVite وTailwind CSS، مع دعم كامل لاتجاه RTL ومعرض يضم عشر صور للأنشطة.

## التشغيل محلياً

يتطلب المشروع Node.js وpnpm.

```bash
pnpm install
pnpm dev
```

لإنشاء نسخة الإنتاج:

```bash
pnpm run check
pnpm run build
```

## الرفع إلى GitHub

أنشئ مستودعاً جديداً، ثم نفّذ الأوامر التالية من داخل مجلد المشروع:

```bash
git init
git add .
git commit -m "Build Alhaia Arabic activities website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

## ملاحظات

المشروع واجهة أمامية ثابتة ولا يحتاج إلى قاعدة بيانات أو خادم API. الشعار والصور موجودة داخل `client/public`، لذلك يعمل الموقع مباشرة بعد رفعه إلى GitHub أو أي استضافة للملفات الثابتة. روابط التواصل في الصفحة تفتح واتساب والهاتف وحسابات الجمعية الخارجية.
