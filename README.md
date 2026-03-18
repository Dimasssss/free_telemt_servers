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

# Server Metrics 2026-03-18 21:11:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20776.3 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488383
telemt_connections_bad_total 27926
telemt_handshake_timeouts_total 9692
telemt_upstream_connect_attempt_total 3679
telemt_upstream_connect_success_total 3676
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1822
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 2621
telemt_me_reconnect_success_total 2605
telemt_me_reader_eof_total 2717
telemt_me_idle_close_by_peer_total 2717
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 198454
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414779
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2491
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1753
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 798
telemt_desync_frames_bucket_total{bucket="gt_10"} 1115
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2653
telemt_me_writer_restored_same_endpoint_total 2585
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 414598
telemt_user_connections_current{user="hello"} 886
telemt_user_octets_from_client{user="hello"} 7960812260 (7.41 GB)
telemt_user_octets_to_client{user="hello"} 152873465356 (142.37 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 25604.2 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2206874
telemt_connections_bad_total 154731
telemt_connections_current 2669
telemt_connections_me_current 2669
telemt_handshake_timeouts_total 36859
telemt_upstream_connect_attempt_total 3984
telemt_upstream_connect_success_total 3959
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2678
telemt_me_reconnect_success_total 2659
telemt_me_reader_eof_total 2710
telemt_me_idle_close_by_peer_total 2709
telemt_me_route_drop_no_conn_total 1859392
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1910178
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6919
telemt_desync_full_logged_total 2237
telemt_desync_suppressed_total 4682
telemt_desync_frames_bucket_total{bucket="1_2"} 1204
telemt_desync_frames_bucket_total{bucket="3_10"} 2717
telemt_desync_frames_bucket_total{bucket="gt_10"} 2998
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2628
telemt_me_writer_restored_same_endpoint_total 2657
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1905569
telemt_user_connections_current{user="hello"} 2669
telemt_user_octets_from_client{user="hello"} 30338474728 (28.25 GB)
telemt_user_octets_to_client{user="hello"} 669270446768 (623.31 GB)
telemt_user_unique_ips_current{user="hello"} 911
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 25532.5 (7h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1689040
telemt_connections_bad_total 139071
telemt_connections_current 2269
telemt_connections_me_current 2269
telemt_handshake_timeouts_total 40582
telemt_upstream_connect_attempt_total 3701
telemt_upstream_connect_success_total 3681
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 3701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2398
telemt_me_reconnect_success_total 2378
telemt_me_reader_eof_total 2529
telemt_me_idle_close_by_peer_total 2529
telemt_me_route_drop_no_conn_total 681471
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1362099
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6630
telemt_desync_full_logged_total 2025
telemt_desync_suppressed_total 4605
telemt_desync_frames_bucket_total{bucket="1_2"} 1632
telemt_desync_frames_bucket_total{bucket="3_10"} 2477
telemt_desync_frames_bucket_total{bucket="gt_10"} 2521
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 2436
telemt_me_writer_restored_same_endpoint_total 2361
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1361298
telemt_user_connections_current{user="hello"} 2269
telemt_user_octets_from_client{user="hello"} 29406703260 (27.39 GB)
telemt_user_octets_to_client{user="hello"} 698079160488 (650.14 GB)
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 26247.1 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2332089
telemt_connections_bad_total 84572
telemt_connections_current 1899
telemt_connections_me_current 1899
telemt_handshake_timeouts_total 22974
telemt_upstream_connect_attempt_total 3999
telemt_upstream_connect_success_total 3961
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2635
telemt_me_reconnect_success_total 2605
telemt_me_reader_eof_total 2716
telemt_me_idle_close_by_peer_total 2715
telemt_me_route_drop_no_conn_total 3743983
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2054676
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7805
telemt_desync_full_logged_total 2054
telemt_desync_suppressed_total 5751
telemt_desync_frames_bucket_total{bucket="1_2"} 1717
telemt_desync_frames_bucket_total{bucket="3_10"} 3559
telemt_desync_frames_bucket_total{bucket="gt_10"} 2529
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 2624
telemt_me_writer_restored_same_endpoint_total 2594
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2054579
telemt_user_connections_current{user="hello"} 1899
telemt_user_octets_from_client{user="hello"} 21505000632 (20.03 GB)
telemt_user_octets_to_client{user="hello"} 387830433620 (361.20 GB)
telemt_user_unique_ips_current{user="hello"} 666
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20761.8 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1370369
telemt_connections_bad_total 231788
telemt_handshake_timeouts_total 13073
telemt_upstream_connect_attempt_total 3733
telemt_upstream_connect_success_total 3624
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 3733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 7100
telemt_me_reconnect_success_total 2568
telemt_me_reader_eof_total 2780
telemt_me_idle_close_by_peer_total 2780
telemt_me_route_drop_no_conn_total 566575
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1016798
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3971
telemt_desync_full_logged_total 1444
telemt_desync_suppressed_total 2527
telemt_desync_frames_bucket_total{bucket="1_2"} 702
telemt_desync_frames_bucket_total{bucket="3_10"} 1342
telemt_desync_frames_bucket_total{bucket="gt_10"} 1927
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2754
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2542
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 1016161
telemt_user_connections_current{user="hello"} 2211
telemt_user_octets_from_client{user="hello"} 18248441960 (17.00 GB)
telemt_user_octets_to_client{user="hello"} 501256064544 (466.83 GB)
telemt_user_unique_ips_current{user="hello"} 845
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 25694.7 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383237
telemt_connections_bad_total 10713
telemt_connections_current 637
telemt_connections_me_current 637
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4246
telemt_upstream_connect_attempt_total 8473
telemt_upstream_connect_success_total 8438
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 332782
telemt_me_reconnect_success_total 3311
telemt_me_reader_eof_total 3405
telemt_me_idle_close_by_peer_total 3405
telemt_me_route_drop_no_conn_total 225406
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341712
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 793
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 501
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3279
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3300
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 345251
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 7448333701 (6.94 GB)
telemt_user_octets_to_client{user="hello"} 90133467073 (83.94 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 24766.4 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1365559
telemt_connections_bad_total 107036
telemt_connections_current 2129
telemt_connections_me_current 2129
telemt_handshake_timeouts_total 30206
telemt_upstream_connect_attempt_total 4065
telemt_upstream_connect_success_total 4064
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18325
telemt_me_reconnect_success_total 2801
telemt_me_reader_eof_total 2876
telemt_me_idle_close_by_peer_total 2875
telemt_me_route_drop_no_conn_total 606600
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1141997
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5449
telemt_desync_full_logged_total 1774
telemt_desync_suppressed_total 3675
telemt_desync_frames_bucket_total{bucket="1_2"} 1327
telemt_desync_frames_bucket_total{bucket="3_10"} 1826
telemt_desync_frames_bucket_total{bucket="gt_10"} 2296
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2790
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2740
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1140680
telemt_user_connections_current{user="hello"} 2129
telemt_user_octets_from_client{user="hello"} 22765138020 (21.20 GB)
telemt_user_octets_to_client{user="hello"} 662861807448 (617.34 GB)
telemt_user_unique_ips_current{user="hello"} 693
telemt_user_unique_ips_recent_window{user="hello"} 203
```