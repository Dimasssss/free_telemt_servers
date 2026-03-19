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

# Server Metrics 2026-03-19 03:04:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 18963.8 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233581
telemt_connections_bad_total 27823
telemt_connections_current 701
telemt_connections_me_current 701
telemt_handshake_timeouts_total 14361
telemt_upstream_connect_attempt_total 3750
telemt_upstream_connect_success_total 3691
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 3750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2744
telemt_me_reconnect_success_total 2730
telemt_me_reader_eof_total 2858
telemt_me_idle_close_by_peer_total 2858
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 63105
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180723
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1241
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 914
telemt_desync_frames_bucket_total{bucket="1_2"} 457
telemt_desync_frames_bucket_total{bucket="3_10"} 529
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2746
telemt_me_writer_restored_same_endpoint_total 2714
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 177950
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 1878960012 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 55360035588 (51.56 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 18967.5 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418111
telemt_connections_bad_total 25808
telemt_connections_current 1848
telemt_connections_me_current 1848
telemt_handshake_timeouts_total 10157
telemt_upstream_connect_attempt_total 3652
telemt_upstream_connect_success_total 3589
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 3652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 2630
telemt_me_reconnect_success_total 2619
telemt_me_reader_eof_total 2756
telemt_me_idle_close_by_peer_total 2756
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 128329
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355525
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1307
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 856
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2660
telemt_me_writer_restored_same_endpoint_total 2604
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 355497
telemt_user_connections_current{user="hello"} 1848
telemt_user_octets_from_client{user="hello"} 12179360016 (11.34 GB)
telemt_user_octets_to_client{user="hello"} 140904053932 (131.23 GB)
telemt_user_unique_ips_current{user="hello"} 703
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 18964.8 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352410
telemt_connections_bad_total 76626
telemt_connections_current 1478
telemt_connections_me_current 1478
telemt_handshake_timeouts_total 8313
telemt_upstream_connect_attempt_total 3619
telemt_upstream_connect_success_total 3619
telemt_upstream_connect_attempts_per_request{bucket="1"} 3619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2658
telemt_me_reconnect_success_total 2648
telemt_me_reader_eof_total 2795
telemt_me_idle_close_by_peer_total 2795
telemt_me_route_drop_no_conn_total 100744
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257258
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1290
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 805
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2688
telemt_me_writer_restored_same_endpoint_total 2632
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 257250
telemt_user_connections_current{user="hello"} 1478
telemt_user_octets_from_client{user="hello"} 5444692592 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 154417201972 (143.81 GB)
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 19018.0 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409035
telemt_connections_bad_total 38089
telemt_connections_current 1218
telemt_connections_me_current 1218
telemt_handshake_timeouts_total 6706
telemt_upstream_connect_attempt_total 3492
telemt_upstream_connect_success_total 3492
telemt_upstream_connect_attempts_per_request{bucket="1"} 3492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2519
telemt_me_reconnect_success_total 2508
telemt_me_reader_eof_total 2638
telemt_me_idle_close_by_peer_total 2637
telemt_me_route_drop_no_conn_total 111900
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257505
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 650
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 276
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2536
telemt_me_writer_restored_same_endpoint_total 2484
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 257249
telemt_user_connections_current{user="hello"} 1218
telemt_user_octets_from_client{user="hello"} 2259500008 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 88382838988 (82.31 GB)
telemt_user_unique_ips_current{user="hello"} 481
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 18961.4 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366786
telemt_connections_bad_total 24098
telemt_connections_current 1484
telemt_connections_me_current 1484
telemt_handshake_timeouts_total 13152
telemt_upstream_connect_attempt_total 3571
telemt_upstream_connect_success_total 3550
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2599
telemt_me_reconnect_success_total 2585
telemt_me_reader_eof_total 2727
telemt_me_idle_close_by_peer_total 2727
telemt_me_route_drop_no_conn_total 109941
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278583
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1225
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 757
telemt_desync_frames_bucket_total{bucket="1_2"} 325
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 422
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2601
telemt_me_writer_restored_same_endpoint_total 2561
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 278504
telemt_user_connections_current{user="hello"} 1484
telemt_user_octets_from_client{user="hello"} 9638929616 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 157854722300 (147.01 GB)
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 18972.8 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89615
telemt_connections_bad_total 9834
telemt_connections_current 387
telemt_connections_me_current 387
telemt_handshake_timeouts_total 400
telemt_upstream_connect_attempt_total 5453
telemt_upstream_connect_success_total 5296
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 5453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2763
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_reconnect_attempts_total 6174
telemt_me_reconnect_success_total 4339
telemt_me_reader_eof_total 4546
telemt_me_idle_close_by_peer_total 4546
telemt_me_route_drop_no_conn_total 35998
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76439
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
telemt_me_writer_removed_unexpected_total 4401
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4309
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 76436
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 1608369988 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 54538375140 (50.79 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 18963.8 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258490
telemt_connections_bad_total 26012
telemt_connections_current 1329
telemt_connections_me_current 1329
telemt_handshake_timeouts_total 12991
telemt_upstream_connect_attempt_total 4040
telemt_upstream_connect_success_total 4040
telemt_upstream_connect_attempts_per_request{bucket="1"} 4040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3085
telemt_me_reconnect_success_total 3076
telemt_me_reader_eof_total 3239
telemt_me_idle_close_by_peer_total 3239
telemt_me_route_drop_no_conn_total 75191
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212927
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1123
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 685
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 462
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3111
telemt_me_writer_restored_same_endpoint_total 3061
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 212949
telemt_user_connections_current{user="hello"} 1329
telemt_user_octets_from_client{user="hello"} 2252964400 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 111834759048 (104.15 GB)
telemt_user_unique_ips_current{user="hello"} 520
telemt_user_unique_ips_recent_window{user="hello"} 148
```