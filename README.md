# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-05 23:46:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 5470.0 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56297
telemt_connections_bad_total 51892
telemt_handshake_timeouts_total 938
telemt_upstream_connect_attempt_total 3424
telemt_upstream_connect_success_total 3424
telemt_upstream_connect_attempts_per_request{bucket="1"} 3424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3422
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 49225062 (46.94 MB)
telemt_user_octets_to_client{user="hello"} 6159766562 (5.74 GB)
telemt_user_msgs_from_client{user="hello"} 114625
telemt_user_msgs_to_client{user="hello"} 869298
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 5467.6 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432
telemt_connections_bad_total 18
telemt_upstream_connect_attempt_total 415
telemt_upstream_connect_success_total 415
telemt_upstream_connect_attempts_per_request{bucket="1"} 415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 413
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 2089696 (1.99 MB)
telemt_user_octets_to_client{user="hello"} 98329156 (93.77 MB)
telemt_user_msgs_from_client{user="hello"} 5844
telemt_user_msgs_to_client{user="hello"} 37518
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 5468.1 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337
telemt_connections_bad_total 38
telemt_upstream_connect_attempt_total 301
telemt_upstream_connect_success_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 299
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 1060091 (1.01 MB)
telemt_user_octets_to_client{user="hello"} 48421881 (46.18 MB)
telemt_user_msgs_from_client{user="hello"} 2731
telemt_user_msgs_to_client{user="hello"} 14250
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 5470.9 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 610
telemt_upstream_connect_success_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 608
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 17820483 (16.99 MB)
telemt_user_octets_to_client{user="hello"} 2836091389 (2.64 GB)
telemt_user_msgs_from_client{user="hello"} 51168
telemt_user_msgs_to_client{user="hello"} 501844
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 5470.6 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1745
telemt_connections_bad_total 986
telemt_upstream_connect_attempt_total 745
telemt_upstream_connect_success_total 745
telemt_upstream_connect_attempts_per_request{bucket="1"} 745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 743
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 28801422 (27.47 MB)
telemt_user_octets_to_client{user="hello"} 7849053109 (7.31 GB)
telemt_user_msgs_from_client{user="hello"} 79067
telemt_user_msgs_to_client{user="hello"} 1369557
telemt_user_unique_ips_current{user="hello"} 3
```