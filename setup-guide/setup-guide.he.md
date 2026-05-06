<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: he
-->

# מדריך התקנה

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | 🇮🇱 עברית | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

חבר את GateTap לבקר הגישה שלך

## לפני שמתחילים

ודא שהאייפון שלך מחובר לאותה רשת מקומית כמו בקר הגישה שלך.

GateTap פועל כולו בתוך הרשת המקומית שלך וצרכי:
• כתובת ה-IP של הבקר
• שם משתמש וסיסמה


## שלב 1: מצא את הכתובת והאישורים של הבקר

כדי לחבר את GateTap, אתה צריך את כתובת ה-IP של הבקר ואת אישורי הכניסה.

בחר אחת מהאפשרויות הבאות:


## אפשרות א': שאל את המתקין שלך (מומלץ)

אם המערכת שלך הותקנה על ידי חשמלאי או טכנאי, סביר להניח שהם כבר הגדירו הכל.

במקרים רבים:
• הבקר משתמש בכתובת IP קבועה
• או שהנתב מקצה את אותו IP באמצעות הזמנה

בקש מהם את כתובת ה-IP ופרטי הכניסה. זו בדרך כלל הדרך הקלה והמהירה ביותר.


## אפשרות ב': בדוק את הנתב שלך

פתח את דף התצורה של הנתב שלך וחפש התקנים מחוברים.

כדי לגשת לנתב שלך, אתה בדרך כלל צריך את הכתובת המקומית שלו (למשל `192.168.1.1` או שם כמו `fritz.box`) ואת פרטי הכניסה של הנתב.

ניתן לקרוא לסעיף זה:
• התקנים מחוברים
• LAN
• לקוחות DHCP

חפש:
• מכשירים קוויים לא ידועים
• ערכים שעשויים לייצג את הבקר שלך

כתובת ה-IP בדרך כלל תיראה כך:
`192.168.x.x` או `10.0.x.x`

![דוגמה להתקנים מחוברים לנתב](../assets/setup-guide/he/img_01.png)


## אפשרות ג': סרוק את הרשת שלך

השתמש באפליקציית סורק רשת באייפון או במחשב שלך.

סרוק את הרשת שלך ונסה לפתוח כתובות IP שהתגלו בספארי, לדוגמה:

`http://192.168.1.50`

אם מופיע דף הכניסה של הבקר, מצאת את הכתובת הנכונה.

![דוגמה לסורק רשת](../assets/setup-guide/he/img_02.png)


## שלב 2: הוסף את הבקר ב-GateTap

פתח את GateTap והזן:
• כתובת ה-IP
• שם המשתמש שלך
• הסיסמה שלך

השתמש באותם אישורים כמו עבור ממשק האינטרנט של הבקר.


## שלב 3: בדוק את החיבור

שמור את התצורה שלך ונסה לפתוח דלת או שער.

אם לא קורה כלום, בדוק:
• האייפון שלך נמצא באותה רשת
• כתובת ה-IP נכונה
• הבקר מופעל וניתן להגיע אליו


## שלב 4: שמור על כתובת ה-IP יציבה

כדי למנוע בעיות מאוחר יותר, הבקר צריך תמיד להשתמש באותה כתובת IP.

ניתן לעשות זאת על ידי:
• הגדרת IP סטטי בבקר
• יצירת הזמנת DHCP בנתב שלך


## אבטחה

הנתונים שלך נשארים במכשיר שלך.

באפשרותך להגן על GateTap באמצעות Face ID או Touch ID בהגדרות האפליקציה.


