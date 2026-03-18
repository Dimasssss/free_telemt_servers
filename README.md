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

# Server Metrics 2026-03-18 20:35:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18629.6 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453989
telemt_connections_bad_total 26210
telemt_handshake_timeouts_total 9504
telemt_upstream_connect_attempt_total 3286
telemt_upstream_connect_success_total 3283
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 2350
telemt_me_reconnect_success_total 2335
telemt_me_reader_eof_total 2436
telemt_me_idle_close_by_peer_total 2436
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 188273
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388666
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2318
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1638
telemt_desync_frames_bucket_total{bucket="1_2"} 537
telemt_desync_frames_bucket_total{bucket="3_10"} 740
telemt_desync_frames_bucket_total{bucket="gt_10"} 1041
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2381
telemt_me_writer_restored_same_endpoint_total 2317
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 388484
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 7515615108 (7.00 GB)
telemt_user_octets_to_client{user="hello"} 141607389744 (131.88 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 23457.6 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2106909
telemt_connections_bad_total 148553
telemt_connections_current 2917
telemt_connections_me_current 2917
telemt_handshake_timeouts_total 35891
telemt_upstream_connect_attempt_total 3643
telemt_upstream_connect_success_total 3621
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2453
telemt_me_reconnect_success_total 2436
telemt_me_reader_eof_total 2470
telemt_me_idle_close_by_peer_total 2469
telemt_me_route_drop_no_conn_total 1823319
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1823008
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6505
telemt_desync_full_logged_total 2097
telemt_desync_suppressed_total 4408
telemt_desync_frames_bucket_total{bucket="1_2"} 1131
telemt_desync_frames_bucket_total{bucket="3_10"} 2566
telemt_desync_frames_bucket_total{bucket="gt_10"} 2808
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2400
telemt_me_writer_restored_same_endpoint_total 2434
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1818388
telemt_user_connections_current{user="hello"} 2917
telemt_user_octets_from_client{user="hello"} 27935969636 (26.02 GB)
telemt_user_octets_to_client{user="hello"} 624886081408 (581.97 GB)
telemt_user_unique_ips_current{user="hello"} 1001
telemt_user_unique_ips_recent_window{user="hello"} 337
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 23386.1 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1608083
telemt_connections_bad_total 130112
telemt_connections_current 2516
telemt_connections_me_current 2516
telemt_handshake_timeouts_total 38337
telemt_upstream_connect_attempt_total 3327
telemt_upstream_connect_success_total 3310
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2156
telemt_me_reconnect_success_total 2136
telemt_me_reader_eof_total 2271
telemt_me_idle_close_by_peer_total 2271
telemt_me_route_drop_no_conn_total 652234
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1294098
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6290
telemt_desync_full_logged_total 1920
telemt_desync_suppressed_total 4370
telemt_desync_frames_bucket_total{bucket="1_2"} 1565
telemt_desync_frames_bucket_total{bucket="3_10"} 2360
telemt_desync_frames_bucket_total{bucket="gt_10"} 2365
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2191
telemt_me_writer_restored_same_endpoint_total 2119
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1293295
telemt_user_connections_current{user="hello"} 2516
telemt_user_octets_from_client{user="hello"} 27558915036 (25.67 GB)
telemt_user_octets_to_client{user="hello"} 653781136420 (608.88 GB)
telemt_user_unique_ips_current{user="hello"} 877
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 24100.7 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2243842
telemt_connections_bad_total 69798
telemt_connections_current 2042
telemt_connections_me_current 2042
telemt_handshake_timeouts_total 22343
telemt_upstream_connect_attempt_total 3619
telemt_upstream_connect_success_total 3583
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 3619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1721
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2386
telemt_me_reconnect_success_total 2359
telemt_me_reader_eof_total 2458
telemt_me_idle_close_by_peer_total 2457
telemt_me_route_drop_no_conn_total 3715851
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1999123
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7583
telemt_desync_full_logged_total 1981
telemt_desync_suppressed_total 5602
telemt_desync_frames_bucket_total{bucket="1_2"} 1640
telemt_desync_frames_bucket_total{bucket="3_10"} 3500
telemt_desync_frames_bucket_total{bucket="gt_10"} 2443
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2378
telemt_me_writer_restored_same_endpoint_total 2348
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 1999030
telemt_user_connections_current{user="hello"} 2042
telemt_user_octets_from_client{user="hello"} 18889079672 (17.59 GB)
telemt_user_octets_to_client{user="hello"} 360865553536 (336.08 GB)
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18615.6 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1287522
telemt_connections_bad_total 227961
telemt_handshake_timeouts_total 12226
telemt_upstream_connect_attempt_total 3344
telemt_upstream_connect_success_total 3243
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 3344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 6826
telemt_me_reconnect_success_total 2296
telemt_me_reader_eof_total 2500
telemt_me_idle_close_by_peer_total 2500
telemt_me_route_drop_no_conn_total 538213
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 945967
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3559
telemt_desync_full_logged_total 1289
telemt_desync_suppressed_total 2270
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 1213
telemt_desync_frames_bucket_total{bucket="gt_10"} 1704
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2478
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 2270
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 945337
telemt_user_connections_current{user="hello"} 2524
telemt_user_octets_from_client{user="hello"} 16963202596 (15.80 GB)
telemt_user_octets_to_client{user="hello"} 461670172236 (429.96 GB)
telemt_user_unique_ips_current{user="hello"} 915
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 23548.4 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366207
telemt_connections_bad_total 10700
telemt_connections_current 682
telemt_connections_me_current 682
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4157
telemt_upstream_connect_attempt_total 8104
telemt_upstream_connect_success_total 8071
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3864
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 332503
telemt_me_reconnect_success_total 3033
telemt_me_reader_eof_total 3103
telemt_me_idle_close_by_peer_total 3103
telemt_me_route_drop_no_conn_total 218051
telemt_me_route_drop_channel_closed_total 104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325208
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 714
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 451
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2995
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 3022
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 328892
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 6990928277 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 80517791165 (74.99 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 22620.1 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1291346
telemt_connections_bad_total 102111
telemt_connections_current 2315
telemt_connections_me_current 2315
telemt_handshake_timeouts_total 26889
telemt_upstream_connect_attempt_total 3749
telemt_upstream_connect_success_total 3748
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18095
telemt_me_reconnect_success_total 2574
telemt_me_reader_eof_total 2636
telemt_me_idle_close_by_peer_total 2635
telemt_me_route_drop_no_conn_total 580023
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1079912
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4910
telemt_desync_full_logged_total 1628
telemt_desync_suppressed_total 3282
telemt_desync_frames_bucket_total{bucket="1_2"} 1157
telemt_desync_frames_bucket_total{bucket="3_10"} 1676
telemt_desync_frames_bucket_total{bucket="gt_10"} 2077
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2558
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2513
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1078662
telemt_user_connections_current{user="hello"} 2315
telemt_user_octets_from_client{user="hello"} 21314044372 (19.85 GB)
telemt_user_octets_to_client{user="hello"} 627176857724 (584.10 GB)
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 262
```