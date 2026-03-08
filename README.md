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

# Server Metrics 2026-03-08 17:03:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 35702.4 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85783
telemt_connections_bad_total 5045
telemt_handshake_timeouts_total 1110
telemt_upstream_connect_attempt_total 76758
telemt_upstream_connect_success_total 76732
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 76758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76726
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 1927979488 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 43909036630 (40.89 GB)
telemt_user_msgs_from_client{user="hello"} 1819769
telemt_user_msgs_to_client{user="hello"} 2536376
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 35701.8 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18662
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 18067
telemt_upstream_connect_success_total 18063
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 18067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18059
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 647619554 (617.62 MB)
telemt_user_octets_to_client{user="hello"} 18097207274 (16.85 GB)
telemt_user_msgs_from_client{user="hello"} 710572
telemt_user_msgs_to_client{user="hello"} 4925444
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 35701.6 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11392
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 10747
telemt_upstream_connect_success_total 10671
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 10747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10667
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 227052797 (216.53 MB)
telemt_user_octets_to_client{user="hello"} 3907342244 (3.64 GB)
telemt_user_msgs_from_client{user="hello"} 186893
telemt_user_msgs_to_client{user="hello"} 681161
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 35701.5 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15173
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 14465
telemt_upstream_connect_success_total 14434
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 14465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1042
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14430
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 1006203606 (959.59 MB)
telemt_user_octets_to_client{user="hello"} 5186113996 (4.83 GB)
telemt_user_msgs_from_client{user="hello"} 508238
telemt_user_msgs_to_client{user="hello"} 1173862
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 35701.7 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20459
telemt_connections_bad_total 6586
telemt_handshake_timeouts_total 227
telemt_upstream_connect_attempt_total 13336
telemt_upstream_connect_success_total 13332
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 13336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13328
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 256208502 (244.34 MB)
telemt_user_octets_to_client{user="hello"} 11136591815 (10.37 GB)
telemt_user_msgs_from_client{user="hello"} 334263
telemt_user_msgs_to_client{user="hello"} 1454272
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```