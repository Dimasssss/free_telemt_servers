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

# Server Metrics 2026-02-27 17:16:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 468.4 (0h 7m)
telemt_connections_total 71
telemt_user_connections_total{user="hello"} 71
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 3088993 (2.95 MB)
telemt_user_octets_to_client{user="hello"} 3919527 (3.74 MB)
telemt_user_msgs_from_client{user="hello"} 1085
telemt_user_msgs_to_client{user="hello"} 1856
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 959.5 (0h 15m)
telemt_connections_total 26
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 9049 (8.84 KB)
telemt_user_octets_to_client{user="hello"} 4185 (4.09 KB)
telemt_user_msgs_from_client{user="hello"} 32
telemt_user_msgs_to_client{user="hello"} 28
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 601.6 (0h 10m)
telemt_connections_total 48
telemt_user_connections_total{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 188573 (184.15 KB)
telemt_user_octets_to_client{user="hello"} 1258206 (1.20 MB)
telemt_user_msgs_from_client{user="hello"} 599
telemt_user_msgs_to_client{user="hello"} 715
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 714.2 (0h 11m)
telemt_connections_total 37
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 8
telemt_user_connections_total{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 7300 (7.13 KB)
telemt_user_octets_to_client{user="hello"} 4947 (4.83 KB)
telemt_user_msgs_from_client{user="hello"} 26
telemt_user_msgs_to_client{user="hello"} 28
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 770.7 (0h 12m)
telemt_connections_total 9
telemt_user_connections_total{user="hello"} 9
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 52805 (51.57 KB)
telemt_user_octets_to_client{user="hello"} 1818892 (1.73 MB)
telemt_user_msgs_from_client{user="hello"} 177
telemt_user_msgs_to_client{user="hello"} 689
```