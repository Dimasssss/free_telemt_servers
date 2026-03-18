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

# Server Metrics 2026-03-18 22:23:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 2090.2 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25348
telemt_connections_bad_total 1760
telemt_connections_current 698
telemt_connections_me_current 698
telemt_handshake_timeouts_total 249
telemt_upstream_connect_attempt_total 370
telemt_upstream_connect_success_total 364
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 216
telemt_me_reconnect_success_total 215
telemt_me_reader_eof_total 189
telemt_me_idle_close_by_peer_total 189
telemt_me_route_drop_no_conn_total 6332
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21920
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 205
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 21919
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 229876880 (219.23 MB)
telemt_user_octets_to_client{user="hello"} 7971350940 (7.42 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 2093.5 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66481
telemt_connections_bad_total 1648
telemt_connections_current 1926
telemt_connections_me_current 1926
telemt_handshake_timeouts_total 526
telemt_upstream_connect_attempt_total 343
telemt_upstream_connect_success_total 336
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 183
telemt_me_reconnect_success_total 183
telemt_me_reader_eof_total 173
telemt_me_idle_close_by_peer_total 173
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 25842
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61215
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 190
telemt_me_writer_restored_same_endpoint_total 173
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 61213
telemt_user_connections_current{user="hello"} 1926
telemt_user_octets_from_client{user="hello"} 2631879664 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 19714460176 (18.36 GB)
telemt_user_unique_ips_current{user="hello"} 711
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 2090.8 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57507
telemt_connections_bad_total 6346
telemt_connections_current 1615
telemt_connections_me_current 1615
telemt_handshake_timeouts_total 1274
telemt_upstream_connect_attempt_total 439
telemt_upstream_connect_success_total 439
telemt_upstream_connect_attempts_per_request{bucket="1"} 439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 186
telemt_me_reconnect_attempts_total 285
telemt_me_reconnect_success_total 285
telemt_me_reader_eof_total 269
telemt_me_idle_close_by_peer_total 269
telemt_me_route_drop_no_conn_total 19777
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48272
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 171
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 283
telemt_me_writer_restored_same_endpoint_total 269
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_user_connections_total{user="hello"} 48279
telemt_user_connections_current{user="hello"} 1615
telemt_user_octets_from_client{user="hello"} 586152760 (559.00 MB)
telemt_user_octets_to_client{user="hello"} 30276738580 (28.20 GB)
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 2144.0 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60771
telemt_connections_bad_total 3457
telemt_connections_current 1310
telemt_connections_me_current 1310
telemt_handshake_timeouts_total 749
telemt_upstream_connect_attempt_total 404
telemt_upstream_connect_success_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 254
telemt_me_reconnect_success_total 253
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 34555
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54041
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 122
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 257
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 53989
telemt_user_connections_current{user="hello"} 1310
telemt_user_octets_from_client{user="hello"} 440068508 (419.68 MB)
telemt_user_octets_to_client{user="hello"} 15057707228 (14.02 GB)
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 2087.4 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59235
telemt_connections_bad_total 2666
telemt_connections_current 1508
telemt_connections_me_current 1508
telemt_handshake_timeouts_total 1577
telemt_upstream_connect_attempt_total 376
telemt_upstream_connect_success_total 372
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 217
telemt_me_reconnect_success_total 216
telemt_me_reader_eof_total 195
telemt_me_idle_close_by_peer_total 195
telemt_me_route_drop_no_conn_total 15641
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47299
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 223
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 210
telemt_me_writer_restored_same_endpoint_total 192
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 47266
telemt_user_connections_current{user="hello"} 1508
telemt_user_octets_from_client{user="hello"} 474610360 (452.62 MB)
telemt_user_octets_to_client{user="hello"} 28881593660 (26.90 GB)
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 2098.8 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13153
telemt_connections_bad_total 3410
telemt_connections_current 418
telemt_connections_me_current 418
telemt_handshake_timeouts_total 29
telemt_upstream_connect_attempt_total 612
telemt_upstream_connect_success_total 592
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1116
telemt_me_reconnect_success_total 442
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 3759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9415
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
telemt_me_writer_removed_unexpected_total 428
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 412
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 9415
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 183234048 (174.75 MB)
telemt_user_octets_to_client{user="hello"} 4983242328 (4.64 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 2089.7 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47709
telemt_connections_bad_total 8133
telemt_connections_current 1392
telemt_connections_me_current 1392
telemt_handshake_timeouts_total 1284
telemt_upstream_connect_attempt_total 381
telemt_upstream_connect_success_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 165
telemt_me_reconnect_attempts_total 226
telemt_me_reconnect_success_total 226
telemt_me_reader_eof_total 214
telemt_me_idle_close_by_peer_total 214
telemt_me_route_drop_no_conn_total 11977
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37043
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 333
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 229
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 37048
telemt_user_connections_current{user="hello"} 1392
telemt_user_octets_from_client{user="hello"} 469737172 (447.98 MB)
telemt_user_octets_to_client{user="hello"} 26295191888 (24.49 GB)
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 138
```