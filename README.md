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

# Server Metrics 2026-02-27 18:02:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 3239.4 (0h 53m)
telemt_connections_total 311
telemt_connections_bad_total 2
telemt_user_connections_total{user="hello"} 304
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 4076121 (3.89 MB)
telemt_user_octets_to_client{user="hello"} 18032013 (17.20 MB)
telemt_user_msgs_from_client{user="hello"} 3835
telemt_user_msgs_to_client{user="hello"} 10226
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 3730.8 (1h 2m)
telemt_connections_total 135
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 126
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 111398 (108.79 KB)
telemt_user_octets_to_client{user="hello"} 158681 (154.96 KB)
telemt_user_msgs_from_client{user="hello"} 399
telemt_user_msgs_to_client{user="hello"} 327
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 3372.9 (0h 56m)
telemt_connections_total 86
telemt_connections_bad_total 2
telemt_user_connections_total{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 229592 (224.21 KB)
telemt_user_octets_to_client{user="hello"} 4969485 (4.74 MB)
telemt_user_msgs_from_client{user="hello"} 688
telemt_user_msgs_to_client{user="hello"} 1722
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 3485.4 (0h 58m)
telemt_connections_total 180
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 16
telemt_user_connections_total{user="hello"} 145
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 192772 (188.25 KB)
telemt_user_octets_to_client{user="hello"} 248266 (242.45 KB)
telemt_user_msgs_from_client{user="hello"} 568
telemt_user_msgs_to_client{user="hello"} 403
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 3542.0 (0h 59m)
telemt_connections_total 29
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 71397 (69.72 KB)
telemt_user_octets_to_client{user="hello"} 1953125 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 253
telemt_user_msgs_to_client{user="hello"} 809
```