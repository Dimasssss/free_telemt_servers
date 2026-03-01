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

# Server Metrics 2026-03-01 10:45:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 69709.3 (19h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24185
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 23353
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 148560552 (141.68 MB)
telemt_user_octets_to_client{user="hello"} 970377287 (925.42 MB)
telemt_user_msgs_from_client{user="hello"} 122203
telemt_user_msgs_to_client{user="hello"} 264206
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 4347.8 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285
telemt_connections_bad_total 15
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1311
telemt_me_reconnect_success_total 1369
telemt_me_route_drop_no_conn_total 55
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 15
telemt_me_writer_removed_unexpected_total 1336
telemt_me_writer_restored_same_endpoint_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 1172484 (1.12 MB)
telemt_user_octets_to_client{user="hello"} 4520704 (4.31 MB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 4436.0 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110
telemt_connections_bad_total 9
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 2038
telemt_me_reconnect_success_total 2089
telemt_me_route_drop_no_conn_total 9
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 11
telemt_me_writer_removed_unexpected_total 2066
telemt_me_writer_restored_same_endpoint_total 2001
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 93180 (91.00 KB)
telemt_user_octets_to_client{user="hello"} 1749048 (1.67 MB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 4317.6 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166
telemt_connections_bad_total 17
telemt_me_keepalive_timeout_total 441
telemt_me_reconnect_attempts_total 1545
telemt_me_reconnect_success_total 1604
telemt_me_route_drop_no_conn_total 22
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1585
telemt_me_writer_restored_same_endpoint_total 1466
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 148720 (145.23 KB)
telemt_user_octets_to_client{user="hello"} 21762400 (20.75 MB)
```