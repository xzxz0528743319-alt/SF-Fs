# מדיניות פרטיות – ספר טלפונים

עדכון אחרון: נובמבר 2026

אפליקציית "ספר טלפונים" היא אפליקציית טלפון, הודעות וספר כתובות. אין בה פרסומות, ואין בה כלי מעקב, סטטיסטיקה או פרסום.

## מה נשמר רק בטלפון שלך
- **הספר האישי** – אנשי הקשר שתוסיף לספר האישי נשמרים רק בטלפון. הם לא נשלחים לשום שרת.
- **יומן השיחות וההודעות** – האפליקציה קוראת ומציגה אותם מתוך הטלפון, כדי לשמש כאפליקציית הטלפון וה-SMS שלך. הם לא נשלחים לשום מקום.
- **אנשי הקשר של הטלפון** – משמשים רק כדי להציג שם של מי שמתקשר. לא נשלחים לשום מקום.

## מה נשלח לשרת
- **חשבון** – כדי להשתמש בספר הכללי המשותף נרשמים עם כתובת מייל וסיסמה. המייל משמש רק להתחברות ולא מוצג למשתמשים אחרים.
- **הספר הכללי** – רשומות שתבחר להוסיף לספר הכללי (שם, טלפון, עיר, כתובת, שם האב, חם, שטיבל) גלויות לכל משתמשי האפליקציה. אימייל של איש קשר נשמר אבל לא מוצג לאף משתמש אחר. רק מי שהוסיף רשומה יכול לערוך או למחוק אותה.
- **דיווחים על העוזרת** – אם תדווח על תשובה של העוזרת, השאלה והתשובה נשמרות לבדיקה.

השרת מופעל באמצעות Supabase, והתקשורת אליו מוצפנת (HTTPS).

## העוזרת (AI)
העוזרת היא תוספת אופציונלית ופועלת רק אם הזנת מפתח API משלך. כשאתה שואל אותה, השאלה שלך ורשומות מתאימות מהספר הכללי נשלחות ל-Anthropic (Claude) כדי לקבל תשובה. **הספר האישי לעולם לא נשלח לעוזרת.** התשובות נוצרות אוטומטית ועלולות לכלול טעויות.

## הרשאות שהאפליקציה מבקשת
טלפון, יומן שיחות, SMS, אנשי קשר והתראות – כדי לחייג, לקבל שיחות והודעות ולזהות מתקשרים, כאפליקציית ברירת המחדל. ההרשאות משמשות רק לתפקודים האלה.

## מחיקת מידע
- **מחיקת החשבון:** באפליקציה – הגדרות ← חשבון וספר כללי ← "מחיקת החשבון". החשבון נמחק, וכל הרשומות שהוספת לספר הכללי מוסרות מכל הטלפונים.
- **מחיקת הספר האישי:** מחיקת איש קשר, או הסרת האפליקציה, מוחקות אותו מהטלפון.
- אפשר גם לבקש מחיקה בפנייה לכתובת המייל של המפתח שמופיעה בדף האפליקציה ב-Google Play.

## ילדים
האפליקציה לא מיועדת לילדים מתחת לגיל 13.

---

# Privacy Policy – Phonebook (ספר טלפונים)

Last updated: November 2026

Phonebook is a phone, SMS and contacts app. It contains no ads, analytics or trackers.

**Stored only on your device:** your personal book, your call log and SMS (read to act as your default phone/SMS app), and device contacts (used only for caller ID). None of these are sent anywhere.

**Sent to our server (Supabase, over HTTPS):** your account email (used only for sign-in, never shown to others); entries you choose to add to the shared book (name, phone, city, address, father's name, in-law, synagogue) – visible to all app users, except the contact's email which is never shown; and AI responses you report.

**AI assistant (optional):** works only with your own API key. Your question and matching shared-book entries are sent to Anthropic (Claude). Your personal book is never sent.

**Permissions:** phone, call log, SMS, contacts and notifications are used only to work as your default phone and SMS app.

**Deleting data:** in the app go to Settings → Account → "Delete account". Your account is deleted and all entries you added to the shared book are removed. You can also request deletion via the developer email listed on Google Play.

**Children:** not directed at children under 13.
