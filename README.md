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

# Server Metrics 2026-02-27 22:34:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 19572.2 (5h 26m)
telemt_connections_total 4296
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 3
telemt_user_connections_total{user="hello"} 4083
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 10964383 (10.46 MB)
telemt_user_octets_to_client{user="hello"} 391942857 (373.79 MB)
telemt_user_msgs_from_client{user="hello"} 25727
telemt_user_msgs_to_client{user="hello"} 96405
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 20063.8 (5h 34m)
telemt_connections_total 1137
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 1105
telemt_user_octets_from_client{user="hello"} 1072765 (1.02 MB)
telemt_user_octets_to_client{user="hello"} 2755523 (2.63 MB)
telemt_user_msgs_from_client{user="hello"} 3771
telemt_user_msgs_to_client{user="hello"} 3203
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 19706.0 (5h 28m)
telemt_connections_total 656
telemt_connections_bad_total 34
telemt_user_connections_total{user="hello"} 585
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 2936456 (2.80 MB)
telemt_user_octets_to_client{user="hello"} 173393361 (165.36 MB)
telemt_user_msgs_from_client{user="hello"} 5679
telemt_user_msgs_to_client{user="hello"} 37798
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 19818.5 (5h 30m)
telemt_connections_total 819
telemt_connections_bad_total 115
telemt_handshake_timeouts_total 37
telemt_user_connections_total{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 2435050 (2.32 MB)
telemt_user_octets_to_client{user="hello"} 28111766 (26.81 MB)
telemt_user_msgs_from_client{user="hello"} 4996
telemt_user_msgs_to_client{user="hello"} 10416
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 19874.9 (5h 31m)
telemt_connections_total 112
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 7
telemt_user_connections_total{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 129980 (126.93 KB)
telemt_user_octets_to_client{user="hello"} 2043540 (1.95 MB)
telemt_user_msgs_from_client{user="hello"} 435
telemt_user_msgs_to_client{user="hello"} 948
```