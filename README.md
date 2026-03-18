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

# Server Metrics 2026-03-18 20:00:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16481.9 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414804
telemt_connections_bad_total 24358
telemt_handshake_timeouts_total 9090
telemt_upstream_connect_attempt_total 2984
telemt_upstream_connect_success_total 2981
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 2134
telemt_me_reconnect_success_total 2121
telemt_me_reader_eof_total 2210
telemt_me_idle_close_by_peer_total 2210
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 175429
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358978
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2143
telemt_desync_full_logged_total 606
telemt_desync_suppressed_total 1537
telemt_desync_frames_bucket_total{bucket="1_2"} 511
telemt_desync_frames_bucket_total{bucket="3_10"} 682
telemt_desync_frames_bucket_total{bucket="gt_10"} 950
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2161
telemt_me_writer_restored_same_endpoint_total 2103
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 358810
telemt_user_connections_current{user="hello"} 1100
telemt_user_octets_from_client{user="hello"} 7151578728 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 127707540000 (118.94 GB)
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 21310.0 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1991708
telemt_connections_bad_total 139570
telemt_connections_current 3232
telemt_connections_me_current 3232
telemt_handshake_timeouts_total 34337
telemt_upstream_connect_attempt_total 3375
telemt_upstream_connect_success_total 3357
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 2293
telemt_me_reconnect_success_total 2276
telemt_me_reader_eof_total 2298
telemt_me_idle_close_by_peer_total 2297
telemt_me_route_drop_no_conn_total 1779899
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1721205
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6009
telemt_desync_full_logged_total 1929
telemt_desync_suppressed_total 4080
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 2388
telemt_desync_frames_bucket_total{bucket="gt_10"} 2586
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2233
telemt_me_writer_restored_same_endpoint_total 2274
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1716477
telemt_user_connections_current{user="hello"} 3232
telemt_user_octets_from_client{user="hello"} 26432588932 (24.62 GB)
telemt_user_octets_to_client{user="hello"} 571100127768 (531.88 GB)
telemt_user_unique_ips_current{user="hello"} 1072
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 21238.3 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1513630
telemt_connections_bad_total 125212
telemt_connections_current 2821
telemt_connections_me_current 2821
telemt_handshake_timeouts_total 33716
telemt_upstream_connect_attempt_total 3048
telemt_upstream_connect_success_total 3032
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1964
telemt_me_reconnect_success_total 1947
telemt_me_reader_eof_total 2070
telemt_me_idle_close_by_peer_total 2070
telemt_me_route_drop_no_conn_total 614679
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1214008
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5790
telemt_desync_full_logged_total 1789
telemt_desync_suppressed_total 4001
telemt_desync_frames_bucket_total{bucket="1_2"} 1447
telemt_desync_frames_bucket_total{bucket="3_10"} 2189
telemt_desync_frames_bucket_total{bucket="gt_10"} 2154
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 1997
telemt_me_writer_restored_same_endpoint_total 1930
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 1213210
telemt_user_connections_current{user="hello"} 2821
telemt_user_octets_from_client{user="hello"} 26399197796 (24.59 GB)
telemt_user_octets_to_client{user="hello"} 597301481512 (556.28 GB)
telemt_user_unique_ips_current{user="hello"} 950
telemt_user_unique_ips_recent_window{user="hello"} 331
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 21953.0 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2153022
telemt_connections_bad_total 55449
telemt_connections_current 2430
telemt_connections_me_current 2430
telemt_handshake_timeouts_total 21815
telemt_upstream_connect_attempt_total 3343
telemt_upstream_connect_success_total 3308
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1575
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 2197
telemt_me_reconnect_success_total 2170
telemt_me_reader_eof_total 2258
telemt_me_idle_close_by_peer_total 2257
telemt_me_route_drop_no_conn_total 3676368
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1926581
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7170
telemt_desync_full_logged_total 1845
telemt_desync_suppressed_total 5325
telemt_desync_frames_bucket_total{bucket="1_2"} 1567
telemt_desync_frames_bucket_total{bucket="3_10"} 3337
telemt_desync_frames_bucket_total{bucket="gt_10"} 2266
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2186
telemt_me_writer_restored_same_endpoint_total 2159
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1926490
telemt_user_connections_current{user="hello"} 2430
telemt_user_octets_from_client{user="hello"} 17765046328 (16.54 GB)
telemt_user_octets_to_client{user="hello"} 325972866940 (303.59 GB)
telemt_user_unique_ips_current{user="hello"} 825
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16467.8 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1187202
telemt_connections_bad_total 217530
telemt_handshake_timeouts_total 11408
telemt_upstream_connect_attempt_total 2973
telemt_upstream_connect_success_total 2882
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 2973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 4119
telemt_me_reconnect_success_total 2023
telemt_me_reader_eof_total 2146
telemt_me_idle_close_by_peer_total 2146
telemt_me_route_drop_no_conn_total 505811
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 867322
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3064
telemt_desync_full_logged_total 1102
telemt_desync_suppressed_total 1962
telemt_desync_frames_bucket_total{bucket="1_2"} 566
telemt_desync_frames_bucket_total{bucket="3_10"} 1045
telemt_desync_frames_bucket_total{bucket="gt_10"} 1453
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2124
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1997
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 866686
telemt_user_connections_current{user="hello"} 2864
telemt_user_octets_from_client{user="hello"} 15121019240 (14.08 GB)
telemt_user_octets_to_client{user="hello"} 412055251556 (383.76 GB)
telemt_user_unique_ips_current{user="hello"} 975
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 21401.0 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346498
telemt_connections_bad_total 10663
telemt_connections_current 654
telemt_connections_me_current 654
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3880
telemt_upstream_connect_attempt_total 7722
telemt_upstream_connect_success_total 7690
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 332251
telemt_me_reconnect_success_total 2781
telemt_me_reader_eof_total 2832
telemt_me_idle_close_by_peer_total 2832
telemt_me_route_drop_no_conn_total 209688
telemt_me_route_drop_channel_closed_total 101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307595
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 394
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 19
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2738
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2770
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 311280
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 6054143473 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 70115195729 (65.30 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 20472.5 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1209212
telemt_connections_bad_total 99137
telemt_connections_current 2718
telemt_connections_me_current 2718
telemt_handshake_timeouts_total 24378
telemt_upstream_connect_attempt_total 3397
telemt_upstream_connect_success_total 3396
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17873
telemt_me_reconnect_success_total 2353
telemt_me_reader_eof_total 2399
telemt_me_idle_close_by_peer_total 2399
telemt_me_route_drop_no_conn_total 548710
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1006366
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4345
telemt_desync_full_logged_total 1463
telemt_desync_suppressed_total 2882
telemt_desync_frames_bucket_total{bucket="1_2"} 991
telemt_desync_frames_bucket_total{bucket="3_10"} 1508
telemt_desync_frames_bucket_total{bucket="gt_10"} 1846
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2335
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 2292
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1005146
telemt_user_connections_current{user="hello"} 2718
telemt_user_octets_from_client{user="hello"} 20268672364 (18.88 GB)
telemt_user_octets_to_client{user="hello"} 577375276252 (537.72 GB)
telemt_user_unique_ips_current{user="hello"} 835
telemt_user_unique_ips_recent_window{user="hello"} 334
```