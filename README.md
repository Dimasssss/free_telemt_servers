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

# Server Metrics 2026-02-27 19:14:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 7568.2 (2h 6m)
telemt_connections_total 892
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_user_connections_total{user="hello"} 805
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 6897783 (6.58 MB)
telemt_user_octets_to_client{user="hello"} 238386274 (227.34 MB)
telemt_user_msgs_from_client{user="hello"} 11698
telemt_user_msgs_to_client{user="hello"} 53254
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 8059.3 (2h 14m)
telemt_connections_total 212
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 146456 (143.02 KB)
telemt_user_octets_to_client{user="hello"} 193608 (189.07 KB)
telemt_user_msgs_from_client{user="hello"} 535
telemt_user_msgs_to_client{user="hello"} 412
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 7701.5 (2h 8m)
telemt_connections_total 327
telemt_connections_bad_total 7
telemt_user_connections_total{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 1604407 (1.53 MB)
telemt_user_octets_to_client{user="hello"} 10334373 (9.86 MB)
telemt_user_msgs_from_client{user="hello"} 1796
telemt_user_msgs_to_client{user="hello"} 4635
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 7814.1 (2h 10m)
telemt_connections_total 343
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 22
telemt_user_connections_total{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 1130649 (1.08 MB)
telemt_user_octets_to_client{user="hello"} 6460837 (6.16 MB)
telemt_user_msgs_from_client{user="hello"} 2900
telemt_user_msgs_to_client{user="hello"} 3297
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 7870.5 (2h 11m)
telemt_connections_total 58
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 74077 (72.34 KB)
telemt_user_octets_to_client{user="hello"} 1954730 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 263
telemt_user_msgs_to_client{user="hello"} 817
```