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

# Server Metrics 2026-03-18 22:28:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 2397.2 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28510
telemt_connections_bad_total 2135
telemt_connections_current 692
telemt_connections_me_current 692
telemt_handshake_timeouts_total 291
telemt_upstream_connect_attempt_total 410
telemt_upstream_connect_success_total 404
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 256
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 229
telemt_me_idle_close_by_peer_total 229
telemt_me_route_drop_no_conn_total 8110
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24891
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 102
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 245
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 24403
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 261898160 (249.77 MB)
telemt_user_octets_to_client{user="hello"} 11176987908 (10.41 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 2400.7 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73998
telemt_connections_bad_total 1722
telemt_connections_current 1864
telemt_connections_me_current 1864
telemt_handshake_timeouts_total 601
telemt_upstream_connect_attempt_total 377
telemt_upstream_connect_success_total 370
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 217
telemt_me_reconnect_success_total 216
telemt_me_reader_eof_total 208
telemt_me_idle_close_by_peer_total 208
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 28004
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68215
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 203
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 225
telemt_me_writer_restored_same_endpoint_total 206
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 68214
telemt_user_connections_current{user="hello"} 1864
telemt_user_octets_from_client{user="hello"} 3092939684 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 24201621088 (22.54 GB)
telemt_user_unique_ips_current{user="hello"} 687
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 2398.0 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64562
telemt_connections_bad_total 7810
telemt_connections_current 1572
telemt_connections_me_current 1572
telemt_handshake_timeouts_total 1565
telemt_upstream_connect_attempt_total 475
telemt_upstream_connect_success_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 205
telemt_me_reconnect_attempts_total 321
telemt_me_reconnect_success_total 321
telemt_me_reader_eof_total 305
telemt_me_idle_close_by_peer_total 305
telemt_me_route_drop_no_conn_total 22459
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53420
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 197
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 319
telemt_me_writer_restored_same_endpoint_total 305
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_user_connections_total{user="hello"} 53427
telemt_user_connections_current{user="hello"} 1572
telemt_user_octets_from_client{user="hello"} 695473680 (663.26 MB)
telemt_user_octets_to_client{user="hello"} 34064577216 (31.73 GB)
telemt_user_unique_ips_current{user="hello"} 599
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 2451.2 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66671
telemt_connections_bad_total 3654
telemt_connections_current 1360
telemt_connections_me_current 1360
telemt_handshake_timeouts_total 886
telemt_upstream_connect_attempt_total 434
telemt_upstream_connect_success_total 434
telemt_upstream_connect_attempts_per_request{bucket="1"} 434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 284
telemt_me_reconnect_success_total 283
telemt_me_reader_eof_total 271
telemt_me_idle_close_by_peer_total 271
telemt_me_route_drop_no_conn_total 36427
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58847
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 132
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 287
telemt_me_writer_restored_same_endpoint_total 259
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 58785
telemt_user_connections_current{user="hello"} 1360
telemt_user_octets_from_client{user="hello"} 525162444 (500.83 MB)
telemt_user_octets_to_client{user="hello"} 18222001608 (16.97 GB)
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 2394.8 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66013
telemt_connections_bad_total 2987
telemt_connections_current 1505
telemt_connections_me_current 1505
telemt_handshake_timeouts_total 1856
telemt_upstream_connect_attempt_total 419
telemt_upstream_connect_success_total 415
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 260
telemt_me_reconnect_success_total 259
telemt_me_reader_eof_total 238
telemt_me_idle_close_by_peer_total 238
telemt_me_route_drop_no_conn_total 18201
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52613
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 245
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 253
telemt_me_writer_restored_same_endpoint_total 235
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 52577
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 543707308 (518.52 MB)
telemt_user_octets_to_client{user="hello"} 31678140092 (29.50 GB)
telemt_user_unique_ips_current{user="hello"} 628
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 2406.1 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15053
telemt_connections_bad_total 3773
telemt_connections_current 394
telemt_connections_me_current 394
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 701
telemt_upstream_connect_success_total 681
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1205
telemt_me_reconnect_success_total 531
telemt_me_reader_eof_total 495
telemt_me_idle_close_by_peer_total 495
telemt_me_route_drop_no_conn_total 4331
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10870
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
telemt_me_writer_removed_unexpected_total 517
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 501
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 10870
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 193220040 (184.27 MB)
telemt_user_octets_to_client{user="hello"} 6128183348 (5.71 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 2397.0 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53517
telemt_connections_bad_total 9329
telemt_connections_current 1371
telemt_connections_me_current 1371
telemt_handshake_timeouts_total 1416
telemt_upstream_connect_attempt_total 420
telemt_upstream_connect_success_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 180
telemt_me_reconnect_attempts_total 265
telemt_me_reconnect_success_total 265
telemt_me_reader_eof_total 253
telemt_me_idle_close_by_peer_total 253
telemt_me_route_drop_no_conn_total 13762
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41383
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 368
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 239
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 268
telemt_me_writer_restored_same_endpoint_total 250
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 41388
telemt_user_connections_current{user="hello"} 1371
telemt_user_octets_from_client{user="hello"} 515899608 (492.00 MB)
telemt_user_octets_to_client{user="hello"} 28608443940 (26.64 GB)
telemt_user_unique_ips_current{user="hello"} 543
telemt_user_unique_ips_recent_window{user="hello"} 140
```