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

# Server Metrics 2026-02-27 21:48:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 16803.1 (4h 40m)
telemt_connections_total 3684
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 3
telemt_user_connections_total{user="hello"} 3488
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 10392130 (9.91 MB)
telemt_user_octets_to_client{user="hello"} 389525807 (371.48 MB)
telemt_user_msgs_from_client{user="hello"} 23583
telemt_user_msgs_to_client{user="hello"} 91840
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 17294.4 (4h 48m)
telemt_connections_total 1130
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 1101
telemt_user_octets_from_client{user="hello"} 1070953 (1.02 MB)
telemt_user_octets_to_client{user="hello"} 2754403 (2.63 MB)
telemt_user_msgs_from_client{user="hello"} 3765
telemt_user_msgs_to_client{user="hello"} 3197
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 16936.4 (4h 42m)
telemt_connections_total 615
telemt_connections_bad_total 26
telemt_user_connections_total{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 1808518 (1.72 MB)
telemt_user_octets_to_client{user="hello"} 11873384 (11.32 MB)
telemt_user_msgs_from_client{user="hello"} 2457
telemt_user_msgs_to_client{user="hello"} 5825
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 17049.1 (4h 44m)
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

telemt_uptime_seconds 17105.5 (4h 45m)
telemt_connections_total 94
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 2
telemt_user_connections_total{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 125323 (122.39 KB)
telemt_user_octets_to_client{user="hello"} 2031762 (1.94 MB)
telemt_user_msgs_from_client{user="hello"} 418
telemt_user_msgs_to_client{user="hello"} 933
```