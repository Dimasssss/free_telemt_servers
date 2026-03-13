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

# Server Metrics 2026-03-13 11:56:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 102200.8 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413687
telemt_connections_bad_total 3199
telemt_handshake_timeouts_total 8217
telemt_upstream_connect_attempt_total 25758
telemt_upstream_connect_success_total 25636
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 25758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1852
telemt_me_reconnect_attempts_total 24033
telemt_me_reconnect_success_total 20510
telemt_me_reader_eof_total 21904
telemt_me_idle_close_by_peer_total 21903
telemt_me_route_drop_no_conn_total 131488
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358449
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1215
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 782
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 449
telemt_desync_frames_bucket_total{bucket="gt_10"} 523
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 20834
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 20494
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 358043
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 6378978596 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 154821258100 (144.19 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 102093.6 (28h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190507
telemt_connections_bad_total 1652
telemt_handshake_timeouts_total 1457
telemt_upstream_connect_attempt_total 53147
telemt_upstream_connect_success_total 52458
telemt_upstream_connect_fail_total 689
telemt_upstream_connect_attempts_per_request{bucket="1"} 53147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 529
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 689
telemt_me_keepalive_timeout_total 847
telemt_me_reconnect_attempts_total 94170
telemt_me_reconnect_success_total 25907
telemt_me_reader_eof_total 28800
telemt_me_idle_close_by_peer_total 28800
telemt_me_route_drop_no_conn_total 78905
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158336
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28264
telemt_me_refill_failed_total 2129
telemt_me_writer_restored_same_endpoint_total 25890
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2357
telemt_user_connections_total{user="hello"} 179551
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 1839378786 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 58466621689 (54.45 GB)
telemt_user_msgs_from_client{user="hello"} 312241
telemt_user_msgs_to_client{user="hello"} 2236488
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 102057.7 (28h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231628
telemt_connections_bad_total 2055
telemt_handshake_timeouts_total 6609
telemt_upstream_connect_attempt_total 27808
telemt_upstream_connect_success_total 27805
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 27808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 852
telemt_me_reconnect_attempts_total 23847
telemt_me_reconnect_success_total 22637
telemt_me_reader_eof_total 24246
telemt_me_idle_close_by_peer_total 24246
telemt_me_route_drop_no_conn_total 86233
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214515
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 22884
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 22617
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 214429
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 9315802356 (8.68 GB)
telemt_user_octets_to_client{user="hello"} 95380436500 (88.83 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 102032.9 (28h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323168
telemt_connections_bad_total 13736
telemt_handshake_timeouts_total 2332
telemt_upstream_connect_attempt_total 39788
telemt_upstream_connect_success_total 29723
telemt_upstream_connect_fail_total 10065
telemt_upstream_connect_attempts_per_request{bucket="1"} 39788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10065
telemt_me_keepalive_timeout_total 3674
telemt_me_reconnect_attempts_total 91726
telemt_me_reconnect_success_total 21550
telemt_me_reader_eof_total 24387
telemt_me_idle_close_by_peer_total 24380
telemt_me_route_drop_no_conn_total 116786
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278476
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 982
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 690
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 24011
telemt_me_refill_failed_total 2188
telemt_me_writer_restored_same_endpoint_total 21540
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2461
telemt_user_connections_total{user="hello"} 281388
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 5846880130 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 106578079145 (99.26 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 52204.3 (14h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75308
telemt_connections_bad_total 10349
telemt_handshake_timeouts_total 796
telemt_upstream_connect_attempt_total 22878
telemt_upstream_connect_success_total 22702
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 22878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_keepalive_timeout_total 489
telemt_me_reconnect_attempts_total 25098
telemt_me_reconnect_success_total 15182
telemt_me_reader_eof_total 16295
telemt_me_idle_close_by_peer_total 16295
telemt_me_route_drop_no_conn_total 22070
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56837
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 93
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15624
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15164
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 61748
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 543130037 (517.97 MB)
telemt_user_octets_to_client{user="hello"} 17115768387 (15.94 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 101989.3 (28h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578961
telemt_connections_bad_total 17418
telemt_handshake_timeouts_total 12823
telemt_upstream_connect_attempt_total 21714
telemt_upstream_connect_success_total 21601
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 21714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 1692
telemt_me_reconnect_attempts_total 21129
telemt_me_reconnect_success_total 16510
telemt_me_reader_eof_total 17723
telemt_me_idle_close_by_peer_total 17720
telemt_me_route_drop_no_conn_total 287421
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 555753
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 16871
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16503
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 361
telemt_user_connections_total{user="hello"} 528814
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 9497703988 (8.85 GB)
telemt_user_octets_to_client{user="hello"} 284220994796 (264.70 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 61
```