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

# Server Metrics 2026-02-27 18:12:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 3855.1 (1h 4m)
telemt_connections_total 317
telemt_connections_bad_total 2
telemt_user_connections_total{user="hello"} 310
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 4275521 (4.08 MB)
telemt_user_octets_to_client{user="hello"} 28671797 (27.34 MB)
telemt_user_msgs_from_client{user="hello"} 4466
telemt_user_msgs_to_client{user="hello"} 13185
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 4346.8 (1h 12m)
telemt_connections_total 136
telemt_connections_bad_total 4
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

telemt_uptime_seconds 3988.5 (1h 6m)
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

telemt_uptime_seconds 4101.1 (1h 8m)
telemt_connections_total 182
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 16
telemt_user_connections_total{user="hello"} 147
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 210488 (205.55 KB)
telemt_user_octets_to_client{user="hello"} 356030 (347.69 KB)
telemt_user_msgs_from_client{user="hello"} 608
telemt_user_msgs_to_client{user="hello"} 461
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 4157.6 (1h 9m)
telemt_connections_total 29
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 71397 (69.72 KB)
telemt_user_octets_to_client{user="hello"} 1953125 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 253
telemt_user_msgs_to_client{user="hello"} 809
```