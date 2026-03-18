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

# Server Metrics 2026-03-18 20:25:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18015.8 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443358
telemt_connections_bad_total 25661
telemt_handshake_timeouts_total 9405
telemt_upstream_connect_attempt_total 3159
telemt_upstream_connect_success_total 3156
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 2266
telemt_me_reconnect_success_total 2251
telemt_me_reader_eof_total 2348
telemt_me_idle_close_by_peer_total 2348
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 185161
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381012
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2274
telemt_desync_full_logged_total 664
telemt_desync_suppressed_total 1610
telemt_desync_frames_bucket_total{bucket="1_2"} 535
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 1020
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2297
telemt_me_writer_restored_same_endpoint_total 2233
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 380832
telemt_user_connections_current{user="hello"} 984
telemt_user_octets_from_client{user="hello"} 7445435148 (6.93 GB)
telemt_user_octets_to_client{user="hello"} 138355635176 (128.85 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 22843.7 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2080084
telemt_connections_bad_total 148506
telemt_connections_current 3044
telemt_connections_me_current 3044
telemt_handshake_timeouts_total 35646
telemt_upstream_connect_attempt_total 3594
telemt_upstream_connect_success_total 3572
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2420
telemt_me_reconnect_success_total 2403
telemt_me_reader_eof_total 2437
telemt_me_idle_close_by_peer_total 2436
telemt_me_route_drop_no_conn_total 1813198
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1797169
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6332
telemt_desync_full_logged_total 2042
telemt_desync_suppressed_total 4290
telemt_desync_frames_bucket_total{bucket="1_2"} 1099
telemt_desync_frames_bucket_total{bucket="3_10"} 2497
telemt_desync_frames_bucket_total{bucket="gt_10"} 2736
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2367
telemt_me_writer_restored_same_endpoint_total 2401
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1792545
telemt_user_connections_current{user="hello"} 3044
telemt_user_octets_from_client{user="hello"} 27533905324 (25.64 GB)
telemt_user_octets_to_client{user="hello"} 610332185488 (568.42 GB)
telemt_user_unique_ips_current{user="hello"} 1037
telemt_user_unique_ips_recent_window{user="hello"} 343
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 22772.6 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1584133
telemt_connections_bad_total 128824
telemt_connections_current 2714
telemt_connections_me_current 2714
telemt_handshake_timeouts_total 37220
telemt_upstream_connect_attempt_total 3293
telemt_upstream_connect_success_total 3276
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2122
telemt_me_reconnect_success_total 2103
telemt_me_reader_eof_total 2236
telemt_me_idle_close_by_peer_total 2236
telemt_me_route_drop_no_conn_total 642602
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1273938
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6170
telemt_desync_full_logged_total 1888
telemt_desync_suppressed_total 4282
telemt_desync_frames_bucket_total{bucket="1_2"} 1553
telemt_desync_frames_bucket_total{bucket="3_10"} 2322
telemt_desync_frames_bucket_total{bucket="gt_10"} 2295
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2156
telemt_me_writer_restored_same_endpoint_total 2086
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 1273139
telemt_user_connections_current{user="hello"} 2714
telemt_user_octets_from_client{user="hello"} 27269663676 (25.40 GB)
telemt_user_octets_to_client{user="hello"} 637831612392 (594.03 GB)
telemt_user_unique_ips_current{user="hello"} 902
telemt_user_unique_ips_recent_window{user="hello"} 309
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 23486.7 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2220736
telemt_connections_bad_total 65254
telemt_connections_current 2115
telemt_connections_me_current 2115
telemt_handshake_timeouts_total 22165
telemt_upstream_connect_attempt_total 3533
telemt_upstream_connect_success_total 3497
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 3533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2307
telemt_me_reconnect_success_total 2280
telemt_me_reader_eof_total 2374
telemt_me_idle_close_by_peer_total 2373
telemt_me_route_drop_no_conn_total 3707815
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1981591
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7530
telemt_desync_full_logged_total 1959
telemt_desync_suppressed_total 5571
telemt_desync_frames_bucket_total{bucket="1_2"} 1638
telemt_desync_frames_bucket_total{bucket="3_10"} 3479
telemt_desync_frames_bucket_total{bucket="gt_10"} 2413
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2298
telemt_me_writer_restored_same_endpoint_total 2269
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 1981498
telemt_user_connections_current{user="hello"} 2115
telemt_user_octets_from_client{user="hello"} 18638891944 (17.36 GB)
telemt_user_octets_to_client{user="hello"} 350539335720 (326.47 GB)
telemt_user_unique_ips_current{user="hello"} 766
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18001.6 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1256287
telemt_connections_bad_total 221047
telemt_handshake_timeouts_total 11918
telemt_upstream_connect_attempt_total 3250
telemt_upstream_connect_success_total 3154
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 3250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 5500
telemt_me_reconnect_success_total 2251
telemt_me_reader_eof_total 2413
telemt_me_idle_close_by_peer_total 2413
telemt_me_route_drop_no_conn_total 529713
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924275
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3418
telemt_desync_full_logged_total 1235
telemt_desync_suppressed_total 2183
telemt_desync_frames_bucket_total{bucket="1_2"} 624
telemt_desync_frames_bucket_total{bucket="3_10"} 1176
telemt_desync_frames_bucket_total{bucket="gt_10"} 1618
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2391
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 2225
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 923642
telemt_user_connections_current{user="hello"} 2496
telemt_user_octets_from_client{user="hello"} 16114506320 (15.01 GB)
telemt_user_octets_to_client{user="hello"} 448187484032 (417.41 GB)
telemt_user_unique_ips_current{user="hello"} 915
telemt_user_unique_ips_recent_window{user="hello"} 317
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 22934.8 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360645
telemt_connections_bad_total 10692
telemt_connections_current 676
telemt_connections_me_current 676
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 4085
telemt_upstream_connect_attempt_total 7996
telemt_upstream_connect_success_total 7963
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 332438
telemt_me_reconnect_success_total 2968
telemt_me_reader_eof_total 3036
telemt_me_idle_close_by_peer_total 3036
telemt_me_route_drop_no_conn_total 215858
telemt_me_route_drop_channel_closed_total 103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320411
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 674
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2929
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2957
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 324096
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 6951066957 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 77911561341 (72.56 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 22006.1 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1269465
telemt_connections_bad_total 101216
telemt_connections_current 2386
telemt_connections_me_current 2386
telemt_handshake_timeouts_total 26128
telemt_upstream_connect_attempt_total 3649
telemt_upstream_connect_success_total 3648
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18038
telemt_me_reconnect_success_total 2517
telemt_me_reader_eof_total 2572
telemt_me_idle_close_by_peer_total 2572
telemt_me_route_drop_no_conn_total 569758
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1060477
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4789
telemt_desync_full_logged_total 1588
telemt_desync_suppressed_total 3201
telemt_desync_frames_bucket_total{bucket="1_2"} 1123
telemt_desync_frames_bucket_total{bucket="3_10"} 1637
telemt_desync_frames_bucket_total{bucket="gt_10"} 2029
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2500
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2456
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1059232
telemt_user_connections_current{user="hello"} 2386
telemt_user_octets_from_client{user="hello"} 20967793316 (19.53 GB)
telemt_user_octets_to_client{user="hello"} 615851376172 (573.56 GB)
telemt_user_unique_ips_current{user="hello"} 749
telemt_user_unique_ips_recent_window{user="hello"} 249
```