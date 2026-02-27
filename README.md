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

# Server Metrics 2026-02-27 17:21:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 776.7 (0h 12m)
telemt_connections_total 112
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 111
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 3223371 (3.07 MB)
telemt_user_octets_to_client{user="hello"} 11308638 (10.78 MB)
telemt_user_msgs_from_client{user="hello"} 1508
telemt_user_msgs_to_client{user="hello"} 3840
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 1268.0 (0h 21m)
telemt_connections_total 27
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 9325 (9.11 KB)
telemt_user_octets_to_client{user="hello"} 4294 (4.19 KB)
telemt_user_msgs_from_client{user="hello"} 33
telemt_user_msgs_to_client{user="hello"} 29
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 910.0 (0h 15m)
telemt_connections_total 49
telemt_user_connections_total{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 188832 (184.41 KB)
telemt_user_octets_to_client{user="hello"} 1258382 (1.20 MB)
telemt_user_msgs_from_client{user="hello"} 600
telemt_user_msgs_to_client{user="hello"} 716
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 1022.6 (0h 17m)
telemt_connections_total 38
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 8
telemt_user_connections_total{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 7444 (7.27 KB)
telemt_user_octets_to_client{user="hello"} 5045 (4.93 KB)
telemt_user_msgs_from_client{user="hello"} 27
telemt_user_msgs_to_client{user="hello"} 29
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 1079.2 (0h 17m)
telemt_connections_total 13
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 71397 (69.72 KB)
telemt_user_octets_to_client{user="hello"} 1953125 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 253
telemt_user_msgs_to_client{user="hello"} 809
```