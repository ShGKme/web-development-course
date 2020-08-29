# Курс "Web-программирование" | ПГНИУ

<!-- TOC -->
- [О курсе](#О-курсе)
  - [Цель курса](#Цель-курса)
  - [Тезисы](#Тезисы)
  - [Комментарии к тезисам](#Комментарии-к-тезисам)
- [План](#План)
- [Практика](#Практика)
  - [Проект](#Проект)
  - [Лабораторные работы](#Лабораторные-работы)
- [Экзамен](#Экзамен)

<!-- TOC END -->

## О курсе

### Цель курса

Web-программирование занимает существенную часть в мире современной разработки. Многие студенты делают Web-приложения в рамках НИР или занимаются этим на первой работе.

Web-приложения, создаваемые в рамках НИР, чаще всего нетиповые приложения. На работе студенты работают с современными технологиями веб-разработки: SPA приложениями, JS фреймворками, используют самые разные языки на серверной части.

**Цели курса:** изучить Web-программирование в теоретической части от базового фундамента до современных подходов, а также получить практические навыки как в традиционной, так и современной Web-разработке.

### Тезисы

1. Теория впереди примеров
2. Акцент на клиентскую часть
3. В вёрстке нужны только основы
4. Важны как традиционные, так и современные технологии
5. Больше обзора, чем конкретных технологий
6. Маленькие лабораторные вместо большого проекта
7. Решение одних задач разными инструментами
8. Простые задачи на минимальную оценку

### Комментарии к тезисам

1. Сначала рассматриваем, что происходит, зачем, а потом примеры реализации. Начинаем с теории клиент-серверных приложений, немного про запросы, протоколы. В языке с основ, парадигмы, особенностей, синтаксиса. Больше внимания спецификациям.
2. Серверная часть веб-приложения -- это обычное приложение. Оно мало чем отличается от веб-сервиса, который мало чем отличается от сервиса (что студенты проходят на ТРРП). Оно может быть сделано на любом языке программирования. Студенты уже умеют программировать, уже знают какие-то языки программирования, у многих есть “свой любимый язык”, умеют работать с БД. Требуется лишь знать основные подходы, паттерны, инструменты.
3. С одной стороны, вёрстка -- сложная и большая тема. Особенно, если углубляться, изучать методологии, правила хорошего тона, семантику, доступность, знать как традиционные, так и актуальные походы. Вёрстку нельзя изучить за небольшое число занятий. С другой стороны, самостоятельная верстка занимает много времени, в то время как при разработке у студентов акцент на работающий прототип, а не уникальный дизайн.
4. Изучать только традиционный веб -- плохо, для решения в НИР и на работе им понадобится современный. Но изучать сразу современный без понимания основ также нельзя, это приводит к большему непониманию.
5. Важно, чтобы студенты представляли, какие есть инструменты в мире веб-разработки, когда и какие лучше применять и могли решать широкий спектр задач, углубляясь в нужные им технологии.
6. Командная разработка большого проекта -- это очень хорошо. Но времени и возможностей разработать командой проект нет. При этом требуется попробовать различные технологии и подходы, решить разные независимые задачи. Возможно, такой вариант можно сделать альтернативным.
7. Решение одних и тех же задач как традиционным, так и современным подходом, позволит лучше почувствовать разницу между ними.
8. Простые задачи на минимальную оценку

## План

**[> Подробный план](./Plan.md)**

| Лекции                                                           | Практики                                                 |
|------------------------------------------------------------------|----------------------------------------------------------|
| 1. Введение: о курсе, история web, основные понятия              | 1. HTML  (лекция + практика)                             |
| 2. JavaScript: основы языка                                      | 2. CSS. Блочная модель (лекция + практика)               |
| 3. JavaScript: DOM, BOM, jQuery                                  | 3. Flex. Вёрстка (лекция + практика вёрстки)             |
| 4. Введение в серверную часть: основные компоненты, формы        | 4. Сдача лабораторных: 1, 2                              |
| 5. Аутентификация, хранение данных на клиенте, сессия            | 5. UI фреймворки (лекция + практика с примером)          |
| 6. AJAX; API                                                     | 6. Практика по традиционной серверной части              |
| 7. JS-Фреймворки (c примерами на Vue.js)                         | 7. CMS и конструкторы сайтов (лекция + практика по AJAX) |
| 8. Современный Front-End: Node.js, инструменты разработки        | 8. Сдача лабораторных: 3, 4                              |
| 9. SPA                                                           | 9. Практика: Современный JS                              |
| 10. Доклады: React, Angular,  Ember (?)                          | 10. Практика: SPA                                        |
| 11. Аутентификация 2; Инфраструктура современного веб-приложения | 11. Практика: аутентификация в SPA                       |
| 12. Доклады: PHP, Go, Java, dotnet, Node.js                      | 12. Сдача лабораторных: 5, 6                             |
| 13. Развёртывание: On-Premise, IaaS, PaaS, SaaS, FaaS            | 13. Практика: пример развёртывания; Досдача лабораторных |
| 14. Что ещё есть в веб-разработке                                | 14. Экзамен                                              | 

## Практика

Лабораторные работы реализуют части проекта - Мини-почту.

### Проект

Мини-почта -- реализация простой почты.

Зарегистрированный пользователь может отправить "письмо" другому зарегистрированному пользователю по его имени. Каждый пользователь видит список всех своих сообщений: исходящих и входящих. Письмо может находиться в состоянии "прочитано" и "не прочитано". Непрочитанные письма можно удалять. 

### Лабораторные работы

> ⚠ По ссылкам описание старых лабораторных работ

1. **HTML, CSS:** вёрстка страницы проекта по эскизу ([ссылка](./labs/---))
2. **JS:** разработка маленькой игры на JavaScript ([ссылка](./labs/Лабораторная%20работа%202%20-%20JavaScript.md))
3. **Традиционное Web-приложение:** реализация части проекта традиционным подходом без JS ([ссылка](./labs/Лабораторная%20работа%203%20-%20ToDo.md))
4. **AJAX:** добавление AJAX в проект ([ссылка](./labs/Лабораторная%20работа%204%20-%20ToDo%20Ajax.md))
5. **SPA:** реализация клиентской части как SPA приложения ([ссылка](./labs/Лабораторная%20работа%205%20-%20ToDo%20SPA.md))
6. **Проект:** Окончательная реализация Web-приложения с SPA и API (([ссылка](./labs/Лабораторная%20работа%206%20-%20ToDo%20App.md)))

## Экзамен

**[> Экзамен](./Exam.md)**
