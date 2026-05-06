<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: he
-->

# מדריך התקנה

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | 🌐 he | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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


