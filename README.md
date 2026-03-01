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

# Server Metrics 2026-03-01 10:19:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.3

telemt_uptime_seconds 68153.3 (18h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23525
telemt_connections_bad_total 242
telemt_handshake_timeouts_total 19
telemt_user_connections_total{user="hello"} 22697
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 147249404 (140.43 MB)
telemt_user_octets_to_client{user="hello"} 940611941 (897.04 MB)
telemt_user_msgs_from_client{user="hello"} 117883
telemt_user_msgs_to_client{user="hello"} 255809
```

## psb.hosting

```
telemt 3.1.3

telemt_uptime_seconds 2791.9 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199
telemt_connections_bad_total 15
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 694
telemt_me_reconnect_success_total 757
telemt_me_route_drop_no_conn_total 41
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 724
telemt_me_writer_restored_same_endpoint_total 674
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 183
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1005396 (981.83 KB)
telemt_user_octets_to_client{user="hello"} 4312576 (4.11 MB)
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.1.3

telemt_uptime_seconds 2879.7 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50
telemt_connections_bad_total 8
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1173
telemt_me_reconnect_success_total 1224
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_removed_unexpected_total 1202
telemt_me_writer_restored_same_endpoint_total 1152
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 19872 (19.41 KB)
telemt_user_octets_to_client{user="hello"} 108072 (105.54 KB)
```

## landvps.ru

```
telemt 3.1.3

telemt_uptime_seconds 2761.5 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114
telemt_connections_bad_total 6
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 873
telemt_me_reconnect_success_total 924
telemt_me_route_drop_no_conn_total 21
telemt_me_writer_removed_unexpected_total 899
telemt_me_writer_restored_same_endpoint_total 855
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 89
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 137456 (134.23 KB)
telemt_user_octets_to_client{user="hello"} 21757892 (20.75 MB)
telemt_user_unique_ips_current{user="hello"} 1
```