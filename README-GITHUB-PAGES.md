# Empire Bloom — הפעלה ב־GitHub Pages

הפרויקט הומר מ־Lovable / TanStack Start לגרסת Vite React סטטית שמתאימה ל־GitHub Pages.

## העלאה לגיטהאב

1. צור Repository חדש ב־GitHub.
2. העלה את כל הקבצים שבתיקייה הזו ל־Repository.
3. ודא שה־branch הראשי נקרא `main`.
4. ב־GitHub היכנס אל Settings → Pages.
5. תחת Build and deployment בחר Source: **GitHub Actions**.
6. היכנס ללשונית Actions וחכה שה־workflow בשם **Deploy to GitHub Pages** יסתיים בהצלחה.

## הרצה מקומית

```bash
npm install
npm run dev
```

## בנייה מקומית

```bash
npm run build
npm run preview
```

## הערה חשובה

אם שם ה־repository הוא רגיל, לדוגמה `empire-bloom`, האתר ייטען מכתובת בסגנון:
`https://USER.github.io/empire-bloom/`

אם זה repository מסוג `USER.github.io`, האתר ייטען מהשורש:
`https://USER.github.io/`
