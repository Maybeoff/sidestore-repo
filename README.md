# My SideStore Repository

Персональный репозиторий приложений для SideStore (форка AltStore).

## Приложения

- **Spotify++** v8.6.54 - Spotify с дополнительными возможностями
- **YouTube++** v1.0.0 - YouTube с дополнительными возможностями
- **Avito** v148.0 - Площадка объявлений
- **Tinkoff Bank** v6.13.5 - Мобильный банк Тинькофф

## Использование

### Способ 1: Через кнопку (рекомендуется)

[![Add to SideStore](https://img.shields.io/badge/Add%20to-SideStore-blue?style=for-the-badge)](https://stikstore.app/altdirect/?url=https://maybeyoou.ru/sidestore-repo/apps.json)

### Способ 2: Вручную

1. Откройте SideStore
2. Перейдите в "Sources" (Источники)
3. Нажмите "+" и добавьте URL репозитория:
   ```
   https://maybeyoou.ru/sidestore-repo/apps.json
   ```
4. Приложения появятся в списке доступных для установки

## Структура репозитория

```
.
├── apps.json           # Основной файл репозитория
├── ipas/               # Папка с IPA файлами
│   ├── 4-Spotify++ v8.6.54.ipa
│   ├── YouTube++.ipa
│   ├── ru_avito_app_148_0_und3fined.ipa
│   └── Tinkoff+Bank+6.13.5.ipa
├── README.md           # Этот файл
└── .gitattributes      # Git LFS конфигурация
```

## Требования

- iOS 14.0+
- SideStore 0.6.0+ или AltStore 2.0+

## Примечания

- IPA файлы хранятся в GitHub с использованием Git LFS
- Все приложения подписаны и готовы к установке
- Обновления добавляются регулярно

## Лицензия

MIT
