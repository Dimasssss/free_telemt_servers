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

# Server Metrics 2026-03-01 09:43:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 65999.0 (18h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22583
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 21796
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 145497763 (138.76 MB)
telemt_user_octets_to_client{user="hello"} 817070495 (779.22 MB)
telemt_user_msgs_from_client{user="hello"} 112706
telemt_user_msgs_to_client{user="hello"} 233045
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 637.5 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36
telemt_connections_bad_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 140
telemt_me_reconnect_success_total 167
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_removed_unexpected_total 144
telemt_me_writer_restored_same_endpoint_total 134
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 70640 (68.98 KB)
telemt_user_octets_to_client{user="hello"} 101756 (99.37 KB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 725.4 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 155
telemt_me_reconnect_success_total 186
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_removed_unexpected_total 162
telemt_me_writer_restored_same_endpoint_total 150
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 16100 (15.72 KB)
telemt_user_octets_to_client{user="hello"} 105616 (103.14 KB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 607.2 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25
telemt_connections_bad_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 147
telemt_me_reconnect_success_total 178
telemt_me_route_drop_no_conn_total 1
telemt_me_writer_removed_unexpected_total 153
telemt_me_writer_restored_same_endpoint_total 146
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 19728 (19.27 KB)
telemt_user_octets_to_client{user="hello"} 39908 (38.97 KB)
```