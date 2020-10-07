# Курс "Web-программирование" | ПГНИУ

<!-- toc -->

- [О курсе](#%D0%BE-%D0%BA%D1%83%D1%80%D1%81%D0%B5)
  * [Цель курса](#%D1%86%D0%B5%D0%BB%D1%8C-%D0%BA%D1%83%D1%80%D1%81%D0%B0)
  * [Тезисы](#%D1%82%D0%B5%D0%B7%D0%B8%D1%81%D1%8B)
- [План](#%D0%BF%D0%BB%D0%B0%D0%BD)
- [Материалы](#%D0%BC%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B)
- [Практика](#%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%D0%B0)
  * [Проект](#%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82)
  * [Лабораторные работы](#%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D1%8B%D0%B5-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B)
- [Экзамен](#%D1%8D%D0%BA%D0%B7%D0%B0%D0%BC%D0%B5%D0%BD)
- [Вклад в курс](#%D0%B2%D0%BA%D0%BB%D0%B0%D0%B4-%D0%B2-%D0%BA%D1%83%D1%80%D1%81)
- [Разработка курса](#%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0-%D0%BA%D1%83%D1%80%D1%81%D0%B0)

<!-- tocstop -->

## О курсе

### Цель курса

Web-программирование занимает существенную часть в мире современной разработки. Многие студенты делают Web-приложения в рамках НИР или занимаются этим на первой работе.

Web-приложения, создаваемые в рамках НИР, чаще всего нетиповые приложения. На работе студенты работают с современными технологиями веб-разработки: SPA приложениями, JS фреймворками, используют самые разные языки на серверной части.

**Цели курса:** изучить Web-программирование в теоретической части от базового фундамента до современных подходов, а также получить практические навыки как в традиционной, так и современной Web-разработке.

### Тезисы
<details>
<summary>1. Практический курс с вниманием к теории.</summary>

Главное в курсе - получение практических навыков разработки. Но курс университетский и большое внимание уделяется изучению концепций, подходов и систематизации знаний.
</details>

<details>
<summary>2. Больше о клиентской части, чем о серверной.</summary>

Серверная часть веб-приложения ближе к "обычному" приложению. Студенты изучают работу с БД на курсе "БД и СУБД", сетевое взаимодействие, разработку веб-сервисов и распределённых приложений на курсе "Технологии разработки распределённых приложений". Важно научиться разрабатывать приложение для веб-браузера и понимать, как применять навыки, полученные на других курсах, в разработке серверной части веб-приложения. 
</details>

<details><summary>3. Вёрстка - только основы.</summary>

Вёрстка - большая тема. Её сложно изучить за небольшое число занятий и требуется много практики. В то же время в университете студентам важнее быстрая разработка работающего прототипа, а не реализация уникального дизайна.
</details>

<details>
<summary>4. Изучение как традиционных, так и современных подходов, и их сравнение.</summary>

Изучение традиционных подходов важно для понимания основ, а современных - для решения актуальных практических задач. Решение одних и тех же задач разными подходами поможет лучше понять разницу между ними. 
</details>


<details>
<summary>5. Изучать конкретные языки или фреймворки не так важно.</summary>

Курс не посвящён разработке сайтов на фреймворке A для языка B. У студентов разные предпочтения, они работают на разных технологических стеках как самостоятельно, так и на работе. Важно понимать основные концепции, и систематизировать знания. Тем не менее, примеры показываются на определённых (но простых) технологиях.   
</details>

 
<details>
<summary>6. Простые задачи на минимальную оценку, сложные на максимальную.</summary>

Не всем интересна и нужна веб-разработка. Курс должен быть как можно полезнее для заинтересованных, но не становиться ночным кошмаром для тех, для кого это "просто ещё один курс, который надо сдать". Для получения проходного балла достаточно сдать простые лабораторные работы.
</details>

## План

**[> Подробный план](./Plan.md)**

| Лекции                                                           | Практики                                                 |
|------------------------------------------------------------------|----------------------------------------------------------|
| 1. Введение: о курсе, история web, основные понятия              | 1. HTML  (лекция + практика)                             |
| 2. JavaScript: основы языка                                      | 2. CSS. Блочная модель (лекция + практика)               |
| 3. JavaScript: DOM, BOM, jQuery                                  | 3. Flex. Вёрстка (лекция + практика вёрстки)             |
| 4. Введение в серверную часть: основные компоненты, формы        | 4. Сдача лабораторных: 1, 2                              |
| 5. Аутентификация, сессия                                        | 5. UI фреймворки (лекция + практика с примером)          |
| 6. AJAX; API                                                     | 6. Практика по традиционной серверной части              |
| 7. JS-Фреймворки (c примерами на Vue.js)                         | 7. CMS и конструкторы сайтов (лекция + практика по AJAX) |
| 8. Современный Front-End: Node.js, инструменты разработки        | 8. Сдача лабораторных: 3, 4                              |
| 9. SPA                                                           | 9. Практика: Современный JS                              |
| 10. Доклады: React, Angular,  Ember (?)                          | 10. Практика: SPA                                        |
| 11. Аутентификация 2; Инфраструктура современного веб-приложения | 11. Практика: аутентификация в SPA                       |
| 12. Доклады: PHP, Go, Java, dotnet, Node.js                      | 12. Сдача лабораторных: 5, 6                             |
| 13. Развёртывание: On-Premise, IaaS, PaaS, SaaS, FaaS            | 13. Практика: пример развёртывания; Досдача лабораторных |
| 14. Что ещё есть в веб-разработке                                | 14. Экзамен                                              | 

## Материалы

Материалы находиться в директории **[> materials](materials)**.

## Практика

Лабораторные работы реализуют части проекта - Мини-почту.

### Проект

Мини-почта - реализация простой почты.

Зарегистрированный пользователь может отправить "письмо" другому зарегистрированному пользователю по его имени. Каждый пользователь видит список всех своих сообщений: исходящих и входящих. Письмо может находиться в состоянии "прочитано" и "не прочитано". Непрочитанные письма можно удалять. 

### Лабораторные работы

| Лабораторная работа                                      | КТ | Условие                                                                | ПМИ-1                                           | ПМИ-2                                           | ПМИ-3,4                                         | ФИТ-1                                           | ФИТ-2                                           |
|----------------------------------------------------------|----|------------------------------------------------------------------------|-------------------------------------------------|-------------------------------------------------|-------------------------------------------------|-------------------------------------------------|-------------------------------------------------|
| 0. **Входной контроль:** работа с БД                     | 1  | [html](labs/0-Incoming-control.md), [PDF](labs/0-Incoming-control.pdf) | -                                               | -                                               |                                                        |                                                |                                                 |
| 1. **HTML, CSS:** вёрстка страницы проекта по эскизу     | 2  | [html](labs/1-HTML-CSS.md), [PDF](labs/1-HTML-CSS.pdf)                 | [link](https://classroom.github.com/a/mPQWFIkk) | [link](https://classroom.github.com/a/9FQJl6vk) | [link](https://classroom.github.com/a/B2y0h1gC) | [link](https://classroom.github.com/a/QyIfQVn3) | [link](https://classroom.github.com/a/wMwud7u1) |
| 2. **JS:** разработка маленькой игры на JavaScript       | 2  | - | - | - | - | - | - |
| 3. **Традиционное Web-приложение:** часть проекта без JS | 3  | - | - | - | - | - | - |
| 4. **AJAX:** добавление AJAX в проект                    | 4  | - | - | - | - | - | - |
| 5. **SPA:** реализация клиентской части проекта как SPA  | 5  | - | - | - | - | - | - |
| 6. **Проект:** окончательная реализация SPA и API        | 6  | - | - | - | - | - | - |

## Экзамен

Информация об экзамене и вопросах к экзамену  на странице **[> Экзамен](./Exam.md)**

## Вклад в курс

Это открытый курс, выложенный на [GitHub репозитории](https://github.com/movs-psu/web-development-course). Вы можете помочь сделать его лучше и внести в него вклад!

- Есть предложения по улучшению плана?
- Знаете, как сделать задания полезнее и интереснее?
- Нет идей, как сделать лучше, но знаете, что не нравится в текущем курсе? 
- Нашли фактическую ошибку в материалах?
- Нашли опечатку?
- Или просто хотите высказать своё мнение?

Помогите сделать этот курс лучше для вас или будущих студентов!

Подробности в разделе **[> CONTRIBUTING](./CONTRIBUTING.md)**.

## Разработка курса

Техническая информация о разработке курса (сборка презентаций, преобразование в HTML и PDF файлы) в разделе **[> DEVELOPMENT](./DEVELOPMENT.md)**
