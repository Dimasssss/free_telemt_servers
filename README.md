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

# Server Metrics 2026-03-19 04:31:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 24177.3 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334225
telemt_connections_bad_total 35642
telemt_connections_current 923
telemt_connections_me_current 923
telemt_handshake_timeouts_total 19734
telemt_upstream_connect_attempt_total 4716
telemt_upstream_connect_success_total 4643
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 4716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3458
telemt_me_reconnect_success_total 3442
telemt_me_reader_eof_total 3622
telemt_me_idle_close_by_peer_total 3622
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 84727
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242880
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1730
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 1263
telemt_desync_frames_bucket_total{bucket="1_2"} 647
telemt_desync_frames_bucket_total{bucket="3_10"} 703
telemt_desync_frames_bucket_total{bucket="gt_10"} 380
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3470
telemt_me_writer_restored_same_endpoint_total 3425
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 240127
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 2701293312 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 72004955948 (67.06 GB)
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 24181.4 (6h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614043
telemt_connections_bad_total 39210
telemt_connections_current 2624
telemt_connections_me_current 2624
telemt_handshake_timeouts_total 17392
telemt_upstream_connect_attempt_total 4552
telemt_upstream_connect_success_total 4470
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 4552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_reconnect_attempts_total 3277
telemt_me_reconnect_success_total 3260
telemt_me_reader_eof_total 3434
telemt_me_idle_close_by_peer_total 3434
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 183703
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507150
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1934
telemt_desync_full_logged_total 654
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 390
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3315
telemt_me_writer_restored_same_endpoint_total 3242
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 507105
telemt_user_connections_current{user="hello"} 2624
telemt_user_octets_from_client{user="hello"} 14539258604 (13.54 GB)
telemt_user_octets_to_client{user="hello"} 220974939568 (205.80 GB)
telemt_user_unique_ips_current{user="hello"} 962
telemt_user_unique_ips_recent_window{user="hello"} 375
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 24178.8 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518985
telemt_connections_bad_total 105089
telemt_connections_current 2179
telemt_connections_me_current 2179
telemt_handshake_timeouts_total 16406
telemt_upstream_connect_attempt_total 4459
telemt_upstream_connect_success_total 4459
telemt_upstream_connect_attempts_per_request{bucket="1"} 4459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3263
telemt_me_reconnect_success_total 3252
telemt_me_reader_eof_total 3441
telemt_me_idle_close_by_peer_total 3441
telemt_me_route_drop_no_conn_total 152784
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370567
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1740
telemt_desync_full_logged_total 647
telemt_desync_suppressed_total 1093
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 728
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3305
telemt_me_writer_restored_same_endpoint_total 3236
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 370567
telemt_user_connections_current{user="hello"} 2179
telemt_user_octets_from_client{user="hello"} 8140952248 (7.58 GB)
telemt_user_octets_to_client{user="hello"} 231515491472 (215.62 GB)
telemt_user_unique_ips_current{user="hello"} 767
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 24231.9 (6h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 611445
telemt_connections_bad_total 72248
telemt_connections_current 1651
telemt_connections_me_current 1651
telemt_handshake_timeouts_total 12710
telemt_upstream_connect_attempt_total 4323
telemt_upstream_connect_success_total 4323
telemt_upstream_connect_attempts_per_request{bucket="1"} 4323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 3132
telemt_me_reconnect_success_total 3120
telemt_me_reader_eof_total 3289
telemt_me_idle_close_by_peer_total 3288
telemt_me_route_drop_no_conn_total 154104
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369188
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1070
telemt_desync_full_logged_total 393
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 462
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3156
telemt_me_writer_restored_same_endpoint_total 3096
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 368949
telemt_user_connections_current{user="hello"} 1651
telemt_user_octets_from_client{user="hello"} 4419197020 (4.12 GB)
telemt_user_octets_to_client{user="hello"} 142786817176 (132.98 GB)
telemt_user_unique_ips_current{user="hello"} 644
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 24175.3 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 683420
telemt_connections_bad_total 190487
telemt_connections_current 1911
telemt_connections_me_current 1911
telemt_handshake_timeouts_total 19405
telemt_upstream_connect_attempt_total 4468
telemt_upstream_connect_success_total 4440
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 3248
telemt_me_reconnect_success_total 3229
telemt_me_reader_eof_total 3409
telemt_me_idle_close_by_peer_total 3409
telemt_me_route_drop_no_conn_total 166964
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400499
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1744
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1068
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 599
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3259
telemt_me_writer_restored_same_endpoint_total 3205
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 400413
telemt_user_connections_current{user="hello"} 1911
telemt_user_octets_from_client{user="hello"} 11573524712 (10.78 GB)
telemt_user_octets_to_client{user="hello"} 233808356524 (217.75 GB)
telemt_user_unique_ips_current{user="hello"} 771
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 24186.9 (6h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120405
telemt_connections_bad_total 10274
telemt_connections_current 510
telemt_connections_me_current 510
telemt_handshake_timeouts_total 550
telemt_upstream_connect_attempt_total 6701
telemt_upstream_connect_success_total 6519
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 6701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3451
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_reconnect_attempts_total 7157
telemt_me_reconnect_success_total 5316
telemt_me_reader_eof_total 5574
telemt_me_idle_close_by_peer_total 5574
telemt_me_route_drop_no_conn_total 49660
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105414
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 108
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5388
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5286
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 105404
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 1952916012 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 67550085436 (62.91 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 24177.6 (6h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391942
telemt_connections_bad_total 42829
telemt_connections_current 1734
telemt_connections_me_current 1734
telemt_handshake_timeouts_total 20337
telemt_upstream_connect_attempt_total 5018
telemt_upstream_connect_success_total 5018
telemt_upstream_connect_attempts_per_request{bucket="1"} 5018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3826
telemt_me_reconnect_success_total 3816
telemt_me_reader_eof_total 4024
telemt_me_idle_close_by_peer_total 4024
telemt_me_route_drop_no_conn_total 110545
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316574
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1610
telemt_desync_full_logged_total 614
telemt_desync_suppressed_total 996
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 627
telemt_desync_frames_bucket_total{bucket="gt_10"} 656
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3856
telemt_me_writer_restored_same_endpoint_total 3801
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 316592
telemt_user_connections_current{user="hello"} 1734
telemt_user_octets_from_client{user="hello"} 3789123672 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 181802512504 (169.32 GB)
telemt_user_unique_ips_current{user="hello"} 629
telemt_user_unique_ips_recent_window{user="hello"} 210
```