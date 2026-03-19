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

# Server Metrics 2026-03-19 02:59:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 18656.9 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229017
telemt_connections_bad_total 27373
telemt_connections_current 747
telemt_connections_me_current 747
telemt_handshake_timeouts_total 14117
telemt_upstream_connect_attempt_total 3703
telemt_upstream_connect_success_total 3644
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 3703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2721
telemt_me_reconnect_success_total 2707
telemt_me_reader_eof_total 2836
telemt_me_idle_close_by_peer_total 2836
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 61982
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177179
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1215
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 894
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2723
telemt_me_writer_restored_same_endpoint_total 2692
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 174407
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 1862538268 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 54561167448 (50.81 GB)
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 18660.8 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408779
telemt_connections_bad_total 24770
telemt_connections_current 1716
telemt_connections_me_current 1716
telemt_handshake_timeouts_total 9898
telemt_upstream_connect_attempt_total 3611
telemt_upstream_connect_success_total 3548
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 3611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 2614
telemt_me_reconnect_success_total 2603
telemt_me_reader_eof_total 2738
telemt_me_idle_close_by_peer_total 2738
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 125403
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348058
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1253
telemt_desync_full_logged_total 431
telemt_desync_suppressed_total 822
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 480
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2642
telemt_me_writer_restored_same_endpoint_total 2588
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 348031
telemt_user_connections_current{user="hello"} 1716
telemt_user_octets_from_client{user="hello"} 12120140608 (11.29 GB)
telemt_user_octets_to_client{user="hello"} 137502101172 (128.06 GB)
telemt_user_unique_ips_current{user="hello"} 676
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 18658.0 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344979
telemt_connections_bad_total 75528
telemt_connections_current 1341
telemt_connections_me_current 1341
telemt_handshake_timeouts_total 8123
telemt_upstream_connect_attempt_total 3557
telemt_upstream_connect_success_total 3557
telemt_upstream_connect_attempts_per_request{bucket="1"} 3557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2624
telemt_me_reconnect_success_total 2614
telemt_me_reader_eof_total 2761
telemt_me_idle_close_by_peer_total 2761
telemt_me_route_drop_no_conn_total 98626
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251486
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1272
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 794
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 516
telemt_desync_frames_bucket_total{bucket="gt_10"} 539
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2654
telemt_me_writer_restored_same_endpoint_total 2598
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 251481
telemt_user_connections_current{user="hello"} 1341
telemt_user_octets_from_client{user="hello"} 5144664164 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 150093602200 (139.79 GB)
telemt_user_unique_ips_current{user="hello"} 541
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 18711.2 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398950
telemt_connections_bad_total 36296
telemt_connections_current 1075
telemt_connections_me_current 1075
telemt_handshake_timeouts_total 6397
telemt_upstream_connect_attempt_total 3431
telemt_upstream_connect_success_total 3431
telemt_upstream_connect_attempts_per_request{bucket="1"} 3431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2501
telemt_me_reconnect_success_total 2490
telemt_me_reader_eof_total 2620
telemt_me_idle_close_by_peer_total 2619
telemt_me_route_drop_no_conn_total 109496
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252136
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 640
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2518
telemt_me_writer_restored_same_endpoint_total 2466
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 252044
telemt_user_connections_current{user="hello"} 1075
telemt_user_octets_from_client{user="hello"} 2227869644 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 86067879828 (80.16 GB)
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 18654.8 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359103
telemt_connections_bad_total 23203
telemt_connections_current 1305
telemt_connections_me_current 1305
telemt_handshake_timeouts_total 12852
telemt_upstream_connect_attempt_total 3522
telemt_upstream_connect_success_total 3503
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 2572
telemt_me_reconnect_success_total 2558
telemt_me_reader_eof_total 2700
telemt_me_idle_close_by_peer_total 2700
telemt_me_route_drop_no_conn_total 107822
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273009
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1207
telemt_desync_full_logged_total 458
telemt_desync_suppressed_total 749
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2574
telemt_me_writer_restored_same_endpoint_total 2534
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 272929
telemt_user_connections_current{user="hello"} 1305
telemt_user_octets_from_client{user="hello"} 9139076372 (8.51 GB)
telemt_user_octets_to_client{user="hello"} 153584399996 (143.04 GB)
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 18666.1 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87661
telemt_connections_bad_total 9363
telemt_connections_current 349
telemt_connections_me_current 349
telemt_handshake_timeouts_total 387
telemt_upstream_connect_attempt_total 5390
telemt_upstream_connect_success_total 5237
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 5390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2733
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_reconnect_attempts_total 6135
telemt_me_reconnect_success_total 4300
telemt_me_reader_eof_total 4507
telemt_me_idle_close_by_peer_total 4507
telemt_me_route_drop_no_conn_total 35261
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75062
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 34
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 4362
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4270
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 75060
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 1599083108 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 53959946184 (50.25 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 18657.0 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252593
telemt_connections_bad_total 25326
telemt_connections_current 1122
telemt_connections_me_current 1122
telemt_handshake_timeouts_total 12652
telemt_upstream_connect_attempt_total 3988
telemt_upstream_connect_success_total 3988
telemt_upstream_connect_attempts_per_request{bucket="1"} 3988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3058
telemt_me_reconnect_success_total 3049
telemt_me_reader_eof_total 3212
telemt_me_idle_close_by_peer_total 3212
telemt_me_route_drop_no_conn_total 73570
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208113
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1110
telemt_desync_full_logged_total 432
telemt_desync_suppressed_total 678
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 458
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3084
telemt_me_writer_restored_same_endpoint_total 3034
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 208140
telemt_user_connections_current{user="hello"} 1122
telemt_user_octets_from_client{user="hello"} 2175916632 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 109502968676 (101.98 GB)
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 114
```