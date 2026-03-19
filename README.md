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

# Server Metrics 2026-03-19 17:36:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 1129.5 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42106
telemt_connections_bad_total 991
telemt_connections_current 1642
telemt_connections_me_current 1642
telemt_handshake_timeouts_total 493
telemt_upstream_connect_attempt_total 200
telemt_upstream_connect_success_total 196
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 75
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 87
telemt_me_reconnect_success_total 87
telemt_me_reader_eof_total 70
telemt_me_idle_close_by_peer_total 70
telemt_me_route_drop_no_conn_total 13928
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36762
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 170
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 92
telemt_me_writer_restored_same_endpoint_total 74
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 36788
telemt_user_connections_current{user="hello"} 1642
telemt_user_octets_from_client{user="hello"} 543230908 (518.07 MB)
telemt_user_octets_to_client{user="hello"} 11500375368 (10.71 GB)
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 17585.1 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1796379
telemt_connections_bad_total 90906
telemt_connections_current 3910
telemt_connections_me_current 3910
telemt_handshake_timeouts_total 33987
telemt_upstream_connect_attempt_total 4252
telemt_upstream_connect_success_total 4198
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6272
telemt_me_reconnect_success_total 2049
telemt_me_reader_eof_total 2218
telemt_me_idle_close_by_peer_total 2218
telemt_me_route_drop_no_conn_total 1063702
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1481356
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5742
telemt_desync_full_logged_total 1782
telemt_desync_suppressed_total 3960
telemt_desync_frames_bucket_total{bucket="1_2"} 1136
telemt_desync_frames_bucket_total{bucket="3_10"} 2266
telemt_desync_frames_bucket_total{bucket="gt_10"} 2340
telemt_pool_swap_total 11
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2191
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1994
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 1481355
telemt_user_connections_current{user="hello"} 3910
telemt_user_octets_from_client{user="hello"} 22039764570 (20.53 GB)
telemt_user_octets_to_client{user="hello"} 469052098178 (436.84 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1339
telemt_user_unique_ips_recent_window{user="hello"} 573
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 17564.1 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1671402
telemt_connections_bad_total 205433
telemt_connections_current 2915
telemt_connections_me_current 2915
telemt_handshake_timeouts_total 17544
telemt_upstream_connect_attempt_total 2825
telemt_upstream_connect_success_total 2806
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2802
telemt_me_reconnect_success_total 1884
telemt_me_reader_eof_total 1905
telemt_me_idle_close_by_peer_total 1904
telemt_me_route_drop_no_conn_total 1524006
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1264287
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3974
telemt_desync_full_logged_total 1168
telemt_desync_suppressed_total 2806
telemt_desync_frames_bucket_total{bucket="1_2"} 1060
telemt_desync_frames_bucket_total{bucket="3_10"} 1484
telemt_desync_frames_bucket_total{bucket="gt_10"} 1430
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 1871
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1883
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1261498
telemt_user_connections_current{user="hello"} 2915
telemt_user_octets_from_client{user="hello"} 15469727364 (14.41 GB)
telemt_user_octets_to_client{user="hello"} 377891854404 (351.94 GB)
telemt_user_unique_ips_current{user="hello"} 998
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 17551.4 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1462327
telemt_connections_bad_total 57415
telemt_connections_current 3266
telemt_connections_me_current 3266
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 21155
telemt_upstream_connect_attempt_total 19991
telemt_upstream_connect_success_total 19069
telemt_upstream_connect_fail_total 922
telemt_upstream_connect_attempts_per_request{bucket="1"} 19991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 922
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4480
telemt_me_reconnect_success_total 2210
telemt_me_reader_eof_total 2294
telemt_me_idle_close_by_peer_total 2293
telemt_me_route_drop_no_conn_total 1165347
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1257529
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5129
telemt_desync_full_logged_total 1603
telemt_desync_suppressed_total 3526
telemt_desync_frames_bucket_total{bucket="1_2"} 1355
telemt_desync_frames_bucket_total{bucket="3_10"} 1901
telemt_desync_frames_bucket_total{bucket="gt_10"} 1873
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_removed_unexpected_total 2540
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2206
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 1272827
telemt_user_connections_current{user="hello"} 3266
telemt_user_octets_from_client{user="hello"} 24279119761 (22.61 GB)
telemt_user_octets_to_client{user="hello"} 286175050982 (266.52 GB)
telemt_user_msgs_from_client{user="hello"} 40382
telemt_user_msgs_to_client{user="hello"} 85113
telemt_user_unique_ips_current{user="hello"} 1032
telemt_user_unique_ips_recent_window{user="hello"} 614
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 71274.4 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5131377
telemt_connections_bad_total 897119
telemt_connections_current 3434
telemt_connections_me_current 3434
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 96186
telemt_upstream_connect_attempt_total 64468
telemt_upstream_connect_success_total 61977
telemt_upstream_connect_fail_total 2491
telemt_upstream_connect_attempts_per_request{bucket="1"} 64468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74612
telemt_me_reconnect_success_total 9207
telemt_me_reader_eof_total 9699
telemt_me_idle_close_by_peer_total 9696
telemt_me_route_drop_no_conn_total 2415071
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3594694
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
telemt_desync_total 15729
telemt_desync_full_logged_total 4784
telemt_desync_suppressed_total 10945
telemt_desync_frames_bucket_total{bucket="1_2"} 2582
telemt_desync_frames_bucket_total{bucket="3_10"} 6587
telemt_desync_frames_bucket_total{bucket="gt_10"} 6560
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9443
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9183
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 3642825
telemt_user_connections_current{user="hello"} 3434
telemt_user_octets_from_client{user="hello"} 56980245763 (53.07 GB)
telemt_user_octets_to_client{user="hello"} 1326326877160 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1160
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 17516.0 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362267
telemt_connections_bad_total 28555
telemt_connections_current 861
telemt_connections_me_current 861
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 7793
telemt_upstream_connect_attempt_total 6107
telemt_upstream_connect_success_total 5969
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 6107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_reconnect_attempts_total 2547
telemt_me_reconnect_success_total 2507
telemt_me_reader_eof_total 2558
telemt_me_idle_close_by_peer_total 2558
telemt_me_route_drop_no_conn_total 219765
telemt_me_route_drop_channel_closed_total 63
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304742
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 953
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 661
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 438
telemt_pool_swap_total 10
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 67
telemt_me_writer_removed_unexpected_total 2503
telemt_me_writer_restored_same_endpoint_total 2498
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 307317
telemt_user_connections_current{user="hello"} 861
telemt_user_octets_from_client{user="hello"} 4226867396 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 79106205082 (73.67 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 17515.7 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1177015
telemt_connections_bad_total 81503
telemt_connections_current 2952
telemt_connections_me_current 2952
telemt_handshake_timeouts_total 19648
telemt_upstream_connect_attempt_total 2966
telemt_upstream_connect_success_total 2943
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 2040
telemt_me_reconnect_success_total 2015
telemt_me_reader_eof_total 2106
telemt_me_idle_close_by_peer_total 2106
telemt_me_route_drop_no_conn_total 462051
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1008966
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5606
telemt_desync_full_logged_total 1695
telemt_desync_suppressed_total 3911
telemt_desync_frames_bucket_total{bucket="1_2"} 1128
telemt_desync_frames_bucket_total{bucket="3_10"} 1929
telemt_desync_frames_bucket_total{bucket="gt_10"} 2549
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 2056
telemt_me_writer_restored_same_endpoint_total 1998
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1008513
telemt_user_connections_current{user="hello"} 2952
telemt_user_octets_from_client{user="hello"} 15347512052 (14.29 GB)
telemt_user_octets_to_client{user="hello"} 435293366412 (405.40 GB)
telemt_user_unique_ips_current{user="hello"} 1018
telemt_user_unique_ips_recent_window{user="hello"} 367
```