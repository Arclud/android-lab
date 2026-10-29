# Android Lab

Учебный сайт на русском про современную Android-разработку: Kotlin, Compose и архитектуру. Адаптирован для телефона и компьютера. Есть переключение акцента в демо и план обучения с сохранением прогресса в браузере.

## Посмотреть локально

Откройте `index.html` в браузере. Установка и сборка не нужны.

## Опубликовать на GitHub Pages через браузер

1. Войдите на https://github.com и создайте новый репозиторий: кнопка **+ → New repository**.
2. Назовите его `android-lab`, выберите **Public**, включите **Add a README file**, затем **Create repository**.
3. В репозитории нажмите **Add file → Upload files**. Перетащите `index.html` из этой папки. Файл должен оказаться в корне репозитория, рядом с README, а не внутри папки `android-lab`.
4. Нажмите **Commit changes** (при запросе выберите сохранение в ветку `main`).
5. Откройте **Settings → Pages**. В разделе **Build and deployment** выберите **Source: Deploy from a branch**, **Branch: main**, папку **/(root)**. Нажмите **Save**.
6. Дождитесь публикации — изменения могут появляться до 10 минут. На этой же странице появится ссылка **Visit site**.

Обычный адрес: `https://ВАШ-ЛОГИН.github.io/android-lab/`.

Для обновления загрузите изменённый `index.html` в тот же репозиторий и сохраните изменения. GitHub Pages обновит сайт автоматически.

Сайт не требует сервера, ключей, Node.js или платных библиотек. Все стили и скрипт находятся в index.html; внешние шрифты и изображения не загружаются. Ссылки на документацию открываются в новой вкладке.

## Источники

- Публикация: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Создание Pages: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- Архитектура: https://developer.android.com/topic/architecture/recommendations
- Kotlin: https://kotlinlang.org/docs/getting-started.html
- Compose: https://developer.android.com/develop/ui/compose

Неофициальный учебный проект. Интерактивный макет выполнен на HTML/CSS/JavaScript и иллюстрирует идею управления интерфейсом через состояние; пример Kotlin предназначен для знакомства с Compose.
