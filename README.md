# דף נחיתה · ליווי לניהול סושיאל

אתר סטטי מוכן ל-GitHub Pages: `index.html` + תיקיית `media` (תמונות וסרטונים).

## העלאה
1. ב-GitHub: New repository → שם (למשל `landing`) → Public → Create.
2. בעמוד הריפו: "uploading an existing file" → לגרור את **התוכן** של התיקייה (index.html, README.md, .nojekyll ותיקיית media) → Commit.
3. Settings → Pages → Source: Deploy from a branch → Branch: main, תיקייה / (root) → Save.
4. אחרי דקה-שתיים הכתובת תופיע שם: `https://<שם-משתמש>.github.io/landing/`

## הטופס
הטופס מחובר לוואטסאפ 050-2411710 (בקובץ: `var WHATSAPP_NUMBER = "972502411710";`). כדי להחליף מספר, משנים את השורה הזו.
בראש הסקריפט בתחתית index.html יש את השורה הזו.
כשממלאים מספר (למשל `972501234567`), כל מי שממלא את הטופס שולח לכם את הפרטים בוואטסאפ. כשהשורה ריקה, הטופס רק מציג הודעת תודה והפרטים לא נשמרים.
