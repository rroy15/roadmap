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

### Regular Expressions


## Backend


### Python

