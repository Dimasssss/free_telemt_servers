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

# Server Metrics 2026-03-19 05:12:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 26629.1 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383438
telemt_connections_bad_total 38811
telemt_connections_current 977
telemt_connections_me_current 977
telemt_handshake_timeouts_total 20559
telemt_upstream_connect_attempt_total 5166
telemt_upstream_connect_success_total 5081
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 5166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3767
telemt_me_reconnect_success_total 3750
telemt_me_reader_eof_total 3955
telemt_me_idle_close_by_peer_total 3954
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 99047
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280009
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1930
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 1400
telemt_desync_frames_bucket_total{bucket="1_2"} 706
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 458
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3781
telemt_me_writer_restored_same_endpoint_total 3733
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 277258
telemt_user_connections_current{user="hello"} 977
telemt_user_octets_from_client{user="hello"} 3403131384 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 91096908388 (84.84 GB)
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 26633.1 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 739664
telemt_connections_bad_total 45228
telemt_connections_current 3078
telemt_connections_me_current 3078
telemt_handshake_timeouts_total 22820
telemt_upstream_connect_attempt_total 4992
telemt_upstream_connect_success_total 4898
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 4991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_reconnect_attempts_total 3574
telemt_me_reconnect_success_total 3555
telemt_me_reader_eof_total 3754
telemt_me_idle_close_by_peer_total 3754
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 225401
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613522
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2470
telemt_desync_full_logged_total 839
telemt_desync_suppressed_total 1631
telemt_desync_frames_bucket_total{bucket="1_2"} 477
telemt_desync_frames_bucket_total{bucket="3_10"} 918
telemt_desync_frames_bucket_total{bucket="gt_10"} 1075
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3617
telemt_me_writer_restored_same_endpoint_total 3536
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 613432
telemt_user_connections_current{user="hello"} 3077
telemt_user_octets_from_client{user="hello"} 15709254884 (14.63 GB)
telemt_user_octets_to_client{user="hello"} 268872834468 (250.41 GB)
telemt_user_unique_ips_current{user="hello"} 1055
telemt_user_unique_ips_recent_window{user="hello"} 395
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 26630.3 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 628688
telemt_connections_bad_total 114446
telemt_connections_current 2305
telemt_connections_me_current 2305
telemt_handshake_timeouts_total 22547
telemt_upstream_connect_attempt_total 4890
telemt_upstream_connect_success_total 4890
telemt_upstream_connect_attempts_per_request{bucket="1"} 4890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3560
telemt_me_reconnect_success_total 3546
telemt_me_reader_eof_total 3755
telemt_me_idle_close_by_peer_total 3755
telemt_me_route_drop_no_conn_total 185491
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452923
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2361
telemt_desync_full_logged_total 769
telemt_desync_suppressed_total 1592
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 837
telemt_desync_frames_bucket_total{bucket="gt_10"} 1167
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3608
telemt_me_writer_restored_same_endpoint_total 3530
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 452904
telemt_user_connections_current{user="hello"} 2305
telemt_user_octets_from_client{user="hello"} 9533505532 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 281652733096 (262.31 GB)
telemt_user_unique_ips_current{user="hello"} 873
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 26683.6 (7h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 716262
telemt_connections_bad_total 85703
telemt_connections_current 2064
telemt_connections_me_current 2064
telemt_handshake_timeouts_total 16132
telemt_upstream_connect_attempt_total 4724
telemt_upstream_connect_success_total 4724
telemt_upstream_connect_attempts_per_request{bucket="1"} 4724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 3401
telemt_me_reconnect_success_total 3385
telemt_me_reader_eof_total 3575
telemt_me_idle_close_by_peer_total 3574
telemt_me_route_drop_no_conn_total 203036
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445933
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1399
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 897
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 587
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 3428
telemt_me_writer_restored_same_endpoint_total 3361
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 444900
telemt_user_connections_current{user="hello"} 2064
telemt_user_octets_from_client{user="hello"} 6756672180 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 171425136744 (159.65 GB)
telemt_user_unique_ips_current{user="hello"} 778
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 26626.7 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818467
telemt_connections_bad_total 225208
telemt_connections_current 2358
telemt_connections_me_current 2358
telemt_handshake_timeouts_total 22587
telemt_upstream_connect_attempt_total 4847
telemt_upstream_connect_success_total 4817
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 3495
telemt_me_reconnect_success_total 3475
telemt_me_reader_eof_total 3676
telemt_me_idle_close_by_peer_total 3676
telemt_me_route_drop_no_conn_total 200315
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 483166
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2233
telemt_desync_full_logged_total 825
telemt_desync_suppressed_total 1408
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 950
telemt_desync_frames_bucket_total{bucket="gt_10"} 771
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3511
telemt_me_writer_restored_same_endpoint_total 3451
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 483080
telemt_user_connections_current{user="hello"} 2358
telemt_user_octets_from_client{user="hello"} 14176797768 (13.20 GB)
telemt_user_octets_to_client{user="hello"} 276540607888 (257.55 GB)
telemt_user_unique_ips_current{user="hello"} 867
telemt_user_unique_ips_recent_window{user="hello"} 323
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 26638.2 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143011
telemt_connections_bad_total 10423
telemt_connections_current 483
telemt_connections_me_current 483
telemt_handshake_timeouts_total 880
telemt_upstream_connect_attempt_total 7385
telemt_upstream_connect_success_total 7187
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 7385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3743
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_reconnect_attempts_total 7692
telemt_me_reconnect_success_total 5848
telemt_me_reader_eof_total 6127
telemt_me_idle_close_by_peer_total 6127
telemt_me_route_drop_no_conn_total 57693
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125458
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 161
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5922
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5818
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 125450
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 2190016148 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 76495270352 (71.24 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 26629.2 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477240
telemt_connections_bad_total 49171
telemt_connections_current 2203
telemt_connections_me_current 2203
telemt_handshake_timeouts_total 23921
telemt_upstream_connect_attempt_total 5478
telemt_upstream_connect_success_total 5478
telemt_upstream_connect_attempts_per_request{bucket="1"} 5478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4155
telemt_me_reconnect_success_total 4143
telemt_me_reader_eof_total 4368
telemt_me_idle_close_by_peer_total 4368
telemt_me_route_drop_no_conn_total 135085
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389619
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2150
telemt_desync_full_logged_total 793
telemt_desync_suppressed_total 1357
telemt_desync_frames_bucket_total{bucket="1_2"} 449
telemt_desync_frames_bucket_total{bucket="3_10"} 818
telemt_desync_frames_bucket_total{bucket="gt_10"} 883
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4190
telemt_me_writer_restored_same_endpoint_total 4128
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 389638
telemt_user_connections_current{user="hello"} 2203
telemt_user_octets_from_client{user="hello"} 5065215948 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 230004737680 (214.21 GB)
telemt_user_unique_ips_current{user="hello"} 722
telemt_user_unique_ips_recent_window{user="hello"} 260
```