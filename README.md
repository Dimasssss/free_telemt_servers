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

# Server Metrics 2026-03-19 02:54:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 18350.3 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224306
telemt_connections_bad_total 26934
telemt_connections_current 664
telemt_connections_me_current 664
telemt_handshake_timeouts_total 13839
telemt_upstream_connect_attempt_total 3664
telemt_upstream_connect_success_total 3605
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 3664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2682
telemt_me_reconnect_success_total 2669
telemt_me_reader_eof_total 2796
telemt_me_idle_close_by_peer_total 2796
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 61100
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173637
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1194
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 439
telemt_desync_frames_bucket_total{bucket="3_10"} 510
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2683
telemt_me_writer_restored_same_endpoint_total 2654
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 170865
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 1820685956 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 53763990508 (50.07 GB)
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 18354.1 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401848
telemt_connections_bad_total 24686
telemt_connections_current 1710
telemt_connections_me_current 1710
telemt_handshake_timeouts_total 9524
telemt_upstream_connect_attempt_total 3589
telemt_upstream_connect_success_total 3526
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 3589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 2592
telemt_me_reconnect_success_total 2581
telemt_me_reader_eof_total 2716
telemt_me_idle_close_by_peer_total 2716
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 123648
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342192
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1238
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 812
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2620
telemt_me_writer_restored_same_endpoint_total 2566
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 342168
telemt_user_connections_current{user="hello"} 1710
telemt_user_octets_from_client{user="hello"} 12071704396 (11.24 GB)
telemt_user_octets_to_client{user="hello"} 133504896644 (124.34 GB)
telemt_user_unique_ips_current{user="hello"} 663
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 18351.1 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337063
telemt_connections_bad_total 72576
telemt_connections_current 1330
telemt_connections_me_current 1330
telemt_handshake_timeouts_total 7970
telemt_upstream_connect_attempt_total 3521
telemt_upstream_connect_success_total 3521
telemt_upstream_connect_attempts_per_request{bucket="1"} 3521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2588
telemt_me_reconnect_success_total 2578
telemt_me_reader_eof_total 2725
telemt_me_idle_close_by_peer_total 2725
telemt_me_route_drop_no_conn_total 97201
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246909
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1247
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 783
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 509
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2618
telemt_me_writer_restored_same_endpoint_total 2562
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 246909
telemt_user_connections_current{user="hello"} 1330
telemt_user_octets_from_client{user="hello"} 4840694744 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 147432016832 (137.31 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 18404.4 (5h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390712
telemt_connections_bad_total 35709
telemt_connections_current 1064
telemt_connections_me_current 1064
telemt_handshake_timeouts_total 6119
telemt_upstream_connect_attempt_total 3409
telemt_upstream_connect_success_total 3409
telemt_upstream_connect_attempts_per_request{bucket="1"} 3409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2479
telemt_me_reconnect_success_total 2468
telemt_me_reader_eof_total 2596
telemt_me_idle_close_by_peer_total 2595
telemt_me_route_drop_no_conn_total 108273
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247904
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 639
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2494
telemt_me_writer_restored_same_endpoint_total 2444
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 247812
telemt_user_connections_current{user="hello"} 1064
telemt_user_octets_from_client{user="hello"} 2196102576 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 83851078068 (78.09 GB)
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 18347.8 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352455
telemt_connections_bad_total 22340
telemt_connections_current 1255
telemt_connections_me_current 1255
telemt_handshake_timeouts_total 12592
telemt_upstream_connect_attempt_total 3492
telemt_upstream_connect_success_total 3473
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 2542
telemt_me_reconnect_success_total 2528
telemt_me_reader_eof_total 2669
telemt_me_idle_close_by_peer_total 2669
telemt_me_route_drop_no_conn_total 106205
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268585
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1182
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 735
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 411
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2543
telemt_me_writer_restored_same_endpoint_total 2504
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 268504
telemt_user_connections_current{user="hello"} 1255
telemt_user_octets_from_client{user="hello"} 8590975912 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 149596981108 (139.32 GB)
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 18359.3 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86450
telemt_connections_bad_total 9363
telemt_connections_current 319
telemt_connections_me_current 319
telemt_handshake_timeouts_total 379
telemt_upstream_connect_attempt_total 5357
telemt_upstream_connect_success_total 5204
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 5357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2715
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_reconnect_attempts_total 6102
telemt_me_reconnect_success_total 4267
telemt_me_reader_eof_total 4472
telemt_me_idle_close_by_peer_total 4472
telemt_me_route_drop_no_conn_total 34771
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73931
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
telemt_me_writer_removed_unexpected_total 4327
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4237
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 73929
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 1584705188 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 53375770008 (49.71 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 18350.3 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248397
telemt_connections_bad_total 25048
telemt_connections_current 1164
telemt_connections_me_current 1164
telemt_handshake_timeouts_total 12321
telemt_upstream_connect_attempt_total 3937
telemt_upstream_connect_success_total 3937
telemt_upstream_connect_attempts_per_request{bucket="1"} 3937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3007
telemt_me_reconnect_success_total 2998
telemt_me_reader_eof_total 3161
telemt_me_idle_close_by_peer_total 3161
telemt_me_route_drop_no_conn_total 72479
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204592
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1094
telemt_desync_full_logged_total 428
telemt_desync_suppressed_total 666
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3033
telemt_me_writer_restored_same_endpoint_total 2983
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 204617
telemt_user_connections_current{user="hello"} 1164
telemt_user_octets_from_client{user="hello"} 2140082948 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 107630255812 (100.24 GB)
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 107
```