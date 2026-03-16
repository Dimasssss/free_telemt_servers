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

# Server Metrics 2026-03-16 19:08:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 1396.3 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11007
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 193
telemt_upstream_connect_attempt_total 266
telemt_upstream_connect_success_total 262
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 152
telemt_me_reconnect_success_total 151
telemt_me_reader_eof_total 121
telemt_me_idle_close_by_peer_total 121
telemt_me_route_drop_no_conn_total 3352
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10150
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 68
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 142
telemt_me_writer_restored_same_endpoint_total 130
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 10146
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 193179908 (184.23 MB)
telemt_user_octets_to_client{user="hello"} 8677054500 (8.08 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 1649.3 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11250
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 282
telemt_upstream_connect_attempt_total 245
telemt_upstream_connect_success_total 240
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 131
telemt_me_reconnect_success_total 131
telemt_me_reader_eof_total 107
telemt_me_idle_close_by_peer_total 107
telemt_me_route_drop_no_conn_total 4877
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10582
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 130
telemt_me_writer_restored_same_endpoint_total 115
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_user_connections_total{user="hello"} 10582
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 95443680 (91.02 MB)
telemt_user_octets_to_client{user="hello"} 3661924980 (3.41 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 1423.9 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5485
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 257
telemt_upstream_connect_success_total 255
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 145
telemt_me_reconnect_success_total 144
telemt_me_reader_eof_total 121
telemt_me_idle_close_by_peer_total 121
telemt_me_route_drop_no_conn_total 1528
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5311
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 142
telemt_me_writer_restored_same_endpoint_total 133
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_user_connections_total{user="hello"} 5310
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 152448244 (145.39 MB)
telemt_user_octets_to_client{user="hello"} 2054558876 (1.91 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 1483.0 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11749
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 253
telemt_upstream_connect_success_total 248
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 134
telemt_me_reconnect_success_total 133
telemt_me_reader_eof_total 107
telemt_me_idle_close_by_peer_total 107
telemt_me_route_drop_no_conn_total 3225
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11188
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 44
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_me_writer_removed_unexpected_total 129
telemt_me_writer_restored_same_endpoint_total 126
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_user_connections_total{user="hello"} 11185
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 181097760 (172.71 MB)
telemt_user_octets_to_client{user="hello"} 4086157896 (3.81 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 1455.2 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6140
telemt_connections_bad_total 1670
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 327
telemt_upstream_connect_success_total 322
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 214
telemt_me_reconnect_success_total 213
telemt_me_reader_eof_total 177
telemt_me_idle_close_by_peer_total 177
telemt_me_route_drop_no_conn_total 1632
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4222
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 194
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_user_connections_total{user="hello"} 4222
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 30968180 (29.53 MB)
telemt_user_octets_to_client{user="hello"} 896867044 (855.32 MB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 1616.6 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17087
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 228
telemt_upstream_connect_success_total 226
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 117
telemt_me_reconnect_success_total 117
telemt_me_reader_eof_total 100
telemt_me_idle_close_by_peer_total 100
telemt_me_route_drop_no_conn_total 6746
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16418
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 122
telemt_me_writer_restored_same_endpoint_total 107
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 16415
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 177773772 (169.54 MB)
telemt_user_octets_to_client{user="hello"} 6244400872 (5.82 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 91
```