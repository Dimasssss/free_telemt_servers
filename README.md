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

# Server Metrics 2026-03-19 01:01:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 11602.6 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131882
telemt_connections_bad_total 15979
telemt_connections_current 667
telemt_connections_me_current 667
telemt_handshake_timeouts_total 1299
telemt_upstream_connect_attempt_total 2337
telemt_upstream_connect_success_total 2298
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 2337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1719
telemt_me_reconnect_success_total 1714
telemt_me_reader_eof_total 1772
telemt_me_idle_close_by_peer_total 1772
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 40544
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108909
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 610
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 439
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 267
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1716
telemt_me_writer_restored_same_endpoint_total 1701
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 106143
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 1024282216 (976.83 MB)
telemt_user_octets_to_client{user="hello"} 37962658580 (35.36 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 11606.2 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269339
telemt_connections_bad_total 19496
telemt_connections_current 1431
telemt_connections_me_current 1431
telemt_handshake_timeouts_total 3495
telemt_upstream_connect_attempt_total 2176
telemt_upstream_connect_success_total 2131
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 1546
telemt_me_reconnect_success_total 1541
telemt_me_reader_eof_total 1617
telemt_me_idle_close_by_peer_total 1617
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 80776
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230758
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 857
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1567
telemt_me_writer_restored_same_endpoint_total 1528
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 230798
telemt_user_connections_current{user="hello"} 1431
telemt_user_octets_from_client{user="hello"} 10856095632 (10.11 GB)
telemt_user_octets_to_client{user="hello"} 87503267692 (81.49 GB)
telemt_user_unique_ips_current{user="hello"} 595
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 11603.4 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214425
telemt_connections_bad_total 36396
telemt_connections_current 1096
telemt_connections_me_current 1096
telemt_handshake_timeouts_total 5556
telemt_upstream_connect_attempt_total 2247
telemt_upstream_connect_success_total 2247
telemt_upstream_connect_attempts_per_request{bucket="1"} 2247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1662
telemt_me_reconnect_success_total 1658
telemt_me_reader_eof_total 1736
telemt_me_idle_close_by_peer_total 1736
telemt_me_route_drop_no_conn_total 69046
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165867
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 753
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 471
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 298
telemt_desync_frames_bucket_total{bucket="gt_10"} 304
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1680
telemt_me_writer_restored_same_endpoint_total 1642
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 165867
telemt_user_connections_current{user="hello"} 1096
telemt_user_octets_from_client{user="hello"} 2118699804 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 98660586564 (91.88 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 11656.7 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230237
telemt_connections_bad_total 27351
telemt_connections_current 896
telemt_connections_me_current 896
telemt_handshake_timeouts_total 4250
telemt_upstream_connect_attempt_total 2117
telemt_upstream_connect_success_total 2117
telemt_upstream_connect_attempts_per_request{bucket="1"} 2117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1533
telemt_me_reconnect_success_total 1527
telemt_me_reader_eof_total 1594
telemt_me_idle_close_by_peer_total 1594
telemt_me_route_drop_no_conn_total 75920
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168959
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 467
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1545
telemt_me_writer_restored_same_endpoint_total 1503
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 168878
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 1682463940 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 58292937108 (54.29 GB)
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 11600.0 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235820
telemt_connections_bad_total 13751
telemt_connections_current 1137
telemt_connections_me_current 1137
telemt_handshake_timeouts_total 7836
telemt_upstream_connect_attempt_total 2162
telemt_upstream_connect_success_total 2150
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1565
telemt_me_reconnect_success_total 1555
telemt_me_reader_eof_total 1622
telemt_me_idle_close_by_peer_total 1622
telemt_me_route_drop_no_conn_total 73733
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180202
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 698
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1561
telemt_me_writer_restored_same_endpoint_total 1531
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 180129
telemt_user_connections_current{user="hello"} 1137
telemt_user_octets_from_client{user="hello"} 2293487724 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 106559564760 (99.24 GB)
telemt_user_unique_ips_current{user="hello"} 497
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 11611.6 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58718
telemt_connections_bad_total 9062
telemt_connections_current 361
telemt_connections_me_current 361
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 3388
telemt_upstream_connect_success_total 3281
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 3388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 4525
telemt_me_reconnect_success_total 2698
telemt_me_reader_eof_total 2804
telemt_me_idle_close_by_peer_total 2804
telemt_me_route_drop_no_conn_total 21936
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47998
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2745
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2668
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 47998
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 670967512 (639.88 MB)
telemt_user_octets_to_client{user="hello"} 31109074292 (28.97 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 11602.3 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166940
telemt_connections_bad_total 19823
telemt_connections_current 989
telemt_connections_me_current 989
telemt_handshake_timeouts_total 7101
telemt_upstream_connect_attempt_total 2430
telemt_upstream_connect_success_total 2430
telemt_upstream_connect_attempts_per_request{bucket="1"} 2430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 1845
telemt_me_reconnect_success_total 1839
telemt_me_reader_eof_total 1923
telemt_me_idle_close_by_peer_total 1923
telemt_me_route_drop_no_conn_total 49952
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136758
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 926
telemt_desync_full_logged_total 373
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 383
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1861
telemt_me_writer_restored_same_endpoint_total 1824
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 136781
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 1357608408 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 71692354548 (66.77 GB)
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 96
```