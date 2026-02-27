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

# Server Metrics 2026-02-27 22:13:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 18341.6 (5h 5m)
telemt_connections_total 3990
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 3
telemt_user_connections_total{user="hello"} 3789
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 10762014 (10.26 MB)
telemt_user_octets_to_client{user="hello"} 391340164 (373.21 MB)
telemt_user_msgs_from_client{user="hello"} 24885
telemt_user_msgs_to_client{user="hello"} 94524
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 18833.1 (5h 13m)
telemt_connections_total 1134
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 1103
telemt_user_octets_from_client{user="hello"} 1072225 (1.02 MB)
telemt_user_octets_to_client{user="hello"} 2755167 (2.63 MB)
telemt_user_msgs_from_client{user="hello"} 3769
telemt_user_msgs_to_client{user="hello"} 3201
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 18475.1 (5h 7m)
telemt_connections_total 643
telemt_connections_bad_total 31
telemt_user_connections_total{user="hello"} 575
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 2057158 (1.96 MB)
telemt_user_octets_to_client{user="hello"} 52347508 (49.92 MB)
telemt_user_msgs_from_client{user="hello"} 3103
telemt_user_msgs_to_client{user="hello"} 13609
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 18587.7 (5h 9m)
telemt_connections_total 809
telemt_connections_bad_total 106
telemt_handshake_timeouts_total 37
telemt_user_connections_total{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 2434944 (2.32 MB)
telemt_user_octets_to_client{user="hello"} 28111563 (26.81 MB)
telemt_user_msgs_from_client{user="hello"} 4995
telemt_user_msgs_to_client{user="hello"} 10415
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 18644.2 (5h 10m)
telemt_connections_total 108
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 7
telemt_user_connections_total{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 129683 (126.64 KB)
telemt_user_octets_to_client{user="hello"} 2043271 (1.95 MB)
telemt_user_msgs_from_client{user="hello"} 433
telemt_user_msgs_to_client{user="hello"} 946
```