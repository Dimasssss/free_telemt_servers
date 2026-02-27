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

# Server Metrics 2026-02-27 21:07:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 14340.4 (3h 59m)
telemt_connections_total 2981
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 3
telemt_user_connections_total{user="hello"} 2795
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 9598545 (9.15 MB)
telemt_user_octets_to_client{user="hello"} 386096787 (368.21 MB)
telemt_user_msgs_from_client{user="hello"} 20869
telemt_user_msgs_to_client{user="hello"} 87484
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 14832.1 (4h 7m)
telemt_connections_total 1003
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 977481 (954.57 KB)
telemt_user_octets_to_client{user="hello"} 2685190 (2.56 MB)
telemt_user_msgs_from_client{user="hello"} 3431
telemt_user_msgs_to_client{user="hello"} 2959
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 14474.2 (4h 1m)
telemt_connections_total 500
telemt_connections_bad_total 13
telemt_user_connections_total{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 1739174 (1.66 MB)
telemt_user_octets_to_client{user="hello"} 11809947 (11.26 MB)
telemt_user_msgs_from_client{user="hello"} 2209
telemt_user_msgs_to_client{user="hello"} 5666
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 14586.8 (4h 3m)
telemt_connections_total 732
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 37
telemt_user_connections_total{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 1529932 (1.46 MB)
telemt_user_octets_to_client{user="hello"} 22792759 (21.74 MB)
telemt_user_msgs_from_client{user="hello"} 4032
telemt_user_msgs_to_client{user="hello"} 8183
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 14643.1 (4h 4m)
telemt_connections_total 66
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 2
telemt_user_connections_total{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 76171 (74.39 KB)
telemt_user_octets_to_client{user="hello"} 1955928 (1.87 MB)
telemt_user_msgs_from_client{user="hello"} 271
telemt_user_msgs_to_client{user="hello"} 825
```