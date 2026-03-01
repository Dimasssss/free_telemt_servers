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

# Server Metrics 2026-03-01 10:50:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 70017.4 (19h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24312
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 23480
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 148985718 (142.08 MB)
telemt_user_octets_to_client{user="hello"} 982533473 (937.02 MB)
telemt_user_msgs_from_client{user="hello"} 123348
telemt_user_msgs_to_client{user="hello"} 267167
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 4655.8 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291
telemt_connections_bad_total 15
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1425
telemt_me_reconnect_success_total 1489
telemt_me_route_drop_no_conn_total 55
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 15
telemt_me_writer_removed_unexpected_total 1454
telemt_me_writer_restored_same_endpoint_total 1384
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 275
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 1292412 (1.23 MB)
telemt_user_octets_to_client{user="hello"} 4566632 (4.36 MB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 4743.8 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110
telemt_connections_bad_total 9
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 2151
telemt_me_reconnect_success_total 2204
telemt_me_route_drop_no_conn_total 9
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 11
telemt_me_writer_removed_unexpected_total 2182
telemt_me_writer_restored_same_endpoint_total 2114
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 93180 (91.00 KB)
telemt_user_octets_to_client{user="hello"} 1749048 (1.67 MB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 4625.3 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175
telemt_connections_bad_total 26
telemt_me_keepalive_timeout_total 441
telemt_me_reconnect_attempts_total 1641
telemt_me_reconnect_success_total 1707
telemt_me_route_drop_no_conn_total 22
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1688
telemt_me_writer_restored_same_endpoint_total 1558
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 148720 (145.23 KB)
telemt_user_octets_to_client{user="hello"} 21762400 (20.75 MB)
```