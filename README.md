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

# Server Metrics 2026-03-14 14:51:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 5687.8 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33598
telemt_connections_bad_total 6192
telemt_handshake_timeouts_total 170
telemt_upstream_connect_attempt_total 1473
telemt_upstream_connect_success_total 1473
telemt_upstream_connect_attempts_per_request{bucket="1"} 1473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1139
telemt_me_reconnect_success_total 1122
telemt_me_reader_eof_total 1150
telemt_me_idle_close_by_peer_total 1150
telemt_me_route_drop_no_conn_total 12847
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26625
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1149
telemt_me_writer_restored_same_endpoint_total 1104
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 26565
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 419650012 (400.21 MB)
telemt_user_octets_to_client{user="hello"} 9810456220 (9.14 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 5685.8 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13255
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 480
telemt_upstream_connect_attempt_total 1666
telemt_upstream_connect_success_total 1641
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 1666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2539
telemt_me_reconnect_success_total 1296
telemt_me_reader_eof_total 1356
telemt_me_idle_close_by_peer_total 1356
telemt_me_route_drop_no_conn_total 7023
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12319
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1355
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 1291
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 12302
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 157308536 (150.02 MB)
telemt_user_octets_to_client{user="hello"} 3589338152 (3.34 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 5690.1 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12731
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 218
telemt_upstream_connect_attempt_total 2872
telemt_upstream_connect_success_total 2850
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 96064
telemt_me_reconnect_success_total 2189
telemt_me_reader_eof_total 2302
telemt_me_idle_close_by_peer_total 2302
telemt_me_route_drop_no_conn_total 4962
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11377
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2306
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 2151
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 11678
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 458593233 (437.35 MB)
telemt_user_octets_to_client{user="hello"} 5302351858 (4.94 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 5695.1 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17826
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 1527
telemt_upstream_connect_success_total 1521
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1189
telemt_me_reconnect_success_total 1179
telemt_me_reader_eof_total 1207
telemt_me_idle_close_by_peer_total 1207
telemt_me_route_drop_no_conn_total 9009
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16895
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 223
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1183
telemt_me_writer_restored_same_endpoint_total 1177
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 16777
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 200490412 (191.20 MB)
telemt_user_octets_to_client{user="hello"} 5904394728 (5.50 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 5688.2 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13014
telemt_connections_bad_total 1202
telemt_handshake_timeouts_total 154
telemt_upstream_connect_attempt_total 1396
telemt_upstream_connect_success_total 1373
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 6157
telemt_me_reconnect_success_total 1029
telemt_me_reader_eof_total 1166
telemt_me_idle_close_by_peer_total 1166
telemt_me_route_drop_no_conn_total 4527
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10915
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 1186
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 1025
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 10911
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 97633800 (93.11 MB)
telemt_user_octets_to_client{user="hello"} 2845590660 (2.65 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 5687.9 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45326
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 340
telemt_upstream_connect_attempt_total 1265
telemt_upstream_connect_success_total 1233
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 1265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 887
telemt_me_reader_eof_total 898
telemt_me_idle_close_by_peer_total 898
telemt_me_route_drop_no_conn_total 22818
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41640
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 888
telemt_me_writer_restored_same_endpoint_total 883
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 41550
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 742073632 (707.70 MB)
telemt_user_octets_to_client{user="hello"} 15604418588 (14.53 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 76
```