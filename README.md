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

# Server Metrics 2026-02-27 17:10:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.2

telemt_uptime_seconds 160.0 (0h 2m)
telemt_connections_total 39
telemt_user_connections_total{user="hello"} 39
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 2999461 (2.86 MB)
telemt_user_octets_to_client{user="hello"} 184586 (180.26 KB)
telemt_user_msgs_from_client{user="hello"} 800
telemt_user_msgs_to_client{user="hello"} 649
```

## psb.hosting

```
telemt 3.1.2

telemt_uptime_seconds 651.3 (0h 10m)
telemt_connections_total 8
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 2490 (2.43 KB)
telemt_user_octets_to_client{user="hello"} 1357 (1.33 KB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 9
```

## koara.io

```
telemt 3.1.2

telemt_uptime_seconds 293.4 (0h 4m)
telemt_connections_total 3
telemt_user_connections_total{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1399 (1.37 KB)
telemt_user_octets_to_client{user="hello"} 1072 (1.05 KB)
telemt_user_msgs_from_client{user="hello"} 6
telemt_user_msgs_to_client{user="hello"} 8
```

## landvps.ru

```
telemt 3.1.2

telemt_uptime_seconds 406.0 (0h 6m)
telemt_connections_total 4
telemt_connections_bad_total 1
telemt_user_connections_total{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1879 (1.83 KB)
telemt_user_octets_to_client{user="hello"} 1896 (1.85 KB)
telemt_user_msgs_from_client{user="hello"} 6
telemt_user_msgs_to_client{user="hello"} 9
```

## 4vps.su

```
telemt 3.1.2

telemt_uptime_seconds 462.6 (0h 7m)
telemt_connections_total 3
telemt_user_connections_total{user="hello"} 3
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1585 (1.55 KB)
telemt_user_octets_to_client{user="hello"} 2160 (2.11 KB)
telemt_user_msgs_from_client{user="hello"} 6
telemt_user_msgs_to_client{user="hello"} 9
```