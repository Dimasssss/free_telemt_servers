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

# Server Metrics 2026-03-01 09:48:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 66306.9 (18h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22706
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 21916
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 145984723 (139.22 MB)
telemt_user_octets_to_client{user="hello"} 832144315 (793.59 MB)
telemt_user_msgs_from_client{user="hello"} 113918
telemt_user_msgs_to_client{user="hello"} 236056
telemt_user_unique_ips_current{user="hello"} 1
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 945.3 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38
telemt_connections_bad_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 227
telemt_me_reconnect_success_total 265
telemt_me_route_drop_no_conn_total 4
telemt_me_writer_removed_unexpected_total 240
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 71004 (69.34 KB)
telemt_user_octets_to_client{user="hello"} 102008 (99.62 KB)
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 1032.9 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 242
telemt_me_reconnect_success_total 280
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_removed_unexpected_total 255
telemt_me_writer_restored_same_endpoint_total 237
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 16244 (15.86 KB)
telemt_user_octets_to_client{user="hello"} 105800 (103.32 KB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 914.8 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25
telemt_connections_bad_total 2
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 244
telemt_me_reconnect_success_total 278
telemt_me_route_drop_no_conn_total 1
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_restored_same_endpoint_total 239
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 19728 (19.27 KB)
telemt_user_octets_to_client{user="hello"} 39908 (38.97 KB)
```