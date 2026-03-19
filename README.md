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

# Server Metrics 2026-03-19 05:53:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 29081.7 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434103
telemt_connections_bad_total 42089
telemt_connections_current 1200
telemt_connections_me_current 1200
telemt_handshake_timeouts_total 21739
telemt_upstream_connect_attempt_total 5632
telemt_upstream_connect_success_total 5533
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 5632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4087
telemt_me_reconnect_success_total 4066
telemt_me_reader_eof_total 4283
telemt_me_idle_close_by_peer_total 4282
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 114091
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322381
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2115
telemt_desync_full_logged_total 594
telemt_desync_suppressed_total 1521
telemt_desync_frames_bucket_total{bucket="1_2"} 750
telemt_desync_frames_bucket_total{bucket="3_10"} 832
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4103
telemt_me_writer_restored_same_endpoint_total 4049
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 319633
telemt_user_connections_current{user="hello"} 1200
telemt_user_octets_from_client{user="hello"} 3992473252 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 109009498768 (101.52 GB)
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 29085.9 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 898254
telemt_connections_bad_total 53937
telemt_connections_current 3052
telemt_connections_me_current 3052
telemt_handshake_timeouts_total 25685
telemt_upstream_connect_attempt_total 5482
telemt_upstream_connect_success_total 5381
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 5482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 3922
telemt_me_reconnect_success_total 3899
telemt_me_reader_eof_total 4108
telemt_me_idle_close_by_peer_total 4108
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 277116
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738706
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2987
telemt_desync_full_logged_total 1028
telemt_desync_suppressed_total 1959
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 1117
telemt_desync_frames_bucket_total{bucket="gt_10"} 1309
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3967
telemt_me_writer_restored_same_endpoint_total 3880
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 738581
telemt_user_connections_current{user="hello"} 3052
telemt_user_octets_from_client{user="hello"} 17144989656 (15.97 GB)
telemt_user_octets_to_client{user="hello"} 325182444860 (302.85 GB)
telemt_user_unique_ips_current{user="hello"} 1132
telemt_user_unique_ips_recent_window{user="hello"} 414
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 29082.6 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759677
telemt_connections_bad_total 128338
telemt_connections_current 2540
telemt_connections_me_current 2540
telemt_handshake_timeouts_total 25534
telemt_upstream_connect_attempt_total 5273
telemt_upstream_connect_success_total 5273
telemt_upstream_connect_attempts_per_request{bucket="1"} 5273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3813
telemt_me_reconnect_success_total 3796
telemt_me_reader_eof_total 4023
telemt_me_idle_close_by_peer_total 4023
telemt_me_route_drop_no_conn_total 230731
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 551247
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2842
telemt_desync_full_logged_total 927
telemt_desync_suppressed_total 1915
telemt_desync_frames_bucket_total{bucket="1_2"} 502
telemt_desync_frames_bucket_total{bucket="3_10"} 999
telemt_desync_frames_bucket_total{bucket="gt_10"} 1341
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3868
telemt_me_writer_restored_same_endpoint_total 3780
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 551131
telemt_user_connections_current{user="hello"} 2540
telemt_user_octets_from_client{user="hello"} 10739626764 (10.00 GB)
telemt_user_octets_to_client{user="hello"} 327754608180 (305.25 GB)
telemt_user_unique_ips_current{user="hello"} 898
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 29136.1 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 839431
telemt_connections_bad_total 87408
telemt_connections_current 2264
telemt_connections_me_current 2264
telemt_handshake_timeouts_total 20136
telemt_upstream_connect_attempt_total 5168
telemt_upstream_connect_success_total 5168
telemt_upstream_connect_attempts_per_request{bucket="1"} 5168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 3712
telemt_me_reconnect_success_total 3690
telemt_me_reader_eof_total 3892
telemt_me_idle_close_by_peer_total 3891
telemt_me_route_drop_no_conn_total 246433
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545210
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1911
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 1217
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 780
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3743
telemt_me_writer_restored_same_endpoint_total 3666
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 544130
telemt_user_connections_current{user="hello"} 2264
telemt_user_octets_from_client{user="hello"} 8067146536 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 209667287592 (195.27 GB)
telemt_user_unique_ips_current{user="hello"} 824
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 29079.4 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1003182
telemt_connections_bad_total 289847
telemt_connections_current 2635
telemt_connections_me_current 2635
telemt_handshake_timeouts_total 26481
telemt_upstream_connect_attempt_total 5212
telemt_upstream_connect_success_total 5181
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 3729
telemt_me_reconnect_success_total 3706
telemt_me_reader_eof_total 3925
telemt_me_idle_close_by_peer_total 3925
telemt_me_route_drop_no_conn_total 239922
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585046
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2829
telemt_desync_full_logged_total 979
telemt_desync_suppressed_total 1850
telemt_desync_frames_bucket_total{bucket="1_2"} 690
telemt_desync_frames_bucket_total{bucket="3_10"} 1216
telemt_desync_frames_bucket_total{bucket="gt_10"} 923
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 3747
telemt_me_writer_restored_same_endpoint_total 3682
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 584957
telemt_user_connections_current{user="hello"} 2635
telemt_user_octets_from_client{user="hello"} 15554835836 (14.49 GB)
telemt_user_octets_to_client{user="hello"} 321140741728 (299.09 GB)
telemt_user_unique_ips_current{user="hello"} 958
telemt_user_unique_ips_recent_window{user="hello"} 342
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 29091.4 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170705
telemt_connections_bad_total 11240
telemt_connections_current 599
telemt_connections_me_current 599
telemt_handshake_timeouts_total 1314
telemt_upstream_connect_attempt_total 7977
telemt_upstream_connect_success_total 7767
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 7977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3985
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_reconnect_attempts_total 10732
telemt_me_reconnect_success_total 6295
telemt_me_reader_eof_total 6671
telemt_me_idle_close_by_peer_total 6671
telemt_me_route_drop_no_conn_total 67934
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148653
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6456
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6265
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 148649
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 2501284448 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 84042766820 (78.27 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 29081.9 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600597
telemt_connections_bad_total 71914
telemt_connections_current 2571
telemt_connections_me_current 2571
telemt_handshake_timeouts_total 26950
telemt_upstream_connect_attempt_total 5947
telemt_upstream_connect_success_total 5947
telemt_upstream_connect_attempts_per_request{bucket="1"} 5947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4493
telemt_me_reconnect_success_total 4480
telemt_me_reader_eof_total 4731
telemt_me_idle_close_by_peer_total 4731
telemt_me_route_drop_no_conn_total 214371
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 483464
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2714
telemt_desync_full_logged_total 978
telemt_desync_suppressed_total 1736
telemt_desync_frames_bucket_total{bucket="1_2"} 557
telemt_desync_frames_bucket_total{bucket="3_10"} 1041
telemt_desync_frames_bucket_total{bucket="gt_10"} 1116
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4529
telemt_me_writer_restored_same_endpoint_total 4465
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 483275
telemt_user_connections_current{user="hello"} 2571
telemt_user_octets_from_client{user="hello"} 6286751656 (5.85 GB)
telemt_user_octets_to_client{user="hello"} 281004894368 (261.71 GB)
telemt_user_unique_ips_current{user="hello"} 846
telemt_user_unique_ips_recent_window{user="hello"} 308
```