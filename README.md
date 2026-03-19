# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 19:44:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 8794.7 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267775
telemt_connections_bad_total 11918
telemt_connections_current 1212
telemt_connections_me_current 1212
telemt_handshake_timeouts_total 2700
telemt_upstream_connect_attempt_total 1328
telemt_upstream_connect_success_total 1313
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 858
telemt_me_reconnect_success_total 852
telemt_me_reader_eof_total 886
telemt_me_idle_close_by_peer_total 886
telemt_me_route_drop_no_conn_total 80083
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209482
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1034
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 694
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 874
telemt_me_writer_restored_same_endpoint_total 839
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 209726
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 9038647692 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 73351324116 (68.31 GB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 25250.2 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2377423
telemt_connections_bad_total 105432
telemt_connections_current 3266
telemt_connections_me_current 3266
telemt_handshake_timeouts_total 45555
telemt_upstream_connect_attempt_total 5380
telemt_upstream_connect_success_total 5308
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 5380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7022
telemt_me_reconnect_success_total 2795
telemt_me_reader_eof_total 3018
telemt_me_idle_close_by_peer_total 3018
telemt_me_route_drop_no_conn_total 1295137
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2007086
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8476
telemt_desync_full_logged_total 2752
telemt_desync_suppressed_total 5724
telemt_desync_frames_bucket_total{bucket="1_2"} 1555
telemt_desync_frames_bucket_total{bucket="3_10"} 3350
telemt_desync_frames_bucket_total{bucket="gt_10"} 3571
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2951
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2740
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 2007077
telemt_user_connections_current{user="hello"} 3266
telemt_user_octets_from_client{user="hello"} 29376040314 (27.36 GB)
telemt_user_octets_to_client{user="hello"} 682872580370 (635.97 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1178
telemt_user_unique_ips_recent_window{user="hello"} 410
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 25228.3 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2148537
telemt_connections_bad_total 252903
telemt_connections_current 2680
telemt_connections_me_current 2680
telemt_handshake_timeouts_total 25257
telemt_upstream_connect_attempt_total 3885
telemt_upstream_connect_success_total 3859
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3503
telemt_me_reconnect_success_total 2584
telemt_me_reader_eof_total 2659
telemt_me_idle_close_by_peer_total 2658
telemt_me_route_drop_no_conn_total 1761045
telemt_me_route_drop_channel_closed_total 157
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1635074
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5834
telemt_desync_full_logged_total 1746
telemt_desync_suppressed_total 4088
telemt_desync_frames_bucket_total{bucket="1_2"} 1470
telemt_desync_frames_bucket_total{bucket="3_10"} 2205
telemt_desync_frames_bucket_total{bucket="gt_10"} 2159
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 55
telemt_me_writer_removed_unexpected_total 2587
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2583
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 1631427
telemt_user_connections_current{user="hello"} 2680
telemt_user_octets_from_client{user="hello"} 23110518868 (21.52 GB)
telemt_user_octets_to_client{user="hello"} 556791659728 (518.55 GB)
telemt_user_unique_ips_current{user="hello"} 876
telemt_user_unique_ips_recent_window{user="hello"} 294
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 25216.1 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2029884
telemt_connections_bad_total 67951
telemt_connections_current 2345
telemt_connections_me_current 2345
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 26025
telemt_upstream_connect_attempt_total 31113
telemt_upstream_connect_success_total 29589
telemt_upstream_connect_fail_total 1524
telemt_upstream_connect_attempts_per_request{bucket="1"} 31113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1524
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5547
telemt_me_reconnect_success_total 3020
telemt_me_reader_eof_total 3125
telemt_me_idle_close_by_peer_total 3124
telemt_me_route_drop_no_conn_total 1708282
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1743125
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7039
telemt_desync_full_logged_total 2207
telemt_desync_suppressed_total 4832
telemt_desync_frames_bucket_total{bucket="1_2"} 1739
telemt_desync_frames_bucket_total{bucket="3_10"} 2582
telemt_desync_frames_bucket_total{bucket="gt_10"} 2718
telemt_pool_swap_total 12
telemt_me_writer_close_signal_drop_total 288
telemt_me_writer_removed_unexpected_total 3468
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3016
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 1767313
telemt_user_connections_current{user="hello"} 2345
telemt_user_octets_from_client{user="hello"} 30132304060 (28.06 GB)
telemt_user_octets_to_client{user="hello"} 404044736022 (376.30 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 827
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 78939.4 (21h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5705136
telemt_connections_bad_total 1016695
telemt_connections_current 2807
telemt_connections_me_current 2807
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 104832
telemt_upstream_connect_attempt_total 65490
telemt_upstream_connect_success_total 62992
telemt_upstream_connect_fail_total 2498
telemt_upstream_connect_attempts_per_request{bucket="1"} 65490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2498
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75281
telemt_me_reconnect_success_total 9868
telemt_me_reader_eof_total 10408
telemt_me_idle_close_by_peer_total 10405
telemt_me_route_drop_no_conn_total 2626301
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3996295
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17570
telemt_desync_full_logged_total 5429
telemt_desync_suppressed_total 12141
telemt_desync_frames_bucket_total{bucket="1_2"} 2937
telemt_desync_frames_bucket_total{bucket="3_10"} 7307
telemt_desync_frames_bucket_total{bucket="gt_10"} 7326
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 10121
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9844
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 4044361
telemt_user_connections_current{user="hello"} 2807
telemt_user_octets_from_client{user="hello"} 63016735515 (58.69 GB)
telemt_user_octets_to_client{user="hello"} 1514178090628 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 971
telemt_user_unique_ips_recent_window{user="hello"} 343
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 25180.8 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554492
telemt_connections_bad_total 42674
telemt_connections_current 658
telemt_connections_me_current 658
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10869
telemt_upstream_connect_attempt_total 7720
telemt_upstream_connect_success_total 7523
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 550
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 3320
telemt_me_reconnect_success_total 3261
telemt_me_reader_eof_total 3362
telemt_me_idle_close_by_peer_total 3361
telemt_me_route_drop_no_conn_total 377489
telemt_me_route_drop_channel_closed_total 134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439481
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1124
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 768
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 456
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 136
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3286
telemt_me_writer_restored_same_endpoint_total 3252
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 458126
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 5205986676 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 97089902450 (90.42 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 25180.9 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1596587
telemt_connections_bad_total 96929
telemt_connections_current 2707
telemt_connections_me_current 2707
telemt_handshake_timeouts_total 25878
telemt_upstream_connect_attempt_total 4131
telemt_upstream_connect_success_total 4101
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2852
telemt_me_reconnect_success_total 2823
telemt_me_reader_eof_total 2962
telemt_me_idle_close_by_peer_total 2962
telemt_me_route_drop_no_conn_total 606331
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1385843
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7249
telemt_desync_full_logged_total 2249
telemt_desync_suppressed_total 5000
telemt_desync_frames_bucket_total{bucket="1_2"} 1366
telemt_desync_frames_bucket_total{bucket="3_10"} 2516
telemt_desync_frames_bucket_total{bucket="gt_10"} 3367
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2880
telemt_me_writer_restored_same_endpoint_total 2806
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 1385099
telemt_user_connections_current{user="hello"} 2707
telemt_user_octets_from_client{user="hello"} 22382267976 (20.85 GB)
telemt_user_octets_to_client{user="hello"} 642946927424 (598.79 GB)
telemt_user_unique_ips_current{user="hello"} 869
telemt_user_unique_ips_recent_window{user="hello"} 318
```