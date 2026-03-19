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

# Server Metrics 2026-03-19 05:22:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 27241.6 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396112
telemt_connections_bad_total 40112
telemt_connections_current 1008
telemt_connections_me_current 1008
telemt_handshake_timeouts_total 21016
telemt_upstream_connect_attempt_total 5280
telemt_upstream_connect_success_total 5191
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 5280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3834
telemt_me_reconnect_success_total 3816
telemt_me_reader_eof_total 4027
telemt_me_idle_close_by_peer_total 4026
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 103096
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289874
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1964
telemt_desync_full_logged_total 543
telemt_desync_suppressed_total 1421
telemt_desync_frames_bucket_total{bucket="1_2"} 712
telemt_desync_frames_bucket_total{bucket="3_10"} 781
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3847
telemt_me_writer_restored_same_endpoint_total 3799
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 287128
telemt_user_connections_current{user="hello"} 1008
telemt_user_octets_from_client{user="hello"} 3647477200 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 96219396512 (89.61 GB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 27245.7 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774200
telemt_connections_bad_total 46942
telemt_connections_current 3064
telemt_connections_me_current 3064
telemt_handshake_timeouts_total 23366
telemt_upstream_connect_attempt_total 5089
telemt_upstream_connect_success_total 4995
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 5089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 3627
telemt_me_reconnect_success_total 3608
telemt_me_reader_eof_total 3813
telemt_me_idle_close_by_peer_total 3813
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 236352
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642537
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2592
telemt_desync_full_logged_total 877
telemt_desync_suppressed_total 1715
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 965
telemt_desync_frames_bucket_total{bucket="gt_10"} 1131
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3672
telemt_me_writer_restored_same_endpoint_total 3589
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 642437
telemt_user_connections_current{user="hello"} 3064
telemt_user_octets_from_client{user="hello"} 15993903392 (14.90 GB)
telemt_user_octets_to_client{user="hello"} 281682618232 (262.34 GB)
telemt_user_unique_ips_current{user="hello"} 1080
telemt_user_unique_ips_recent_window{user="hello"} 377
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 27243.1 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 663008
telemt_connections_bad_total 116875
telemt_connections_current 2334
telemt_connections_me_current 2334
telemt_handshake_timeouts_total 23465
telemt_upstream_connect_attempt_total 4992
telemt_upstream_connect_success_total 4992
telemt_upstream_connect_attempts_per_request{bucket="1"} 4992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3619
telemt_me_reconnect_success_total 3605
telemt_me_reader_eof_total 3820
telemt_me_idle_close_by_peer_total 3820
telemt_me_route_drop_no_conn_total 195432
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476684
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2479
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 1677
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 886
telemt_desync_frames_bucket_total{bucket="gt_10"} 1218
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 3668
telemt_me_writer_restored_same_endpoint_total 3589
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 476668
telemt_user_connections_current{user="hello"} 2334
telemt_user_octets_from_client{user="hello"} 9820139092 (9.15 GB)
telemt_user_octets_to_client{user="hello"} 293916686408 (273.73 GB)
telemt_user_unique_ips_current{user="hello"} 860
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 27296.1 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744019
telemt_connections_bad_total 85987
telemt_connections_current 2034
telemt_connections_me_current 2034
telemt_handshake_timeouts_total 17152
telemt_upstream_connect_attempt_total 4825
telemt_upstream_connect_success_total 4825
telemt_upstream_connect_attempts_per_request{bucket="1"} 4825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 3459
telemt_me_reconnect_success_total 3441
telemt_me_reader_eof_total 3637
telemt_me_idle_close_by_peer_total 3636
telemt_me_route_drop_no_conn_total 212526
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470193
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1468
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 934
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 608
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3487
telemt_me_writer_restored_same_endpoint_total 3417
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 469152
telemt_user_connections_current{user="hello"} 2034
telemt_user_octets_from_client{user="hello"} 7115994780 (6.63 GB)
telemt_user_octets_to_client{user="hello"} 179673449752 (167.33 GB)
telemt_user_unique_ips_current{user="hello"} 761
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 27239.5 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 854688
telemt_connections_bad_total 232266
telemt_connections_current 2420
telemt_connections_me_current 2420
telemt_handshake_timeouts_total 23754
telemt_upstream_connect_attempt_total 4948
telemt_upstream_connect_success_total 4918
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 3553
telemt_me_reconnect_success_total 3532
telemt_me_reader_eof_total 3738
telemt_me_idle_close_by_peer_total 3738
telemt_me_route_drop_no_conn_total 209802
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507744
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2369
telemt_desync_full_logged_total 864
telemt_desync_suppressed_total 1505
telemt_desync_frames_bucket_total{bucket="1_2"} 558
telemt_desync_frames_bucket_total{bucket="3_10"} 1005
telemt_desync_frames_bucket_total{bucket="gt_10"} 806
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 3569
telemt_me_writer_restored_same_endpoint_total 3508
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 507653
telemt_user_connections_current{user="hello"} 2420
telemt_user_octets_from_client{user="hello"} 14494943020 (13.50 GB)
telemt_user_octets_to_client{user="hello"} 287466277384 (267.72 GB)
telemt_user_unique_ips_current{user="hello"} 910
telemt_user_unique_ips_recent_window{user="hello"} 349
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 27251.0 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149333
telemt_connections_bad_total 10571
telemt_connections_current 547
telemt_connections_me_current 547
telemt_handshake_timeouts_total 1070
telemt_upstream_connect_attempt_total 7600
telemt_upstream_connect_success_total 7393
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 7600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3839
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 9134
telemt_me_reconnect_success_total 6010
telemt_me_reader_eof_total 6331
telemt_me_idle_close_by_peer_total 6331
telemt_me_route_drop_no_conn_total 59990
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130815
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 186
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6126
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 5980
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 130808
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 2255883412 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 78479958476 (73.09 GB)
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 27242.1 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503085
telemt_connections_bad_total 50045
telemt_connections_current 2315
telemt_connections_me_current 2315
telemt_handshake_timeouts_total 24709
telemt_upstream_connect_attempt_total 5619
telemt_upstream_connect_success_total 5619
telemt_upstream_connect_attempts_per_request{bucket="1"} 5619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4253
telemt_me_reconnect_success_total 4241
telemt_me_reader_eof_total 4478
telemt_me_idle_close_by_peer_total 4478
telemt_me_route_drop_no_conn_total 143211
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412301
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2248
telemt_desync_full_logged_total 828
telemt_desync_suppressed_total 1420
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 863
telemt_desync_frames_bucket_total{bucket="gt_10"} 920
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4289
telemt_me_writer_restored_same_endpoint_total 4226
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 412338
telemt_user_connections_current{user="hello"} 2315
telemt_user_octets_from_client{user="hello"} 5285093196 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 240747617728 (224.21 GB)
telemt_user_unique_ips_current{user="hello"} 768
telemt_user_unique_ips_recent_window{user="hello"} 313
```