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

# Server Metrics 2026-03-18 13:55:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 18886.3 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 700609
telemt_connections_bad_total 34537
telemt_handshake_timeouts_total 19220
telemt_upstream_connect_attempt_total 66572
telemt_upstream_connect_success_total 65614
telemt_upstream_connect_fail_total 958
telemt_upstream_connect_attempts_per_request{bucket="1"} 66572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 958
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514342
telemt_me_reconnect_success_total 2690
telemt_me_reader_eof_total 2863
telemt_me_idle_close_by_peer_total 2861
telemt_me_route_drop_no_conn_total 395053
telemt_me_route_drop_channel_closed_total 153
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541482
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2370
telemt_desync_full_logged_total 826
telemt_desync_suppressed_total 1544
telemt_desync_frames_bucket_total{bucket="1_2"} 655
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 895
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2866
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2585
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 599649
telemt_user_connections_current{user="hello"} 1709
telemt_user_octets_from_client{user="hello"} 8319733108 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 155066450229 (144.42 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 18918.2 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1856898
telemt_connections_bad_total 138148
telemt_handshake_timeouts_total 41707
telemt_upstream_connect_attempt_total 3321
telemt_upstream_connect_success_total 3309
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3447
telemt_me_reconnect_success_total 2301
telemt_me_reader_eof_total 2387
telemt_me_idle_close_by_peer_total 2386
telemt_me_route_drop_no_conn_total 1446785
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1586026
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4947
telemt_desync_full_logged_total 1552
telemt_desync_suppressed_total 3395
telemt_desync_frames_bucket_total{bucket="1_2"} 1006
telemt_desync_frames_bucket_total{bucket="3_10"} 1994
telemt_desync_frames_bucket_total{bucket="gt_10"} 1947
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2352
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2300
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1585014
telemt_user_connections_current{user="hello"} 4340
telemt_user_octets_from_client{user="hello"} 37533111036 (34.96 GB)
telemt_user_octets_to_client{user="hello"} 495464126552 (461.44 GB)
telemt_user_unique_ips_current{user="hello"} 1318
telemt_user_unique_ips_recent_window{user="hello"} 568
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 18833.8 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1364461
telemt_connections_bad_total 104491
telemt_handshake_timeouts_total 30307
telemt_upstream_connect_attempt_total 11853
telemt_upstream_connect_success_total 11853
telemt_upstream_connect_attempts_per_request{bucket="1"} 11853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 612262
telemt_me_reconnect_success_total 2657
telemt_me_reader_eof_total 2806
telemt_me_idle_close_by_peer_total 2805
telemt_me_route_drop_no_conn_total 668071
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1067271
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3327
telemt_desync_full_logged_total 1096
telemt_desync_suppressed_total 2231
telemt_desync_frames_bucket_total{bucket="1_2"} 923
telemt_desync_frames_bucket_total{bucket="3_10"} 1199
telemt_desync_frames_bucket_total{bucket="gt_10"} 1205
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2796
telemt_me_refill_failed_total 19794
telemt_me_writer_restored_same_endpoint_total 2622
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1074748
telemt_user_connections_current{user="hello"} 3299
telemt_user_octets_from_client{user="hello"} 13774250847 (12.83 GB)
telemt_user_octets_to_client{user="hello"} 435982196896 (406.04 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1011
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 98.2 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12120
telemt_connections_bad_total 2
telemt_connections_current 2623
telemt_connections_me_current 2623
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 125
telemt_upstream_connect_success_total 124
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 55
telemt_me_reconnect_success_total 55
telemt_me_route_drop_no_conn_total 3597
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9336
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 21
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 9319
telemt_user_connections_current{user="hello"} 2623
telemt_user_octets_from_client{user="hello"} 69479904 (66.26 MB)
telemt_user_octets_to_client{user="hello"} 718356544 (685.08 MB)
telemt_user_unique_ips_current{user="hello"} 785
telemt_user_unique_ips_recent_window{user="hello"} 369
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 18758.2 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1472613
telemt_connections_bad_total 105912
telemt_handshake_timeouts_total 24350
telemt_upstream_connect_attempt_total 14841
telemt_upstream_connect_success_total 14813
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 14841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986634
telemt_me_reconnect_success_total 2198
telemt_me_reader_eof_total 2300
telemt_me_idle_close_by_peer_total 2300
telemt_me_route_drop_no_conn_total 1329637
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1226360
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3720
telemt_desync_full_logged_total 1275
telemt_desync_suppressed_total 2445
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 1434
telemt_desync_frames_bucket_total{bucket="gt_10"} 1710
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2262
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2083
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 1228262
telemt_user_connections_current{user="hello"} 3098
telemt_user_octets_from_client{user="hello"} 19623936971 (18.28 GB)
telemt_user_octets_to_client{user="hello"} 437695781977 (407.64 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 1013
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 42.2 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3993
telemt_connections_current 941
telemt_connections_direct_current 818
telemt_connections_me_current 123
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_upstream_connect_attempt_total 2271
telemt_upstream_connect_success_total 2268
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 24320
telemt_me_reconnect_success_total 124
telemt_me_route_drop_no_conn_total 280
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1127
telemt_me_writer_pick_total{mode="p2c",result="full"} 94
telemt_me_writer_pick_total{mode="p2c",result="closed"} 180
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 19
telemt_me_refill_failed_total 1426
telemt_me_writer_restored_same_endpoint_total 27
telemt_me_writer_restored_fallback_total 97
telemt_me_async_recovery_trigger_total 5928
telemt_user_connections_total{user="hello"} 3284
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 3578309 (3.41 MB)
telemt_user_octets_to_client{user="hello"} 37270758 (35.54 MB)
telemt_user_msgs_from_client{user="hello"} 5432
telemt_user_msgs_to_client{user="hello"} 6170
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 273
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 18714.2 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1199300
telemt_connections_bad_total 135323
telemt_handshake_timeouts_total 23856
telemt_upstream_connect_attempt_total 3451
telemt_upstream_connect_success_total 3420
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 3451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 4887
telemt_me_reconnect_success_total 2409
telemt_me_reader_eof_total 2542
telemt_me_idle_close_by_peer_total 2542
telemt_me_route_drop_no_conn_total 694468
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 946810
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3180
telemt_desync_full_logged_total 1059
telemt_desync_suppressed_total 2121
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 1080
telemt_desync_frames_bucket_total{bucket="gt_10"} 1519
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2508
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 2399
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 946146
telemt_user_connections_current{user="hello"} 2988
telemt_user_octets_from_client{user="hello"} 19050863956 (17.74 GB)
telemt_user_octets_to_client{user="hello"} 429718869524 (400.21 GB)
telemt_user_unique_ips_current{user="hello"} 896
telemt_user_unique_ips_recent_window{user="hello"} 404
```