# GymTracker 🏋️‍♂️

[English](#english-guide) | [العربية](#الليل-الإرشادي)

---

## English Guide

GymTracker is a private, cloud-free body measurement tracker designed to help you monitor your fitness progress over long periods. It is a Progressive Web App (PWA) that works offline and saves data directly to your device.

### 🚀 How to Deploy

#### Option 1: GitHub Pages (Recommended)
1. Fork or upload these files to your GitHub repository.
2. Go to your repository **Settings**.
3. Navigate to **Pages** in the sidebar.
4. Under **Build and deployment**, set the branch to `main` and the folder to `/ (root)`.
5. Click **Save**. Your app will be live at `https://yourusername.github.io/your-repo-name/`.

#### Option 2: Netlify Drop
1. Drag and drop the main folder to [Netlify Drop](https://app.netlify.com/drop).
2. Use the provided URL to access your app.

### 💾 How Storage Works
Your privacy is the priority. Your data **never leaves your device**.
- **IndexedDB:** The app uses a local database inside your browser (Chrome/Safari) called IndexedDB.
- **Persistent Storage:** On first launch, the app requests "Persistent Storage" status. This prevents the operating system from deleting your data even if your phone storage is low.
- **Privacy:** There is no "Login" or "Cloud". You own the data. 
- **Backups:** Use the **Export JSON** feature in the settings page to download a backup of your data. It is recommended to do this monthly.

### 📱 Installation
Open the site URL in Chrome (Android) or Safari (iOS) and select **"Add to Home Screen"**. The app will then appear in your app drawer and work just like a native app, even without internet.

---

## الدليل الإرشادي (Arabic Guide)

GymTracker هو متتبع خاص لمقاييس الجسم، بدون سحابة، مصمم لمساعدتك في مراقبة تقدمك اللياقي عبر فترات طويلة. هو عبارة عن تطبيق ويب تقدمي (PWA) يعمل بدون إنترنت ويحفظ البيانات مباشرة على جهازك.

### 🚀 كيفية النشر

#### الخيار الأول: GitHub Pages (موصى به)
1. قم برفع هذه الملفات إلى مستودع GitHub الخاص بك.
2. اذهب إلى **إعدادات (Settings)** مستودعك.
3. انتقل إلى قسم **Pages** في القائمة الجانبية.
4. ضمن **Build and deployment**، اضبط الفرع (branch) على `main` والمجلد على `/ (root)`.
5. اضغط **حفظ (Save)**. سيكون تطبيقك متاحاً على الرابط `https://yourusername.github.io/your-repo-name/`.

#### الخيار الثاني: Netlify Drop
1. قم بسحب وإفلات المجلد الرئيسي في [Netlify Drop](https://app.netlify.com/drop).
2. استخدم الرابط المقدم للوصول إلى تطبيقك.

### 💾 كيف يعمل التخزين
خصوصيتك هي الأولوية. بياناتك **لا تغادر جهازك أبداً**.
- **IndexedDB:** يستخدم التطبيق قاعدة بيانات محلية داخل متصفحك تسمى IndexedDB.
- **التخزين الدائم (Persistent Storage):** عند التشغيل الأول، يطلب التطبيق حالة "التخزين الدائم". هذا يمنع نظام التشغيل من حذف بياناتك حتى لو كانت مساحة الهاتف منخفضة.
- **الخصوصية:** لا يوجد "تسجيل دخول" أو "سحابة". أنت تملك البيانات بالكامل.
- **النسخ الاحتياطي:** استخدم ميزة **Export JSON** في صفحة الإعدادات لتحميل نسخة احتياطية من بياناتك. يوصى بالقيام بذلك شهرياً.

### 📱 التثبيت
افتح رابط الموقع في Chrome (اندرويد) أو Safari (آيفون) واختر **"إضافة إلى الشاشة الرئيسية" (Add to Home Screen)**. سيظهر التطبيق كأنه تطبيق أصلي وسيعمل حتى بدون وجود إنترنت.
