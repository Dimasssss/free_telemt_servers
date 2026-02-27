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

# Server Metrics 2026-02-27 19:04:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 6951.8 (1h 55m)
telemt_connections_total 603
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 2
telemt_user_connections_total{user="hello"} 537
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 6212071 (5.92 MB)
telemt_user_octets_to_client{user="hello"} 192427967 (183.51 MB)
telemt_user_msgs_from_client{user="hello"} 9747
telemt_user_msgs_to_client{user="hello"} 44549
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 7443.4 (2h 4m)
telemt_connections_total 157
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 116957 (114.22 KB)
telemt_user_octets_to_client{user="hello"} 162111 (158.31 KB)
telemt_user_msgs_from_client{user="hello"} 417
telemt_user_msgs_to_client{user="hello"} 342
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 7085.3 (1h 58m)
telemt_connections_total 299
telemt_connections_bad_total 7
telemt_user_connections_total{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 1545730 (1.47 MB)
telemt_user_octets_to_client{user="hello"} 8313869 (7.93 MB)
telemt_user_msgs_from_client{user="hello"} 1628
telemt_user_msgs_to_client{user="hello"} 3946
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 7197.9 (1h 59m)
telemt_connections_total 339
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 22
telemt_user_connections_total{user="hello"} 280
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 1098896 (1.05 MB)
telemt_user_octets_to_client{user="hello"} 6118713 (5.84 MB)
telemt_user_msgs_from_client{user="hello"} 2797
telemt_user_msgs_to_client{user="hello"} 3117
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 7254.3 (2h 0m)
telemt_connections_total 58
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 74077 (72.34 KB)
telemt_user_octets_to_client{user="hello"} 1954730 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 263
telemt_user_msgs_to_client{user="hello"} 817
```