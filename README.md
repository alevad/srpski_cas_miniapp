# Srpski_Cas Mini App (placeholder)

## Что это
Минимальная страница для Mini App, чтобы получить HTTPS‑URL и подключить его к боту.

## Публикация через GitHub Pages
1) Инициализировать git:
   - `git init`
2) Закоммитить:
   - `git add -A`
   - `git commit -m "Publish mini app"`
3) Создать репозиторий на GitHub (например `srpski-cas-miniapp`) и подключить remote:
   - `git remote add origin https://github.com/<username>/srpski-cas-miniapp.git`
   - `git push -u origin main`
4) В GitHub: Settings → Pages → Deploy from branch → `main` / `/root`
5) Полученный URL вставить в `WEBAPP_URL` в `C:\Users\aleva\Srpski_Cas\infra\.env`
