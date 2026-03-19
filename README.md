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

# Server Metrics 2026-03-19 02:44:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 17736.9 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216212
telemt_connections_bad_total 26039
telemt_connections_current 714
telemt_connections_me_current 714
telemt_handshake_timeouts_total 13249
telemt_upstream_connect_attempt_total 3526
telemt_upstream_connect_success_total 3471
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 3526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2591
telemt_me_reconnect_success_total 2578
telemt_me_reader_eof_total 2695
telemt_me_idle_close_by_peer_total 2695
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 59259
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167280
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1156
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 850
telemt_desync_frames_bucket_total{bucket="1_2"} 429
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2590
telemt_me_writer_restored_same_endpoint_total 2563
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 164508
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 1774868112 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 52252991812 (48.66 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 17740.6 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387488
telemt_connections_bad_total 23637
telemt_connections_current 1694
telemt_connections_me_current 1694
telemt_handshake_timeouts_total 9315
telemt_upstream_connect_attempt_total 3456
telemt_upstream_connect_success_total 3394
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 3456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 2504
telemt_me_reconnect_success_total 2493
telemt_me_reader_eof_total 2618
telemt_me_idle_close_by_peer_total 2618
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 119695
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330309
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1209
telemt_desync_full_logged_total 407
telemt_desync_suppressed_total 802
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 465
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2532
telemt_me_writer_restored_same_endpoint_total 2478
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 330284
telemt_user_connections_current{user="hello"} 1694
telemt_user_octets_from_client{user="hello"} 11918816000 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 127696409080 (118.93 GB)
telemt_user_unique_ips_current{user="hello"} 674
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 17737.8 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314998
telemt_connections_bad_total 60061
telemt_connections_current 1229
telemt_connections_me_current 1229
telemt_handshake_timeouts_total 7553
telemt_upstream_connect_attempt_total 3394
telemt_upstream_connect_success_total 3394
telemt_upstream_connect_attempts_per_request{bucket="1"} 3394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2504
telemt_me_reconnect_success_total 2494
telemt_me_reader_eof_total 2635
telemt_me_idle_close_by_peer_total 2635
telemt_me_route_drop_no_conn_total 94369
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238541
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1227
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 776
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 500
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2532
telemt_me_writer_restored_same_endpoint_total 2478
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 238542
telemt_user_connections_current{user="hello"} 1229
telemt_user_octets_from_client{user="hello"} 4307755780 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 140047296520 (130.43 GB)
telemt_user_unique_ips_current{user="hello"} 520
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 17791.1 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375455
telemt_connections_bad_total 35576
telemt_connections_current 1025
telemt_connections_me_current 1025
telemt_handshake_timeouts_total 5644
telemt_upstream_connect_attempt_total 3271
telemt_upstream_connect_success_total 3271
telemt_upstream_connect_attempts_per_request{bucket="1"} 3271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2384
telemt_me_reconnect_success_total 2373
telemt_me_reader_eof_total 2492
telemt_me_idle_close_by_peer_total 2491
telemt_me_route_drop_no_conn_total 105656
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239387
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 620
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2398
telemt_me_writer_restored_same_endpoint_total 2349
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 239295
telemt_user_connections_current{user="hello"} 1025
telemt_user_octets_from_client{user="hello"} 2137375324 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 81418949352 (75.83 GB)
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 17734.5 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339626
telemt_connections_bad_total 20566
telemt_connections_current 1247
telemt_connections_me_current 1247
telemt_handshake_timeouts_total 11792
telemt_upstream_connect_attempt_total 3368
telemt_upstream_connect_success_total 3350
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2463
telemt_me_reconnect_success_total 2449
telemt_me_reader_eof_total 2583
telemt_me_idle_close_by_peer_total 2583
telemt_me_route_drop_no_conn_total 103118
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260360
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 422
telemt_desync_suppressed_total 698
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 396
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2464
telemt_me_writer_restored_same_endpoint_total 2425
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 260280
telemt_user_connections_current{user="hello"} 1247
telemt_user_octets_from_client{user="hello"} 8403393864 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 145065705832 (135.10 GB)
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 17745.9 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83884
telemt_connections_bad_total 9361
telemt_connections_current 331
telemt_connections_me_current 331
telemt_handshake_timeouts_total 370
telemt_upstream_connect_attempt_total 5176
telemt_upstream_connect_success_total 5026
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 5176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_reconnect_attempts_total 5968
telemt_me_reconnect_success_total 4133
telemt_me_reader_eof_total 4318
telemt_me_idle_close_by_peer_total 4318
telemt_me_route_drop_no_conn_total 33675
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71455
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
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4189
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4103
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 71453
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 1549511680 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 52246066200 (48.66 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 17736.9 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239636
telemt_connections_bad_total 24543
telemt_connections_current 1199
telemt_connections_me_current 1199
telemt_handshake_timeouts_total 11801
telemt_upstream_connect_attempt_total 3789
telemt_upstream_connect_success_total 3789
telemt_upstream_connect_attempts_per_request{bucket="1"} 3789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2902
telemt_me_reconnect_success_total 2893
telemt_me_reader_eof_total 3044
telemt_me_idle_close_by_peer_total 3044
telemt_me_route_drop_no_conn_total 69962
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197006
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1083
telemt_desync_full_logged_total 421
telemt_desync_suppressed_total 662
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 446
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2926
telemt_me_writer_restored_same_endpoint_total 2878
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 197031
telemt_user_connections_current{user="hello"} 1199
telemt_user_octets_from_client{user="hello"} 2050656944 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 101425329752 (94.46 GB)
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 121
```