# StudyMate AI – Live

אפליקציית סטודנטים בעברית: העלאת PDF/TXT, סיכום AI, יצירת מבחן AI, בדיקת תשובות וציונים מקומיים.

## פריסה
1. העלה את **כל התיקייה** למאגר GitHub חדש.
2. ב-Netlify בחר Add new project > Import an existing project > GitHub.
3. Build command: ריק. Publish directory: `.`. Functions directory: `netlify/functions` (מוגדר בקובץ netlify.toml).
4. Site configuration > Environment variables > Add variable: `OPENAI_API_KEY` = המפתח שלך. Scope: Functions או All scopes.
5. Deploy / Trigger deploy מחדש.
6. העלה חומר לימודי ובדוק סיכום ומבחן.

**חשוב:** פריסה באמצעות Netlify Drop לא תמיד כוללת בניית/פריסת Functions. מומלץ להשתמש ב-GitHub.

ציונים ומסמכים נשמרים רק ב-localStorage בדפדפן. אין חשבונות או סנכרון בין מכשירים. PDF סרוק אינו נתמך ללא OCR. שליחת סיכומים ל-API כרוכה בעיבוד אצל ספק AI ובעלות אפשרית. אל תעלה חומר רגיש ללא הרשאה. אין להוסיף מפתח API לקוד או ל-GitHub.
