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

# Server Metrics 2026-03-17 22:59:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 101650.7 (28h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1221942
telemt_connections_bad_total 8807
telemt_handshake_timeouts_total 32231
telemt_upstream_connect_attempt_total 22911
telemt_upstream_connect_success_total 22416
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 22911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32194
telemt_me_reconnect_success_total 15062
telemt_me_reader_eof_total 16357
telemt_me_idle_close_by_peer_total 16356
telemt_me_route_drop_no_conn_total 543394
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1121719
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7397
telemt_desync_full_logged_total 2151
telemt_desync_suppressed_total 5246
telemt_desync_frames_bucket_total{bucket="1_2"} 1979
telemt_desync_frames_bucket_total{bucket="3_10"} 2799
telemt_desync_frames_bucket_total{bucket="gt_10"} 2619
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 15816
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15040
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 754
telemt_user_connections_total{user="hello"} 1115943
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 20825136323 (19.39 GB)
telemt_user_octets_to_client{user="hello"} 403033657323 (375.35 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 101901.9 (28h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1293330
telemt_connections_bad_total 60493
telemt_handshake_timeouts_total 45148
telemt_upstream_connect_attempt_total 458408
telemt_upstream_connect_success_total 457501
telemt_upstream_connect_fail_total 907
telemt_upstream_connect_attempts_per_request{bucket="1"} 458408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 907
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58554
telemt_me_reconnect_success_total 15397
telemt_me_reader_eof_total 17421
telemt_me_idle_close_by_peer_total 17421
telemt_me_route_drop_no_conn_total 335990
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 685680
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3138
telemt_desync_full_logged_total 1027
telemt_desync_suppressed_total 2111
telemt_desync_frames_bucket_total{bucket="1_2"} 618
telemt_desync_frames_bucket_total{bucket="3_10"} 1285
telemt_desync_frames_bucket_total{bucket="gt_10"} 1235
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 16936
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15381
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1539
telemt_user_connections_total{user="hello"} 1122110
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 15461291386 (14.40 GB)
telemt_user_octets_to_client{user="hello"} 384088065562 (357.71 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 101678.0 (28h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755249
telemt_connections_bad_total 47110
telemt_handshake_timeouts_total 23551
telemt_upstream_connect_attempt_total 24005
telemt_upstream_connect_success_total 23866
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39436
telemt_me_reconnect_success_total 18755
telemt_me_reader_eof_total 20444
telemt_me_idle_close_by_peer_total 20437
telemt_me_route_drop_no_conn_total 310763
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 644031
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2111
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1431
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 818
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 19658
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18743
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 903
telemt_user_connections_total{user="hello"} 642292
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 31256928652 (29.11 GB)
telemt_user_octets_to_client{user="hello"} 282031520688 (262.66 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 101737.4 (28h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1246488
telemt_connections_bad_total 45028
telemt_handshake_timeouts_total 21629
telemt_upstream_connect_attempt_total 83605
telemt_upstream_connect_success_total 83171
telemt_upstream_connect_fail_total 434
telemt_upstream_connect_attempts_per_request{bucket="1"} 83605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 434
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35049
telemt_me_reconnect_success_total 14724
telemt_me_reader_eof_total 16224
telemt_me_idle_close_by_peer_total 16222
telemt_me_route_drop_no_conn_total 513842
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1019032
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3826
telemt_desync_full_logged_total 1255
telemt_desync_suppressed_total 2571
telemt_desync_frames_bucket_total{bucket="1_2"} 938
telemt_desync_frames_bucket_total{bucket="3_10"} 1607
telemt_desync_frames_bucket_total{bucket="gt_10"} 1281
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15632
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14715
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 908
telemt_user_connections_total{user="hello"} 1081521
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 16942913023 (15.78 GB)
telemt_user_octets_to_client{user="hello"} 484240041257 (450.98 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 101709.3 (28h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 804709
telemt_connections_bad_total 95748
telemt_handshake_timeouts_total 6450
telemt_upstream_connect_attempt_total 42630
telemt_upstream_connect_success_total 42053
telemt_upstream_connect_fail_total 577
telemt_upstream_connect_attempts_per_request{bucket="1"} 42630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 404
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 577
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55457
telemt_me_reconnect_success_total 20504
telemt_me_reader_eof_total 22339
telemt_me_idle_close_by_peer_total 22337
telemt_me_route_drop_no_conn_total 255243
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645042
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2975
telemt_desync_full_logged_total 876
telemt_desync_suppressed_total 2099
telemt_desync_frames_bucket_total{bucket="1_2"} 963
telemt_desync_frames_bucket_total{bucket="3_10"} 1192
telemt_desync_frames_bucket_total{bucket="gt_10"} 820
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21945
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20496
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1441
telemt_user_connections_total{user="hello"} 661653
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 12654603928 (11.79 GB)
telemt_user_octets_to_client{user="hello"} 329149507308 (306.54 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 101870.5 (28h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035253
telemt_connections_bad_total 88155
telemt_handshake_timeouts_total 9525
telemt_upstream_connect_attempt_total 20166
telemt_upstream_connect_success_total 20052
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 20166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26230
telemt_me_reconnect_success_total 14950
telemt_me_reader_eof_total 16233
telemt_me_idle_close_by_peer_total 16231
telemt_me_route_drop_no_conn_total 696656
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1009390
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2100
telemt_desync_full_logged_total 734
telemt_desync_suppressed_total 1366
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 798
telemt_desync_frames_bucket_total{bucket="gt_10"} 841
telemt_pool_swap_total 88
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15548
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14936
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 598
telemt_user_connections_total{user="hello"} 872416
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 13755835788 (12.81 GB)
telemt_user_octets_to_client{user="hello"} 370236878828 (344.81 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 49637.5 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365937
telemt_connections_bad_total 44557
telemt_handshake_timeouts_total 10630
telemt_upstream_connect_attempt_total 19052
telemt_upstream_connect_success_total 18875
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 19052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27806
telemt_me_reconnect_success_total 16211
telemt_me_reader_eof_total 17139
telemt_me_idle_close_by_peer_total 17139
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 91661
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275969
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 985
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 366
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16763
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16182
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 275907
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 21384492717 (19.92 GB)
telemt_user_octets_to_client{user="hello"} 226445005454 (210.89 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 26
```