# Информация

Покупаю сервера у разных хостингов для тестов и запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

SNI взяты с https://github.com/hxehex/russia-mobile-internet-whitelist  
<sub>Если нужно добавить больше SNI в таблицы, то пишите в [Issues](https://github.com/Dimasssss/free_telemt_servers/issues).</sub>

-----

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание: 2 vCore, 2 Gb ram, 1 gbit/s, Traffic Unlime
- Цена в месяц: 4.99$
- Оплачен до: 26 марта

#### Ссылки с SNI
| SNI               | link                                                                                                                |
| ----------------- | ------------------------------------------------------------------------------------------------------------------- |
| yandex.ru         | tg://proxy?server=195.226.94.42&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9379616e6465782e7275                |
| hd.kinopoisk.ru   | tg://proxy?server=195.226.94.42&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9368642e6b696e6f706f69736b2e7275    |
| my.mail.ru        | tg://proxy?server=195.226.94.42&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d792e6d61696c2e7275              |
| max.ru            | tg://proxy?server=195.226.94.42&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d61782e7275                      |
| avito.ru          | tg://proxy?server=195.226.94.42&port=443&secret=eebe3007e927acd147dde12bee8b1a7c93617669746f2e7275                  |
| gosuslugi.ru      | tg://proxy?server=195.226.94.42&port=443&secret=eebe3007e927acd147dde12bee8b1a7c93676f7375736c7567692e7275          |

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание: 2 vCore, 4 Gb ram, 1 gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта

#### Ссылки с SNI
| SNI               | link                                                                                                                |
| ----------------- | ------------------------------------------------------------------------------------------------------------------- |
| yandex.ru         | tg://proxy?server=45.147.28.10&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9379616e6465782e7275                 |
| hd.kinopoisk.ru   | tg://proxy?server=45.147.28.10&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9368642e6b696e6f706f69736b2e7275     |
| my.mail.ru        | tg://proxy?server=45.147.28.10&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d792e6d61696c2e7275               |
| max.ru            | tg://proxy?server=45.147.28.10&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d61782e7275                       |
| avito.ru          | tg://proxy?server=45.147.28.10&port=443&secret=eebe3007e927acd147dde12bee8b1a7c93617669746f2e7275                   |
| gosuslugi.ru      | tg://proxy?server=45.147.28.10&port=443&secret=eebe3007e927acd147dde12bee8b1a7c93676f7375736c7567692e7275           |

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание: 2 vCore, 4 Gb ram, 1 gbit/s
- Цена в месяц: 639.00 RUB
- Оплачен до: 25 марта

#### Ссылки с SNI
| SNI               | link                                                                                                                |
| ----------------- | ------------------------------------------------------------------------------------------------------------------- |
| yandex.ru         | tg://proxy?server=108.165.174.245&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9379616e6465782e7275              |
| hd.kinopoisk.ru   | tg://proxy?server=108.165.174.245&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9368642e6b696e6f706f69736b2e7275  |
| my.mail.ru        | tg://proxy?server=108.165.174.245&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d792e6d61696c2e7275            |
| max.ru            | tg://proxy?server=108.165.174.245&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d61782e7275                    |
| avito.ru          | tg://proxy?server=108.165.174.245&port=443&secret=eebe3007e927acd147dde12bee8b1a7c93617669746f2e7275                |
| gosuslugi.ru      | tg://proxy?server=108.165.174.245&port=443&secret=eebe3007e927acd147dde12bee8b1a7c93676f7375736c7567692e7275        |

-----

# Server Metrics 2026-02-26 10:20:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.0

telemt_uptime_seconds 7122.8 (1h 58m)
telemt_connections_total 88
telemt_connections_bad_total 15
telemt_user_connections_total{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 104515 (102.07 KB)
telemt_user_octets_to_client{user="hello"} 220973 (215.79 KB)
telemt_user_msgs_from_client{user="hello"} 209
telemt_user_msgs_to_client{user="hello"} 199
```

## psb.hosting

```
telemt 3.1.0

telemt_uptime_seconds 4476.4 (1h 14m)
telemt_connections_total 38
telemt_connections_bad_total 9
telemt_user_connections_total{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 12351 (12.06 KB)
telemt_user_octets_to_client{user="hello"} 6015 (5.87 KB)
telemt_user_msgs_from_client{user="hello"} 42
telemt_user_msgs_to_client{user="hello"} 43
```

## koara.io

```
telemt 3.1.0

telemt_uptime_seconds 1684.1 (0h 28m)
telemt_connections_total 62
telemt_connections_bad_total 4
telemt_user_connections_total{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 111604 (108.99 KB)
telemt_user_octets_to_client{user="hello"} 31501732 (30.04 MB)
telemt_user_msgs_from_client{user="hello"} 211
telemt_user_msgs_to_client{user="hello"} 4193
```