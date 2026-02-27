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

# Server Metrics 2026-02-27 18:22:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 4470.3 (1h 14m)
telemt_connections_total 328
telemt_connections_bad_total 2
telemt_user_connections_total{user="hello"} 319
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 4438884 (4.23 MB)
telemt_user_octets_to_client{user="hello"} 29725902 (28.35 MB)
telemt_user_msgs_from_client{user="hello"} 4996
telemt_user_msgs_to_client{user="hello"} 14778
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 4961.5 (1h 22m)
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

telemt_uptime_seconds 4603.6 (1h 16m)
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

telemt_uptime_seconds 4716.2 (1h 18m)
telemt_connections_total 190
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 16
telemt_user_connections_total{user="hello"} 152
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 249750 (243.90 KB)
telemt_user_octets_to_client{user="hello"} 535017 (522.48 KB)
telemt_user_msgs_from_client{user="hello"} 712
telemt_user_msgs_to_client{user="hello"} 594
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 4772.8 (1h 19m)
telemt_connections_total 33
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 71397 (69.72 KB)
telemt_user_octets_to_client{user="hello"} 1953125 (1.86 MB)
telemt_user_msgs_from_client{user="hello"} 253
telemt_user_msgs_to_client{user="hello"} 809
```