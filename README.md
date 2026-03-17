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

# Server Metrics 2026-03-17 19:55:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 90625.8 (25h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1123399
telemt_connections_bad_total 7968
telemt_handshake_timeouts_total 30228
telemt_upstream_connect_attempt_total 20851
telemt_upstream_connect_success_total 20363
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 20851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30657
telemt_me_reconnect_success_total 13529
telemt_me_reader_eof_total 14714
telemt_me_idle_close_by_peer_total 14713
telemt_me_route_drop_no_conn_total 504263
telemt_me_route_drop_channel_closed_total 152
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1028924
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6811
telemt_desync_full_logged_total 1946
telemt_desync_suppressed_total 4865
telemt_desync_frames_bucket_total{bucket="1_2"} 1832
telemt_desync_frames_bucket_total{bucket="3_10"} 2583
telemt_desync_frames_bucket_total{bucket="gt_10"} 2396
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14263
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13507
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 734
telemt_user_connections_total{user="hello"} 1023164
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 15450438327 (14.39 GB)
telemt_user_octets_to_client{user="hello"} 357634632243 (333.07 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 90877.3 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1118921
telemt_connections_bad_total 56707
telemt_handshake_timeouts_total 39792
telemt_upstream_connect_attempt_total 456424
telemt_upstream_connect_success_total 455549
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 456424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57164
telemt_me_reconnect_success_total 14013
telemt_me_reader_eof_total 15942
telemt_me_idle_close_by_peer_total 15942
telemt_me_route_drop_no_conn_total 277754
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 525366
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2193
telemt_desync_full_logged_total 704
telemt_desync_suppressed_total 1489
telemt_desync_frames_bucket_total{bucket="1_2"} 449
telemt_desync_frames_bucket_total{bucket="3_10"} 926
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 15534
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13997
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1521
telemt_user_connections_total{user="hello"} 961802
telemt_user_connections_current{user="hello"} 1493
telemt_user_octets_from_client{user="hello"} 13376368950 (12.46 GB)
telemt_user_octets_to_client{user="hello"} 300680861138 (280.03 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 90653.6 (25h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598862
telemt_connections_bad_total 26095
telemt_handshake_timeouts_total 22004
telemt_upstream_connect_attempt_total 22060
telemt_upstream_connect_success_total 21931
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 22060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38020
telemt_me_reconnect_success_total 17348
telemt_me_reader_eof_total 18947
telemt_me_idle_close_by_peer_total 18940
telemt_me_route_drop_no_conn_total 265262
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522086
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1540
telemt_desync_full_logged_total 458
telemt_desync_suppressed_total 1082
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 481
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 18231
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17336
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 883
telemt_user_connections_total{user="hello"} 520375
telemt_user_connections_current{user="hello"} 1147
telemt_user_octets_from_client{user="hello"} 27761809388 (25.86 GB)
telemt_user_octets_to_client{user="hello"} 207329707412 (193.09 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 90712.9 (25h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1099327
telemt_connections_bad_total 28818
telemt_handshake_timeouts_total 20633
telemt_upstream_connect_attempt_total 81627
telemt_upstream_connect_success_total 81222
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 81627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33620
telemt_me_reconnect_success_total 13313
telemt_me_reader_eof_total 14684
telemt_me_idle_close_by_peer_total 14683
telemt_me_route_drop_no_conn_total 454443
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 893002
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2994
telemt_desync_full_logged_total 962
telemt_desync_suppressed_total 2032
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 1302
telemt_desync_frames_bucket_total{bucket="gt_10"} 978
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14193
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13304
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 880
telemt_user_connections_total{user="hello"} 956060
telemt_user_connections_current{user="hello"} 1362
telemt_user_octets_from_client{user="hello"} 13678217647 (12.74 GB)
telemt_user_octets_to_client{user="hello"} 371896749521 (346.36 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 90684.8 (25h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 651447
telemt_connections_bad_total 77241
telemt_handshake_timeouts_total 5548
telemt_upstream_connect_attempt_total 40298
telemt_upstream_connect_success_total 39762
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 40298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51219
telemt_me_reconnect_success_total 18735
telemt_me_reader_eof_total 20427
telemt_me_idle_close_by_peer_total 20425
telemt_me_route_drop_no_conn_total 203979
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516168
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2329
telemt_desync_full_logged_total 647
telemt_desync_suppressed_total 1682
telemt_desync_frames_bucket_total{bucket="1_2"} 820
telemt_desync_frames_bucket_total{bucket="3_10"} 922
telemt_desync_frames_bucket_total{bucket="gt_10"} 587
telemt_pool_swap_total 45
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20070
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18727
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1335
telemt_user_connections_total{user="hello"} 532814
telemt_user_connections_current{user="hello"} 1209
telemt_user_octets_from_client{user="hello"} 10583577212 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 247003809280 (230.04 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 90846.7 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 930259
telemt_connections_bad_total 61582
telemt_handshake_timeouts_total 8993
telemt_upstream_connect_attempt_total 18003
telemt_upstream_connect_success_total 17901
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 18003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24639
telemt_me_reconnect_success_total 13364
telemt_me_reader_eof_total 14524
telemt_me_idle_close_by_peer_total 14522
telemt_me_route_drop_no_conn_total 664307
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943751
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1866
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1216
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 717
telemt_desync_frames_bucket_total{bucket="gt_10"} 708
telemt_pool_swap_total 75
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13941
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13350
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 806788
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 12340569332 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 349618440672 (325.61 GB)
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 38612.8 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260908
telemt_connections_bad_total 34608
telemt_handshake_timeouts_total 6577
telemt_upstream_connect_attempt_total 16490
telemt_upstream_connect_success_total 16340
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 16490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 25830
telemt_me_reconnect_success_total 14242
telemt_me_reader_eof_total 15054
telemt_me_idle_close_by_peer_total 15054
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 63405
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200635
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 605
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 444
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14774
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14216
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 532
telemt_user_connections_total{user="hello"} 200582
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 19525724441 (18.18 GB)
telemt_user_octets_to_client{user="hello"} 167216030682 (155.73 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 87
```