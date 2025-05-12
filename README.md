# جدول امتحانات كلية علوم الرياضة - جامعة أسيوط (Faculty of Sports Science Exam Schedule Viewer)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

هذا المشروع عبارة عن صفحة ويب لعرض جدول امتحانات الفرقة الأولى بكلية علوم الرياضة في جامعة أسيوط. تم تصميمه ليكون سهل الاستخدام، جذاب بصرياً، ومتجاوب مع مختلف أحجام الشاشات.

This project is a web page designed to display the exam schedule for the first year at the Faculty of Sports Science, Assiut University. It aims to be user-friendly, visually appealing, and responsive across different screen sizes.

---

## ✨ الميزات الرئيسية | Key Features

*   **📅 عرض متعدد | Multiple Views:**
    *   **بطاقات (Cards):** عرض تفصيلي لكل امتحان في بطاقة منفصلة.
    *   **جدول (Table):** عرض كلاسيكي لجميع الامتحانات في شكل جدول منظم.
    *   **تقويم (Calendar):** عرض مرئي للامتحانات على تقويم الشهر.
*   **⏳ عداد تنازلي | Countdown Timer:** يعرض الوقت المتبقي لكل امتحان قادم.
*   **🚦 حالة الامتحان | Exam Status:** يوضح حالة كل امتحان (قادم، قريب، استعد، اليوم، انتهى).
*   **🎨 وضع ليلي/نهاري | Dark/Light Mode:** زر لتبديل المظهر بين الوضع الفاتح والداكن.
*   **📱 تصميم متجاوب | Responsive Design:** يعمل بشكل جيد على أجهزة الكمبيوتر المكتبية والأجهزة اللوحية والهواتف المحمولة.
*   **🌍 دعم اللغة العربية | Arabic (RTL) Support:** واجهة مصممة بالكامل لدعم اللغة العربية والتنسيق من اليمين لليسار.
*   **💅 تصميم حديث | Modern UI:** واجهة مستخدم نظيفة وجذابة مع انتقالات سلسة.
*   **🛠️ كود نقي | Vanilla Code:** مكتوب باستخدام HTML، CSS، و JavaScript فقط (بدون مكتبات أو أطر عمل).

---

## 🚀 كيف يعمل | How to Use

لا توجد خطوات تثبيت معقدة. فقط قم بما يلي:

No complex installation is required. Just follow these steps:

1.  **📥 تحميل الريبو | Clone/Download:**
    *   قم بنسخ (Clone) هذا المستودع أو تحميله كملف مضغوط (Download ZIP).
    *   Clone this repository or download it as a ZIP file.
2.  **📂 فتح الملف | Open the File:**
    *   افتح الملف `code (18).html` (أو أي اسم قمت بحفظه به) في متصفح الويب المفضل لديك (مثل Chrome, Firefox, Edge).
    *   Open the `index.html` file in your favorite web browser (e.g., Chrome, Firefox, Edge).

وها أنت ذا! سترى جدول الامتحانات.
That's it! You should see the exam schedule page.

---

## 🔧 التقنيات المستخدمة | Technologies Used

*   **HTML5:** لهيكلة محتوى الصفحة. (For structuring the page content)
*   **CSS3:** لتصميم وتنسيق الصفحة، بما في ذلك الوضع الداكن والتصميم المتجاوب. (For styling, including dark mode and responsive design)
*   **JavaScript (Vanilla):** للوظائف الديناميكية مثل:
    *   عرض بيانات الامتحانات. (Rendering exam data)
    *   تبديل طرق العرض. (Switching views)
    *   حساب وعرض العد التنازلي. (Calculating and displaying countdowns)
    *   تبديل المظهر (الوضع الداكن/الفاتح). (Toggling the theme)
    *   إنشاء عرض التقويم. (Generating the calendar view)

---

## ✏️ التخصيص | Customization

لتعديل بيانات الامتحانات (إضافة، حذف، أو تغيير المواد والمواعيد):

To modify the exam data (add, remove, or change subjects and dates):

1.  افتح ملف الـ `HTML`. (Open the `HTML` file).
2.  ابحث عن المتغير `exams` داخل وسم `<script>` في نهاية الملف. (Find the `exams` variable within the `<script>` tag near the end of the file).
3.  قم بتعديل المصفوفة (array) حسب الحاجة. كل عنصر في المصفوفة يمثل امتحانًا وله الخصائص التالية:
    *   `date`: تاريخ الامتحان (YYYY-MM-DD).
    *   `day`: اسم اليوم (نص).
    *   `subject`: اسم المادة (نص).
    *   `time`: وقت الامتحان (نص).
    *   `icon`: رمز تعبيري للمادة (اختياري).
    *   `details`: تفاصيل إضافية (مثل القاعة - حاليًا تم تعديل الكود لعرض "صالات هندسة" بشكل ثابت في عرض البطاقات).
    *   Modify the array as needed. Each object in the array represents an exam and has the following properties:
        *   `date`: Exam date (YYYY-MM-DD).
        *   `day`: Day name (string).
        *   `subject`: Subject name (string).
        *   `time`: Exam time (string).
        *   `icon`: Emoji for the subject (optional).
        *   `details`: Additional details (like the hall - currently, the code is modified to show "صالات هندسة" statically in the card view).

---


## 🤝 المساهمة | Contributing

المساهمات مرحب بها! إذا كان لديك اقتراحات لتحسين الكود أو إضافة ميزات جديدة، لا تتردد في فتح Issue أو Pull Request.

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

---

## 📜 الترخيص | License

هذا المشروع مرخص بموجب ترخيص MIT. انظر ملف `LICENSE` لمزيد من التفاصيل (يمكنك إنشاء ملف LICENSE وإضافة محتوى ترخيص MIT القياسي إليه).

This project is licensed under the MIT License. See the `LICENSE` .
