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

# Server Metrics 2026-02-27 18:33:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 5086.6 (1h 24m)
telemt_connections_total 345
telemt_connections_bad_total 5
telemt_user_connections_total{user="hello"} 333
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 4715125 (4.50 MB)
telemt_user_octets_to_client{user="hello"} 76945312 (73.38 MB)
telemt_user_msgs_from_client{user="hello"} 5875
telemt_user_msgs_to_client{user="hello"} 22670
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 5577.9 (1h 32m)
telemt_connections_total 140
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 113391 (110.73 KB)
telemt_user_octets_to_client{user="hello"} 159821 (156.08 KB)
telemt_user_msgs_from_client{user="hello"} 405
telemt_user_msgs_to_client{user="hello"} 331
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 5220.0 (1h 27m)
telemt_connections_total 167
telemt_connections_bad_total 5
telemt_user_connections_total{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 316226 (308.81 KB)
telemt_user_octets_to_client{user="hello"} 7787289 (7.43 MB)
telemt_user_msgs_from_client{user="hello"} 986
telemt_user_msgs_to_client{user="hello"} 3133
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 5332.5 (1h 28m)
telemt_connections_total 205
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 16
telemt_user_connections_total{user="hello"} 165
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 359731 (351.30 KB)
telemt_user_octets_to_client{user="hello"} 1230594 (1.17 MB)
telemt_user_msgs_from_client{user="hello"} 1004
telemt_user_msgs_to_client{user="hello"} 990
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 5389.0 (1h 29m)
telemt_connections_total 48
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 71397 (69.72 KB)
telemt_user_octets_to_client{user="hello"} 1953125 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 253
telemt_user_msgs_to_client{user="hello"} 809
```