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

# Server Metrics 2026-03-18 23:04:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 4545.2 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54782
telemt_connections_bad_total 5558
telemt_connections_current 631
telemt_connections_me_current 631
telemt_handshake_timeouts_total 612
telemt_upstream_connect_attempt_total 829
telemt_upstream_connect_success_total 817
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 572
telemt_me_reconnect_success_total 571
telemt_me_reader_eof_total 566
telemt_me_idle_close_by_peer_total 566
telemt_me_route_drop_no_conn_total 19944
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48664
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 231
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_restored_same_endpoint_total 561
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 45907
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 486237376 (463.71 MB)
telemt_user_octets_to_client{user="hello"} 19316295600 (17.99 GB)
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 4549.0 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126625
telemt_connections_bad_total 3510
telemt_connections_current 1730
telemt_connections_me_current 1730
telemt_handshake_timeouts_total 1012
telemt_upstream_connect_attempt_total 738
telemt_upstream_connect_success_total 722
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 469
telemt_me_reconnect_success_total 468
telemt_me_reader_eof_total 474
telemt_me_idle_close_by_peer_total 474
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 43576
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115423
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 421
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 277
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 480
telemt_me_writer_restored_same_endpoint_total 457
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 115484
telemt_user_connections_current{user="hello"} 1730
telemt_user_octets_from_client{user="hello"} 8185723492 (7.62 GB)
telemt_user_octets_to_client{user="hello"} 46466953592 (43.28 GB)
telemt_user_unique_ips_current{user="hello"} 666
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 4546.3 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106121
telemt_connections_bad_total 15511
telemt_connections_current 1242
telemt_connections_me_current 1242
telemt_handshake_timeouts_total 2847
telemt_upstream_connect_attempt_total 856
telemt_upstream_connect_success_total 856
telemt_upstream_connect_attempts_per_request{bucket="1"} 856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 395
telemt_me_reconnect_attempts_total 597
telemt_me_reconnect_success_total 596
telemt_me_reader_eof_total 601
telemt_me_idle_close_by_peer_total 601
telemt_me_route_drop_no_conn_total 36318
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84672
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 344
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 205
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 602
telemt_me_writer_restored_same_endpoint_total 580
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 84675
telemt_user_connections_current{user="hello"} 1242
telemt_user_octets_from_client{user="hello"} 1250869616 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 56315202300 (52.45 GB)
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 4599.6 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121692
telemt_connections_bad_total 23196
telemt_connections_current 1096
telemt_connections_me_current 1096
telemt_handshake_timeouts_total 2698
telemt_upstream_connect_attempt_total 783
telemt_upstream_connect_success_total 783
telemt_upstream_connect_attempts_per_request{bucket="1"} 783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 504
telemt_me_reconnect_success_total 502
telemt_me_reader_eof_total 507
telemt_me_idle_close_by_peer_total 507
telemt_me_route_drop_no_conn_total 49875
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90322
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 207
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 512
telemt_me_writer_restored_same_endpoint_total 478
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 90251
telemt_user_connections_current{user="hello"} 1096
telemt_user_octets_from_client{user="hello"} 916532448 (874.07 MB)
telemt_user_octets_to_client{user="hello"} 32201808724 (29.99 GB)
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 4543.0 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113725
telemt_connections_bad_total 5084
telemt_connections_current 1401
telemt_connections_me_current 1401
telemt_handshake_timeouts_total 3524
telemt_upstream_connect_attempt_total 799
telemt_upstream_connect_success_total 793
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 538
telemt_me_reconnect_success_total 536
telemt_me_reader_eof_total 534
telemt_me_idle_close_by_peer_total 534
telemt_me_route_drop_no_conn_total 34132
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90088
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 406
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 537
telemt_me_writer_restored_same_endpoint_total 512
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 90052
telemt_user_connections_current{user="hello"} 1401
telemt_user_octets_from_client{user="hello"} 1185443940 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 54080613868 (50.37 GB)
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 4554.5 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25487
telemt_connections_bad_total 5014
telemt_connections_current 348
telemt_connections_me_current 348
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 1297
telemt_upstream_connect_success_total 1256
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 522
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 1805
telemt_me_reconnect_success_total 1003
telemt_me_reader_eof_total 997
telemt_me_idle_close_by_peer_total 997
telemt_me_route_drop_no_conn_total 8194
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19808
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
telemt_me_writer_removed_unexpected_total 1000
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 973
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 19808
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 252763960 (241.05 MB)
telemt_user_octets_to_client{user="hello"} 12705134580 (11.83 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 4545.2 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86354
telemt_connections_bad_total 11958
telemt_connections_current 1172
telemt_connections_me_current 1172
telemt_handshake_timeouts_total 2597
telemt_upstream_connect_attempt_total 795
telemt_upstream_connect_success_total 795
telemt_upstream_connect_attempts_per_request{bucket="1"} 795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 536
telemt_me_reconnect_success_total 535
telemt_me_reader_eof_total 542
telemt_me_idle_close_by_peer_total 542
telemt_me_route_drop_no_conn_total 25224
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69895
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 537
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 544
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 69903
telemt_user_connections_current{user="hello"} 1172
telemt_user_octets_from_client{user="hello"} 761306080 (726.04 MB)
telemt_user_octets_to_client{user="hello"} 42680061076 (39.75 GB)
telemt_user_unique_ips_current{user="hello"} 497
telemt_user_unique_ips_recent_window{user="hello"} 114
```