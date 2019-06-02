# roadmap
Python backend developer roadmap.

## Table of contents

[General](#general)

- Git and Gitflow
- Terminal
- SOLID, KISS, YAGNI
- Design Patterns
- [SSH](#ssh)
- [TCP/IP, HTTP, HTTPS and APIs](#network-communication-and-security-protocols)
- [Regular Expressions](#regular-expressions)
- Semantic versioning
- Character Encodings
- Licenses
- Data structures and algorithms

[Backend](#backend)

- [Python](#python) (standards and best practices)
- Pip
- Relational DB and SQL (Postgresql)
- Django
  - Models and databases
    - Models
    - Making queries
    - Aggregation
    - Search
    - Managers
    - Performing raw SQL queries
    - Database transactions
    - Multiple databases
    - Tablespaces
    - Database access optimization
    - Database instrumentation
    - Examples
- NoSQL DB (MongoDB)
- Caching
- REST API
- Authentication/Authorization methodologies
- Message Brokers
- Search Engine
- Docker
- Web servers
- Web sockets

## General

### SSH

**ssh** - защищённый протокол удалённого доступа к компьютерам.

Ссылки:

- [Что такое SSH](https://guides.hexlet.io/ssh/)
- [Connecting to Github with SSH](https://help.github.com/en/articles/connecting-to-github-with-ssh)


### Network communication and security protocols

#### TCP/IP

Сетевая модель передачи данных. Состоит из четырёх уровней. 

- Канальный уровень (link layer / network access). Определяются правила использования физического уровня узлами сети. Передаёт данные узлам, находящимся в одном сегменте локальной сети. Примеры: **Ethernet, Point-to-Point Protocol, HDLC и ADCCP**. 

- Сетевой уровень (internet layer). Предназначает для определения пути передачи данных. Например, протокол **IP**.

- Транспортный уровень (transport layer). Решают проблему негарантированной доставки сообщений, а также обеспечивают правильную последовательность прихода данных. Примеры: **TCP, UDP, SCTP, DCCP**

- Прикладной уровень (application layer). На прикладном уровне работают большинство сетевых приложений. Является пограничным между прикладной программой и другими уровнями, обеспечивая удобный интерфейс связи для сетевых программ пользователя.

> **HTTP** протокол для веб-браузера; **SMTP** для почтовых программ; **FTP** для ftp-клиента; и многие другие. 

> **80** и **8080** порты для **HTTP**; **FTP** на 20 и 21; **SSH** на 22; **DNS** на порт UDP 53;

#### HTTP

> Протокол передачи гипертекста - (HyperText Transfer Protocol) - это протокол прикладного уровня для передачи гипертекстовых документов, таких как HTML. Создан для связи межеду веб-серверами и веб-браузерами, хотя в принципе может использоваться и для других целей.

[Больше информации тут.](https://developer.mozilla.org/ru/docs/Web/HTTP)

"HTTP as an application layer protocol, on top of TCP (transport layer) and IP (network layer) and below the presentation layer.

<img alt="HTTP as an application layer protocol, on top of TCP (transport layer) and IP (network layer) and below the presentation layer." src="https://mdn.mozillademos.org/files/13673/HTTP%20&amp;%20layers.png" style="float: left; height: 299px; padding-bottom: 15px; padding-right: 20px; width: 418px;">


HTML-сообщения бывают двух видов:

Запросы от клиента (обычно, GET или POST):
- HTTP-метод, обычно глагол подобно GET, POST или существительное, как OPTIONS или HEAD, определяющее операцию, которую клиент хочет выполнить. Обычно, клиент хочет получить ресурс (используя GET) или передать значения HTML-формы (используя POST), хотя другие операция могут быть необходимы в других случаях.
- Путь к ресурсу: URL ресурсы лишены элементов, которые очевидны из контекста, например без protocol (http://), domain (здесь developer.mozilla.org), или TCP port (здесь 80).
- Версию HTTP-протокола.
- Заголовки  (опционально), предоставляюшие дополнительную информацию для сервера.
- Или тело, для некоторых методов, таких как POST, которое содержит отправленный ресурс.

Пример:

<img alt="A basic HTTP request" src="https://mdn.mozillademos.org/files/13687/HTTP_Request.png" style="height: 336px; width: 693px;">

Ответы от сервера:
- Версию HTTP-протокола.
- HTTP код состояния, сообщающий об успешности запроса или причине неудачи.
- Сообщение состояния -- краткое описание кода состояния.
- HTTP заголовки, подобно заголовкам в запросах.
- Опционально: тело, содержащее пересылаемый ресурс.

Пример:

<img alt="" src="https://mdn.mozillademos.org/files/13691/HTTP_Response.png" style="height: 494px; width: 758px;">


HTTP коды состояния делятся на пять групп:

- Информационные сообщения (начинаются с числа 100)
- Сообщения о том, что операция прошла успешно (начинаются с числа 200)
- Перенаправления (начинаются с числа 300)
- Ошибки на стороне клиента (начинаются с числа 400)
- Ошибки сервера (начинаются с числа 500)

[Ссылка.](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)

Основные HTTP методы:

- GET - служит для получения какой-то информации с сервера.
- HEAD - тоже самое, что и GET, но сервер в ответ на такой запрос не возвращает response body.
- POST - служит для отравки данных на сервер.
- PUT - тоже самое, что и POST. Разница между ними заключается в том, что многократные вызовы PUT будут приносить один и тот же результат, без side effect.

### Regular Expressions

## Backend


### Python

