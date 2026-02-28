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

# Server Metrics 2026-02-28 07:23:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 28590.9 (7h 56m)
telemt_connections_total 3283
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 4
telemt_user_connections_total{user="hello"} 3137
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 3983492 (3.80 MB)
telemt_user_octets_to_client{user="hello"} 68456620 (65.29 MB)
telemt_user_msgs_from_client{user="hello"} 12905
telemt_user_msgs_to_client{user="hello"} 35034
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 28417.5 (7h 53m)
telemt_connections_total 133
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 4
telemt_user_connections_total{user="hello"} 60
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 57336 (55.99 KB)
telemt_user_octets_to_client{user="hello"} 134914 (131.75 KB)
telemt_user_msgs_from_client{user="hello"} 202
telemt_user_msgs_to_client{user="hello"} 154
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 28585.4 (7h 56m)
telemt_connections_total 1240
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 14
telemt_user_connections_total{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 1482433 (1.41 MB)
telemt_user_octets_to_client{user="hello"} 71382274 (68.08 MB)
telemt_user_msgs_from_client{user="hello"} 4420
telemt_user_msgs_to_client{user="hello"} 21020
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 29728.3 (8h 15m)
telemt_connections_total 2488
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 3896 (3.80 KB)
telemt_user_octets_to_client{user="hello"} 3193 (3.12 KB)
telemt_user_msgs_from_client{user="hello"} 17
telemt_user_msgs_to_client{user="hello"} 14
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 28579.0 (7h 56m)
telemt_connections_total 182
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 5
telemt_user_connections_total{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 2779 (2.71 KB)
telemt_user_octets_to_client{user="hello"} 1719 (1.68 KB)
telemt_user_msgs_from_client{user="hello"} 8
telemt_user_msgs_to_client{user="hello"} 5
```