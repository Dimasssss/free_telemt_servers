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

# Server Metrics 2026-03-01 10:40:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 69401.4 (19h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24053
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 23221
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 148043175 (141.18 MB)
telemt_user_octets_to_client{user="hello"} 958236804 (913.85 MB)
telemt_user_msgs_from_client{user="hello"} 120738
telemt_user_msgs_to_client{user="hello"} 261306
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 4039.8 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282
telemt_connections_bad_total 15
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1184
telemt_me_reconnect_success_total 1244
telemt_me_route_drop_no_conn_total 52
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 15
telemt_me_writer_removed_unexpected_total 1208
telemt_me_writer_restored_same_endpoint_total 1149
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 266
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 1170264 (1.12 MB)
telemt_user_octets_to_client{user="hello"} 4514732 (4.31 MB)
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 4128.0 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107
telemt_connections_bad_total 8
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1926
telemt_me_reconnect_success_total 1976
telemt_me_route_drop_no_conn_total 9
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 11
telemt_me_writer_removed_unexpected_total 1954
telemt_me_writer_restored_same_endpoint_total 1899
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 92092 (89.93 KB)
telemt_user_octets_to_client{user="hello"} 1748428 (1.67 MB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 4009.5 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155
telemt_connections_bad_total 8
telemt_me_keepalive_timeout_total 440
telemt_me_reconnect_attempts_total 1436
telemt_me_reconnect_success_total 1492
telemt_me_route_drop_no_conn_total 22
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1474
telemt_me_writer_restored_same_endpoint_total 1358
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 147120 (143.67 KB)
telemt_user_octets_to_client{user="hello"} 21761624 (20.75 MB)
```