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

# Server Metrics 2026-03-19 03:09:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 19270.7 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238136
telemt_connections_bad_total 28273
telemt_connections_current 730
telemt_connections_me_current 730
telemt_handshake_timeouts_total 14636
telemt_upstream_connect_attempt_total 3829
telemt_upstream_connect_success_total 3769
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 3829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2803
telemt_me_reconnect_success_total 2789
telemt_me_reader_eof_total 2924
telemt_me_idle_close_by_peer_total 2924
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 64085
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184355
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1258
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 924
telemt_desync_frames_bucket_total{bucket="1_2"} 464
telemt_desync_frames_bucket_total{bucket="3_10"} 537
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2805
telemt_me_writer_restored_same_endpoint_total 2773
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 181581
telemt_user_connections_current{user="hello"} 730
telemt_user_octets_from_client{user="hello"} 1938725940 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 56140835452 (52.29 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 19274.5 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432175
telemt_connections_bad_total 32233
telemt_connections_current 1804
telemt_connections_me_current 1804
telemt_handshake_timeouts_total 10387
telemt_upstream_connect_attempt_total 3730
telemt_upstream_connect_success_total 3667
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 3730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 2690
telemt_me_reconnect_success_total 2679
telemt_me_reader_eof_total 2820
telemt_me_idle_close_by_peer_total 2820
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 130598
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362571
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1346
telemt_desync_full_logged_total 462
telemt_desync_suppressed_total 884
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 506
telemt_desync_frames_bucket_total{bucket="gt_10"} 532
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2720
telemt_me_writer_restored_same_endpoint_total 2663
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 362547
telemt_user_connections_current{user="hello"} 1804
telemt_user_octets_from_client{user="hello"} 12247015860 (11.41 GB)
telemt_user_octets_to_client{user="hello"} 145269506312 (135.29 GB)
telemt_user_unique_ips_current{user="hello"} 704
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 19271.9 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358878
telemt_connections_bad_total 77610
telemt_connections_current 1444
telemt_connections_me_current 1444
telemt_handshake_timeouts_total 8578
telemt_upstream_connect_attempt_total 3685
telemt_upstream_connect_success_total 3685
telemt_upstream_connect_attempts_per_request{bucket="1"} 3685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2709
telemt_me_reconnect_success_total 2699
telemt_me_reader_eof_total 2855
telemt_me_idle_close_by_peer_total 2855
telemt_me_route_drop_no_conn_total 102779
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262295
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1303
telemt_desync_full_logged_total 492
telemt_desync_suppressed_total 811
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 546
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2740
telemt_me_writer_restored_same_endpoint_total 2683
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 262289
telemt_user_connections_current{user="hello"} 1444
telemt_user_octets_from_client{user="hello"} 5626785556 (5.24 GB)
telemt_user_octets_to_client{user="hello"} 158433753788 (147.55 GB)
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 19324.7 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419089
telemt_connections_bad_total 40315
telemt_connections_current 1243
telemt_connections_me_current 1243
telemt_handshake_timeouts_total 7099
telemt_upstream_connect_attempt_total 3556
telemt_upstream_connect_success_total 3556
telemt_upstream_connect_attempts_per_request{bucket="1"} 3556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2583
telemt_me_reconnect_success_total 2572
telemt_me_reader_eof_total 2707
telemt_me_idle_close_by_peer_total 2706
telemt_me_route_drop_no_conn_total 113533
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262112
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 658
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 414
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2602
telemt_me_writer_restored_same_endpoint_total 2548
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 261855
telemt_user_connections_current{user="hello"} 1243
telemt_user_octets_from_client{user="hello"} 2310537240 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 90722456416 (84.49 GB)
telemt_user_unique_ips_current{user="hello"} 468
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 19268.3 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376124
telemt_connections_bad_total 26550
telemt_connections_current 1434
telemt_connections_me_current 1434
telemt_handshake_timeouts_total 13378
telemt_upstream_connect_attempt_total 3688
telemt_upstream_connect_success_total 3667
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2692
telemt_me_reconnect_success_total 2677
telemt_me_reader_eof_total 2821
telemt_me_idle_close_by_peer_total 2821
telemt_me_route_drop_no_conn_total 112079
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283809
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1282
telemt_desync_full_logged_total 487
telemt_desync_suppressed_total 795
telemt_desync_frames_bucket_total{bucket="1_2"} 337
telemt_desync_frames_bucket_total{bucket="3_10"} 509
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2695
telemt_me_writer_restored_same_endpoint_total 2653
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 283729
telemt_user_connections_current{user="hello"} 1434
telemt_user_octets_from_client{user="hello"} 10025247096 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 160475611708 (149.45 GB)
telemt_user_unique_ips_current{user="hello"} 596
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 19279.6 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91116
telemt_connections_bad_total 9904
telemt_connections_current 329
telemt_connections_me_current 329
telemt_handshake_timeouts_total 407
telemt_upstream_connect_attempt_total 5538
telemt_upstream_connect_success_total 5381
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 5538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_reconnect_attempts_total 6236
telemt_me_reconnect_success_total 4399
telemt_me_reader_eof_total 4618
telemt_me_idle_close_by_peer_total 4618
telemt_me_route_drop_no_conn_total 36617
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77819
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
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4463
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4369
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 77814
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 1615899396 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 54810661284 (51.05 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 19270.6 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265338
telemt_connections_bad_total 27695
telemt_connections_current 1342
telemt_connections_me_current 1342
telemt_handshake_timeouts_total 13343
telemt_upstream_connect_attempt_total 4136
telemt_upstream_connect_success_total 4136
telemt_upstream_connect_attempts_per_request{bucket="1"} 4136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3162
telemt_me_reconnect_success_total 3153
telemt_me_reader_eof_total 3323
telemt_me_idle_close_by_peer_total 3323
telemt_me_route_drop_no_conn_total 76622
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217663
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1137
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 695
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 458
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3188
telemt_me_writer_restored_same_endpoint_total 3138
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 217685
telemt_user_connections_current{user="hello"} 1342
telemt_user_octets_from_client{user="hello"} 2318557044 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 114758426312 (106.88 GB)
telemt_user_unique_ips_current{user="hello"} 510
telemt_user_unique_ips_recent_window{user="hello"} 140
```