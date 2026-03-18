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

# Server Metrics 2026-03-18 20:40:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18936.2 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458912
telemt_connections_bad_total 26446
telemt_handshake_timeouts_total 9521
telemt_upstream_connect_attempt_total 3320
telemt_upstream_connect_success_total 3317
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 2372
telemt_me_reconnect_success_total 2357
telemt_me_reader_eof_total 2458
telemt_me_idle_close_by_peer_total 2458
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 189721
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392288
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2330
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 1643
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 1049
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2403
telemt_me_writer_restored_same_endpoint_total 2339
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 392106
telemt_user_connections_current{user="hello"} 845
telemt_user_octets_from_client{user="hello"} 7579890728 (7.06 GB)
telemt_user_octets_to_client{user="hello"} 142899117232 (133.09 GB)
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 23764.4 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2121550
telemt_connections_bad_total 148575
telemt_connections_current 2812
telemt_connections_me_current 2812
telemt_handshake_timeouts_total 36024
telemt_upstream_connect_attempt_total 3724
telemt_upstream_connect_success_total 3699
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2504
telemt_me_reconnect_success_total 2487
telemt_me_reader_eof_total 2525
telemt_me_idle_close_by_peer_total 2524
telemt_me_route_drop_no_conn_total 1828394
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1836867
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6571
telemt_desync_full_logged_total 2121
telemt_desync_suppressed_total 4450
telemt_desync_frames_bucket_total{bucket="1_2"} 1145
telemt_desync_frames_bucket_total{bucket="3_10"} 2583
telemt_desync_frames_bucket_total{bucket="gt_10"} 2843
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2451
telemt_me_writer_restored_same_endpoint_total 2485
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1832240
telemt_user_connections_current{user="hello"} 2812
telemt_user_octets_from_client{user="hello"} 28129663068 (26.20 GB)
telemt_user_octets_to_client{user="hello"} 632967333708 (589.50 GB)
telemt_user_unique_ips_current{user="hello"} 972
telemt_user_unique_ips_recent_window{user="hello"} 314
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 23692.9 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1618636
telemt_connections_bad_total 130636
telemt_connections_current 2372
telemt_connections_me_current 2372
telemt_handshake_timeouts_total 38759
telemt_upstream_connect_attempt_total 3419
telemt_upstream_connect_success_total 3402
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2205
telemt_me_reconnect_success_total 2185
telemt_me_reader_eof_total 2324
telemt_me_idle_close_by_peer_total 2324
telemt_me_route_drop_no_conn_total 656697
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1303388
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6338
telemt_desync_full_logged_total 1939
telemt_desync_suppressed_total 4399
telemt_desync_frames_bucket_total{bucket="1_2"} 1575
telemt_desync_frames_bucket_total{bucket="3_10"} 2382
telemt_desync_frames_bucket_total{bucket="gt_10"} 2381
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2240
telemt_me_writer_restored_same_endpoint_total 2168
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1302584
telemt_user_connections_current{user="hello"} 2372
telemt_user_octets_from_client{user="hello"} 27665315308 (25.77 GB)
telemt_user_octets_to_client{user="hello"} 661396671624 (615.97 GB)
telemt_user_unique_ips_current{user="hello"} 839
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 24407.5 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2254950
telemt_connections_bad_total 72033
telemt_connections_current 2067
telemt_connections_me_current 2067
telemt_handshake_timeouts_total 22401
telemt_upstream_connect_attempt_total 3685
telemt_upstream_connect_success_total 3648
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 3685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2408
telemt_me_reconnect_success_total 2380
telemt_me_reader_eof_total 2479
telemt_me_idle_close_by_peer_total 2478
telemt_me_route_drop_no_conn_total 3720053
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2007110
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7609
telemt_desync_full_logged_total 1990
telemt_desync_suppressed_total 5619
telemt_desync_frames_bucket_total{bucket="1_2"} 1647
telemt_desync_frames_bucket_total{bucket="3_10"} 3509
telemt_desync_frames_bucket_total{bucket="gt_10"} 2453
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2399
telemt_me_writer_restored_same_endpoint_total 2369
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2007017
telemt_user_connections_current{user="hello"} 2067
telemt_user_octets_from_client{user="hello"} 19481563220 (18.14 GB)
telemt_user_octets_to_client{user="hello"} 365545292540 (340.44 GB)
telemt_user_unique_ips_current{user="hello"} 742
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18922.0 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1299280
telemt_connections_bad_total 228166
telemt_handshake_timeouts_total 12274
telemt_upstream_connect_attempt_total 3358
telemt_upstream_connect_success_total 3257
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 3358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 6840
telemt_me_reconnect_success_total 2309
telemt_me_reader_eof_total 2514
telemt_me_idle_close_by_peer_total 2514
telemt_me_route_drop_no_conn_total 542512
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 956397
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3624
telemt_desync_full_logged_total 1313
telemt_desync_suppressed_total 2311
telemt_desync_frames_bucket_total{bucket="1_2"} 647
telemt_desync_frames_bucket_total{bucket="3_10"} 1229
telemt_desync_frames_bucket_total{bucket="gt_10"} 1748
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2492
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2283
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 955764
telemt_user_connections_current{user="hello"} 2377
telemt_user_octets_from_client{user="hello"} 17229345280 (16.05 GB)
telemt_user_octets_to_client{user="hello"} 467943096700 (435.81 GB)
telemt_user_unique_ips_current{user="hello"} 872
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 23855.3 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368865
telemt_connections_bad_total 10702
telemt_connections_current 711
telemt_connections_me_current 711
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4173
telemt_upstream_connect_attempt_total 8159
telemt_upstream_connect_success_total 8126
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3897
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 332556
telemt_me_reconnect_success_total 3086
telemt_me_reader_eof_total 3164
telemt_me_idle_close_by_peer_total 3164
telemt_me_route_drop_no_conn_total 219116
telemt_me_route_drop_channel_closed_total 104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327791
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 727
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3050
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3075
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 331475
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 7135141117 (6.65 GB)
telemt_user_octets_to_client{user="hello"} 82127041421 (76.49 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 22926.7 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1301762
telemt_connections_bad_total 102435
telemt_connections_current 2283
telemt_connections_me_current 2283
telemt_handshake_timeouts_total 27629
telemt_upstream_connect_attempt_total 3801
telemt_upstream_connect_success_total 3800
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18147
telemt_me_reconnect_success_total 2625
telemt_me_reader_eof_total 2689
telemt_me_idle_close_by_peer_total 2688
telemt_me_route_drop_no_conn_total 585031
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1088762
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4978
telemt_desync_full_logged_total 1646
telemt_desync_suppressed_total 3332
telemt_desync_frames_bucket_total{bucket="1_2"} 1175
telemt_desync_frames_bucket_total{bucket="3_10"} 1695
telemt_desync_frames_bucket_total{bucket="gt_10"} 2108
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2611
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2564
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1087501
telemt_user_connections_current{user="hello"} 2283
telemt_user_octets_from_client{user="hello"} 21508836760 (20.03 GB)
telemt_user_octets_to_client{user="hello"} 632672047596 (589.22 GB)
telemt_user_unique_ips_current{user="hello"} 721
telemt_user_unique_ips_recent_window{user="hello"} 223
```