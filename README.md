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

# Server Metrics 2026-03-18 22:43:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 3318.3 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40169
telemt_connections_bad_total 3680
telemt_connections_current 699
telemt_connections_me_current 699
telemt_handshake_timeouts_total 407
telemt_upstream_connect_attempt_total 588
telemt_upstream_connect_success_total 580
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 389
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 15769
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36584
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 380
telemt_me_writer_restored_same_endpoint_total 378
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 33831
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 397221648 (378.82 MB)
telemt_user_octets_to_client{user="hello"} 15943278324 (14.85 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 3321.3 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97971
telemt_connections_bad_total 2633
telemt_connections_current 1854
telemt_connections_me_current 1854
telemt_handshake_timeouts_total 766
telemt_upstream_connect_attempt_total 538
telemt_upstream_connect_success_total 527
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 330
telemt_me_reconnect_success_total 329
telemt_me_reader_eof_total 327
telemt_me_idle_close_by_peer_total 327
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 34998
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89331
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 316
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 209
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 338
telemt_me_writer_restored_same_endpoint_total 319
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 89349
telemt_user_connections_current{user="hello"} 1854
telemt_user_octets_from_client{user="hello"} 5042255716 (4.70 GB)
telemt_user_octets_to_client{user="hello"} 37214069108 (34.66 GB)
telemt_user_unique_ips_current{user="hello"} 675
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 3318.6 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83176
telemt_connections_bad_total 11735
telemt_connections_current 1346
telemt_connections_me_current 1346
telemt_handshake_timeouts_total 2189
telemt_upstream_connect_attempt_total 643
telemt_upstream_connect_success_total 643
telemt_upstream_connect_attempts_per_request{bucket="1"} 643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 292
telemt_me_reconnect_attempts_total 446
telemt_me_reconnect_success_total 446
telemt_me_reader_eof_total 439
telemt_me_idle_close_by_peer_total 439
telemt_me_route_drop_no_conn_total 29453
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66997
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 247
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 105
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 448
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 67001
telemt_user_connections_current{user="hello"} 1346
telemt_user_octets_from_client{user="hello"} 842914640 (803.87 MB)
telemt_user_octets_to_client{user="hello"} 43485734824 (40.50 GB)
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 3371.8 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90758
telemt_connections_bad_total 12172
telemt_connections_current 1150
telemt_connections_me_current 1150
telemt_handshake_timeouts_total 1706
telemt_upstream_connect_attempt_total 587
telemt_upstream_connect_success_total 587
telemt_upstream_connect_attempts_per_request{bucket="1"} 587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 394
telemt_me_reconnect_success_total 392
telemt_me_reader_eof_total 390
telemt_me_idle_close_by_peer_total 390
telemt_me_route_drop_no_conn_total 43238
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72668
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 145
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 399
telemt_me_writer_restored_same_endpoint_total 368
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 72598
telemt_user_connections_current{user="hello"} 1150
telemt_user_octets_from_client{user="hello"} 814654192 (776.91 MB)
telemt_user_octets_to_client{user="hello"} 26785823244 (24.95 GB)
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 3315.3 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86796
telemt_connections_bad_total 3800
telemt_connections_current 1405
telemt_connections_me_current 1405
telemt_handshake_timeouts_total 2622
telemt_upstream_connect_attempt_total 590
telemt_upstream_connect_success_total 584
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 386
telemt_me_reconnect_success_total 384
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 25202
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68563
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 382
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 68527
telemt_user_connections_current{user="hello"} 1405
telemt_user_octets_from_client{user="hello"} 807911796 (770.48 MB)
telemt_user_octets_to_client{user="hello"} 42515003804 (39.60 GB)
telemt_user_unique_ips_current{user="hello"} 605
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 3326.8 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20214
telemt_connections_bad_total 4728
telemt_connections_current 370
telemt_connections_me_current 370
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 925
telemt_upstream_connect_success_total 894
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 1503
telemt_me_reconnect_success_total 701
telemt_me_reader_eof_total 693
telemt_me_idle_close_by_peer_total 693
telemt_me_route_drop_no_conn_total 6181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14964
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
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 696
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 671
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 14964
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 218034060 (207.93 MB)
telemt_user_octets_to_client{user="hello"} 8643671152 (8.05 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 3317.6 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68850
telemt_connections_bad_total 10763
telemt_connections_current 1265
telemt_connections_me_current 1265
telemt_handshake_timeouts_total 1903
telemt_upstream_connect_attempt_total 587
telemt_upstream_connect_success_total 587
telemt_upstream_connect_attempts_per_request{bucket="1"} 587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 269
telemt_me_reconnect_attempts_total 389
telemt_me_reconnect_success_total 389
telemt_me_reader_eof_total 387
telemt_me_idle_close_by_peer_total 387
telemt_me_route_drop_no_conn_total 19308
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54578
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 394
telemt_me_writer_restored_same_endpoint_total 374
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 54583
telemt_user_connections_current{user="hello"} 1265
telemt_user_octets_from_client{user="hello"} 652219844 (622.01 MB)
telemt_user_octets_to_client{user="hello"} 34325938184 (31.97 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 127
```