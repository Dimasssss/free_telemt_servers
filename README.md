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

# Server Metrics 2026-03-01 11:00:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 70633.0 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24521
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 23688
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 149415190 (142.49 MB)
telemt_user_octets_to_client{user="hello"} 992473499 (946.50 MB)
telemt_user_msgs_from_client{user="hello"} 124818
telemt_user_msgs_to_client{user="hello"} 270331
telemt_user_unique_ips_current{user="hello"} 1
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 5271.5 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416
telemt_connections_bad_total 16
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1639
telemt_me_reconnect_success_total 1706
telemt_me_route_drop_no_conn_total 80
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 16
telemt_me_writer_removed_unexpected_total 1675
telemt_me_writer_restored_same_endpoint_total 1596
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 1443360 (1.38 MB)
telemt_user_octets_to_client{user="hello"} 4695772 (4.48 MB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 5359.6 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143
telemt_connections_bad_total 9
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 2415
telemt_me_reconnect_success_total 2470
telemt_me_route_drop_no_conn_total 10
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 21
telemt_me_writer_removed_unexpected_total 2447
telemt_me_writer_restored_same_endpoint_total 2377
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 111340 (108.73 KB)
telemt_user_octets_to_client{user="hello"} 1763416 (1.68 MB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 5241.3 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191
telemt_connections_bad_total 26
telemt_me_keepalive_timeout_total 446
telemt_me_reconnect_attempts_total 1842
telemt_me_reconnect_success_total 1912
telemt_me_route_drop_no_conn_total 23
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1903
telemt_me_writer_restored_same_endpoint_total 1753
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 130
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 182516 (178.24 KB)
telemt_user_octets_to_client{user="hello"} 21939900 (20.92 MB)
```