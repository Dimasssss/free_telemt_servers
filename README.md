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

# Server Metrics 2026-02-27 21:22:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 15264.0 (4h 14m)
telemt_connections_total 3348
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 3
telemt_user_connections_total{user="hello"} 3155
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 9931581 (9.47 MB)
telemt_user_octets_to_client{user="hello"} 386949736 (369.02 MB)
telemt_user_msgs_from_client{user="hello"} 22086
telemt_user_msgs_to_client{user="hello"} 89228
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 15755.3 (4h 22m)
telemt_connections_total 1067
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 1
telemt_user_connections_total{user="hello"} 1044
telemt_user_octets_from_client{user="hello"} 1030989 (1006.83 KB)
telemt_user_octets_to_client{user="hello"} 2718362 (2.59 MB)
telemt_user_msgs_from_client{user="hello"} 3622
telemt_user_msgs_to_client{user="hello"} 3106
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 15397.3 (4h 16m)
telemt_connections_total 570
telemt_connections_bad_total 20
telemt_user_connections_total{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 1778297 (1.70 MB)
telemt_user_octets_to_client{user="hello"} 11838180 (11.29 MB)
telemt_user_msgs_from_client{user="hello"} 2350
telemt_user_msgs_to_client{user="hello"} 5755
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 15509.8 (4h 18m)
telemt_connections_total 762
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 37
telemt_user_connections_total{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 1545280 (1.47 MB)
telemt_user_octets_to_client{user="hello"} 22803874 (21.75 MB)
telemt_user_msgs_from_client{user="hello"} 4088
telemt_user_msgs_to_client{user="hello"} 8224
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 15566.3 (4h 19m)
telemt_connections_total 70
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 2
telemt_user_connections_total{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 76769 (74.97 KB)
telemt_user_octets_to_client{user="hello"} 1956385 (1.87 MB)
telemt_user_msgs_from_client{user="hello"} 274
telemt_user_msgs_to_client{user="hello"} 827
```