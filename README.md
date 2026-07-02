# تطبيق ترقيم الفواتير - PDF Sequencer

تطبيق Flutter لترقيم الفواتير تلقائياً عن طريق وضع رقم تسلسلي على نموذج PDF.

---

## 🚀 كيفية الحصول على ملف APK عبر GitHub (مجاني)

### الخطوة 1: إنشاء حساب GitHub
- اذهب إلى: https://github.com
- اضغط **Sign up** وأنشئ حساباً مجانياً

### الخطوة 2: إنشاء مستودع جديد
1. بعد الدخول، اضغط الزر الأخضر **New** أو اذهب إلى: https://github.com/new
2. في **Repository name** اكتب: `pdf-sequencer`
3. اختر **Public** (مجاني)
4. **لا تضع أي علامة** على Initialize, .gitignore, license
5. اضغط **Create repository**

### الخطوة 3: رفع الملفات
افتح موجه الأوامر (CMD) في هذا المجلد:
```
C:\Users\alaqel computer\.gemini\antigravity\scratch\pdf_sequencer_flutter
```

ثم نفّذ هذه الأوامر بالترتيب (استبدل `YOUR_USERNAME` باسم مستخدمك في GitHub):
```bash
git init
git add .
git commit -m "Initial commit: PDF Sequencer app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/pdf-sequencer.git
git push -u origin main
```

### الخطوة 4: انتظر بناء APK
1. اذهب إلى مستودعك على GitHub: `https://github.com/YOUR_USERNAME/pdf-sequencer`
2. اضغط على تبويب **Actions**
3. ستجد workflow يعمل باسم **"Build Flutter APK"**
4. انتظر 5-10 دقائق حتى ينتهي (ستتحول الدائرة من 🟡 إلى ✅)

### الخطوة 5: تحميل APK
1. انقر على اسم الـ workflow الذي اكتمل
2. في الأسفل ستجد قسم **Artifacts**
3. انقر على **pdf-sequencer-apk** لتحميل الملف
4. فكّ ضغط الملف المحمّل وستجد `app-release.apk`

### الخطوة 6: تثبيت على الهاتف
1. انقل الملف `app-release.apk` إلى هاتفك
2. على الهاتف: **الإعدادات ← الأمان ← السماح بمصادر غير معروفة**
3. افتح الملف وثبّت التطبيق

---

## 📱 كيفية استخدام التطبيق

1. **اختر نموذج الفاتورة** - اضغط "اختيار نموذج الفاتورة" وحدد ملف PDF
2. **حدد مكان الرقم** - انقر على المعاينة في المكان الذي تريد ظهور الرقم فيه
3. **أدخل النطاق** - مثلاً: من 1 إلى 100
4. **تخصيص الرقم** - اختر البادئة، اللاحقة، حجم الخط، واللون
5. **ابدأ الترقيم** - اضغط "بدء الترقيم وتصدير الفواتير"
6. ستجد الفواتير محفوظة في مجلد المستندات على هاتفك
