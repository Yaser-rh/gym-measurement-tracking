# GymTracker 🏋️‍♂️

A simple, private way to track your body measurements and see your progress over time.

## 🚀 How to Set Up (Get it on your phone)

1. **Upload your files:** Go to [Netlify Drop](https://app.netlify.com/drop) on your computer.
2. **Drag and drop:** Drag the entire `track app` folder onto that page.
3. **Get your link:** Netlify will give you a private website link (e.g., `https://shiny-gym-123.netlify.app`).
4. **Open on your phone:** Send that link to your phone and open it in Chrome (Android) or Safari (iPhone).
5. **Add to Home Screen:**
   - **Android:** Tap the three dots (⋮) and select **"Add to Home Screen"**.
   - **iPhone:** Tap the Share button and select **"Add to Home Screen"**.

Now you have a private gym app that works even without internet!

---

## 💾 Technical: How Storage Works

This app is designed with a "Privacy-First, Cloud-Free" architecture.

- **No Cloud Storage:** Your data never leaves your device. There is no central server or database.
- **IndexedDB:** The app uses a high-performance local database system built into your browser called **IndexedDB**. This allows for complex querying (for graphs) and large data history storage directly on your hardware.
- **Persistence API:** Upon first launch, the app requests **Persistent Storage** status from the browser (`navigator.storage.persist()`). When granted, the operating system is prohibited from automatically "cleaning up" or deleting your data, even if your phone's storage becomes full.
- **Service Workers:** Using a Service Worker script (`sw.js`), the app files themselves are cached locally. This allows the app to load instantly and function fully offline.
- **Portability:** Since the data is local, you should use the **Export JSON** feature in the settings periodically. This extracts your internal IndexedDB records into a standardized JSON file that you can use to move your data to a new device or keep a personal backup.

---

# [العربية] الدليل الإرشادي

## GymTracker 🏋️‍♂️ (متتبع التمارين)
وسيلة بسيطة وخاصة لتتبع قياسات جسمك ومراقبة تطورك مع مرور الوقت.

### 🚀 كيفية الإعداد (تثبيته على هاتفك)
1.  **رفع الملفات:** اذهب إلى موقع [Netlify Drop](https://app.netlify.com/drop) عبر جهاز الكمبيوتر.
2.  **السحب والإفلات:** قم بسحب مجلد `track app` بالكامل وإفلاته داخل الصفحة.
3.  **الحصول على الرابط:** سيمنحك الموقع رابطاً خاصاً (مثال: `https://shiny-gym-123.netlify.app`).
4.  **الفتح على الهاتف:** أرسل الرابط إلى هاتفك وافتحه باستخدام متصفح كروم (أندرويد) أو سفاري (آيفون).
5.  **الإضافة إلى الشاشة الرئيسية:**
    -   **أندرويد:** اضغط على النقاط الثلاث (⋮) ثم اختر **"الإضافة إلى الشاشة الرئيسية"**.
    -   **آيفون:** اضغط على زر **"مشاركة"** ثم اختر **"الإضافة إلى الشاشة الرئيسية"**.

الآن أصبح لديك تطبيق رياضي خاص يعمل حتى بدون إنترنت!

---

### 💾 معلومات تقنية: كيف يتم تخزين البيانات؟
تم تصميم هذا التطبيق وفق مبدأ "الخصوصية أولاً، وبدون سحابة إلكترونية".

*   **لا يوجد تخزين سحابي:** بياناتك لا تغادر جهازك أبداً، ولا يوجد خادم (Server) مركزي أو قاعدة بيانات خارجية.
*   **تقنية IndexedDB:** يستخدم التطبيق نظام قاعدة بيانات محلية عالية الأداء مدمجة في متصفحك تسمى **IndexedDB**. تتيح هذه التقنية عرض الرسوم البيانية وتخزين سجل بيانات ضخم مباشرة على جهازك.
*   **واجهة برمجة الثبات (Persistence API):** عند تشغيل التطبيق لأول مرة، يطلب المتصفح إذناً لـ "التخزين الدائم". بمجرد الموافقة، يُمنع نظام التشغيل من مسح بياناتك تلقائياً لتوفير مساحة، حتى لو كانت ذاكرة الهاتف ممتلئة.
*   **تقنية Service Workers:** بفضل ملف (`sw.js`)، يتم حفظ ملفات التطبيق نفسه مؤقتاً على الجهاز، مما يسمح للتطبيق بالعمل فوراً وبشكل كامل دون الحاجة لاتصال بالإنترنت.
*   **نقل البيانات:** بما أن البيانات محلية، يُنصح باستخدام ميزة **"تصدير JSON"** من الإعدادات بشكل دوري. سيؤدي ذلك لاستخراج بياناتك في ملف بصيغة JSON يمكنك استخدامه لنقل بياناتك إلى جهاز جديد أو للاحتفاظ بنسخة احتياطية.

