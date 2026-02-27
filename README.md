# Информация

Покупаю сервера у разных хостингов для тестов и запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта

#### Ссылки с SNI
| SNI               | link                                                                                                                |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| microsoft.com     | tg://proxy?server=195.226.94.42&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d6963726f736f66742e636f6d        |
| drive.google.com  | tg://proxy?server=195.226.94.42&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d  |

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта

#### Ссылки с SNI
| SNI               | link                                                                                                                |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| microsoft.com     | tg://proxy?server=45.147.28.10&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d6963726f736f66742e636f6d         |
| drive.google.com  | tg://proxy?server=45.147.28.10&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d   |

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта

#### Ссылки с SNI
| SNI               | link                                                                                                                |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| microsoft.com     | tg://proxy?server=108.165.174.245&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d6963726f736f66742e636f6d      |
| drive.google.com  | tg://proxy?server=108.165.174.245&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d|

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта

#### Ссылки с SNI
| SNI               | link                                                                                                                |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| microsoft.com     | tg://proxy?server=185.225.203.236&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d6963726f736f66742e636f6d      |
| drive.google.com  | tg://proxy?server=185.225.203.236&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d|

-----

## 4vps.su
- Локация: Финляндия, Хельсинки
- Тариф: FI-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 28 марта

#### Ссылки с SNI
| SNI               | link                                                                                                                |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| microsoft.com     | tg://proxy?server=213.176.17.198&port=443&secret=eebe3007e927acd147dde12bee8b1a7c936d6963726f736f66742e636f6d       |
| drive.google.com  | tg://proxy?server=213.176.17.198&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d |

-----

# Server Metrics 2026-02-27 18:48:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 6010.7 (1h 40m)
telemt_connections_total 440
telemt_connections_bad_total 5
telemt_user_connections_total{user="hello"} 427
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 5530772 (5.27 MB)
telemt_user_octets_to_client{user="hello"} 82974666 (79.13 MB)
telemt_user_msgs_from_client{user="hello"} 7695
telemt_user_msgs_to_client{user="hello"} 26849
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 6502.1 (1h 48m)
telemt_connections_total 145
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 115418 (112.71 KB)
telemt_user_octets_to_client{user="hello"} 161055 (157.28 KB)
telemt_user_msgs_from_client{user="hello"} 412
telemt_user_msgs_to_client{user="hello"} 337
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 6143.9 (1h 42m)
telemt_connections_total 289
telemt_connections_bad_total 7
telemt_user_connections_total{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 1198936 (1.14 MB)
telemt_user_octets_to_client{user="hello"} 8306066 (7.92 MB)
telemt_user_msgs_from_client{user="hello"} 1518
telemt_user_msgs_to_client{user="hello"} 3885
```

## landvps.ru

Не удалось получить метрики для этого сервера.

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 6313.0 (1h 45m)
telemt_connections_total 51
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 72401 (70.70 KB)
telemt_user_octets_to_client{user="hello"} 1953596 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 256
telemt_user_msgs_to_client{user="hello"} 812
```