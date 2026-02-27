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

# Server Metrics 2026-02-27 17:41:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 2008.2 (0h 33m)
telemt_connections_total 249
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 245
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 3751675 (3.58 MB)
telemt_user_octets_to_client{user="hello"} 13788364 (13.15 MB)
telemt_user_msgs_from_client{user="hello"} 3101
telemt_user_msgs_to_client{user="hello"} 7453
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 2499.6 (0h 41m)
telemt_connections_total 30
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 10406 (10.16 KB)
telemt_user_octets_to_client{user="hello"} 4941 (4.83 KB)
telemt_user_msgs_from_client{user="hello"} 36
telemt_user_msgs_to_client{user="hello"} 31
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 2141.7 (0h 35m)
telemt_connections_total 54
telemt_user_connections_total{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 191424 (186.94 KB)
telemt_user_octets_to_client{user="hello"} 1261030 (1.20 MB)
telemt_user_msgs_from_client{user="hello"} 608
telemt_user_msgs_to_client{user="hello"} 726
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 2254.1 (0h 37m)
telemt_connections_total 42
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 9
telemt_user_connections_total{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 8133 (7.94 KB)
telemt_user_octets_to_client{user="hello"} 5585 (5.45 KB)
telemt_user_msgs_from_client{user="hello"} 30
telemt_user_msgs_to_client{user="hello"} 32
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 2310.8 (0h 38m)
telemt_connections_total 13
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 71397 (69.72 KB)
telemt_user_octets_to_client{user="hello"} 1953125 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 253
telemt_user_msgs_to_client{user="hello"} 809
```