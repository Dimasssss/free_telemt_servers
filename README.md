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

# Server Metrics 2026-03-18 20:46:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19242.9 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464044
telemt_connections_bad_total 26686
telemt_handshake_timeouts_total 9538
telemt_upstream_connect_attempt_total 3404
telemt_upstream_connect_success_total 3401
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 2425
telemt_me_reconnect_success_total 2410
telemt_me_reader_eof_total 2517
telemt_me_idle_close_by_peer_total 2517
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 191164
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396119
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2352
telemt_desync_full_logged_total 696
telemt_desync_suppressed_total 1656
telemt_desync_frames_bucket_total{bucket="1_2"} 544
telemt_desync_frames_bucket_total{bucket="3_10"} 753
telemt_desync_frames_bucket_total{bucket="gt_10"} 1055
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2456
telemt_me_writer_restored_same_endpoint_total 2392
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 395937
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 7626197336 (7.10 GB)
telemt_user_octets_to_client{user="hello"} 144412531104 (134.49 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 24071.2 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2134919
telemt_connections_bad_total 149086
telemt_connections_current 2761
telemt_connections_me_current 2761
telemt_handshake_timeouts_total 36220
telemt_upstream_connect_attempt_total 3753
telemt_upstream_connect_success_total 3728
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2533
telemt_me_reconnect_success_total 2515
telemt_me_reader_eof_total 2555
telemt_me_idle_close_by_peer_total 2554
telemt_me_route_drop_no_conn_total 1834074
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1848885
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6651
telemt_desync_full_logged_total 2146
telemt_desync_suppressed_total 4505
telemt_desync_frames_bucket_total{bucket="1_2"} 1152
telemt_desync_frames_bucket_total{bucket="3_10"} 2615
telemt_desync_frames_bucket_total{bucket="gt_10"} 2884
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2481
telemt_me_writer_restored_same_endpoint_total 2513
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1844260
telemt_user_connections_current{user="hello"} 2761
telemt_user_octets_from_client{user="hello"} 28629667480 (26.66 GB)
telemt_user_octets_to_client{user="hello"} 640159364056 (596.19 GB)
telemt_user_unique_ips_current{user="hello"} 947
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 23999.4 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1630560
telemt_connections_bad_total 132148
telemt_connections_current 2270
telemt_connections_me_current 2270
telemt_handshake_timeouts_total 39173
telemt_upstream_connect_attempt_total 3449
telemt_upstream_connect_success_total 3432
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2235
telemt_me_reconnect_success_total 2215
telemt_me_reader_eof_total 2354
telemt_me_idle_close_by_peer_total 2354
telemt_me_route_drop_no_conn_total 660729
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1313154
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6385
telemt_desync_full_logged_total 1953
telemt_desync_suppressed_total 4432
telemt_desync_frames_bucket_total{bucket="1_2"} 1577
telemt_desync_frames_bucket_total{bucket="3_10"} 2398
telemt_desync_frames_bucket_total{bucket="gt_10"} 2410
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2270
telemt_me_writer_restored_same_endpoint_total 2198
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1312353
telemt_user_connections_current{user="hello"} 2270
telemt_user_octets_from_client{user="hello"} 27841147944 (25.93 GB)
telemt_user_octets_to_client{user="hello"} 667686490920 (621.83 GB)
telemt_user_unique_ips_current{user="hello"} 824
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 24714.0 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2266175
telemt_connections_bad_total 72916
telemt_connections_current 1969
telemt_connections_me_current 1969
telemt_handshake_timeouts_total 22496
telemt_upstream_connect_attempt_total 3744
telemt_upstream_connect_success_total 3707
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 3744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1784
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2467
telemt_me_reconnect_success_total 2439
telemt_me_reader_eof_total 2544
telemt_me_idle_close_by_peer_total 2543
telemt_me_route_drop_no_conn_total 3725131
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2015247
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7659
telemt_desync_full_logged_total 2002
telemt_desync_suppressed_total 5657
telemt_desync_frames_bucket_total{bucket="1_2"} 1666
telemt_desync_frames_bucket_total{bucket="3_10"} 3526
telemt_desync_frames_bucket_total{bucket="gt_10"} 2467
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2458
telemt_me_writer_restored_same_endpoint_total 2428
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2015154
telemt_user_connections_current{user="hello"} 1969
telemt_user_octets_from_client{user="hello"} 20883763512 (19.45 GB)
telemt_user_octets_to_client{user="hello"} 369295916436 (343.93 GB)
telemt_user_unique_ips_current{user="hello"} 700
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 19228.8 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1310825
telemt_connections_bad_total 228354
telemt_handshake_timeouts_total 12436
telemt_upstream_connect_attempt_total 3449
telemt_upstream_connect_success_total 3346
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 3449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 6886
telemt_me_reconnect_success_total 2355
telemt_me_reader_eof_total 2564
telemt_me_idle_close_by_peer_total 2564
telemt_me_route_drop_no_conn_total 546393
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 966588
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3705
telemt_desync_full_logged_total 1332
telemt_desync_suppressed_total 2373
telemt_desync_frames_bucket_total{bucket="1_2"} 656
telemt_desync_frames_bucket_total{bucket="3_10"} 1251
telemt_desync_frames_bucket_total{bucket="gt_10"} 1798
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2538
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2329
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 965954
telemt_user_connections_current{user="hello"} 2375
telemt_user_octets_from_client{user="hello"} 17447862748 (16.25 GB)
telemt_user_octets_to_client{user="hello"} 473590970404 (441.07 GB)
telemt_user_unique_ips_current{user="hello"} 886
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 24162.6 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371216
telemt_connections_bad_total 10704
telemt_connections_current 607
telemt_connections_me_current 607
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4187
telemt_upstream_connect_attempt_total 8178
telemt_upstream_connect_success_total 8145
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 332575
telemt_me_reconnect_success_total 3105
telemt_me_reader_eof_total 3183
telemt_me_idle_close_by_peer_total 3183
telemt_me_route_drop_no_conn_total 220194
telemt_me_route_drop_channel_closed_total 104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330074
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 740
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 469
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 286
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 3069
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3094
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 333758
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 7262043853 (6.76 GB)
telemt_user_octets_to_client{user="hello"} 82831623089 (77.14 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 23233.4 (6h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1311931
telemt_connections_bad_total 102819
telemt_connections_current 2311
telemt_connections_me_current 2311
telemt_handshake_timeouts_total 28239
telemt_upstream_connect_attempt_total 3814
telemt_upstream_connect_success_total 3813
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18160
telemt_me_reconnect_success_total 2638
telemt_me_reader_eof_total 2702
telemt_me_idle_close_by_peer_total 2701
telemt_me_route_drop_no_conn_total 589171
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1097543
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5065
telemt_desync_full_logged_total 1666
telemt_desync_suppressed_total 3399
telemt_desync_frames_bucket_total{bucket="1_2"} 1206
telemt_desync_frames_bucket_total{bucket="3_10"} 1715
telemt_desync_frames_bucket_total{bucket="gt_10"} 2144
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2624
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2577
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1096273
telemt_user_connections_current{user="hello"} 2311
telemt_user_octets_from_client{user="hello"} 22199298864 (20.67 GB)
telemt_user_octets_to_client{user="hello"} 637476962112 (593.70 GB)
telemt_user_unique_ips_current{user="hello"} 724
telemt_user_unique_ips_recent_window{user="hello"} 225
```