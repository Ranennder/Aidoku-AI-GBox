# Aidoku AI — источник GBox

Публичный репозиторий для загрузки Aidoku AI через GBox.

В разделе источников GBox добавь эту ссылку:

```text
https://raw.githubusercontent.com/Ranennder/Aidoku-AI-GBox/main/gbox.appsrc
```

Выбери **Aidoku AI**, скачай IPA и подпиши своим сертификатом перед установкой.

## Файлы сборки r2

- [Неподписанная IPA](https://github.com/Ranennder/Aidoku-AI-GBox/releases/download/ai-preview-2026-11-01-r2/Aidoku-AI-unsigned.ipa).
- [Полные исходники этой сборки](https://github.com/Ranennder/Aidoku-AI-GBox/releases/download/ai-preview-2026-11-01-r2/Aidoku-AI-source-d2098a52.zip).

Версия приложения: **0.9 (4)**, bundle ID: `app.ranennder.AidokuAI`, минимальная версия iOS: **15.0**. Исправлено падение при запуске из-за настройки ProMotion. Приложение запустилось в симуляторе; прошли 55 Swift-тестов и 33 теста миграции. На физическом iPhone работа и плавность ещё требуют проверки.

SHA-256 IPA: `1d99b130e86ee917ebf608ad4e2733468015fdd07d53b2e0a4932976a38d0a3a`.

## Подключение к ПК

Для улучшения страниц запусти Mihon AI Companion на ПК и введи его адрес в настройках чтения → **AI на компьютере**. Совместимые расширения Mihon работают на ПК через Suwayomi. Инструкции переноса библиотеки и сборки находятся в `docs/MIGRATION.md` и `docs/BUILD.md` внутри архива исходников.

Aidoku AI основан на [Aidoku](https://github.com/Aidoku/Aidoku); права исходных авторов сохранены. Лицензия кода приложения — GPLv3, переводы имеют отдельную лицензию Apache 2.0. Архив содержит полный код коммита `d2098a52a808f8566cb4222c9339a3e2cf5176b8`, из которого собрана IPA, включая файлы проекта, описание зависимостей и инструкции сборки.

Формат источника описан в [официальной документации GBox](https://github.com/GBoxApp/GBoxSource). При обновлении приложения нужно менять ссылки/версию в `gbox.appsrc` и `sourceUpdateTime`, чтобы GBox перечитал список.
