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

# Server Metrics 2026-03-01 09:58:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 66922.4 (18h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23053
telemt_connections_bad_total 235
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 22260
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 146595906 (139.80 MB)
telemt_user_octets_to_client{user="hello"} 846187643 (806.99 MB)
telemt_user_msgs_from_client{user="hello"} 115740
telemt_user_msgs_to_client{user="hello"} 240181
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 1560.9 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116
telemt_connections_bad_total 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 386
telemt_me_reconnect_success_total 437
telemt_me_route_drop_no_conn_total 13
telemt_me_writer_removed_unexpected_total 407
telemt_me_writer_restored_same_endpoint_total 372
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 196948 (192.33 KB)
telemt_user_octets_to_client{user="hello"} 442932 (432.55 KB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 1648.8 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36
telemt_connections_bad_total 1
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 522
telemt_me_reconnect_success_total 566
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_restored_same_endpoint_total 514
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 17292 (16.89 KB)
telemt_user_octets_to_client{user="hello"} 106436 (103.94 KB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 1530.6 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102
telemt_connections_bad_total 3
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 389
telemt_me_reconnect_success_total 432
telemt_me_route_drop_no_conn_total 21
telemt_me_writer_removed_unexpected_total 400
telemt_me_writer_restored_same_endpoint_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 135432 (132.26 KB)
telemt_user_octets_to_client{user="hello"} 21756716 (20.75 MB)
```