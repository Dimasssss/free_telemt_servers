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

# Server Metrics 2026-03-18 09:56:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 4522.7 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175946
telemt_connections_bad_total 1020
telemt_handshake_timeouts_total 3329
telemt_upstream_connect_attempt_total 63846
telemt_upstream_connect_success_total 62931
telemt_upstream_connect_fail_total 915
telemt_upstream_connect_attempts_per_request{bucket="1"} 63846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 915
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 506260
telemt_me_reconnect_success_total 742
telemt_me_reader_eof_total 649
telemt_me_idle_close_by_peer_total 647
telemt_me_route_drop_no_conn_total 34903
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89736
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 498
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 350
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 690
telemt_me_refill_failed_total 16481
telemt_me_writer_restored_same_endpoint_total 637
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 151596
telemt_user_connections_current{user="hello"} 1503
telemt_user_octets_from_client{user="hello"} 1780843244 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 33703552449 (31.39 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 4553.6 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396677
telemt_connections_bad_total 41017
telemt_handshake_timeouts_total 10052
telemt_upstream_connect_attempt_total 745
telemt_upstream_connect_success_total 745
telemt_upstream_connect_attempts_per_request{bucket="1"} 745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 481
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 439
telemt_me_idle_close_by_peer_total 439
telemt_me_route_drop_no_conn_total 139154
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320269
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1556
telemt_desync_full_logged_total 404
telemt_desync_suppressed_total 1152
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 645
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 448
telemt_me_writer_restored_same_endpoint_total 469
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 319455
telemt_user_connections_current{user="hello"} 3833
telemt_user_octets_from_client{user="hello"} 7891231264 (7.35 GB)
telemt_user_octets_to_client{user="hello"} 117899589192 (109.80 GB)
telemt_user_unique_ips_current{user="hello"} 1105
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 4468.6 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325995
telemt_connections_bad_total 17874
telemt_handshake_timeouts_total 8216
telemt_upstream_connect_attempt_total 9085
telemt_upstream_connect_success_total 9085
telemt_upstream_connect_attempts_per_request{bucket="1"} 9085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606304
telemt_me_reconnect_success_total 632
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 599
telemt_me_route_drop_no_conn_total 163099
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238385
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 577
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 380
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 625
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 597
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 246417
telemt_user_connections_current{user="hello"} 2526
telemt_user_octets_from_client{user="hello"} 2432689555 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 86766274408 (80.81 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 770
telemt_user_unique_ips_recent_window{user="hello"} 377
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 4499.0 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659130
telemt_connections_bad_total 7511
telemt_handshake_timeouts_total 71687
telemt_upstream_connect_attempt_total 11503
telemt_upstream_connect_success_total 11402
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 11503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1021
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2813230
telemt_me_reconnect_success_total 873
telemt_me_reader_eof_total 922
telemt_me_idle_close_by_peer_total 922
telemt_me_route_drop_no_conn_total 1313419
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 515762
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 673
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 475
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_me_writer_removed_unexpected_total 946
telemt_me_refill_failed_total 99624
telemt_me_writer_restored_same_endpoint_total 778
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 534734
telemt_user_connections_current{user="hello"} 2793
telemt_user_octets_from_client{user="hello"} 3406293038 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 58219637729 (54.22 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 798
telemt_user_unique_ips_recent_window{user="hello"} 410
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 4393.5 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309008
telemt_connections_bad_total 9559
telemt_handshake_timeouts_total 4347
telemt_upstream_connect_attempt_total 10414
telemt_upstream_connect_success_total 10413
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982612
telemt_me_reconnect_success_total 664
telemt_me_reader_eof_total 606
telemt_me_idle_close_by_peer_total 606
telemt_me_route_drop_no_conn_total 111745
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248608
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 767
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 491
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 613
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 549
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 257980
telemt_user_connections_current{user="hello"} 3216
telemt_user_octets_from_client{user="hello"} 4741842589 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 101674223401 (94.69 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 451
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 4278.3 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86214
telemt_connections_bad_total 11352
telemt_handshake_timeouts_total 435
telemt_upstream_connect_attempt_total 728
telemt_upstream_connect_success_total 728
telemt_upstream_connect_attempts_per_request{bucket="1"} 728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 332
telemt_me_reconnect_attempts_total 475
telemt_me_reconnect_success_total 473
telemt_me_reader_eof_total 458
telemt_me_idle_close_by_peer_total 458
telemt_me_route_drop_no_conn_total 31078
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71270
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 465
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 68885
telemt_user_connections_current{user="hello"} 905
telemt_user_octets_from_client{user="hello"} 1322510760 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 15678019172 (14.60 GB)
telemt_user_unique_ips_current{user="hello"} 333
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 4349.4 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218806
telemt_connections_bad_total 5758
telemt_handshake_timeouts_total 3888
telemt_upstream_connect_attempt_total 739
telemt_upstream_connect_success_total 722
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 476
telemt_me_reconnect_success_total 466
telemt_me_reader_eof_total 438
telemt_me_idle_close_by_peer_total 438
telemt_me_route_drop_no_conn_total 131498
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192942
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 611
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 404
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 455
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 192801
telemt_user_connections_current{user="hello"} 2372
telemt_user_octets_from_client{user="hello"} 2862907964 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 90134622416 (83.94 GB)
telemt_user_unique_ips_current{user="hello"} 681
telemt_user_unique_ips_recent_window{user="hello"} 309
```