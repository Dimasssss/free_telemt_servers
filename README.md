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

# Server Metrics 2026-03-08 09:00:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 6703.7 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14611
telemt_connections_bad_total 2391
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 11591
telemt_upstream_connect_success_total 11583
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 11590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11581
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 306216612 (292.03 MB)
telemt_user_octets_to_client{user="hello"} 7026021988 (6.54 GB)
telemt_user_msgs_from_client{user="hello"} 274083
telemt_user_msgs_to_client{user="hello"} 360185
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 6704.9 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3112
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 2958
telemt_upstream_connect_success_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 2958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2956
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 38822075 (37.02 MB)
telemt_user_octets_to_client{user="hello"} 2157864478 (2.01 GB)
telemt_user_msgs_from_client{user="hello"} 72805
telemt_user_msgs_to_client{user="hello"} 539796
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 6702.6 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2714
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2643
telemt_upstream_connect_success_total 2643
telemt_upstream_connect_attempts_per_request{bucket="1"} 2643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2641
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 26394639 (25.17 MB)
telemt_user_octets_to_client{user="hello"} 485256895 (462.78 MB)
telemt_user_msgs_from_client{user="hello"} 23069
telemt_user_msgs_to_client{user="hello"} 93524
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 6702.3 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2383
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2283
telemt_upstream_connect_success_total 2279
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 2283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2277
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 51148581 (48.78 MB)
telemt_user_octets_to_client{user="hello"} 708678637 (675.85 MB)
telemt_user_msgs_from_client{user="hello"} 39095
telemt_user_msgs_to_client{user="hello"} 187630
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 6702.7 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4184
telemt_connections_bad_total 1245
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2905
telemt_upstream_connect_success_total 2905
telemt_upstream_connect_attempts_per_request{bucket="1"} 2905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2903
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 39004134 (37.20 MB)
telemt_user_octets_to_client{user="hello"} 2846276199 (2.65 GB)
telemt_user_msgs_from_client{user="hello"} 64969
telemt_user_msgs_to_client{user="hello"} 307419
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 6
```