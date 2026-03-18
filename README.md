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

# Server Metrics 2026-03-18 03:39:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 118450.5 (32h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1352789
telemt_connections_bad_total 10399
telemt_handshake_timeouts_total 33465
telemt_upstream_connect_attempt_total 26171
telemt_upstream_connect_success_total 25661
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 26171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34618
telemt_me_reconnect_success_total 17474
telemt_me_reader_eof_total 18963
telemt_me_idle_close_by_peer_total 18962
telemt_me_route_drop_no_conn_total 581620
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1245913
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7886
telemt_desync_full_logged_total 2348
telemt_desync_suppressed_total 5538
telemt_desync_frames_bucket_total{bucket="1_2"} 2084
telemt_desync_frames_bucket_total{bucket="3_10"} 3018
telemt_desync_frames_bucket_total{bucket="gt_10"} 2784
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 18272
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17452
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 798
telemt_user_connections_total{user="hello"} 1240118
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 25142133279 (23.42 GB)
telemt_user_octets_to_client{user="hello"} 440637711571 (410.38 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 118702.1 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1435706
telemt_connections_bad_total 64722
telemt_handshake_timeouts_total 47861
telemt_upstream_connect_attempt_total 469311
telemt_upstream_connect_success_total 467713
telemt_upstream_connect_fail_total 1598
telemt_upstream_connect_attempts_per_request{bucket="1"} 469311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1598
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125617
telemt_me_reconnect_success_total 18894
telemt_me_reader_eof_total 21132
telemt_me_idle_close_by_peer_total 21119
telemt_me_route_drop_no_conn_total 370583
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 808750
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3726
telemt_desync_full_logged_total 1283
telemt_desync_suppressed_total 2443
telemt_desync_frames_bucket_total{bucket="1_2"} 731
telemt_desync_frames_bucket_total{bucket="3_10"} 1542
telemt_desync_frames_bucket_total{bucket="gt_10"} 1453
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 20508
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 18876
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1614
telemt_user_connections_total{user="hello"} 1251081
telemt_user_connections_current{user="hello"} 853
telemt_user_octets_from_client{user="hello"} 16759559309 (15.61 GB)
telemt_user_octets_to_client{user="hello"} 447300115326 (416.58 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 118478.3 (32h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 878624
telemt_connections_bad_total 61770
telemt_handshake_timeouts_total 25233
telemt_upstream_connect_attempt_total 27520
telemt_upstream_connect_success_total 27361
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14727
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42117
telemt_me_reconnect_success_total 21420
telemt_me_reader_eof_total 23294
telemt_me_idle_close_by_peer_total 23287
telemt_me_route_drop_no_conn_total 342507
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 739358
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2320
telemt_desync_full_logged_total 757
telemt_desync_suppressed_total 1563
telemt_desync_frames_bucket_total{bucket="1_2"} 668
telemt_desync_frames_bucket_total{bucket="3_10"} 892
telemt_desync_frames_bucket_total{bucket="gt_10"} 760
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 22353
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21408
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 933
telemt_user_connections_total{user="hello"} 737473
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 44470622668 (41.42 GB)
telemt_user_octets_to_client{user="hello"} 332440225796 (309.61 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 118537.6 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1354576
telemt_connections_bad_total 63847
telemt_handshake_timeouts_total 23757
telemt_upstream_connect_attempt_total 90421
telemt_upstream_connect_success_total 87990
telemt_upstream_connect_fail_total 2431
telemt_upstream_connect_attempts_per_request{bucket="1"} 90421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2431
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37735
telemt_me_reconnect_success_total 17328
telemt_me_reader_eof_total 19038
telemt_me_idle_close_by_peer_total 19035
telemt_me_route_drop_no_conn_total 553315
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1099805
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4093
telemt_desync_full_logged_total 1349
telemt_desync_suppressed_total 2744
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1708
telemt_desync_frames_bucket_total{bucket="gt_10"} 1381
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 18287
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17308
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 959
telemt_user_connections_total{user="hello"} 1163169
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 18102420150 (16.86 GB)
telemt_user_octets_to_client{user="hello"} 555918967346 (517.74 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 118509.4 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 914143
telemt_connections_bad_total 101645
telemt_handshake_timeouts_total 7309
telemt_upstream_connect_attempt_total 47225
telemt_upstream_connect_success_total 46581
telemt_upstream_connect_fail_total 644
telemt_upstream_connect_attempts_per_request{bucket="1"} 47225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 644
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59166
telemt_me_reconnect_success_total 24202
telemt_me_reader_eof_total 26219
telemt_me_idle_close_by_peer_total 26216
telemt_me_route_drop_no_conn_total 291933
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 740968
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3342
telemt_desync_full_logged_total 1010
telemt_desync_suppressed_total 2332
telemt_desync_frames_bucket_total{bucket="1_2"} 1032
telemt_desync_frames_bucket_total{bucket="3_10"} 1330
telemt_desync_frames_bucket_total{bucket="gt_10"} 980
telemt_pool_swap_total 62
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25672
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24194
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1470
telemt_user_connections_total{user="hello"} 757484
telemt_user_connections_current{user="hello"} 733
telemt_user_octets_from_client{user="hello"} 14433424768 (13.44 GB)
telemt_user_octets_to_client{user="hello"} 374708022676 (348.97 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 118670.3 (32h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1153088
telemt_connections_bad_total 126843
telemt_handshake_timeouts_total 10192
telemt_upstream_connect_attempt_total 23629
telemt_upstream_connect_success_total 23493
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 23629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28894
telemt_me_reconnect_success_total 17601
telemt_me_reader_eof_total 19077
telemt_me_idle_close_by_peer_total 19075
telemt_me_route_drop_no_conn_total 794837
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1128766
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 106
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18226
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17587
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 944396
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 15103984444 (14.07 GB)
telemt_user_octets_to_client{user="hello"} 413783039000 (385.37 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 66437.6 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459836
telemt_connections_bad_total 46309
telemt_handshake_timeouts_total 11917
telemt_upstream_connect_attempt_total 24089
telemt_upstream_connect_success_total 23847
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 24089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32006
telemt_me_reconnect_success_total 20395
telemt_me_reader_eof_total 21555
telemt_me_idle_close_by_peer_total 21555
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 112320
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332269
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1468
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 991
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 562
telemt_pool_swap_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20977
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20353
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 332062
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 22928805765 (21.35 GB)
telemt_user_octets_to_client{user="hello"} 275660513698 (256.73 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 50
```