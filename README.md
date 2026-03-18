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

# Server Metrics 2026-03-18 08:09:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 352.2 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15736
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 102
telemt_upstream_connect_attempt_total 128
telemt_upstream_connect_success_total 98
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 32
telemt_me_reconnect_success_total 27
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 6409
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13067
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 27
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_me_writer_removed_unexpected_total 26
telemt_me_writer_restored_same_endpoint_total 25
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 547
telemt_user_connections_total{user="hello"} 13078
telemt_user_connections_current{user="hello"} 1333
telemt_user_octets_from_client{user="hello"} 227081584 (216.56 MB)
telemt_user_octets_to_client{user="hello"} 2031255500 (1.89 GB)
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 134899.4 (37h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2042511
telemt_connections_bad_total 108633
telemt_handshake_timeouts_total 62650
telemt_upstream_connect_attempt_total 472608
telemt_upstream_connect_success_total 470954
telemt_upstream_connect_fail_total 1654
telemt_upstream_connect_attempts_per_request{bucket="1"} 472608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1654
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 134720
telemt_me_reconnect_success_total 21328
telemt_me_reader_eof_total 23850
telemt_me_idle_close_by_peer_total 23836
telemt_me_route_drop_no_conn_total 665234
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1336162
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6043
telemt_desync_full_logged_total 2094
telemt_desync_suppressed_total 3949
telemt_desync_frames_bucket_total{bucket="1_2"} 1134
telemt_desync_frames_bucket_total{bucket="3_10"} 2451
telemt_desync_frames_bucket_total{bucket="gt_10"} 2458
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 23176
telemt_me_refill_failed_total 3537
telemt_me_writer_restored_same_endpoint_total 21310
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1848
telemt_user_connections_total{user="hello"} 1778559
telemt_user_connections_current{user="hello"} 3158
telemt_user_octets_from_client{user="hello"} 30334852633 (28.25 GB)
telemt_user_octets_to_client{user="hello"} 696914918274 (649.05 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 931
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 134675.6 (37h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1541523
telemt_connections_bad_total 93518
telemt_handshake_timeouts_total 35599
telemt_upstream_connect_attempt_total 30415
telemt_upstream_connect_success_total 30246
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 30415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 45062
telemt_me_reconnect_success_total 23462
telemt_me_reader_eof_total 25489
telemt_me_idle_close_by_peer_total 25481
telemt_me_route_drop_no_conn_total 662248
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1131445
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4061
telemt_desync_full_logged_total 1376
telemt_desync_suppressed_total 2685
telemt_desync_frames_bucket_total{bucket="1_2"} 1110
telemt_desync_frames_bucket_total{bucket="3_10"} 1567
telemt_desync_frames_bucket_total{bucket="gt_10"} 1384
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24474
telemt_me_refill_failed_total 669
telemt_me_writer_restored_same_endpoint_total 23450
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 1012
telemt_user_connections_total{user="hello"} 1129410
telemt_user_connections_current{user="hello"} 2242
telemt_user_octets_from_client{user="hello"} 50868849344 (47.38 GB)
telemt_user_octets_to_client{user="hello"} 523591091300 (487.63 GB)
telemt_user_unique_ips_current{user="hello"} 625
telemt_user_unique_ips_recent_window{user="hello"} 329
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 134734.5 (37h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1990539
telemt_connections_bad_total 89696
telemt_handshake_timeouts_total 37929
telemt_upstream_connect_attempt_total 93511
telemt_upstream_connect_success_total 91046
telemt_upstream_connect_fail_total 2465
telemt_upstream_connect_attempts_per_request{bucket="1"} 93511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 388
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2465
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 41085
telemt_me_reconnect_success_total 19546
telemt_me_reader_eof_total 21408
telemt_me_idle_close_by_peer_total 21405
telemt_me_route_drop_no_conn_total 1023929
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1660207
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6470
telemt_desync_full_logged_total 1981
telemt_desync_suppressed_total 4489
telemt_desync_frames_bucket_total{bucket="1_2"} 1457
telemt_desync_frames_bucket_total{bucket="3_10"} 2660
telemt_desync_frames_bucket_total{bucket="gt_10"} 2353
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20585
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19526
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1039
telemt_user_connections_total{user="hello"} 1723270
telemt_user_connections_current{user="hello"} 2964
telemt_user_octets_from_client{user="hello"} 27179330646 (25.31 GB)
telemt_user_octets_to_client{user="hello"} 745247178834 (694.07 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 809
telemt_user_unique_ips_recent_window{user="hello"} 411
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 134706.5 (37h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1444391
telemt_connections_bad_total 121820
telemt_handshake_timeouts_total 17009
telemt_upstream_connect_attempt_total 50110
telemt_upstream_connect_success_total 49411
telemt_upstream_connect_fail_total 699
telemt_upstream_connect_attempts_per_request{bucket="1"} 50110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 699
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 69112
telemt_me_reconnect_success_total 26232
telemt_me_reader_eof_total 28558
telemt_me_idle_close_by_peer_total 28555
telemt_me_route_drop_no_conn_total 619549
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1200357
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5176
telemt_desync_full_logged_total 1599
telemt_desync_suppressed_total 3577
telemt_desync_frames_bucket_total{bucket="1_2"} 1309
telemt_desync_frames_bucket_total{bucket="3_10"} 2009
telemt_desync_frames_bucket_total{bucket="gt_10"} 1858
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27977
telemt_me_refill_failed_total 1334
telemt_me_writer_restored_same_endpoint_total 26224
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1745
telemt_user_connections_total{user="hello"} 1216615
telemt_user_connections_current{user="hello"} 2673
telemt_user_octets_from_client{user="hello"} 23123884172 (21.54 GB)
telemt_user_octets_to_client{user="hello"} 580611984968 (540.74 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 781
telemt_user_unique_ips_recent_window{user="hello"} 355
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 134867.9 (37h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1355823
telemt_connections_bad_total 142157
telemt_handshake_timeouts_total 11192
telemt_upstream_connect_attempt_total 26916
telemt_upstream_connect_success_total 26758
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 26916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 292
telemt_me_reconnect_attempts_total 31374
telemt_me_reconnect_success_total 20059
telemt_me_reader_eof_total 21683
telemt_me_idle_close_by_peer_total 21680
telemt_me_route_drop_no_conn_total 929658
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1312683
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2579
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 1673
telemt_desync_frames_bucket_total{bucket="1_2"} 554
telemt_desync_frames_bucket_total{bucket="3_10"} 1000
telemt_desync_frames_bucket_total{bucket="gt_10"} 1025
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20721
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 20045
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 662
telemt_user_connections_total{user="hello"} 1121341
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 17035556036 (15.87 GB)
telemt_user_octets_to_client{user="hello"} 476447591332 (443.73 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 82634.8 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824919
telemt_connections_bad_total 77995
telemt_handshake_timeouts_total 17600
telemt_upstream_connect_attempt_total 27464
telemt_upstream_connect_success_total 27150
telemt_upstream_connect_fail_total 314
telemt_upstream_connect_attempts_per_request{bucket="1"} 27464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 314
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 36865
telemt_me_reconnect_success_total 22890
telemt_me_reader_eof_total 24214
telemt_me_idle_close_by_peer_total 24214
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 261071
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625781
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2520
telemt_desync_full_logged_total 860
telemt_desync_suppressed_total 1660
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 1030
telemt_desync_frames_bucket_total{bucket="gt_10"} 1055
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23581
telemt_me_refill_failed_total 432
telemt_me_writer_restored_same_endpoint_total 22843
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 691
telemt_user_connections_total{user="hello"} 625432
telemt_user_connections_current{user="hello"} 1987
telemt_user_octets_from_client{user="hello"} 30152091981 (28.08 GB)
telemt_user_octets_to_client{user="hello"} 439495764318 (409.31 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 582
telemt_user_unique_ips_recent_window{user="hello"} 265
```