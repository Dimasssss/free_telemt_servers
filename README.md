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

# Server Metrics 2026-03-18 19:24:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14318.2 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373415
telemt_connections_bad_total 22545
telemt_handshake_timeouts_total 8124
telemt_upstream_connect_attempt_total 2534
telemt_upstream_connect_success_total 2534
telemt_upstream_connect_attempts_per_request{bucket="1"} 2534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 1817
telemt_me_reconnect_success_total 1810
telemt_me_reader_eof_total 1862
telemt_me_idle_close_by_peer_total 1862
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 160881
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322179
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1961
telemt_desync_full_logged_total 549
telemt_desync_suppressed_total 1412
telemt_desync_frames_bucket_total{bucket="1_2"} 467
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 881
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1840
telemt_me_writer_restored_same_endpoint_total 1792
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 322063
telemt_user_connections_current{user="hello"} 1115
telemt_user_octets_from_client{user="hello"} 5900184544 (5.49 GB)
telemt_user_octets_to_client{user="hello"} 109023244528 (101.54 GB)
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 19146.5 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1844387
telemt_connections_bad_total 123612
telemt_connections_current 3737
telemt_connections_me_current 3737
telemt_handshake_timeouts_total 32123
telemt_upstream_connect_attempt_total 3089
telemt_upstream_connect_success_total 3073
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2095
telemt_me_reconnect_success_total 2078
telemt_me_reader_eof_total 2085
telemt_me_idle_close_by_peer_total 2084
telemt_me_route_drop_no_conn_total 1719103
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1597226
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5353
telemt_desync_full_logged_total 1715
telemt_desync_suppressed_total 3638
telemt_desync_frames_bucket_total{bucket="1_2"} 938
telemt_desync_frames_bucket_total{bucket="3_10"} 2137
telemt_desync_frames_bucket_total{bucket="gt_10"} 2278
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2029
telemt_me_writer_restored_same_endpoint_total 2076
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1592435
telemt_user_connections_current{user="hello"} 3737
telemt_user_octets_from_client{user="hello"} 24645849616 (22.95 GB)
telemt_user_octets_to_client{user="hello"} 508065783268 (473.17 GB)
telemt_user_unique_ips_current{user="hello"} 1186
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 19074.9 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1399612
telemt_connections_bad_total 119160
telemt_connections_current 3159
telemt_connections_me_current 3159
telemt_handshake_timeouts_total 29320
telemt_upstream_connect_attempt_total 2744
telemt_upstream_connect_success_total 2728
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1747
telemt_me_reconnect_success_total 1731
telemt_me_reader_eof_total 1840
telemt_me_idle_close_by_peer_total 1840
telemt_me_route_drop_no_conn_total 571672
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1116539
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5262
telemt_desync_full_logged_total 1626
telemt_desync_suppressed_total 3636
telemt_desync_frames_bucket_total{bucket="1_2"} 1306
telemt_desync_frames_bucket_total{bucket="3_10"} 1990
telemt_desync_frames_bucket_total{bucket="gt_10"} 1966
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 1777
telemt_me_writer_restored_same_endpoint_total 1714
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1115847
telemt_user_connections_current{user="hello"} 3159
telemt_user_octets_from_client{user="hello"} 24511210416 (22.83 GB)
telemt_user_octets_to_client{user="hello"} 529650681584 (493.28 GB)
telemt_user_unique_ips_current{user="hello"} 1052
telemt_user_unique_ips_recent_window{user="hello"} 383
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 19808.5 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2055080
telemt_connections_bad_total 50726
telemt_connections_current 2465
telemt_connections_me_current 2465
telemt_handshake_timeouts_total 21003
telemt_upstream_connect_attempt_total 2986
telemt_upstream_connect_success_total 2957
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1977
telemt_me_reconnect_success_total 1952
telemt_me_reader_eof_total 2016
telemt_me_idle_close_by_peer_total 2015
telemt_me_route_drop_no_conn_total 3622056
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1838956
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6790
telemt_desync_full_logged_total 1697
telemt_desync_suppressed_total 5093
telemt_desync_frames_bucket_total{bucket="1_2"} 1505
telemt_desync_frames_bucket_total{bucket="3_10"} 3183
telemt_desync_frames_bucket_total{bucket="gt_10"} 2102
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 1963
telemt_me_writer_restored_same_endpoint_total 1941
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 1838869
telemt_user_connections_current{user="hello"} 2465
telemt_user_octets_from_client{user="hello"} 16549127412 (15.41 GB)
telemt_user_octets_to_client{user="hello"} 291170900776 (271.17 GB)
telemt_user_unique_ips_current{user="hello"} 863
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14304.1 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1053542
telemt_connections_bad_total 186043
telemt_handshake_timeouts_total 10184
telemt_upstream_connect_attempt_total 2543
telemt_upstream_connect_success_total 2464
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 2543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3830
telemt_me_reconnect_success_total 1735
telemt_me_reader_eof_total 1839
telemt_me_idle_close_by_peer_total 1839
telemt_me_route_drop_no_conn_total 453562
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 775046
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2671
telemt_desync_full_logged_total 949
telemt_desync_suppressed_total 1722
telemt_desync_frames_bucket_total{bucket="1_2"} 511
telemt_desync_frames_bucket_total{bucket="3_10"} 916
telemt_desync_frames_bucket_total{bucket="gt_10"} 1244
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1828
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1709
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 774446
telemt_user_connections_current{user="hello"} 3207
telemt_user_octets_from_client{user="hello"} 13301567380 (12.39 GB)
telemt_user_octets_to_client{user="hello"} 354125958528 (329.81 GB)
telemt_user_unique_ips_current{user="hello"} 1055
telemt_user_unique_ips_recent_window{user="hello"} 384
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 19238.0 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322527
telemt_connections_bad_total 10500
telemt_connections_current 689
telemt_connections_me_current 689
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3401
telemt_upstream_connect_attempt_total 7387
telemt_upstream_connect_success_total 7360
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 332008
telemt_me_reconnect_success_total 2538
telemt_me_reader_eof_total 2573
telemt_me_idle_close_by_peer_total 2573
telemt_me_route_drop_no_conn_total 200587
telemt_me_route_drop_channel_closed_total 94
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287504
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 572
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 361
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2492
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2527
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 291192
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 4371147297 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 62509130321 (58.22 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 18308.6 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1108518
telemt_connections_bad_total 94388
telemt_connections_current 2942
telemt_connections_me_current 2942
telemt_handshake_timeouts_total 21037
telemt_upstream_connect_attempt_total 3085
telemt_upstream_connect_success_total 3084
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17647
telemt_me_reconnect_success_total 2128
telemt_me_reader_eof_total 2157
telemt_me_idle_close_by_peer_total 2157
telemt_me_route_drop_no_conn_total 516253
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 917200
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3795
telemt_desync_full_logged_total 1290
telemt_desync_suppressed_total 2505
telemt_desync_frames_bucket_total{bucket="1_2"} 877
telemt_desync_frames_bucket_total{bucket="3_10"} 1330
telemt_desync_frames_bucket_total{bucket="gt_10"} 1588
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2104
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2067
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 915989
telemt_user_connections_current{user="hello"} 2942
telemt_user_octets_from_client{user="hello"} 18052405060 (16.81 GB)
telemt_user_octets_to_client{user="hello"} 519047812752 (483.40 GB)
telemt_user_unique_ips_current{user="hello"} 910
telemt_user_unique_ips_recent_window{user="hello"} 333
```