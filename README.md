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

# Server Metrics 2026-03-01 10:35:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 69076.3 (19h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23968
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 23136
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 147981951 (141.13 MB)
telemt_user_octets_to_client{user="hello"} 957794351 (913.42 MB)
telemt_user_msgs_from_client{user="hello"} 120491
telemt_user_msgs_to_client{user="hello"} 260850
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 3714.7 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280
telemt_connections_bad_total 15
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 1064
telemt_me_reconnect_success_total 1124
telemt_me_route_drop_no_conn_total 51
telemt_pool_force_close_total 2
telemt_pool_stale_pick_total 15
telemt_me_writer_removed_unexpected_total 1092
telemt_me_writer_restored_same_endpoint_total 1034
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 264
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 1068004 (1.02 MB)
telemt_user_octets_to_client{user="hello"} 4381616 (4.18 MB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 3803.1 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107
telemt_connections_bad_total 8
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 1753
telemt_me_reconnect_success_total 1802
telemt_me_route_drop_no_conn_total 8
telemt_pool_force_close_total 3
telemt_pool_stale_pick_total 11
telemt_me_writer_removed_unexpected_total 1781
telemt_me_writer_restored_same_endpoint_total 1726
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 92092 (89.93 KB)
telemt_user_octets_to_client{user="hello"} 1748428 (1.67 MB)
```

## landvps.ru

Не удалось получить метрики для этого сервера.