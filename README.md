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

# Server Metrics 2026-03-18 07:23:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 131890.5 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1775423
telemt_connections_bad_total 11640
telemt_handshake_timeouts_total 37314
telemt_upstream_connect_attempt_total 28569
telemt_upstream_connect_success_total 28045
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 28569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 36351
telemt_me_reconnect_success_total 19189
telemt_me_reader_eof_total 20785
telemt_me_idle_close_by_peer_total 20784
telemt_me_route_drop_no_conn_total 655957
telemt_me_route_drop_channel_closed_total 190
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1441089
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8663
telemt_desync_full_logged_total 2622
telemt_desync_suppressed_total 6041
telemt_desync_frames_bucket_total{bucket="1_2"} 2233
telemt_desync_frames_bucket_total{bucket="3_10"} 3346
telemt_desync_frames_bucket_total{bucket="gt_10"} 3084
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20011
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19167
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 822
telemt_user_connections_total{user="hello"} 1435365
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 33125840647 (30.85 GB)
telemt_user_octets_to_client{user="hello"} 511263535655 (476.15 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 132141.8 (36h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1866190
telemt_connections_bad_total 97611
telemt_handshake_timeouts_total 58927
telemt_upstream_connect_attempt_total 472126
telemt_upstream_connect_success_total 470476
telemt_upstream_connect_fail_total 1650
telemt_upstream_connect_attempts_per_request{bucket="1"} 472126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1650
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 130256
telemt_me_reconnect_success_total 20993
telemt_me_reader_eof_total 23388
telemt_me_idle_close_by_peer_total 23375
telemt_me_route_drop_no_conn_total 522941
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1180010
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5420
telemt_desync_full_logged_total 1889
telemt_desync_suppressed_total 3531
telemt_desync_frames_bucket_total{bucket="1_2"} 1014
telemt_desync_frames_bucket_total{bucket="3_10"} 2204
telemt_desync_frames_bucket_total{bucket="gt_10"} 2202
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22712
telemt_me_refill_failed_total 3408
telemt_me_writer_restored_same_endpoint_total 20975
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1719
telemt_user_connections_total{user="hello"} 1622384
telemt_user_connections_current{user="hello"} 2532
telemt_user_octets_from_client{user="hello"} 25940336857 (24.16 GB)
telemt_user_octets_to_client{user="hello"} 636955786522 (593.21 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 781
telemt_user_unique_ips_recent_window{user="hello"} 370
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 131917.7 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1377479
telemt_connections_bad_total 85941
telemt_handshake_timeouts_total 32738
telemt_upstream_connect_attempt_total 29804
telemt_upstream_connect_success_total 29637
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 29804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 43739
telemt_me_reconnect_success_total 23020
telemt_me_reader_eof_total 25004
telemt_me_idle_close_by_peer_total 24996
telemt_me_route_drop_no_conn_total 510171
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1013614
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3586
telemt_desync_full_logged_total 1201
telemt_desync_suppressed_total 2385
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1379
telemt_desync_frames_bucket_total{bucket="gt_10"} 1239
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 23990
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 23008
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 970
telemt_user_connections_total{user="hello"} 1011634
telemt_user_connections_current{user="hello"} 1767
telemt_user_octets_from_client{user="hello"} 49242960432 (45.86 GB)
telemt_user_octets_to_client{user="hello"} 489343324216 (455.74 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 131977.3 (36h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1755055
telemt_connections_bad_total 85423
telemt_handshake_timeouts_total 31283
telemt_upstream_connect_attempt_total 92945
telemt_upstream_connect_success_total 90489
telemt_upstream_connect_fail_total 2456
telemt_upstream_connect_attempts_per_request{bucket="1"} 92945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2456
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 40673
telemt_me_reconnect_success_total 19155
telemt_me_reader_eof_total 20992
telemt_me_idle_close_by_peer_total 20989
telemt_me_route_drop_no_conn_total 719394
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1449943
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5624
telemt_desync_full_logged_total 1778
telemt_desync_suppressed_total 3846
telemt_desync_frames_bucket_total{bucket="1_2"} 1314
telemt_desync_frames_bucket_total{bucket="3_10"} 2287
telemt_desync_frames_bucket_total{bucket="gt_10"} 2023
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 20181
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19135
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1026
telemt_user_connections_total{user="hello"} 1513119
telemt_user_connections_current{user="hello"} 2516
telemt_user_octets_from_client{user="hello"} 24953047118 (23.24 GB)
telemt_user_octets_to_client{user="hello"} 709810782046 (661.06 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 131949.0 (36h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1276405
telemt_connections_bad_total 114903
telemt_handshake_timeouts_total 13747
telemt_upstream_connect_attempt_total 49835
telemt_upstream_connect_success_total 49144
telemt_upstream_connect_fail_total 691
telemt_upstream_connect_attempts_per_request{bucket="1"} 49835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 691
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 64886
telemt_me_reconnect_success_total 26104
telemt_me_reader_eof_total 28309
telemt_me_idle_close_by_peer_total 28306
telemt_me_route_drop_no_conn_total 423586
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1052912
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4562
telemt_desync_full_logged_total 1412
telemt_desync_suppressed_total 3150
telemt_desync_frames_bucket_total{bucket="1_2"} 1196
telemt_desync_frames_bucket_total{bucket="3_10"} 1765
telemt_desync_frames_bucket_total{bucket="gt_10"} 1601
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27720
telemt_me_refill_failed_total 1206
telemt_me_writer_restored_same_endpoint_total 26096
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1616
telemt_user_connections_total{user="hello"} 1069266
telemt_user_connections_current{user="hello"} 2228
telemt_user_octets_from_client{user="hello"} 21258159808 (19.80 GB)
telemt_user_octets_to_client{user="hello"} 535962870048 (499.15 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 698
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 132110.2 (36h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1293014
telemt_connections_bad_total 134150
telemt_handshake_timeouts_total 10966
telemt_upstream_connect_attempt_total 26315
telemt_upstream_connect_success_total 26158
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 26315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 30909
telemt_me_reconnect_success_total 19606
telemt_me_reader_eof_total 21215
telemt_me_idle_close_by_peer_total 21212
telemt_me_route_drop_no_conn_total 856494
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1260689
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2494
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 1616
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 962
telemt_desync_frames_bucket_total{bucket="gt_10"} 983
telemt_pool_swap_total 119
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20257
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19592
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 651
telemt_user_connections_total{user="hello"} 1069357
telemt_user_connections_current{user="hello"} 902
telemt_user_octets_from_client{user="hello"} 16676922852 (15.53 GB)
telemt_user_octets_to_client{user="hello"} 469806175484 (437.54 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 79877.2 (22h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 721518
telemt_connections_bad_total 63137
telemt_handshake_timeouts_total 15461
telemt_upstream_connect_attempt_total 26819
telemt_upstream_connect_success_total 26532
telemt_upstream_connect_fail_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 26819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 287
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 34044
telemt_me_reconnect_success_total 22423
telemt_me_reader_eof_total 23686
telemt_me_idle_close_by_peer_total 23686
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 207670
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545779
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2280
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 1499
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 975
telemt_desync_frames_bucket_total{bucket="gt_10"} 926
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23028
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22376
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 605
telemt_user_connections_total{user="hello"} 545466
telemt_user_connections_current{user="hello"} 1647
telemt_user_octets_from_client{user="hello"} 28603081161 (26.64 GB)
telemt_user_octets_to_client{user="hello"} 398689598610 (371.31 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 205
```