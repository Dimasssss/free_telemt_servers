# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 07:36:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 182.2 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1613
telemt_handshake_timeouts_total 93
telemt_upstream_connect_attempt_total 105
telemt_upstream_connect_success_total 104
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 40
telemt_me_reconnect_success_total 40
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1400
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 21
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 29
telemt_me_writer_restored_same_endpoint_total 24
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 24
telemt_user_connections_total{user="hello"} 1400
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 12701800 (12.11 MB)
telemt_user_octets_to_client{user="hello"} 182560132 (174.10 MB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 75.1 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 94
telemt_upstream_connect_success_total 89
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 94
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 27
telemt_me_reconnect_success_total 27
telemt_me_route_drop_no_conn_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 17
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 145
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 210600 (205.66 KB)
telemt_user_octets_to_client{user="hello"} 3830836 (3.65 MB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 38.3 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217
telemt_upstream_connect_attempt_total 100
telemt_upstream_connect_success_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_me_reconnect_attempts_total 36
telemt_me_reconnect_success_total 36
telemt_me_route_drop_no_conn_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_user_connections_total{user="hello"} 207
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 446580 (436.11 KB)
telemt_user_octets_to_client{user="hello"} 31258900 (29.81 MB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

Не удалось получить метрики для этого сервера.

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5675.9 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9831
telemt_connections_bad_total 1077
telemt_handshake_timeouts_total 150
telemt_upstream_connect_attempt_total 8345
telemt_upstream_connect_success_total 8192
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 8345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8190
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 186532161 (177.89 MB)
telemt_user_octets_to_client{user="hello"} 5248766671 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 188150
telemt_user_msgs_to_client{user="hello"} 817863
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 35484.4 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68622
telemt_connections_bad_total 1120
telemt_handshake_timeouts_total 354
telemt_upstream_connect_attempt_total 64211
telemt_upstream_connect_success_total 63906
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 64209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10463
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63902
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 1141475636 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 52560368408 (48.95 GB)
telemt_user_msgs_from_client{user="hello"} 1577997
telemt_user_msgs_to_client{user="hello"} 6836146
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 28
```