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

# Server Metrics 2026-03-08 08:03:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 3316.2 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5729
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 5534
telemt_upstream_connect_success_total 5530
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 5534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5528
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 84171319 (80.27 MB)
telemt_user_octets_to_client{user="hello"} 2014409200 (1.88 GB)
telemt_user_msgs_from_client{user="hello"} 115863
telemt_user_msgs_to_client{user="hello"} 146087
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 3315.4 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1491
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1441
telemt_upstream_connect_success_total 1441
telemt_upstream_connect_attempts_per_request{bucket="1"} 1441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1439
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 15796790 (15.06 MB)
telemt_user_octets_to_client{user="hello"} 742591920 (708.19 MB)
telemt_user_msgs_from_client{user="hello"} 28486
telemt_user_msgs_to_client{user="hello"} 178623
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 3315.2 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1240
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1212
telemt_upstream_connect_success_total 1212
telemt_upstream_connect_attempts_per_request{bucket="1"} 1212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1210
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 19994533 (19.07 MB)
telemt_user_octets_to_client{user="hello"} 329990934 (314.70 MB)
telemt_user_msgs_from_client{user="hello"} 11142
telemt_user_msgs_to_client{user="hello"} 51491
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 3315.0 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1261
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 1220
telemt_upstream_connect_success_total 1217
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 74
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1215
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 36279000 (34.60 MB)
telemt_user_octets_to_client{user="hello"} 342315410 (326.46 MB)
telemt_user_msgs_from_client{user="hello"} 19973
telemt_user_msgs_to_client{user="hello"} 93116
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 3315.4 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2315
telemt_connections_bad_total 593
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1702
telemt_upstream_connect_success_total 1702
telemt_upstream_connect_attempts_per_request{bucket="1"} 1702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1700
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 12530549 (11.95 MB)
telemt_user_octets_to_client{user="hello"} 356017403 (339.52 MB)
telemt_user_msgs_from_client{user="hello"} 21907
telemt_user_msgs_to_client{user="hello"} 71339
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 3
```