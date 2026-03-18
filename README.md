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

# Server Metrics 2026-03-18 12:34:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 13988.4 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503775
telemt_connections_bad_total 7119
telemt_handshake_timeouts_total 14248
telemt_upstream_connect_attempt_total 65794
telemt_upstream_connect_success_total 64849
telemt_upstream_connect_fail_total 945
telemt_upstream_connect_attempts_per_request{bucket="1"} 65794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 945
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 511207
telemt_me_reconnect_success_total 2154
telemt_me_reader_eof_total 2223
telemt_me_idle_close_by_peer_total 2221
telemt_me_route_drop_no_conn_total 302532
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386298
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1632
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 1097
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 592
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2236
telemt_me_refill_failed_total 16591
telemt_me_writer_restored_same_endpoint_total 2049
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 444547
telemt_user_connections_current{user="hello"} 1778
telemt_user_octets_from_client{user="hello"} 6094433272 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 115781008985 (107.83 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 574
telemt_user_unique_ips_recent_window{user="hello"} 340
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 14018.9 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1392303
telemt_connections_bad_total 97614
telemt_handshake_timeouts_total 31637
telemt_upstream_connect_attempt_total 2484
telemt_upstream_connect_success_total 2472
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1743
telemt_me_reconnect_success_total 1694
telemt_me_reader_eof_total 1718
telemt_me_idle_close_by_peer_total 1717
telemt_me_route_drop_no_conn_total 1201700
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1200132
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3792
telemt_desync_full_logged_total 1126
telemt_desync_suppressed_total 2666
telemt_desync_frames_bucket_total{bucket="1_2"} 748
telemt_desync_frames_bucket_total{bucket="3_10"} 1524
telemt_desync_frames_bucket_total{bucket="gt_10"} 1520
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1700
telemt_me_writer_restored_same_endpoint_total 1693
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1199188
telemt_user_connections_current{user="hello"} 4005
telemt_user_octets_from_client{user="hello"} 30050825504 (27.99 GB)
telemt_user_octets_to_client{user="hello"} 351105660744 (326.99 GB)
telemt_user_unique_ips_current{user="hello"} 1245
telemt_user_unique_ips_recent_window{user="hello"} 535
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 13933.9 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 990575
telemt_connections_bad_total 72889
telemt_handshake_timeouts_total 24340
telemt_upstream_connect_attempt_total 10873
telemt_upstream_connect_success_total 10873
telemt_upstream_connect_attempts_per_request{bucket="1"} 10873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607603
telemt_me_reconnect_success_total 1908
telemt_me_reader_eof_total 1934
telemt_me_idle_close_by_peer_total 1933
telemt_me_route_drop_no_conn_total 422195
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751217
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2152
telemt_desync_full_logged_total 733
telemt_desync_suppressed_total 1419
telemt_desync_frames_bucket_total{bucket="1_2"} 593
telemt_desync_frames_bucket_total{bucket="3_10"} 801
telemt_desync_frames_bucket_total{bucket="gt_10"} 758
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1918
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1873
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 758728
telemt_user_connections_current{user="hello"} 3134
telemt_user_octets_from_client{user="hello"} 9056382055 (8.43 GB)
telemt_user_octets_to_client{user="hello"} 316113232072 (294.40 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 968
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 13964.2 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1591841
telemt_connections_bad_total 23526
telemt_handshake_timeouts_total 163548
telemt_upstream_connect_attempt_total 12382
telemt_upstream_connect_success_total 12200
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 12382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2828460
telemt_me_reconnect_success_total 1178
telemt_me_reader_eof_total 1678
telemt_me_idle_close_by_peer_total 1678
telemt_me_route_drop_no_conn_total 2314167
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1271543
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2694
telemt_desync_full_logged_total 857
telemt_desync_suppressed_total 1837
telemt_desync_frames_bucket_total{bucket="1_2"} 670
telemt_desync_frames_bucket_total{bucket="3_10"} 1103
telemt_desync_frames_bucket_total{bucket="gt_10"} 921
telemt_me_writer_removed_unexpected_total 1723
telemt_me_refill_failed_total 100090
telemt_me_writer_restored_same_endpoint_total 1083
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 1290159
telemt_user_connections_current{user="hello"} 3604
telemt_user_octets_from_client{user="hello"} 15983376202 (14.89 GB)
telemt_user_octets_to_client{user="hello"} 208208226449 (193.91 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 960
telemt_user_unique_ips_recent_window{user="hello"} 609
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 13859.0 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1026304
telemt_connections_bad_total 42769
telemt_handshake_timeouts_total 18045
telemt_upstream_connect_attempt_total 11928
telemt_upstream_connect_success_total 11927
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983641
telemt_me_reconnect_success_total 1677
telemt_me_reader_eof_total 1676
telemt_me_idle_close_by_peer_total 1676
telemt_me_route_drop_no_conn_total 636827
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 875081
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2965
telemt_desync_full_logged_total 993
telemt_desync_suppressed_total 1972
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 1165
telemt_desync_frames_bucket_total{bucket="gt_10"} 1373
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1653
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1562
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 875291
telemt_user_connections_current{user="hello"} 3303
telemt_user_octets_from_client{user="hello"} 13328797309 (12.41 GB)
telemt_user_octets_to_client{user="hello"} 334052166505 (311.11 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 13748.4 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291386
telemt_connections_bad_total 26547
telemt_handshake_timeouts_total 2258
telemt_upstream_connect_attempt_total 2725
telemt_upstream_connect_success_total 2725
telemt_upstream_connect_attempts_per_request{bucket="1"} 2725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 5681
telemt_me_reconnect_success_total 1950
telemt_me_reader_eof_total 2105
telemt_me_idle_close_by_peer_total 2104
telemt_me_route_drop_no_conn_total 149538
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250794
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 656
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2084
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 1942
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 241087
telemt_user_connections_current{user="hello"} 990
telemt_user_octets_from_client{user="hello"} 4287069728 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 53256529616 (49.60 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 13815.0 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 834587
telemt_connections_bad_total 110309
telemt_handshake_timeouts_total 18001
telemt_upstream_connect_attempt_total 2520
telemt_upstream_connect_success_total 2494
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 2520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 1758
telemt_me_reconnect_success_total 1730
telemt_me_reader_eof_total 1767
telemt_me_idle_close_by_peer_total 1767
telemt_me_route_drop_no_conn_total 343114
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641262
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2320
telemt_desync_full_logged_total 790
telemt_desync_suppressed_total 1530
telemt_desync_frames_bucket_total{bucket="1_2"} 393
telemt_desync_frames_bucket_total{bucket="3_10"} 806
telemt_desync_frames_bucket_total{bucket="gt_10"} 1121
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1739
telemt_me_writer_restored_same_endpoint_total 1720
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 640769
telemt_user_connections_current{user="hello"} 2973
telemt_user_octets_from_client{user="hello"} 14181769548 (13.21 GB)
telemt_user_octets_to_client{user="hello"} 324232782328 (301.97 GB)
telemt_user_unique_ips_current{user="hello"} 931
telemt_user_unique_ips_recent_window{user="hello"} 410
```