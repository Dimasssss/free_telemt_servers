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

# Server Metrics 2026-03-18 23:29:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 6080.5 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71054
telemt_connections_bad_total 6994
telemt_connections_current 637
telemt_connections_me_current 637
telemt_handshake_timeouts_total 748
telemt_upstream_connect_attempt_total 1109
telemt_upstream_connect_success_total 1094
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 774
telemt_me_reconnect_success_total 772
telemt_me_reader_eof_total 784
telemt_me_idle_close_by_peer_total 784
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 24612
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62051
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 326
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 769
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 59295
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 617480624 (588.88 MB)
telemt_user_octets_to_client{user="hello"} 25798825916 (24.03 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 6084.2 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166494
telemt_connections_bad_total 12950
telemt_connections_current 1576
telemt_connections_me_current 1576
telemt_handshake_timeouts_total 1337
telemt_upstream_connect_attempt_total 1152
telemt_upstream_connect_success_total 1123
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 1152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 796
telemt_me_reconnect_success_total 795
telemt_me_reader_eof_total 823
telemt_me_idle_close_by_peer_total 823
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 52022
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143192
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 562
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 368
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 811
telemt_me_writer_restored_same_endpoint_total 784
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 143272
telemt_user_connections_current{user="hello"} 1576
telemt_user_octets_from_client{user="hello"} 10096866276 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 54770944796 (51.01 GB)
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 6081.5 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130804
telemt_connections_bad_total 19363
telemt_connections_current 1070
telemt_connections_me_current 1070
telemt_handshake_timeouts_total 3810
telemt_upstream_connect_attempt_total 1175
telemt_upstream_connect_success_total 1175
telemt_upstream_connect_attempts_per_request{bucket="1"} 1175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 571
telemt_me_reconnect_attempts_total 849
telemt_me_reconnect_success_total 847
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 871
telemt_me_route_drop_no_conn_total 45207
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104071
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 451
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 273
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 857
telemt_me_writer_restored_same_endpoint_total 831
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 104073
telemt_user_connections_current{user="hello"} 1070
telemt_user_octets_from_client{user="hello"} 1401812040 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 65023189108 (60.56 GB)
telemt_user_unique_ips_current{user="hello"} 496
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 6134.9 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144090
telemt_connections_bad_total 23640
telemt_connections_current 1034
telemt_connections_me_current 1034
telemt_handshake_timeouts_total 3038
telemt_upstream_connect_attempt_total 1086
telemt_upstream_connect_success_total 1086
telemt_upstream_connect_attempts_per_request{bucket="1"} 1086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 763
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 777
telemt_me_idle_close_by_peer_total 777
telemt_me_route_drop_no_conn_total 57568
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109721
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 771
telemt_me_writer_restored_same_endpoint_total 736
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 109650
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 1143515012 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 41345223000 (38.51 GB)
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 6078.4 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143128
telemt_connections_bad_total 6445
telemt_connections_current 1292
telemt_connections_me_current 1292
telemt_handshake_timeouts_total 4545
telemt_upstream_connect_attempt_total 1114
telemt_upstream_connect_success_total 1107
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 780
telemt_me_reconnect_success_total 777
telemt_me_reader_eof_total 791
telemt_me_idle_close_by_peer_total 791
telemt_me_route_drop_no_conn_total 43041
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113056
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 779
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 113014
telemt_user_connections_current{user="hello"} 1292
telemt_user_octets_from_client{user="hello"} 1458916388 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 70259934544 (65.43 GB)
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 6089.7 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33045
telemt_connections_bad_total 6205
telemt_connections_current 335
telemt_connections_me_current 335
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 1925
telemt_upstream_connect_success_total 1870
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 1925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 889
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 3373
telemt_me_reconnect_success_total 1547
telemt_me_reader_eof_total 1575
telemt_me_idle_close_by_peer_total 1575
telemt_me_route_drop_no_conn_total 11268
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26006
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1578
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 1517
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 26007
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 316191208 (301.54 MB)
telemt_user_octets_to_client{user="hello"} 20606348576 (19.19 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 6080.5 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106246
telemt_connections_bad_total 14000
telemt_connections_current 1149
telemt_connections_me_current 1149
telemt_handshake_timeouts_total 3576
telemt_upstream_connect_attempt_total 1144
telemt_upstream_connect_success_total 1144
telemt_upstream_connect_attempts_per_request{bucket="1"} 1144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 817
telemt_me_reconnect_success_total 815
telemt_me_reader_eof_total 836
telemt_me_idle_close_by_peer_total 836
telemt_me_route_drop_no_conn_total 31911
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86464
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 825
telemt_me_writer_restored_same_endpoint_total 800
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 86489
telemt_user_connections_current{user="hello"} 1149
telemt_user_octets_from_client{user="hello"} 910296472 (868.13 MB)
telemt_user_octets_to_client{user="hello"} 48757963692 (45.41 GB)
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 92
```