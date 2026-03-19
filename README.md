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

# Server Metrics 2026-03-19 05:27:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 27548.4 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402001
telemt_connections_bad_total 40351
telemt_connections_current 1021
telemt_connections_me_current 1021
telemt_handshake_timeouts_total 21151
telemt_upstream_connect_attempt_total 5306
telemt_upstream_connect_success_total 5217
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 5306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3860
telemt_me_reconnect_success_total 3842
telemt_me_reader_eof_total 4053
telemt_me_idle_close_by_peer_total 4052
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 105424
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294828
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1979
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 1431
telemt_desync_frames_bucket_total{bucket="1_2"} 715
telemt_desync_frames_bucket_total{bucket="3_10"} 784
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3873
telemt_me_writer_restored_same_endpoint_total 3825
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 292081
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 3706687640 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 97989599300 (91.26 GB)
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 27552.4 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 792262
telemt_connections_bad_total 47268
telemt_connections_current 2966
telemt_connections_me_current 2966
telemt_handshake_timeouts_total 23641
telemt_upstream_connect_attempt_total 5119
telemt_upstream_connect_success_total 5025
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 5119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 3657
telemt_me_reconnect_success_total 3637
telemt_me_reader_eof_total 3843
telemt_me_idle_close_by_peer_total 3843
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 241121
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657020
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2642
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 1746
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 1148
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3702
telemt_me_writer_restored_same_endpoint_total 3618
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 656911
telemt_user_connections_current{user="hello"} 2966
telemt_user_octets_from_client{user="hello"} 16122565812 (15.02 GB)
telemt_user_octets_to_client{user="hello"} 287646304396 (267.89 GB)
telemt_user_unique_ips_current{user="hello"} 1078
telemt_user_unique_ips_recent_window{user="hello"} 413
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 27549.7 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 677896
telemt_connections_bad_total 118218
telemt_connections_current 2336
telemt_connections_me_current 2336
telemt_handshake_timeouts_total 23716
telemt_upstream_connect_attempt_total 5015
telemt_upstream_connect_success_total 5015
telemt_upstream_connect_attempts_per_request{bucket="1"} 5015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3642
telemt_me_reconnect_success_total 3628
telemt_me_reader_eof_total 3843
telemt_me_idle_close_by_peer_total 3843
telemt_me_route_drop_no_conn_total 201518
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 488410
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2565
telemt_desync_full_logged_total 830
telemt_desync_suppressed_total 1735
telemt_desync_frames_bucket_total{bucket="1_2"} 407
telemt_desync_frames_bucket_total{bucket="3_10"} 912
telemt_desync_frames_bucket_total{bucket="gt_10"} 1246
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 3691
telemt_me_writer_restored_same_endpoint_total 3612
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 488395
telemt_user_connections_current{user="hello"} 2336
telemt_user_octets_from_client{user="hello"} 9963543152 (9.28 GB)
telemt_user_octets_to_client{user="hello"} 299153030596 (278.61 GB)
telemt_user_unique_ips_current{user="hello"} 841
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 27602.9 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758857
telemt_connections_bad_total 86402
telemt_connections_current 2059
telemt_connections_me_current 2059
telemt_handshake_timeouts_total 17922
telemt_upstream_connect_attempt_total 4844
telemt_upstream_connect_success_total 4844
telemt_upstream_connect_attempts_per_request{bucket="1"} 4844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 3478
telemt_me_reconnect_success_total 3460
telemt_me_reader_eof_total 3656
telemt_me_idle_close_by_peer_total 3655
telemt_me_route_drop_no_conn_total 217956
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482749
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1524
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 971
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3506
telemt_me_writer_restored_same_endpoint_total 3436
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 481672
telemt_user_connections_current{user="hello"} 2059
telemt_user_octets_from_client{user="hello"} 7319363300 (6.82 GB)
telemt_user_octets_to_client{user="hello"} 184515625592 (171.84 GB)
telemt_user_unique_ips_current{user="hello"} 754
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 27546.3 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 876623
telemt_connections_bad_total 240154
telemt_connections_current 2253
telemt_connections_me_current 2253
telemt_handshake_timeouts_total 24392
telemt_upstream_connect_attempt_total 4974
telemt_upstream_connect_success_total 4944
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 3579
telemt_me_reconnect_success_total 3558
telemt_me_reader_eof_total 3764
telemt_me_idle_close_by_peer_total 3764
telemt_me_route_drop_no_conn_total 213644
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 519643
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2459
telemt_desync_full_logged_total 884
telemt_desync_suppressed_total 1575
telemt_desync_frames_bucket_total{bucket="1_2"} 596
telemt_desync_frames_bucket_total{bucket="3_10"} 1039
telemt_desync_frames_bucket_total{bucket="gt_10"} 824
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 3595
telemt_me_writer_restored_same_endpoint_total 3534
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 519561
telemt_user_connections_current{user="hello"} 2253
telemt_user_octets_from_client{user="hello"} 14622585356 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 292530418324 (272.44 GB)
telemt_user_unique_ips_current{user="hello"} 883
telemt_user_unique_ips_recent_window{user="hello"} 337
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 27557.8 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152368
telemt_connections_bad_total 10574
telemt_connections_current 513
telemt_connections_me_current 513
telemt_handshake_timeouts_total 1120
telemt_upstream_connect_attempt_total 7654
telemt_upstream_connect_success_total 7447
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 7654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3861
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 9188
telemt_me_reconnect_success_total 6064
telemt_me_reader_eof_total 6385
telemt_me_idle_close_by_peer_total 6385
telemt_me_route_drop_no_conn_total 61152
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133376
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 186
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6180
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 6034
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 133369
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 2282520588 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 79467398760 (74.01 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 27548.7 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515661
telemt_connections_bad_total 50281
telemt_connections_current 2268
telemt_connections_me_current 2268
telemt_handshake_timeouts_total 24982
telemt_upstream_connect_attempt_total 5659
telemt_upstream_connect_success_total 5659
telemt_upstream_connect_attempts_per_request{bucket="1"} 5659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4293
telemt_me_reconnect_success_total 4281
telemt_me_reader_eof_total 4519
telemt_me_idle_close_by_peer_total 4519
telemt_me_route_drop_no_conn_total 147004
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423958
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2328
telemt_desync_full_logged_total 858
telemt_desync_suppressed_total 1470
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 895
telemt_desync_frames_bucket_total{bucket="gt_10"} 948
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4330
telemt_me_writer_restored_same_endpoint_total 4266
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 424002
telemt_user_connections_current{user="hello"} 2268
telemt_user_octets_from_client{user="hello"} 5420324728 (5.05 GB)
telemt_user_octets_to_client{user="hello"} 247930849692 (230.90 GB)
telemt_user_unique_ips_current{user="hello"} 751
telemt_user_unique_ips_recent_window{user="hello"} 270
```