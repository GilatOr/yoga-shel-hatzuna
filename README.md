# דף הנחיתה — היוגה של התזונה

## פתיחת תצוגה מקומית

מתיקיית הפרויקט מפעילים שרת מקומי על תיקיית `site`:

```powershell
python -m http.server 8000 --directory site
```

אם הפקודה `python` אינה זמינה, יש להפעיל את Python המצורף לסביבת Codex באותה פקודה.

לאחר מכן פותחים בדפדפן:

http://127.0.0.1:8000/

להפסקת השרת לוחצים `Ctrl+C` בחלון שבו הוא רץ.

### הפעלה ברקע ב-Windows

```powershell
Start-Process python -ArgumentList '-m','http.server','8000','--directory','site' -WindowStyle Hidden
```

האתר הוא סטטי: כל קבצי הדף נמצאים בתיקיית `site`.
