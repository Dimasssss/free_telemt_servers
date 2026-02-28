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

# Server Metrics 2026-02-28 06:26:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 25205.8 (7h 0m)
telemt_connections_total 2915
telemt_connections_bad_total 62
telemt_user_connections_total{user="hello"} 2816
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 2499798 (2.38 MB)
telemt_user_octets_to_client{user="hello"} 24507132 (23.37 MB)
telemt_user_msgs_from_client{user="hello"} 9068
telemt_user_msgs_to_client{user="hello"} 24255
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 25032.1 (6h 57m)
telemt_connections_total 61
telemt_connections_bad_total 46
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 25200.0 (7h 0m)
telemt_connections_total 707
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 10
telemt_user_connections_total{user="hello"} 127
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 466032 (455.11 KB)
telemt_user_octets_to_client{user="hello"} 52027307 (49.62 MB)
telemt_user_msgs_from_client{user="hello"} 1397
telemt_user_msgs_to_client{user="hello"} 11185
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 26343.0 (7h 19m)
telemt_connections_total 629
telemt_connections_bad_total 95
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 778 (778 B)
telemt_user_octets_to_client{user="hello"} 1241 (1.21 KB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 7
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 25193.7 (6h 59m)
telemt_connections_total 169
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 5
```