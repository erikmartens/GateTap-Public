<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: ar
-->

# دليل الإعداد

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | 🇸🇦 العربية | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

قم بتوصيل GateTap بوحدة التحكم في الوصول الخاصة بك

## قبل أن تبدأ

تأكد من أن جهاز iPhone الخاص بك متصل بنفس الشبكة المحلية مثل وحدة التحكم في الوصول الخاصة بك.

تعمل GateTap بالكامل ضمن شبكتك المحلية وتحتاج إلى:
• عنوان IP الخاص بوحدة التحكم
• اسم المستخدم وكلمة المرور


## الخطوة 1: ابحث عن عنوان وحدة التحكم وبيانات الاعتماد

لتوصيل GateTap، تحتاج إلى عنوان IP الخاص بوحدة التحكم وبيانات اعتماد تسجيل الدخول.

اختر أحد الخيارات التالية:


## الخيار أ: اسأل المُثبِّت لديك (موصى به)

إذا تم تثبيت نظامك بواسطة كهربائي أو فني، فمن المحتمل أنه قام بتكوين كل شيء بالفعل.

في كثير من الحالات:
• تستخدم وحدة التحكم عنوان IP ثابتًا
• أو يقوم جهاز التوجيه بتعيين نفس IP عبر الحجز

اطلب منهم عنوان IP وتفاصيل تسجيل الدخول. هذه هي عادة الطريقة الأسهل والأسرع.


## الخيار ب: التحقق من جهاز التوجيه الخاص بك

افتح صفحة تكوين جهاز التوجيه الخاص بك وابحث عن الأجهزة المتصلة.

للوصول إلى جهاز التوجيه الخاص بك، تحتاج عادةً إلى عنوانه المحلي (على سبيل المثال `192.168.1.1` أو اسم مثل `fritz.box`) وبيانات اعتماد تسجيل الدخول الخاصة بجهاز التوجيه.

يمكن أن يسمى هذا القسم:
• الأجهزة المتصلة
• الشبكة المحلية
• عملاء DHCP

ابحث عن:
• أجهزة سلكية غير معروفة
• الإدخالات التي قد تمثل وحدة التحكم الخاصة بك

سيبدو عنوان IP عادةً كما يلي:
`192.168.x.x` أو `10.0.x.x`

![مثال على الأجهزة المتصلة بجهاز التوجيه](../assets/setup-guide/ar/img_01.png)


## الخيار ج: فحص شبكتك

استخدم تطبيق الماسح الضوئي للشبكة على جهاز iPhone أو جهاز الكمبيوتر الخاص بك.

افحص شبكتك وحاول فتح عناوين IP المكتشفة في Safari، على سبيل المثال:

`http://192.168.1.50`

إذا ظهرت صفحة تسجيل الدخول الخاصة بوحدة التحكم، فقد وجدت العنوان الصحيح.

![مثال لفحص الشبكة](../assets/setup-guide/ar/img_02.png)


## الخطوة 2: أضف وحدة التحكم في GateTap

افتح GateTap وأدخل:
• عنوان IP
• اسم المستخدم الخاص بك
• كلمة المرور الخاصة بك

استخدم نفس بيانات الاعتماد المستخدمة في واجهة الويب الخاصة بوحدة التحكم.


## الخطوة 3: اختبار الاتصال

احفظ التكوين الخاص بك وحاول فتح باب أو بوابة.

إذا لم يحدث شيء، تحقق مما يلي:
• جهاز iPhone الخاص بك موجود على نفس الشبكة
• عنوان IP صحيح
• وحدة التحكم مدعومة ويمكن الوصول إليها


## الخطوة 4: حافظ على استقرار عنوان IP

ولتجنب حدوث مشكلات لاحقًا، يجب على وحدة التحكم دائمًا استخدام نفس عنوان IP.

يمكن القيام بذلك عن طريق:
• تحديد IP ثابت على وحدة التحكم
• إنشاء حجز DHCP في جهاز التوجيه الخاص بك


## الأمن

تبقى بياناتك على جهازك.

يمكنك اختياريًا حماية GateTap باستخدام Face ID أو Touch ID في إعدادات التطبيق.


