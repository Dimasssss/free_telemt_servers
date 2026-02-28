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

# Server Metrics 2026-02-28 09:00:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 34459.4 (9h 34m)
telemt_connections_total 5749
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 4
telemt_user_connections_total{user="hello"} 5510
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 5555100 (5.30 MB)
telemt_user_octets_to_client{user="hello"} 108122919 (103.11 MB)
telemt_user_msgs_from_client{user="hello"} 19086
telemt_user_msgs_to_client{user="hello"} 51468
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 34285.6 (9h 31m)
telemt_connections_total 315
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 6
telemt_user_connections_total{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 227038 (221.72 KB)
telemt_user_octets_to_client{user="hello"} 1437965 (1.37 MB)
telemt_user_msgs_from_client{user="hello"} 733
telemt_user_msgs_to_client{user="hello"} 762
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 34453.5 (9h 34m)
telemt_connections_total 1450
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 14
telemt_user_connections_total{user="hello"} 827
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 2005041 (1.91 MB)
telemt_user_octets_to_client{user="hello"} 85171738 (81.23 MB)
telemt_user_msgs_from_client{user="hello"} 5414
telemt_user_msgs_to_client{user="hello"} 24980
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 35596.5 (9h 53m)
telemt_connections_total 5278
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 12
telemt_user_connections_total{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 6877 (6.72 KB)
telemt_user_octets_to_client{user="hello"} 4893 (4.78 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 20
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 34447.2 (9h 34m)
telemt_connections_total 190
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 6
telemt_user_connections_total{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 2779 (2.71 KB)
telemt_user_octets_to_client{user="hello"} 1719 (1.68 KB)
telemt_user_msgs_from_client{user="hello"} 8
telemt_user_msgs_to_client{user="hello"} 5
```