# Лабораторная работа № 6: Web-приложение

> *Максимум 10 баллов. Часть Контрольной точки 3: PHP. Разработка динамических web-страниц.*

## Задача

**Требуется реализовать веб-приложение "ToDo List".**

Приложение позволяет пользователями управлять списком задач (с заголовком и описанием):
- Создавать новые задачи;
- Отменять задачи как выполненные/не выполненные;
- Получать список всех задач, а также фильтровать их по заголовку и состоянию выполнения;
- Изменять заголовок и описание задачи;
- Удалять задачи.

#### Требования

- Можно использовать любой JavaScript фреймворк;
- Для реализации API можно использовать любой язык программирования и фреймворк, кроме готовой CMS;
- API можно реализовывать в любом стиле, но лучше придерживаться (REST)[https://ru.wikipedia.org/wiki/REST], либо использовать готовый стандарт/фреймворк ([GraphQL](https://graphql.org), [gRPC](https://grpc.io/), [JSON:API](https://jsonapi.org/), [JSON-RPC](https://www.jsonrpc.org/) и т.д.);
- Аутентификацию можно делать любым способом, но предпочтительнее использовать простую аутентификацию на **сессии в Cookie** (проще).

#### Критерии:

- (2.5 б) Реализовано веб-приложение "ToDo List" с **SPA** клиентом и сервером **API**;
- (2.5 б) Реализована регистрация пользователей, аутентификация и авторизация;
- (2.5 б) Приложение имеет удобный интерфейс, индикаторы загрузки, минимальную валидацию данных, обработку и отображение ошибок;
- (2.5 б) Приложение корректно обрабатывает ошибки:
    - API возвращает корректный [HTTP статус](https://ru.wikipedia.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_%D0%BA%D0%BE%D0%B4%D0%BE%D0%B2_%D1%81%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%B8%D1%8F_HTTP) для как минимум 200, 401, 403, 404 кодов;
    - Клиент корректно обрабатывает такие ответы.

#### Примечание

Можно сдать вместе с [Лабораторной работой 5](/labs/5-SPA/5-SPA.md).
