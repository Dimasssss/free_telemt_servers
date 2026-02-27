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

# Server Metrics 2026-02-27 19:24:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 8183.9 (2h 16m)
telemt_connections_total 1138
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_user_connections_total{user="hello"} 1021
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 7259723 (6.92 MB)
telemt_user_octets_to_client{user="hello"} 239891621 (228.78 MB)
telemt_user_msgs_from_client{user="hello"} 12676
telemt_user_msgs_to_client{user="hello"} 54900
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 8675.3 (2h 24m)
telemt_connections_total 245
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 256206 (250.20 KB)
telemt_user_octets_to_client{user="hello"} 798255 (779.55 KB)
telemt_user_msgs_from_client{user="hello"} 865
telemt_user_msgs_to_client{user="hello"} 848
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 8317.2 (2h 18m)
telemt_connections_total 347
telemt_connections_bad_total 7
telemt_user_connections_total{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 1627427 (1.55 MB)
telemt_user_octets_to_client{user="hello"} 10630963 (10.14 MB)
telemt_user_msgs_from_client{user="hello"} 1863
telemt_user_msgs_to_client{user="hello"} 4824
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 8430.0 (2h 20m)
telemt_connections_total 378
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 30
telemt_user_connections_total{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 1228161 (1.17 MB)
telemt_user_octets_to_client{user="hello"} 9858451 (9.40 MB)
telemt_user_msgs_from_client{user="hello"} 3079
telemt_user_msgs_to_client{user="hello"} 4470
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 8486.4 (2h 21m)
telemt_connections_total 60
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 75792 (74.02 KB)
telemt_user_octets_to_client{user="hello"} 1955702 (1.87 MB)
telemt_user_msgs_from_client{user="hello"} 269
telemt_user_msgs_to_client{user="hello"} 823
```