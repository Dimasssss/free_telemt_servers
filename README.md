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

# Server Metrics 2026-03-01 10:04:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 67230.2 (18h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23137
telemt_connections_bad_total 239
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 22339
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 146628897 (139.84 MB)
telemt_user_octets_to_client{user="hello"} 846534628 (807.32 MB)
telemt_user_msgs_from_client{user="hello"} 115889
telemt_user_msgs_to_client{user="hello"} 240631
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 1868.7 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155
telemt_connections_bad_total 13
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 467
telemt_me_reconnect_success_total 523
telemt_me_route_drop_no_conn_total 26
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 493
telemt_me_writer_restored_same_endpoint_total 453
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 142
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 471384 (460.34 KB)
telemt_user_octets_to_client{user="hello"} 3521488 (3.36 MB)
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 1956.5 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37
telemt_connections_bad_total 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 661
telemt_me_reconnect_success_total 706
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_restored_same_endpoint_total 648
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 17892 (17.47 KB)
telemt_user_octets_to_client{user="hello"} 106692 (104.19 KB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 1838.4 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105
telemt_connections_bad_total 4
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 464
telemt_me_reconnect_success_total 509
telemt_me_route_drop_no_conn_total 21
telemt_me_writer_removed_unexpected_total 476
telemt_me_writer_restored_same_endpoint_total 452
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 135432 (132.26 KB)
telemt_user_octets_to_client{user="hello"} 21756716 (20.75 MB)
```