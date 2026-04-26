# CI Cyber Readiness Assessment

אבחון מוכנות ניהולית לאירוע סייבר — Critical Impact

---

## 🔗 קישורים ישירים

| קובץ | קישור |
|------|--------|
| 📋 שאלון — עברית | [assessment-he.html](https://gal-debug.github.io/ci_assesment-/assessment-he.html) |
| 📋 שאלון — אנגלית | [assessment-en.html](https://gal-debug.github.io/ci_assesment-/assessment-en.html) |
| 📄 PDF הזמנה — עברית | [invite-he.html](https://gal-debug.github.io/ci_assesment-/invite-he.html) |
| 📄 PDF הזמנה — אנגלית | [invite-en.html](https://gal-debug.github.io/ci_assesment-/invite-en.html) |

---

## 📤 איך שולחים ללקוח (Flow מלא)

**שלב 1 — הורד PDF הזמנה**
1. פתח את [invite-he.html](https://gal-debug.github.io/ci_assesment-/invite-he.html) (עברית) או [invite-en.html](https://gal-debug.github.io/ci_assesment-/invite-en.html) (אנגלית)
2. לחץ **"הורד PDF הזמנה"**
3. בחלון ההדפסה:
   - בחר **Save as PDF**
   - הפעל **Background graphics** ✓
   - שוליים: **None**

**שלב 2 — שלח ב-LinkedIn**
- צרף את ה-PDF להודעת DM ב-LinkedIn

**שלב 3 — הליד ממלא**
- הליד פותח את הקישור / סורק QR
- ממלא שם, מייל, חברה
- עובר 8 שאלות (≈3 דקות)
- מקבל ציון + דוח PDF אישי

**שלב 4 — אתה מקבל**
- מייל אוטומטי דרך Make.com עם כל הפרטים

---

## 📁 קבצים בריפו

| קובץ | תיאור |
|------|--------|
| `assessment-he.html` | השאלון המלא — עברית |
| `assessment-en.html` | השאלון המלא — אנגלית |
| `invite-he.html` | דף יצירת PDF הזמנה — עברית |
| `invite-en.html` | דף יצירת PDF הזמנה — אנגלית |

---

## ⚙️ Webhook / Make.com

**Endpoint:** `https://hook.eu1.make.com/493lc8pdnosjbyha4bk99z1yrjvjig1v`

**נתונים שנשלחים עם כל הגשה:**

```json
{
  "name": "שם המשתמש",
  "email": "מייל",
  "company": "חברה",
  "score": 67,
  "level": "מוכנות בינונית",
  "date": "2026-04-26T10:00:00.000Z",
  "q1": "תשובה לשאלה 1",
  ...
  "q8": "תשובה לשאלה 8"
}
