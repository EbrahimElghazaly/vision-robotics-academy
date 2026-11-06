<!--
=====================================================================
  README.md  ·  Robotics Study Hub · أكاديمية الروبوتات
  Bilingual (AR/EN) README for the "Introduction to Vision and Robotics"
  interactive study companion. Single-file, dependency-free project.
=====================================================================
-->

<div align="center">

# 🤖 Robotics Study Hub · أكاديمية الروبوتات

**An interactive, bilingual (AR/EN) study companion for _Introduction to Vision and Robotics_.**
**ملخص تفاعلي ثنائي اللغة لمقرر _مقدمة في الرؤية والروبوتات_.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-5146e5?style=for-the-badge)](./LICENSE)
[![Single File](https://img.shields.io/badge/single--file-index.html-0891b2?style=for-the-badge)](./index.html)
[![Accessibility](https://img.shields.io/badge/a11y-ready-087b56?style=for-the-badge)](#-accessibility--إمكانية-الوصول)

[Features](#-features--المميزات) ·
[Quick Start](#-quick-start--البدء-السريع) ·
[Structure](#-project-structure--هيكل-المشروع) ·
[Content](#-content-coverage--تغطية-المحتوى) ·
[Tech](#-built-with--التقنيات) ·
[Usage](#-usage-tips--نصائح-الاستخدام) ·
[Contributing](#-contributing--المساهمة) ·
[License](#-license--الترخيص)

</div>

---

## 📖 About · عن المشروع

**EN —** A single-file, dependency-free web application built to help students **study, review, and self-test** the material of _Introduction to Vision and Robotics_ (pages **1–112**). It combines a structured Arabic summary, a **60-question** practice bank with explanations, and a **20-question** graded final quiz — all wrapped in a clean, accessible, dark-mode-ready UI with a **full Arabic ⇄ English language switch**.

The project intentionally ships as **one self-contained `index.html`** so it can be shared, printed, or opened offline without a build step or internet connection.

**AR —** تطبيق ويب **بملف واحد** وبدون أي مكتبات خارجية، صُمم لمساعدة الطلاب على **مذاكرة ومراجعة واختبار** محتوى مقرر **مقدمة في الرؤية والروبوتات** (الصفحات **1–112**). يجمع بين ملخص عربي منظم، وبنك **60 سؤالًا** تدريبيًا مع التفسيرات، وكويز نهائي من **20 سؤالًا** — كل ذلك بواجهة أنيقة، قابلة للوصول، تدعم الوضع الليلي، مع **تبديل كامل بين العربية والإنجليزية**.

المشروع **ملف `index.html` واحد مكتفٍ بذاته**، يمكن مشاركته أو طباعته أو فتحه بدون إنترنت وبدون أي خطوة بناء.

---

## ✨ Features · المميزات

| # | Feature | الميزة |
|---|---|---|
| 🌍 | **Full AR ⇄ EN switch** — every heading, table, question, explanation, and UI label is translated. Preferences saved in `localStorage`. | **تبديل كامل عربي ⇄ إنجليزي** — لكل عنوان وجدول وسؤال وشرح وعنصر واجهة. يُحفظ التفضيل في `localStorage`. |
| 📚 | **9-chapter structured summary** with tables, formulas, callouts, and memory aids. | **ملخص من 9 محاور** مع جداول ومعادلات وتنبيهات ومساعدات حفظ. |
| 🧠 | **60 practice questions** (20 MCQ + 10 True/False + 10 short/calculation in the original bank, plus 20 MCQ + 10 True/False in the extra bank) with instant feedback. | **60 سؤالًا تدريبيًا** (20 اختيار + 10 صح/غلط + 10 قصير/مسائل في البنك الأصلي، و20 اختيار + 10 صح/غلط في البنك الإضافي) مع تصحيح فوري. |
| 🎯 | **20-question final quiz** with question map, progress bar, animated score ring, per-question review, and "mistakes only" filter. | **كويز نهائي من 20 سؤالًا** مع خريطة أسئلة وشريط تقدم وحلقة نتيجة متحركة ومراجعة لكل سؤال وفلتر «الأخطاء فقط». |
| 🔍 | **Search & filter** across both practice banks. | **بحث وتصفية** داخل بنكي الأسئلة. |
| 🌗 | **Light / Dark mode** with saved preference and `prefers-color-scheme` fallback. | **وضع نهاري / ليلي** مع حفظ التفضيل والرجوع لإعداد النظام عند عدم وجود اختيار. |
| 🖨️ | **Print / Save-as-PDF** for the summary + all 60 practice questions with answers. The final quiz is excluded from print. | **طباعة / حفظ PDF** للملخص وكل الأسئلة الستين مع الإجابات. الكويز النهائي مستبعد من الطباعة. |
| ♿ | **Accessibility**: skip-link, `focus-visible`, ARIA roles & states, `prefers-reduced-motion`. | **إمكانية وصول**: skip-link، تركيز مرئي، أدوار وحالات ARIA، احترام تقليل الحركة. |
| 📱 | **Fully responsive** from small phones to wide desktops, with logical CSS properties for correct RTL/LTR mirroring. | **متجاوب بالكامل** من الهواتف الصغيرة لشاشات سطح المكتب، مع خصائص CSS منطقية لانعكاس صحيح RTL/LTR. |
| 🧩 | **Zero dependencies** — no frameworks, no build tools, no external icons. | **بدون أي تبعيات** — لا أطر عمل، لا أدوات بناء، لا أيقونات خارجية. |
| 🌐 | **i18n-ready architecture** — adding a third language is a data-only change. | **بنية جاهزة للغات** — إضافة لغة ثالثة تصبح تغييرًا في البيانات فقط. |

---

## 🚀 Quick Start · البدء السريع

### Option 1 — Run locally · تشغيل محلي

```bash
# 1. Clone the repository
git clone https://github.com/<USERNAME>/<REPO>.git
cd <REPO>

# 2. Open the app
#    → Just double-click index.html, or:
#    macOS:
open index.html
#    Linux:
xdg-open index.html
#    Windows:
start index.html
```

> **AR:** لا يحتاج تثبيتًا ولا سيرفرًا ولا إنترنت — افتح `index.html` مباشرة في أي متصفح حديث (Chrome, Edge, Firefox, Safari).

### Option 2 — Live on GitHub Pages · تشغيل أونلاين

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. **Source:** `Deploy from a branch` · **Branch:** `main` · **Folder:** `/ (root)` → **Save**.
4. Wait ~1 minute, then visit:

   ```
   https://<USERNAME>.github.io/<REPO>/
   ```

> **AR:** بعد الرفع، فعّل GitHub Pages من إعدادات المستودع، وستحصل على رابط حي تشاركه مع أي شخص — بدون أي إعداد إضافي.

### Requirements · المتطلبات

- Any **modern browser** (Chrome/Edge 90+, Firefox 88+, Safari 14+).
- **No Node.js**, no npm, no bundler required.
- Optional: a local static server if you prefer (e.g. `python3 -m http.server`).

---

## 📂 Project Structure · هيكل المشروع

```
.
├── index.html      # The entire app: HTML + CSS + JS + i18n data + question banks + quiz logic
├── README.md       # This file
└── LICENSE         # MIT License
```

> **Design principle / مبدأ التصميم:** ship as **one self-contained file** so the project can be shared, printed, or opened offline. All content (summary, 60 practice questions, 20 quiz questions, translations) lives inside `index.html`.

---

## 🧭 Content Coverage · تغطية المحتوى

The summary is organized into **9 chapters**:

| # | Chapter | المحور |
|---|---|---|
| 01 | History & Applications | التاريخ والتطبيقات |
| 02 | Robots & Autonomy | الروبوت والاستقلالية |
| 03 | Robot Components & Power | مكونات الروبوت والطاقة |
| 04 | Actuators, Motors & Gearing | المشغلات والمحركات والتروس |
| 05 | Locomotion, Stability & DOF | الحركة والاستقرار ودرجات الحرية |
| 06 | Robot Kinematics | حركيات الروبوت |
| 07 | Robot Sensors | حساسات الروبوت |
| 08 | Control Systems & PID | أنظمة التحكم و PID |
| 09 | Homogeneous Transformations | التحويل المتجانس |

### Scope note · ملاحظة النطاق

- **EN —** The summary covers pages **1–112** of the course material. The _Robot Vision_ chapter starting at page **113** is **out of scope**. Vision sensors introduced **before** page 113 are included.
- **AR —** الملخص يغطي الصفحات **1–112** من المادة. فصل **Robot Vision** الذي يبدأ في الصفحة **113** **غير مشمول**. أما حساسات الرؤية الواردة **قبل** ذلك فهي مشمولة.

### Question bank breakdown · تفصيل بنك الأسئلة

| Bank | MCQs | True/False | Short/Calculation | Total |
|---|---:|---:|---:|---:|
| **Original review** · المراجعة الأصلية | 15 | 5 | 10 | **30** |
| **Extra practice** · الأسئلة الإضافية | 20 | 10 | 0 | **30** |
| **Final quiz** · الكويز النهائي | 20 | 0 | 0 | **20** |
| **Total practice** · إجمالي التدريب | 35 | 15 | 10 | **60** |

---

## 🛠️ Built With · التقنيات

- **HTML5** — semantic markup, RTL/LTR aware, accessible roles.
- **CSS3** — custom properties (design tokens), logical properties (`margin-inline`, `inset-inline`, `text-align: start`), grid & flexbox, media queries, print styles, `prefers-reduced-motion`, `prefers-color-scheme`.
- **Vanilla JavaScript (ES2020+)** — no frameworks, no build tools, no polyfills.
- **i18n architecture** — structured translation objects, `data-i18n` attributes, dynamic re-render for banks and quiz on language switch.

### Browser support · دعم المتصفحات

| Browser | Supported |
|---|---|
| Chrome / Edge | ✅ 90+ |
| Firefox | ✅ 88+ |
| Safari | ✅ 14+ |
| Mobile Chrome / Safari | ✅ |

> Uses modern CSS (`clamp()`, logical properties, `:focus-visible`, `backdrop-filter`) and ES2020+ JS (`String.prototype.replaceAll`, optional chaining, `Map`).

---

## ⌨️ Usage Tips · نصائح الاستخدام

- 🌐 **Language switch** — use the globe button in the top bar to switch between **العربية** and **English**. Your **quiz progress and answers are preserved** when you switch.
- 🌙 **Dark mode** — use the moon/sun button to toggle. The preference is saved in `localStorage` and respects `prefers-color-scheme` if no choice is stored.
- 🖨️ **Print / PDF** — use the printer button to export the summary + all 60 practice questions with answers. The final quiz is excluded. Current search filters are temporarily cleared for a complete print, then restored automatically.
- 🔍 **Search & filter** — before practicing, type a keyword (e.g. `PID`, `sensors`, `مفاصل`, `kinematics`) or filter by question type to focus your session.
- 🎯 **Final quiz** — the side **question map** lets you jump to any question. You can change answers freely until you press **Submit**. If questions are missing, the app takes you to the first unanswered one. After submission you get a score, time spent, per-category priority, and a **per-question review** with a **"mistakes only"** filter.
- ♻️ **Reset practice** — each practice bank has its own **Reset** button (with confirmation) that clears **only that bank's** answers.
- ♿ **Keyboard navigation** — every interactive element is keyboard-accessible with visible focus rings.

---

## 🔒 Privacy & Data · الخصوصية والبيانات

- **No tracking, no analytics, no cookies.**
- **No network requests** — the app is 100% offline.
- Only **two values** may be written to `localStorage`:
  - `robotics-study-theme` — `"light"` or `"dark"`.
  - `robotics-study-lang` — `"ar"` or `"en"`.
- Quiz progress is **in-memory only** and is lost on page reload (by design).

> **AR:** لا تتبّع، لا تحليلات، لا كوكيز، ولا طلبات شبكة. يُحفظ فقط المظهر واللغة في `localStorage`. تقدم الكويز في الذاكرة فقط ويُفقد عند إعادة تحميل الصفحة.

---

## 🤝 Contributing · المساهمة

Contributions, corrections, and translations are welcome!

1. **Fork** the repository.
2. Create a branch:
   ```bash
   git checkout -b feature/amazing-idea
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "feat: add XYZ"
   ```
4. Push:
   ```bash
   git push origin feature/amazing-idea
   ```
5. Open a **Pull Request** describing what you changed and why.

### Ideas welcome · أفكار مرحّب بها

- Adding more practice questions or clarifying explanations.
- Improving accessibility, print layout, or dark-mode contrast.
- Adding a third language (the i18n structure is designed for it).
- Fixing typos in Arabic or English technical terms.
- Improving performance or reducing file size.

### Reporting content errors · الإبلاغ عن أخطاء في المحتوى

If you spot a technical error in the summary or questions, please open an **Issue** and include:

- The **chapter** name or **question number**.
- The **page** (if known).
- The **correction** you suggest (with a reference if possible).

> **AR:** عند الإبلاغ عن خطأ تقني، اذكر اسم المحور أو رقم السؤال، والصفحة إن وُجدت، والتصحيح المقترح مع المرجع إن أمكن.

---

## 🐛 Known Limitations · قيود معروفة

- **Quiz progress is not persisted** across page reloads (intentional, privacy-friendly).
- **Print** excludes the final quiz and interactive feedback by design.
- The app targets **modern browsers**; older browsers (IE, legacy Edge) are **not supported**.
- All content lives in `index.html`, which makes the file large but keeps it **portable and shareable** as a single artifact.

> **AR:** تقدم الكويز لا يُحفظ بعد إعادة التحميل (بشكل مقصود). الطباعة تستبعد الكويز والتفاعلات. المتصفحات القديمة غير مدعومة. حجم الملف كبير لأنه يحتوي كل المحتوى، لكنه محمول وقابل للمشاركة كملف واحد.

---

## 📜 License · الترخيص

Released under the **MIT License** — see [`LICENSE`](./LICENSE) for the full text.

> **AR:** المشروع مرخّص تحت **رخصة MIT** — يمكنك استخدامه وتعديله وإعادة توزيعه مع الإبقاء على إشعار حقوق النشر. راجع ملف [`LICENSE`](./LICENSE) للنص الكامل.

---

## 🙏 Acknowledgements · شكر وتقدير

- **Course:** _Introduction to Vision and Robotics_ — **Dr. Aida A. Nasr**, Faculty of Artificial Intelligence, KFS.
- **Icons:** inline SVG (no external icon library).
- **Built with care** for students who prefer a **focused, distraction-free study companion**.

> **AR:** المقرر: _مقدمة في الرؤية والروبوتات_ — **د. عايدة أ. نصر**، كلية الذكاء الاصطناعي، KFS. الأيقونات SVG مضمّنة. صُنع بعناية لطلاب يفضّلون تجربة مذاكرة **مركّزة وخالية من التشتيت**.

---

## 🏷️ Topics · الوسوم المقترحة

Copy these into **Settings → Topics** on GitHub:

```
robotics  education  study-tools  i18n  arabic  english  rtl  single-file
vanilla-js  html5  css3  computer-vision  quiz-app  pid-controller  kinematics
sensors  accessibility  dark-mode  print-friendly  offline-first
```

---

<div align="center">

**If this helped you, give the repo a ⭐ — it really makes a difference!**

**لو المشروع أفادك، اعمله ⭐ — الفرق بسيط لكنه يعني كتير!**

</div>
