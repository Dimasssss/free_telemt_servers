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

# Server Metrics 2026-03-18 22:59:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 4238.7 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51161
telemt_connections_bad_total 5012
telemt_connections_current 631
telemt_connections_me_current 631
telemt_handshake_timeouts_total 566
telemt_upstream_connect_attempt_total 777
telemt_upstream_connect_success_total 767
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 533
telemt_me_reconnect_success_total 532
telemt_me_reader_eof_total 526
telemt_me_idle_close_by_peer_total 526
telemt_me_route_drop_no_conn_total 18844
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45742
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 207
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 524
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 42985
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 465145696 (443.60 MB)
telemt_user_octets_to_client{user="hello"} 18466229788 (17.20 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 4242.4 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119241
telemt_connections_bad_total 3261
telemt_connections_current 1676
telemt_connections_me_current 1676
telemt_handshake_timeouts_total 940
telemt_upstream_connect_attempt_total 694
telemt_upstream_connect_success_total 677
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 438
telemt_me_reconnect_success_total 436
telemt_me_reader_eof_total 443
telemt_me_idle_close_by_peer_total 443
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 41661
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108805
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 379
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 449
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 108856
telemt_user_connections_current{user="hello"} 1676
telemt_user_octets_from_client{user="hello"} 6982355144 (6.50 GB)
telemt_user_octets_to_client{user="hello"} 44574312368 (41.51 GB)
telemt_user_unique_ips_current{user="hello"} 640
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 4239.7 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100845
telemt_connections_bad_total 14698
telemt_connections_current 1360
telemt_connections_me_current 1360
telemt_handshake_timeouts_total 2678
telemt_upstream_connect_attempt_total 812
telemt_upstream_connect_success_total 812
telemt_upstream_connect_attempts_per_request{bucket="1"} 812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 379
telemt_me_reconnect_attempts_total 572
telemt_me_reconnect_success_total 571
telemt_me_reader_eof_total 574
telemt_me_idle_close_by_peer_total 574
telemt_me_route_drop_no_conn_total 34419
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80491
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 575
telemt_me_writer_restored_same_endpoint_total 555
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 80494
telemt_user_connections_current{user="hello"} 1360
telemt_user_octets_from_client{user="hello"} 975066036 (929.90 MB)
telemt_user_octets_to_client{user="hello"} 53804081272 (50.11 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 4292.8 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116250
telemt_connections_bad_total 23124
telemt_connections_current 1109
telemt_connections_me_current 1109
telemt_handshake_timeouts_total 2464
telemt_upstream_connect_attempt_total 724
telemt_upstream_connect_success_total 724
telemt_upstream_connect_attempts_per_request{bucket="1"} 724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 488
telemt_me_reconnect_success_total 486
telemt_me_reader_eof_total 489
telemt_me_idle_close_by_peer_total 489
telemt_me_route_drop_no_conn_total 48356
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85827
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 128
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 494
telemt_me_writer_restored_same_endpoint_total 462
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 85756
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 889672640 (848.46 MB)
telemt_user_octets_to_client{user="hello"} 31067752016 (28.93 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 4236.3 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106915
telemt_connections_bad_total 4725
telemt_connections_current 1383
telemt_connections_me_current 1383
telemt_handshake_timeouts_total 3326
telemt_upstream_connect_attempt_total 758
telemt_upstream_connect_success_total 752
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 511
telemt_me_reconnect_success_total 509
telemt_me_reader_eof_total 505
telemt_me_idle_close_by_peer_total 505
telemt_me_route_drop_no_conn_total 31303
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84639
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 395
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 508
telemt_me_writer_restored_same_endpoint_total 485
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 84603
telemt_user_connections_current{user="hello"} 1383
telemt_user_octets_from_client{user="hello"} 1096239336 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 51402780244 (47.87 GB)
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 4247.8 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24151
telemt_connections_bad_total 5005
telemt_connections_current 384
telemt_connections_me_current 384
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 1210
telemt_upstream_connect_success_total 1169
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 480
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 1735
telemt_me_reconnect_success_total 933
telemt_me_reader_eof_total 925
telemt_me_idle_close_by_peer_total 925
telemt_me_route_drop_no_conn_total 7674
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18507
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
telemt_me_writer_removed_unexpected_total 928
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 903
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 18507
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 241414480 (230.23 MB)
telemt_user_octets_to_client{user="hello"} 11469622852 (10.68 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 4238.6 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81990
telemt_connections_bad_total 11669
telemt_connections_current 1186
telemt_connections_me_current 1186
telemt_handshake_timeouts_total 2425
telemt_upstream_connect_attempt_total 757
telemt_upstream_connect_success_total 757
telemt_upstream_connect_attempts_per_request{bucket="1"} 757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 516
telemt_me_reconnect_success_total 516
telemt_me_reader_eof_total 521
telemt_me_idle_close_by_peer_total 521
telemt_me_route_drop_no_conn_total 23765
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66094
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 520
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 523
telemt_me_writer_restored_same_endpoint_total 501
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 66098
telemt_user_connections_current{user="hello"} 1186
telemt_user_octets_from_client{user="hello"} 737571320 (703.40 MB)
telemt_user_octets_to_client{user="hello"} 41052506340 (38.23 GB)
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 115
```