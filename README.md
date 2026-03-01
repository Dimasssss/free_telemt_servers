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
- Ссылка: `tg://proxy?server=195.226.94.42&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d`

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка: `tg://proxy?server=45.147.28.10&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d`

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка: `tg://proxy?server=108.165.174.245&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d`

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка: `tg://proxy?server=185.225.203.236&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d`

-----

# Server Metrics 2026-03-01 09:38:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 65691.5 (18h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22486
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 21700
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 145336893 (138.60 MB)
telemt_user_octets_to_client{user="hello"} 814794752 (777.05 MB)
telemt_user_msgs_from_client{user="hello"} 112224
telemt_user_msgs_to_client{user="hello"} 231943
telemt_user_unique_ips_current{user="hello"} 1
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 329.9 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35
telemt_connections_bad_total 2
telemt_me_reconnect_attempts_total 65
telemt_me_reconnect_success_total 91
telemt_me_route_drop_no_conn_total 1
telemt_me_writer_removed_unexpected_total 68
telemt_me_writer_restored_same_endpoint_total 65
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 70252 (68.61 KB)
telemt_user_octets_to_client{user="hello"} 101500 (99.12 KB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 417.9 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 86
telemt_me_reconnect_success_total 114
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_removed_unexpected_total 91
telemt_me_writer_restored_same_endpoint_total 84
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 16100 (15.72 KB)
telemt_user_octets_to_client{user="hello"} 105616 (103.14 KB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 299.6 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25
telemt_connections_bad_total 2
telemt_me_reconnect_attempts_total 68
telemt_me_reconnect_success_total 95
telemt_me_route_drop_no_conn_total 1
telemt_me_writer_removed_unexpected_total 72
telemt_me_writer_restored_same_endpoint_total 66
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 19728 (19.27 KB)
telemt_user_octets_to_client{user="hello"} 39908 (38.97 KB)
```