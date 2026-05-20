# GymTracker 🏋️‍♂️

A simple, private way to track your body measurements and see your progress over time.

## 🚀 How to Install & Use (Get it on your phone)

The app is deployed directly on GitHub Pages! 

1. **Open the link:** Visit [https://yaser-rh.github.io/gym-measurement-tracking/](https://yaser-rh.github.io/gym-measurement-tracking/) in your browser (Safari on iPhone, Chrome on Android).
2. **Add / Pin to Home Screen:**
   - **Android (Chrome):** Tap the menu button (three dots `⋮` at the top right) and select **"Add to Home Screen"**.
   - **iPhone (Safari):** Tap the Share button (square with an arrow pointing up at the bottom) and select **"Add to Home Screen"**.

Now you have a private gym app pinned as an app icon on your phone that works fully offline without internet!

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

### 🚀 كيفية التثبيت والاستخدام (على هاتفك)

التطبيق مرفوع وجاهز للاستخدام مباشرة عبر GitHub Pages!

1. **فتح الرابط:** قم بزيارة الرابط التالي من متصفح هاتفك (Safari للآيفون، أو Chrome للأندرويد):
   [https://yaser-rh.github.io/gym-measurement-tracking/](https://yaser-rh.github.io/gym-measurement-tracking/)
2. **الإضافة إلى الشاشة الرئيسية (تثبيت كـ تطبيق):**
   - **أندرويد (Chrome):** اضغط على زر القائمة (الثلاث نقاط `⋮` في الأعلى) ثم اختر **"الإضافة إلى الشاشة الرئيسية"** (Add to Home Screen).
   - **آيفون (Safari):** اضغط على زر المشاركة (مربع يخرج منه سهم للأعلى في الأسفل) ثم اختر **"الإضافة إلى الشاشة الرئيسية"** (Add to Home Screen).

الآن أصبح لديك تطبيق رياضي خاص ومثبت على شاشة هاتفك يعمل بالكامل بدون اتصال بالإنترنت!

---

### 💾 معلومات تقنية: كيف يتم تخزين البيانات؟
تم تصميم هذا التطبيق وفق مبدأ "الخصوصية أولاً، وبدون سحابة إلكترونية".

*   **لا يوجد تخزين سحابي:** بياناتك لا تغادر جهازك أبداً، ولا يوجد خادم (Server) مركزي أو قاعدة بيانات خارجية.
*   **تقنية IndexedDB:** يستخدم التطبيق نظام قاعدة بيانات محلية عالية الأداء مدمجة في متصفحك تسمى **IndexedDB**. تتيح هذه التقنية عرض الرسوم البيانية وتخزين سجل بيانات ضخم مباشرة على جهازك.
*   **واجهة برمجة الثبات (Persistence API):** عند تشغيل التطبيق لأول مرة، يطلب المتصفح إذناً لـ "التخزين الدائم". بمجرد الموافقة، يُمنع نظام التشغيل من مسح بياناتك تلقائياً لتوفير مساحة، حتى لو كانت ذاكرة الهاتف ممتلئة.
*   **تقنية Service Workers:** بفضل ملف (`sw.js`)، يتم حفظ ملفات التطبيق نفسه مؤقتاً على الجهاز، مما يسمح للتطبيق بالعمل فوراً وبشكل كامل دون الحاجة لاتصال بالإنترنت.
*   **نقل البيانات:** بما أن البيانات محلية، يُنصح باستخدام ميزة **"تصدير JSON"** من الإعدادات بشكل دوري. سيؤدي ذلك لاستخراج بياناتك في ملف بصيغة JSON يمكنك استخدامه لنقل بياناتك إلى جهاز جديد أو للاحتفاظ بنسخة احتياطية.

