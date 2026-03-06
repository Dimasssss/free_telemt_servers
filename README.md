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

# Server Metrics 2026-03-06 23:33:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 19512.7 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28282
telemt_connections_bad_total 135
telemt_handshake_timeouts_total 476
telemt_upstream_connect_attempt_total 26383
telemt_upstream_connect_success_total 26376
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26374
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 2043503388 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 30375359317 (28.29 GB)
telemt_user_msgs_from_client{user="hello"} 1295082
telemt_user_msgs_to_client{user="hello"} 4762030
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 19511.2 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6423
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 6024
telemt_upstream_connect_success_total 6021
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6019
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 214720225 (204.77 MB)
telemt_user_octets_to_client{user="hello"} 3891273531 (3.62 GB)
telemt_user_msgs_from_client{user="hello"} 200227
telemt_user_msgs_to_client{user="hello"} 1086660
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 19511.6 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2982
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 2730
telemt_upstream_connect_success_total 2730
telemt_upstream_connect_attempts_per_request{bucket="1"} 2730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 210
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2728
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 64597372 (61.60 MB)
telemt_user_octets_to_client{user="hello"} 1852181165 (1.72 GB)
telemt_user_msgs_from_client{user="hello"} 62661
telemt_user_msgs_to_client{user="hello"} 389207
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 19511.3 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3953
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 3818
telemt_upstream_connect_success_total 3811
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 3818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3809
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 95184772 (90.78 MB)
telemt_user_octets_to_client{user="hello"} 1312628173 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 80450
telemt_user_msgs_to_client{user="hello"} 331851
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 19511.7 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10771
telemt_connections_bad_total 4444
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6187
telemt_upstream_connect_success_total 6186
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 989
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6184
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 226438260 (215.95 MB)
telemt_user_octets_to_client{user="hello"} 7319320566 (6.82 GB)
telemt_user_msgs_from_client{user="hello"} 211077
telemt_user_msgs_to_client{user="hello"} 1505236
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```