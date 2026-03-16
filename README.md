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

# Server Metrics 2026-03-16 21:05:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 8426.8 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57314
telemt_connections_bad_total 553
telemt_handshake_timeouts_total 2822
telemt_upstream_connect_attempt_total 1576
telemt_upstream_connect_success_total 1563
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1107
telemt_me_reconnect_success_total 1103
telemt_me_reader_eof_total 1139
telemt_me_idle_close_by_peer_total 1139
telemt_me_route_drop_no_conn_total 19562
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51639
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 249
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1100
telemt_me_writer_restored_same_endpoint_total 1082
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 51595
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 1056203524 (1007.27 MB)
telemt_user_octets_to_client{user="hello"} 35251151180 (32.83 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 8677.9 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45982
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 2229
telemt_upstream_connect_attempt_total 1861
telemt_upstream_connect_success_total 1837
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1383
telemt_me_reconnect_success_total 1380
telemt_me_reader_eof_total 1434
telemt_me_idle_close_by_peer_total 1434
telemt_me_route_drop_no_conn_total 17786
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41668
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1402
telemt_me_writer_restored_same_endpoint_total 1364
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 41653
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 612557004 (584.18 MB)
telemt_user_octets_to_client{user="hello"} 16093622020 (14.99 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 8454.1 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24448
telemt_connections_bad_total 358
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 1917
telemt_upstream_connect_success_total 1904
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1457
telemt_me_reconnect_success_total 1440
telemt_me_reader_eof_total 1511
telemt_me_idle_close_by_peer_total 1511
telemt_me_route_drop_no_conn_total 8197
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23321
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1456
telemt_me_writer_restored_same_endpoint_total 1429
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 23317
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 564274336 (538.13 MB)
telemt_user_octets_to_client{user="hello"} 8904608392 (8.29 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 8513.3 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48342
telemt_connections_bad_total 2930
telemt_handshake_timeouts_total 366
telemt_upstream_connect_attempt_total 1731
telemt_upstream_connect_success_total 1707
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1255
telemt_me_reconnect_success_total 1239
telemt_me_reader_eof_total 1285
telemt_me_idle_close_by_peer_total 1285
telemt_me_route_drop_no_conn_total 15279
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43659
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1256
telemt_me_writer_restored_same_endpoint_total 1232
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 43652
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 652282960 (622.07 MB)
telemt_user_octets_to_client{user="hello"} 18318903516 (17.06 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 8485.3 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31642
telemt_connections_bad_total 9342
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 2153
telemt_upstream_connect_success_total 2122
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 2153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 2759
telemt_me_reconnect_success_total 1662
telemt_me_reader_eof_total 1717
telemt_me_idle_close_by_peer_total 1717
telemt_me_route_drop_no_conn_total 9004
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20989
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1713
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 1654
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 20987
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 203011860 (193.61 MB)
telemt_user_octets_to_client{user="hello"} 6766291612 (6.30 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 8646.6 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70677
telemt_connections_bad_total 929
telemt_handshake_timeouts_total 702
telemt_upstream_connect_attempt_total 1627
telemt_upstream_connect_success_total 1613
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1159
telemt_me_reconnect_success_total 1156
telemt_me_reader_eof_total 1208
telemt_me_idle_close_by_peer_total 1208
telemt_me_route_drop_no_conn_total 29989
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66623
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1173
telemt_me_writer_restored_same_endpoint_total 1146
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 66616
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 1442163408 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 35784212548 (33.33 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 40
```