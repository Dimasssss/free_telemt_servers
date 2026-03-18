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

# Server Metrics 2026-03-18 20:20:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17708.4 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437124
telemt_connections_bad_total 25390
telemt_handshake_timeouts_total 9331
telemt_upstream_connect_attempt_total 3144
telemt_upstream_connect_success_total 3141
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1542
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 2251
telemt_me_reconnect_success_total 2236
telemt_me_reader_eof_total 2333
telemt_me_idle_close_by_peer_total 2333
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 183448
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376899
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2243
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1595
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 1001
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2282
telemt_me_writer_restored_same_endpoint_total 2218
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 376719
telemt_user_connections_current{user="hello"} 1006
telemt_user_octets_from_client{user="hello"} 7371836816 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 136759407244 (127.37 GB)
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 22536.7 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2065464
telemt_connections_bad_total 148446
telemt_connections_current 3132
telemt_connections_me_current 3132
telemt_handshake_timeouts_total 35509
telemt_upstream_connect_attempt_total 3504
telemt_upstream_connect_success_total 3485
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2373
telemt_me_reconnect_success_total 2356
telemt_me_reader_eof_total 2385
telemt_me_idle_close_by_peer_total 2384
telemt_me_route_drop_no_conn_total 1807119
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1783287
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6258
telemt_desync_full_logged_total 2020
telemt_desync_suppressed_total 4238
telemt_desync_frames_bucket_total{bucket="1_2"} 1089
telemt_desync_frames_bucket_total{bucket="3_10"} 2473
telemt_desync_frames_bucket_total{bucket="gt_10"} 2696
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2318
telemt_me_writer_restored_same_endpoint_total 2354
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1778646
telemt_user_connections_current{user="hello"} 3132
telemt_user_octets_from_client{user="hello"} 27337577304 (25.46 GB)
telemt_user_octets_to_client{user="hello"} 601735007784 (560.41 GB)
telemt_user_unique_ips_current{user="hello"} 1059
telemt_user_unique_ips_recent_window{user="hello"} 360
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 22464.9 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1570611
telemt_connections_bad_total 128329
telemt_connections_current 2716
telemt_connections_me_current 2716
telemt_handshake_timeouts_total 36626
telemt_upstream_connect_attempt_total 3200
telemt_upstream_connect_success_total 3183
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2072
telemt_me_reconnect_success_total 2053
telemt_me_reader_eof_total 2182
telemt_me_idle_close_by_peer_total 2182
telemt_me_route_drop_no_conn_total 636891
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1262268
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6096
telemt_desync_full_logged_total 1865
telemt_desync_suppressed_total 4231
telemt_desync_frames_bucket_total{bucket="1_2"} 1533
telemt_desync_frames_bucket_total{bucket="3_10"} 2302
telemt_desync_frames_bucket_total{bucket="gt_10"} 2261
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2106
telemt_me_writer_restored_same_endpoint_total 2036
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 1261467
telemt_user_connections_current{user="hello"} 2716
telemt_user_octets_from_client{user="hello"} 27029334956 (25.17 GB)
telemt_user_octets_to_client{user="hello"} 630496592560 (587.20 GB)
telemt_user_unique_ips_current{user="hello"} 905
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 23179.5 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2207791
telemt_connections_bad_total 62840
telemt_connections_current 2214
telemt_connections_me_current 2214
telemt_handshake_timeouts_total 22103
telemt_upstream_connect_attempt_total 3482
telemt_upstream_connect_success_total 3446
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 3482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2292
telemt_me_reconnect_success_total 2265
telemt_me_reader_eof_total 2359
telemt_me_idle_close_by_peer_total 2358
telemt_me_route_drop_no_conn_total 3702313
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1971497
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7464
telemt_desync_full_logged_total 1940
telemt_desync_suppressed_total 5524
telemt_desync_frames_bucket_total{bucket="1_2"} 1622
telemt_desync_frames_bucket_total{bucket="3_10"} 3454
telemt_desync_frames_bucket_total{bucket="gt_10"} 2388
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2283
telemt_me_writer_restored_same_endpoint_total 2254
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 1971404
telemt_user_connections_current{user="hello"} 2214
telemt_user_octets_from_client{user="hello"} 18498041516 (17.23 GB)
telemt_user_octets_to_client{user="hello"} 345231786632 (321.52 GB)
telemt_user_unique_ips_current{user="hello"} 792
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 17694.1 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1244498
telemt_connections_bad_total 220713
telemt_handshake_timeouts_total 11862
telemt_upstream_connect_attempt_total 3218
telemt_upstream_connect_success_total 3122
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 3218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 5468
telemt_me_reconnect_success_total 2219
telemt_me_reader_eof_total 2381
telemt_me_idle_close_by_peer_total 2381
telemt_me_route_drop_no_conn_total 525426
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 914078
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3344
telemt_desync_full_logged_total 1209
telemt_desync_suppressed_total 2135
telemt_desync_frames_bucket_total{bucket="1_2"} 612
telemt_desync_frames_bucket_total{bucket="3_10"} 1147
telemt_desync_frames_bucket_total{bucket="gt_10"} 1585
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2359
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 2193
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 913444
telemt_user_connections_current{user="hello"} 2579
telemt_user_octets_from_client{user="hello"} 15846389280 (14.76 GB)
telemt_user_octets_to_client{user="hello"} 440510987472 (410.26 GB)
telemt_user_unique_ips_current{user="hello"} 958
telemt_user_unique_ips_recent_window{user="hello"} 335
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 22628.7 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358114
telemt_connections_bad_total 10691
telemt_connections_current 662
telemt_connections_me_current 662
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4053
telemt_upstream_connect_attempt_total 7938
telemt_upstream_connect_success_total 7905
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 332380
telemt_me_reconnect_success_total 2910
telemt_me_reader_eof_total 2973
telemt_me_idle_close_by_peer_total 2973
telemt_me_route_drop_no_conn_total 214802
telemt_me_route_drop_channel_closed_total 103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318075
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2871
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2899
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 321760
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 6911083365 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 76305532653 (71.07 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 21698.8 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1259295
telemt_connections_bad_total 100975
telemt_connections_current 2479
telemt_connections_me_current 2479
telemt_handshake_timeouts_total 25867
telemt_upstream_connect_attempt_total 3589
telemt_upstream_connect_success_total 3588
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17979
telemt_me_reconnect_success_total 2458
telemt_me_reader_eof_total 2509
telemt_me_idle_close_by_peer_total 2509
telemt_me_route_drop_no_conn_total 565264
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1051038
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4712
telemt_desync_full_logged_total 1564
telemt_desync_suppressed_total 3148
telemt_desync_frames_bucket_total{bucket="1_2"} 1095
telemt_desync_frames_bucket_total{bucket="3_10"} 1611
telemt_desync_frames_bucket_total{bucket="gt_10"} 2006
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2441
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2397
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1049794
telemt_user_connections_current{user="hello"} 2479
telemt_user_octets_from_client{user="hello"} 20811158132 (19.38 GB)
telemt_user_octets_to_client{user="hello"} 607549067644 (565.82 GB)
telemt_user_unique_ips_current{user="hello"} 779
telemt_user_unique_ips_recent_window{user="hello"} 285
```