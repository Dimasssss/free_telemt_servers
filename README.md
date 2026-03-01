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

# Server Metrics 2026-03-01 10:14:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 67845.6 (18h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23433
telemt_connections_bad_total 241
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 22610
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 147176758 (140.36 MB)
telemt_user_octets_to_client{user="hello"} 937960806 (894.51 MB)
telemt_user_msgs_from_client{user="hello"} 117604
telemt_user_msgs_to_client{user="hello"} 254878
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 2484.2 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190
telemt_connections_bad_total 14
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 601
telemt_me_reconnect_success_total 666
telemt_me_route_drop_no_conn_total 41
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 632
telemt_me_writer_restored_same_endpoint_total 587
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 175
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 887724 (866.92 KB)
telemt_user_octets_to_client{user="hello"} 4215708 (4.02 MB)
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 2571.9 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46
telemt_connections_bad_total 8
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 1007
telemt_me_reconnect_success_total 1058
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_removed_unexpected_total 1035
telemt_me_writer_restored_same_endpoint_total 988
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 19008 (18.56 KB)
telemt_user_octets_to_client{user="hello"} 107404 (104.89 KB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 2453.9 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109
telemt_connections_bad_total 5
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 723
telemt_me_reconnect_success_total 774
telemt_me_route_drop_no_conn_total 21
telemt_me_writer_removed_unexpected_total 745
telemt_me_writer_restored_same_endpoint_total 710
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 136852 (133.64 KB)
telemt_user_octets_to_client{user="hello"} 21757688 (20.75 MB)
```