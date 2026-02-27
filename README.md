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

# Server Metrics 2026-02-27 17:31:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 1392.5 (0h 23m)
telemt_connections_total 228
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 226
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 3595925 (3.43 MB)
telemt_user_octets_to_client{user="hello"} 12990157 (12.39 MB)
telemt_user_msgs_from_client{user="hello"} 2689
telemt_user_msgs_to_client{user="hello"} 6233
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 1883.8 (0h 31m)
telemt_connections_total 28
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 9885 (9.65 KB)
telemt_user_octets_to_client{user="hello"} 4674 (4.56 KB)
telemt_user_msgs_from_client{user="hello"} 35
telemt_user_msgs_to_client{user="hello"} 30
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 1526.2 (0h 25m)
telemt_connections_total 53
telemt_user_connections_total{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 191424 (186.94 KB)
telemt_user_octets_to_client{user="hello"} 1261030 (1.20 MB)
telemt_user_msgs_from_client{user="hello"} 608
telemt_user_msgs_to_client{user="hello"} 726
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 1638.6 (0h 27m)
telemt_connections_total 41
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 9
telemt_user_connections_total{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 7618 (7.44 KB)
telemt_user_octets_to_client{user="hello"} 5217 (5.09 KB)
telemt_user_msgs_from_client{user="hello"} 28
telemt_user_msgs_to_client{user="hello"} 30
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 1695.2 (0h 28m)
telemt_connections_total 13
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 71397 (69.72 KB)
telemt_user_octets_to_client{user="hello"} 1953125 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 253
telemt_user_msgs_to_client{user="hello"} 809
```