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

# Server Metrics 2026-03-14 22:30:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 980.6 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2455
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 221
telemt_upstream_connect_success_total 218
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 78
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 120
telemt_me_reconnect_success_total 118
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 428
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2228
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_me_writer_removed_unexpected_total 102
telemt_me_writer_restored_same_endpoint_total 87
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 2228
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 24525736 (23.39 MB)
telemt_user_octets_to_client{user="hello"} 492532484 (469.72 MB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 987.3 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 311
telemt_upstream_connect_success_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 189
telemt_me_reconnect_attempts_total 203
telemt_me_reconnect_success_total 203
telemt_me_reader_eof_total 175
telemt_me_idle_close_by_peer_total 175
telemt_me_route_drop_no_conn_total 355
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 193
telemt_me_writer_restored_same_endpoint_total 187
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 628
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 2670304 (2.55 MB)
telemt_user_octets_to_client{user="hello"} 35675216 (34.02 MB)
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 979.7 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1220
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 247
telemt_upstream_connect_success_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 134
telemt_me_reconnect_attempts_total 143
telemt_me_reconnect_success_total 141
telemt_me_reader_eof_total 118
telemt_me_idle_close_by_peer_total 118
telemt_me_route_drop_no_conn_total 237
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1137
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 130
telemt_me_writer_restored_same_endpoint_total 137
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 1137
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 90510424 (86.32 MB)
telemt_user_octets_to_client{user="hello"} 795577224 (758.72 MB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 979.5 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 219
telemt_upstream_connect_success_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 122
telemt_me_reconnect_success_total 120
telemt_me_reader_eof_total 92
telemt_me_idle_close_by_peer_total 92
telemt_me_route_drop_no_conn_total 301
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 933
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 114
telemt_me_writer_restored_same_endpoint_total 109
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 933
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 8216352 (7.84 MB)
telemt_user_octets_to_client{user="hello"} 1863894132 (1.74 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 979.6 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1433
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 220
telemt_upstream_connect_success_total 212
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 128
telemt_me_reconnect_success_total 128
telemt_me_reader_eof_total 92
telemt_me_idle_close_by_peer_total 92
telemt_me_route_drop_no_conn_total 219
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1230
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 108
telemt_me_writer_restored_same_endpoint_total 116
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 1230
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 8013448 (7.64 MB)
telemt_user_octets_to_client{user="hello"} 682534668 (650.92 MB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 978.6 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3278
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 243
telemt_upstream_connect_success_total 242
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 144
telemt_me_reconnect_success_total 144
telemt_me_reader_eof_total 101
telemt_me_idle_close_by_peer_total 101
telemt_me_route_drop_no_conn_total 1198
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3166
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 122
telemt_me_writer_restored_same_endpoint_total 117
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 3166
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 36478948 (34.79 MB)
telemt_user_octets_to_client{user="hello"} 3481103668 (3.24 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 32
```