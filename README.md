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

# Server Metrics 2026-03-01 10:24:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 68460.9 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23687
telemt_connections_bad_total 242
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 22856
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 147427835 (140.60 MB)
telemt_user_octets_to_client{user="hello"} 942488448 (898.83 MB)
telemt_user_msgs_from_client{user="hello"} 118584
telemt_user_msgs_to_client{user="hello"} 256755
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 3099.2 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223
telemt_connections_bad_total 15
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 806
telemt_me_reconnect_success_total 870
telemt_me_route_drop_no_conn_total 44
telemt_pool_force_close_total 2
telemt_pool_stale_pick_total 15
telemt_me_writer_removed_unexpected_total 837
telemt_me_writer_restored_same_endpoint_total 784
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 207
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 1025032 (1001.01 KB)
telemt_user_octets_to_client{user="hello"} 4336492 (4.14 MB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 3187.6 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70
telemt_connections_bad_total 8
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1373
telemt_me_reconnect_success_total 1423
telemt_me_route_drop_no_conn_total 4
telemt_pool_stale_pick_total 11
telemt_me_writer_removed_unexpected_total 1402
telemt_me_writer_restored_same_endpoint_total 1349
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 62
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 62984 (61.51 KB)
telemt_user_octets_to_client{user="hello"} 1695764 (1.62 MB)
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 3069.0 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120
telemt_connections_bad_total 6
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 1005
telemt_me_reconnect_success_total 1060
telemt_me_route_drop_no_conn_total 22
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1034
telemt_me_writer_restored_same_endpoint_total 987
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 138604 (135.36 KB)
telemt_user_octets_to_client{user="hello"} 21758816 (20.75 MB)
```