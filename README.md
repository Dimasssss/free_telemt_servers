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

# Server Metrics 2026-02-27 21:53:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 17111.0 (4h 45m)
telemt_connections_total 3704
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 3
telemt_user_connections_total{user="hello"} 3507
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 10434327 (9.95 MB)
telemt_user_octets_to_client{user="hello"} 389737447 (371.68 MB)
telemt_user_msgs_from_client{user="hello"} 23735
telemt_user_msgs_to_client{user="hello"} 92215
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 17602.5 (4h 53m)
telemt_connections_total 1133
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 1102
telemt_user_octets_from_client{user="hello"} 1071414 (1.02 MB)
telemt_user_octets_to_client{user="hello"} 2754680 (2.63 MB)
telemt_user_msgs_from_client{user="hello"} 3766
telemt_user_msgs_to_client{user="hello"} 3198
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 17244.5 (4h 47m)
telemt_connections_total 616
telemt_connections_bad_total 26
telemt_user_connections_total{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 1809120 (1.73 MB)
telemt_user_octets_to_client{user="hello"} 11873660 (11.32 MB)
telemt_user_msgs_from_client{user="hello"} 2458
telemt_user_msgs_to_client{user="hello"} 5826
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 17357.0 (4h 49m)
telemt_connections_total 807
telemt_connections_bad_total 105
telemt_handshake_timeouts_total 37
telemt_user_connections_total{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 2434293 (2.32 MB)
telemt_user_octets_to_client{user="hello"} 28111198 (26.81 MB)
telemt_user_msgs_from_client{user="hello"} 4993
telemt_user_msgs_to_client{user="hello"} 10413
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 17413.5 (4h 50m)
telemt_connections_total 97
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 2
telemt_user_connections_total{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 128978 (125.96 KB)
telemt_user_octets_to_client{user="hello"} 2042893 (1.95 MB)
telemt_user_msgs_from_client{user="hello"} 431
telemt_user_msgs_to_client{user="hello"} 944
```