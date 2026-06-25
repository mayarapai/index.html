# מתכנן פרישה מוקדמת — הגשר שלנו

React component — קובץ יחיד, ללא צורך בהתקנות נוספות מעבר ל־recharts.

## שימוש

```bash
npm install recharts
```

ייבא את הקומפוננטה:

```jsx
import App from './RetirementBridgePlanner';
```

## תלויות
- React 18+
- recharts

## הערות
- כל הנתונים נשמרים ב־`window.storage` (פרטי למשתמש)
- אומדני המס מבוססים על קבועי 2026 — לא תחליף לייעוץ מס
