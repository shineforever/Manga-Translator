# translateManga - Переводчик Манги - Руководство Пользователя

*Выбор языка: [English](README.md) | [繁體中文](README_TC.md) | [العربية](README_AR.md) | [Magyar](README_HU.md) | [ไทย](README_TH.md) | [한국어](README_KO.md) | [Türkçe](README_TR.md) | [Polski](README_PL.md) | [Français](README_FR.md) | [Русский](README_RU.md) | [Español](README_ES.md)*

![Баннер переводчика манги](./images/宣传图001.png)

## 📚 Содержание

- [🌟 Введение в Проект](#введение-в-проект)
- [🔍 Технические Принципы](#технические-принципы)
- [✨ Функции](#функции)
- [🚀 Руководство по Использованию](#руководство-по-использованию)
- [🌎 Региональная Адаптация](#региональная-адаптация)
- [📊 Примеры Использования](#примеры-использования)
- [❓ Часто Задаваемые Вопросы](#часто-задаваемые-вопросы)

## 🌟 Введение в Проект

**translateManga** - это продвинутый инструмент для перевода манги на основе искусственного интеллекта, способный интеллектуально распознавать текст в манге и обеспечивать высококачественный многоязычный перевод, при этом идеально сохраняя оригинальный художественный стиль и компоновку. Будь то японская манга, корейская манхва или западные комиксы, вы можете легко наслаждаться чтением на разных языках.

Официальный сайт: [https://translatemanga.online](https://translatemanga.online)

### Основные Преимущества

- **Интеллектуальное Распознавание**: Передовая OCR-технология точно идентифицирует текст манги в различных шрифтах и макетах
- **Точный Перевод**: Контекстный перевод на основе новейших больших языковых моделей (GPT-4, Claude и др.)
- **Сохранение Макета**: Переведенный текст идеально интегрируется в оригинальные пузыри и макет
- **Поддержка Множества Языков**: Поддерживает перевод между более чем 100 языками
- **Пакетная Обработка**: Поддерживает пакетный перевод целых томов манги

![Основные преимущества](./images/宣传图002.png)

## 🔍 Технические Принципы

### Движок Перевода на базе ИИ

Этот инструмент использует передовые нейронные системы перевода, которые не только понимают значения слов, но и улавливают контекстуальные нюансы, обеспечивая естественные и плавные результаты перевода. Система сначала "читает" всю мангу, улавливая общий стиль и характеристики персонажей, а затем создает связные и последовательные переводы.

![Архитектура движка перевода](./images/宣传图003.png)

### Технология OCR-Распознавания Текста

Для решения уникальных задач компоновки в манге мы разработали специализированный детектор текста комиксов, который может точно идентифицировать:

- Вертикальный и горизонтальный текст
- Шрифты в стиле рукописного текста
- Специальные эффектные шрифты и звукоподражания
- Мелкий фоновый текст и аннотации
- Декорированные диалоговые пузыри

Точность распознавания достигает лидирующего в отрасли уровня в 99%, точно извлекая текст даже на сложных фонах.

### Механизм Сохранения Макета

После перевода система интеллектуально настраивает размер шрифта, межстрочный интервал и макет, чтобы переведенный текст идеально интегрировался в оригинальные пузыри и макет. Ключевые технологии включают:

1. **Интеллектуальный Алгоритм Верстки**: Автоматически регулирует размер шрифта и межстрочный интервал в зависимости от длины текста на целевом языке
2. **Технология Восстановления Фона**: Интеллектуально восстанавливает фон после удаления оригинального текста
3. **Стилевое Соответствие**: Поддерживает согласованный стиль шрифта и выразительность с оригинальной мангой

![Эффект сохранения макета](./images/漫画翻译对比1.webp)

## ✨ Функции

### Пакетный Перевод

Поддерживает пакетную обработку целых томов манги или нескольких страниц, позволяя загружать до 300 МБ PDF-файлов или коллекций изображений. Система автоматически обрабатывает каждую страницу и генерирует полную переведенную версию.

![Демонстрация пакетного перевода](./images/宣传图004.png)

### Перевод в Реальном Времени

С помощью расширений для браузера осуществляйте перевод веб-манги в реальном времени. При просмотре поддерживаемых сайтов с мангой расширение автоматически обнаруживает и переводит контент манги на странице без необходимости загрузки оригинальных изображений.

Поддерживаемые сайты включают:
- MangaDex
- MangaFire
- ManhuaRen
- WebToonScan
- И более 100 других сайтов с мангой

![Демонстрация перевода в реальном времени](./images/Auto-translator.mp4)

### Поддержка Множества Языков

Полная поддержка перевода между следующими языками:

- Европейские языки, такие как английский, французский, немецкий, испанский и др.
- Азиатские языки, такие как китайский (упрощенный/традиционный), японский, корейский и др.
- Системы письма RTL, такие как арабский и иврит
- Славянские языки, такие как русский и польский

Система автоматически настраивает макет текста и направление в зависимости от характеристик различных языков.

### Функция Перевода Скриншотов

Для физических книг манги или сайтов, которые не поддерживают автоматический перевод, мы предлагаем мощную функцию перевода скриншотов:

1. Нажмите кнопку скриншота в расширении
2. Выберите область манги, которую вы хотите перевести
3. Система автоматически распознает и переводит текст
4. Результаты перевода отображаются непосредственно на оригинальном изображении

![Функция перевода скриншотов](./images/截图翻译.png)

### Настройка Терминологии

Для конкретных произведений манги вы можете создавать специализированные терминологические глоссарии, чтобы обеспечить согласованность в переводе имен персонажей, названий специальных способностей и других имен собственных. Это особенно важно для длинных серий или франшиз манги.

## 🚀 Руководство по Использованию

### Быстрый Старт - Три Шага для Перевода Манги

#### Шаг 1: Загрузите Мангу
1. Посетите платформу перевода манги [https://translatemanga.online](https://translatemanga.online)
2. Нажмите кнопку "Загрузить"
3. Выберите файлы манги (поддерживаемые форматы включают JPG, PNG, PDF и др.)

#### Шаг 2: Выберите Язык и Настройки
1. Выберите исходный язык манги
2. Выберите целевой язык перевода
3. Настройте параметры перевода (опционально):
   - Стиль шрифта
   - Режим распознавания текста
   - Настройки терминологического глоссария

#### Шаг 3: Получите Результаты Перевода
1. Нажмите кнопку "Начать Перевод"
2. Дождитесь завершения процесса перевода (примерно 1-2 минуты)
3. Просмотрите и скачайте переведенную мангу

![Результаты перевода](./images/manga-translator%20演示.mp4)

### Продвинутые Советы по Использованию

#### Использование Расширения для Браузера

1. Посетите официальный сайт, чтобы скачать и установить расширение для браузера: [https://translatemanga.online](https://translatemanga.online)
2. Поддерживаемые браузеры включают Chrome, Firefox и Edge:
   ![Поддерживаемые браузеры](./images/chrome.svg) ![Firefox](./images/firefox.svg) ![Edge](./images/edge.svg)
3. Выберите язык перевода по умолчанию в настройках расширения
4. При просмотре поддерживаемых сайтов с мангой нажмите на значок расширения для активации перевода
5. Используйте функцию перевода скриншотов для перевода любой панели манги

![Расширение для браузера](./images/截图翻译演示.mp4)

#### Обработка Больших Объемов Манги

1. Сохраните всю мангу в формате PDF или упакуйте ее в файл ZIP/CBZ
2. Загрузите на страницу пакетной обработки
3. Установите глобальные параметры перевода
4. Начните пакетный перевод; время обработки зависит от количества страниц
5. Скачайте полную переведенную версию или читайте онлайн

#### Отслеживание Прогресса Чтения

Чтобы обеспечить более полный опыт чтения манги, расширение translateManga также предлагает кроссплатформенное отслеживание прогресса чтения:

1. Включите функцию синхронизации прогресса чтения
2. Система записывает главы манги, которые вы читаете на разных сайтах
3. Продолжайте с того места, где вы остановились, войдя в систему с любого устройства
4. Поддержка пользовательской категоризации и избранного

![Отслеживание прогресса чтения](./images/manga-tracker%20演示.mp4)

#### Оптимизация Качества Перевода

1. **Создавайте Терминологические Глоссарии**: Добавляйте пары переводов для имен собственных в конкретной манге
2. **Настраивайте Чувствительность Распознавания**: Точно настраивайте параметры обнаружения текста для манги с нестандартными шрифтами
3. **Ручное Редактирование**: Система поддерживает ручную коррекцию и улучшение после перевода

## 🌎 Региональная Адаптация

### Специальные Функции для Западного Рынка

Для привычек чтения западных читателей манги translateManga предлагает следующие специальные функции:

1. **Режим Чтения Слева Направо**: Автоматически регулирует направление чтения японской и корейской манги для адаптации к западным привычкам чтения
2. **Оптимизация Западных Шрифтов**: Предоставляет различные шрифты в стиле западных комиксов для сохранения художественной согласованности после перевода
3. **Локализация Сленга и Культурных Отсылок**: Интеллектуально преобразует выражения, специфичные для культуры, чтобы сделать переводы более релевантными для целевой аудитории

![Функции адаптации для западного рынка](./images/宣传图006.png)

### Мультиплатформенная Поддержка

Чтобы удовлетворить привычки пользователей в разных регионах, translateManga предлагает различные варианты использования:

1. **Веб-Приложение**: Используйте напрямую через браузер без установки
2. **Расширения для Браузера**: Поддержка основных браузеров, включая Chrome, Firefox и Edge
3. **Мобильные Приложения**: Специализированные приложения для платформ iOS и Android, поддерживающие офлайн-перевод
4. **Настольное ПО**: Профессиональные версии для систем Windows и macOS, обеспечивающие более мощные возможности пакетной обработки

### Поддержка Локализации

Для особых потребностей различных регионов translateManga предоставляет следующую поддержку локализации:

1. **Языки Интерфейса**: Локализация интерфейса на 14 основных языках
2. **Обслуживание Клиентов**: Многоязычная поддержка клиентов и локализованная документация по помощи
3. **Соответствие Нормам**: Соблюдение правил защиты данных, таких как GDPR и CCPA в различных регионах

## 📊 Примеры Использования

### Пример Перевода Японской Манги

**Эффект Перевода "SPY×FAMILY"**

Характеристики перевода:
- Сохраняет оригинальный юмор
- Точно передает голос и тон персонажей
- Точно переводит специализированную терминологию
- Локализует звукоподражания

### Пример Перевода Корейской Манхвы (Веб-Туна)

**Эффект Перевода "Tower of God"**

Характеристики перевода:
- Идеально сохраняет вертикальное полосовое расположение
- Сохраняет визуальные эффекты специальных шрифтов
- Поддерживает согласованность терминологии
- Оптимизирует макет длинных диалоговых пузырей

### Пример Перевода Западных Комиксов

**Эффект Перевода "Avengers"**

Характеристики перевода:
- Сохраняет макет западных диалоговых окон
- Воссоздает художественное выражение звуковых эффектов
- Соответствующим образом локализует английский сленг
- Соответствует стилям специальных шрифтов

## ❓ Часто Задаваемые Вопросы

### Связанные с Точностью Перевода

**В: Как обеспечивается качество перевода?**
О: Мы используем самые передовые в отрасли большие модели ИИ (GPT-4o, Claude и др.) для перевода, в сочетании с обучением в конкретной области манги для значительного повышения точности в сценариях манги. Перед переводом система сначала "читает" всю мангу, чтобы понять контекст, обеспечивая связные и последовательные результаты перевода.

**В: Может ли система обрабатывать специфические культурные мемы и игру слов?**
О: Система может идентифицировать большинство общих культурных отсылок и игру слов, пытаясь найти эквивалентные выражения на целевом языке. Для высоко специфических культурных отсылок система сохраняет оригинальный смысл и при необходимости добавляет краткие пояснения.

### Технические Вопросы

**В: Какие форматы файлов поддерживаются?**
О: Поддерживаются распространенные форматы изображений (JPG, PNG, WEBP), форматы, специфичные для манги (CBR, CBZ), а также форматы электронных книг PDF и EPUB, с лимитом размера одного файла в 300 МБ.

**В: Как система справляется с очень длинными страницами манги?**
О: Система поддерживает чрезвычайно длинные полосовые страницы манги до 10 000 пикселей, автоматически обрабатывая их сегментами при сохранении общей согласованности макета.

**В: Как я могу сохранить переведенные файлы?**
О: Результаты перевода можно сохранить в оригинальном формате (например, PDF остается как PDF) или экспортировать как коллекции изображений или ссылки для онлайн-чтения, что облегчает обмен и чтение на разных устройствах.

## Связанные Ссылки и Контактная Информация

- [Официальный сайт](https://translatemanga.online)
- **Email**: support@translatemanga.online
- **Discord**: [Присоединяйтесь к нашему сообществу Discord](https://discord.gg/translatemanga)

Если у вас есть какие-либо вопросы или предложения, не стесняйтесь связаться с нами в любое время!

---

*Этот документ был последний раз обновлен в июне 2024 года* 