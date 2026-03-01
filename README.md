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

# Server Metrics 2026-03-01 09:53:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 66614.7 (18h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22930
telemt_connections_bad_total 235
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 22131
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 146526186 (139.74 MB)
telemt_user_octets_to_client{user="hello"} 845616138 (806.44 MB)
telemt_user_msgs_from_client{user="hello"} 115442
telemt_user_msgs_to_client{user="hello"} 239349
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 1253.0 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58
telemt_connections_bad_total 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 310
telemt_me_reconnect_success_total 359
telemt_me_route_drop_no_conn_total 4
telemt_me_writer_removed_unexpected_total 331
telemt_me_writer_restored_same_endpoint_total 301
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 55
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 91804 (89.65 KB)
telemt_user_octets_to_client{user="hello"} 158004 (154.30 KB)
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 1340.9 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 361
telemt_me_reconnect_success_total 401
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_removed_unexpected_total 376
telemt_me_writer_restored_same_endpoint_total 355
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 16652 (16.26 KB)
telemt_user_octets_to_client{user="hello"} 106072 (103.59 KB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 1222.8 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69
telemt_connections_bad_total 3
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 315
telemt_me_reconnect_success_total 353
telemt_me_route_drop_no_conn_total 13
telemt_me_writer_removed_unexpected_total 324
telemt_me_writer_restored_same_endpoint_total 309
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 120168 (117.35 KB)
telemt_user_octets_to_client{user="hello"} 21720432 (20.71 MB)
```