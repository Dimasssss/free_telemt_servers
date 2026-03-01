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

# Server Metrics 2026-03-01 10:29:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 68768.7 (19h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23821
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 22989
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 147645935 (140.81 MB)
telemt_user_octets_to_client{user="hello"} 952774662 (908.64 MB)
telemt_user_msgs_from_client{user="hello"} 119326
telemt_user_msgs_to_client{user="hello"} 258939
telemt_user_unique_ips_current{user="hello"} 2
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 3406.9 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225
telemt_connections_bad_total 15
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 946
telemt_me_reconnect_success_total 1007
telemt_me_route_drop_no_conn_total 47
telemt_pool_force_close_total 2
telemt_pool_stale_pick_total 15
telemt_me_writer_removed_unexpected_total 974
telemt_me_writer_restored_same_endpoint_total 918
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 1026784 (1002.72 KB)
telemt_user_octets_to_client{user="hello"} 4337136 (4.14 MB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 3495.1 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72
telemt_connections_bad_total 8
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 1569
telemt_me_reconnect_success_total 1621
telemt_me_route_drop_no_conn_total 4
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 11
telemt_me_writer_removed_unexpected_total 1599
telemt_me_writer_restored_same_endpoint_total 1546
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 64
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 64516 (63.00 KB)
telemt_user_octets_to_client{user="hello"} 1697212 (1.62 MB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 3376.8 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125
telemt_connections_bad_total 7
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 1184
telemt_me_reconnect_success_total 1240
telemt_me_route_drop_no_conn_total 22
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1215
telemt_me_writer_restored_same_endpoint_total 1164
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 139264 (136.00 KB)
telemt_user_octets_to_client{user="hello"} 21759184 (20.75 MB)
```