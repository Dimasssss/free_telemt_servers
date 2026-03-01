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

# Server Metrics 2026-03-01 11:05:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 70940.0 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24687
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 20
telemt_user_connections_total{user="hello"} 23851
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 149543592 (142.62 MB)
telemt_user_octets_to_client{user="hello"} 993316011 (947.30 MB)
telemt_user_msgs_from_client{user="hello"} 125310
telemt_user_msgs_to_client{user="hello"} 271122
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 5578.5 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 1
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 1732
telemt_me_reconnect_success_total 1796
telemt_me_route_drop_no_conn_total 88
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 16
telemt_me_writer_removed_unexpected_total 1766
telemt_me_writer_restored_same_endpoint_total 1683
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 1546320 (1.47 MB)
telemt_user_octets_to_client{user="hello"} 4996776 (4.77 MB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 1.2 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 5548.5 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229
telemt_connections_bad_total 26
telemt_me_keepalive_timeout_total 629
telemt_me_reconnect_attempts_total 1971
telemt_me_reconnect_success_total 1971
telemt_me_route_drop_no_conn_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1967
telemt_me_writer_restored_same_endpoint_total 1794
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 167
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 212064 (207.09 KB)
telemt_user_octets_to_client{user="hello"} 22309820 (21.28 MB)
```