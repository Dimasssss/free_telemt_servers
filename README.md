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

# Server Metrics 2026-02-27 18:38:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 5394.3 (1h 29m)
telemt_connections_total 410
telemt_connections_bad_total 5
telemt_user_connections_total{user="hello"} 397
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 5228239 (4.99 MB)
telemt_user_octets_to_client{user="hello"} 78954001 (75.30 MB)
telemt_user_msgs_from_client{user="hello"} 6711
telemt_user_msgs_to_client{user="hello"} 24232
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 5885.9 (1h 38m)
telemt_connections_total 143
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 114616 (111.93 KB)
telemt_user_octets_to_client{user="hello"} 160570 (156.81 KB)
telemt_user_msgs_from_client{user="hello"} 409
telemt_user_msgs_to_client{user="hello"} 335
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 5527.8 (1h 32m)
telemt_connections_total 222
telemt_connections_bad_total 7
telemt_user_connections_total{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 363530 (355.01 KB)
telemt_user_octets_to_client{user="hello"} 7974852 (7.61 MB)
telemt_user_msgs_from_client{user="hello"} 1140
telemt_user_msgs_to_client{user="hello"} 3446
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 5640.5 (1h 34m)
telemt_connections_total 233
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 22
telemt_user_connections_total{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 623847 (609.23 KB)
telemt_user_octets_to_client{user="hello"} 1946427 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 1440
telemt_user_msgs_to_client{user="hello"} 1444
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 5697.1 (1h 34m)
telemt_connections_total 50
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 72401 (70.70 KB)
telemt_user_octets_to_client{user="hello"} 1953596 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 256
telemt_user_msgs_to_client{user="hello"} 812
```