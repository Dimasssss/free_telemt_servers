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

# Server Metrics 2026-03-14 15:11:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 6912.7 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40836
telemt_connections_bad_total 7530
telemt_handshake_timeouts_total 220
telemt_upstream_connect_attempt_total 1851
telemt_upstream_connect_success_total 1849
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 1472
telemt_me_reconnect_success_total 1451
telemt_me_reader_eof_total 1502
telemt_me_idle_close_by_peer_total 1502
telemt_me_route_drop_no_conn_total 15523
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32196
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1483
telemt_me_writer_restored_same_endpoint_total 1433
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 32132
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 471139704 (449.31 MB)
telemt_user_octets_to_client{user="hello"} 11705734760 (10.90 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 6910.9 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16055
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 493
telemt_upstream_connect_attempt_total 2011
telemt_upstream_connect_success_total 1984
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 2010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 4150
telemt_me_reconnect_success_total 1593
telemt_me_reader_eof_total 1697
telemt_me_idle_close_by_peer_total 1697
telemt_me_route_drop_no_conn_total 8754
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15000
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1696
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1588
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 14983
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 189980116 (181.18 MB)
telemt_user_octets_to_client{user="hello"} 4380156284 (4.08 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 6915.2 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15599
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 279
telemt_upstream_connect_attempt_total 3252
telemt_upstream_connect_success_total 3228
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 3252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 96396
telemt_me_reconnect_success_total 2517
telemt_me_reader_eof_total 2635
telemt_me_idle_close_by_peer_total 2635
telemt_me_route_drop_no_conn_total 6106
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14025
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
telemt_me_writer_removed_unexpected_total 2639
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 2479
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 14323
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 492432825 (469.62 MB)
telemt_user_octets_to_client{user="hello"} 7033386070 (6.55 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 6920.1 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21987
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 161
telemt_upstream_connect_attempt_total 1798
telemt_upstream_connect_success_total 1791
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1414
telemt_me_reconnect_success_total 1403
telemt_me_reader_eof_total 1432
telemt_me_idle_close_by_peer_total 1432
telemt_me_route_drop_no_conn_total 10820
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20878
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 263
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 190
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_restored_same_endpoint_total 1401
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 20761
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 236789000 (225.82 MB)
telemt_user_octets_to_client{user="hello"} 7267670764 (6.77 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 6913.2 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15354
telemt_connections_bad_total 1426
telemt_handshake_timeouts_total 169
telemt_upstream_connect_attempt_total 1547
telemt_upstream_connect_success_total 1521
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 917
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 7634
telemt_me_reconnect_success_total 1128
telemt_me_reader_eof_total 1307
telemt_me_idle_close_by_peer_total 1307
telemt_me_route_drop_no_conn_total 5392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12936
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
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
telemt_me_writer_removed_unexpected_total 1328
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1124
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 12932
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 109167280 (104.11 MB)
telemt_user_octets_to_client{user="hello"} 3424406788 (3.19 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 6913.0 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55047
telemt_connections_bad_total 161
telemt_handshake_timeouts_total 392
telemt_upstream_connect_attempt_total 1491
telemt_upstream_connect_success_total 1457
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 1491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1091
telemt_me_reconnect_success_total 1062
telemt_me_reader_eof_total 1079
telemt_me_idle_close_by_peer_total 1079
telemt_me_route_drop_no_conn_total 27911
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50937
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
telemt_me_writer_removed_unexpected_total 1070
telemt_me_writer_restored_same_endpoint_total 1058
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 50843
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 813420796 (775.74 MB)
telemt_user_octets_to_client{user="hello"} 19649923672 (18.30 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 80
```