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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 22:18:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 1783.3 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22079
telemt_connections_bad_total 1507
telemt_connections_current 798
telemt_connections_me_current 798
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 267
telemt_upstream_connect_success_total 263
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 158
telemt_me_reconnect_success_total 158
telemt_me_reader_eof_total 126
telemt_me_idle_close_by_peer_total 126
telemt_me_route_drop_no_conn_total 5481
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19257
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 64
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 148
telemt_me_writer_restored_same_endpoint_total 148
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 19256
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 195615728 (186.55 MB)
telemt_user_octets_to_client{user="hello"} 5448179676 (5.07 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 1786.7 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58395
telemt_connections_bad_total 1553
telemt_connections_current 1977
telemt_connections_me_current 1977
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 244
telemt_upstream_connect_success_total 241
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 131
telemt_me_reconnect_success_total 131
telemt_me_reader_eof_total 115
telemt_me_idle_close_by_peer_total 115
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 22999
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53755
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 134
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 138
telemt_me_writer_restored_same_endpoint_total 121
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 53753
telemt_user_connections_current{user="hello"} 1977
telemt_user_octets_from_client{user="hello"} 2147396872 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 15712832388 (14.63 GB)
telemt_user_unique_ips_current{user="hello"} 733
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 1784.1 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49969
telemt_connections_bad_total 5175
telemt_connections_current 1533
telemt_connections_me_current 1533
telemt_handshake_timeouts_total 1040
telemt_upstream_connect_attempt_total 337
telemt_upstream_connect_success_total 337
telemt_upstream_connect_attempts_per_request{bucket="1"} 337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 143
telemt_me_reconnect_attempts_total 227
telemt_me_reconnect_success_total 227
telemt_me_reader_eof_total 205
telemt_me_idle_close_by_peer_total 205
telemt_me_route_drop_no_conn_total 17497
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42296
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 152
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 225
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_user_connections_total{user="hello"} 42304
telemt_user_connections_current{user="hello"} 1533
telemt_user_octets_from_client{user="hello"} 489180168 (466.52 MB)
telemt_user_octets_to_client{user="hello"} 26866124272 (25.02 GB)
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 1837.3 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54893
telemt_connections_bad_total 3352
telemt_connections_current 1340
telemt_connections_me_current 1340
telemt_handshake_timeouts_total 648
telemt_upstream_connect_attempt_total 314
telemt_upstream_connect_success_total 314
telemt_upstream_connect_attempts_per_request{bucket="1"} 314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 196
telemt_me_reconnect_success_total 195
telemt_me_reader_eof_total 178
telemt_me_idle_close_by_peer_total 178
telemt_me_route_drop_no_conn_total 32667
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48536
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 102
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 198
telemt_me_writer_restored_same_endpoint_total 171
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 48484
telemt_user_connections_current{user="hello"} 1340
telemt_user_octets_from_client{user="hello"} 378076964 (360.56 MB)
telemt_user_octets_to_client{user="hello"} 12067724972 (11.24 GB)
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 1780.7 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51630
telemt_connections_bad_total 2369
telemt_connections_current 1581
telemt_connections_me_current 1581
telemt_handshake_timeouts_total 1332
telemt_upstream_connect_attempt_total 277
telemt_upstream_connect_success_total 274
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 162
telemt_me_reconnect_success_total 161
telemt_me_reader_eof_total 134
telemt_me_idle_close_by_peer_total 134
telemt_me_route_drop_no_conn_total 13649
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41284
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 188
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 155
telemt_me_writer_restored_same_endpoint_total 137
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 41272
telemt_user_connections_current{user="hello"} 1581
telemt_user_octets_from_client{user="hello"} 422174456 (402.62 MB)
telemt_user_octets_to_client{user="hello"} 26264680552 (24.46 GB)
telemt_user_unique_ips_current{user="hello"} 644
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 1792.3 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11230
telemt_connections_bad_total 2806
telemt_connections_current 391
telemt_connections_me_current 391
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 472
telemt_upstream_connect_success_total 460
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 356
telemt_me_reconnect_success_total 354
telemt_me_reader_eof_total 296
telemt_me_idle_close_by_peer_total 296
telemt_me_route_drop_no_conn_total 3101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8178
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 318
telemt_me_writer_restored_same_endpoint_total 324
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 8178
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 174986384 (166.88 MB)
telemt_user_octets_to_client{user="hello"} 4384184388 (4.08 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 1783.1 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41261
telemt_connections_bad_total 6818
telemt_connections_current 1505
telemt_connections_me_current 1505
telemt_handshake_timeouts_total 1066
telemt_upstream_connect_attempt_total 275
telemt_upstream_connect_success_total 275
telemt_upstream_connect_attempts_per_request{bucket="1"} 275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 120
telemt_me_reconnect_attempts_total 164
telemt_me_reconnect_success_total 164
telemt_me_reader_eof_total 147
telemt_me_idle_close_by_peer_total 147
telemt_me_route_drop_no_conn_total 9992
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32303
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 304
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 167
telemt_me_writer_restored_same_endpoint_total 149
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 32309
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 406036924 (387.23 MB)
telemt_user_octets_to_client{user="hello"} 23624534184 (22.00 GB)
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 137
```