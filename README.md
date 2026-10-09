### Привет 👋

Пишу инструменты для интеграций с российскими маркетплейсами и
логистическими сервисами — Wildberries, Ozon, Lamoda, МойСклад,
Деловые Линии. Каждый репозиторий — рабочий инструмент, решающий
конкретную операционную задачу продавца: генерация и учёт кодов,
работа с API, автоматизация рутины.

За несколько лет накопилось множество аналитических таблиц и
прототипов на Google Apps Script — рабочих, но не масштабируемых.
Сейчас перевожу эту логику в полноценные продукты на Python и
других языках. Ориентир на будущее — облачная микросервисная
архитектура, где отдельные модули при необходимости можно
упаковать и развернуть локально.

**Стек:** Python (PySide6, FastAPI, SQLite) для десктоп-инструментов
и бэкендов, Kotlin/Jetpack Compose для Android, Ruby on Rails для
аналитики долгового рынка — выбираю под задачу, а не подгоняю задачу
под любимый стек. Люблю пробовать новый язык на конкретной задаче,
а не на абстрактных туториалах.

**Подход:** тестами покрываю логику до GUI, коммичу маленькими
шагами, документирую бизнес-контекст в README каждого репозитория —
не просто "что делает код", а "зачем он вообще нужен".

### Направления

**Инструменты продавца на маркетплейсах РФ** — генерация и учёт
маркировки, работа с API, мониторинг изменений в контракте площадок:
- [generate-box-code](https://github.com/Servandeath/generate-box-code) —
  генератор уникальных кодов коробов с этикетками Code128/QR и печатью
  на принтер · ✅ [v1.2.0](https://github.com/Servandeath/generate-box-code/releases/latest)
- [wb-barcode-gui](https://github.com/Servandeath/wb-barcode-gui) —
  «Мастер этикеток»: этикетки 58×40 мм с EAN-13 из Excel ·
  ✅ [v1.1.2](https://github.com/Servandeath/wb-barcode-gui/releases/latest)
- [wb-boss-widget](https://github.com/Servandeath/wb-boss-widget) —
  Chrome-виджет с маржой по кабинетам WB · 🟡 MVP работает end-to-end
- [wb-api-workbench](https://github.com/Servandeath/wb-api-workbench) —
  ключи, роли и тестер Wildberries/Ozon API · 🟡 v0.4 в работе
- [api-crash-dog](https://github.com/Servandeath/api-crash-dog) —
  раннее обнаружение изменений в контрактах API площадок · 🔹 концепт

**Внутренняя логистика** — склад с интеграцией МойСклад:
- [stack-flow-survive](https://github.com/Servandeath/stack-flow-survive) —
  WMS: веб-админка и Android-приложение сборки · 🔹 в разработке
- [ms-bin-catcher-go](https://github.com/Servandeath/ms-bin-catcher-go) —
  работа с ячейками склада с телефона · 🔹 ранняя разработка

**Другой трек** — учусь новому языку на реальной задаче, не на туториалах:
[bonds-tracker](https://github.com/Servandeath/bonds-tracker) (Ruby on Rails)

---

Закреплённые репозитории обновляются по мере готовности проектов.

