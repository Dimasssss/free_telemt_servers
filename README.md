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

# Server Metrics 2026-03-14 23:57:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 6169.6 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12288
telemt_connections_bad_total 282
telemt_handshake_timeouts_total 198
telemt_upstream_connect_attempt_total 1579
telemt_upstream_connect_success_total 1571
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1249
telemt_me_reconnect_success_total 1243
telemt_me_reader_eof_total 1283
telemt_me_idle_close_by_peer_total 1283
telemt_me_route_drop_no_conn_total 3321
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11350
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1238
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 11349
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 107180580 (102.22 MB)
telemt_user_octets_to_client{user="hello"} 3371331184 (3.14 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 6176.1 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5336
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 1726
telemt_upstream_connect_success_total 1726
telemt_upstream_connect_attempts_per_request{bucket="1"} 1726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 965
telemt_me_reconnect_attempts_total 1398
telemt_me_reconnect_success_total 1393
telemt_me_reader_eof_total 1460
telemt_me_idle_close_by_peer_total 1460
telemt_me_route_drop_no_conn_total 1807
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5001
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1397
telemt_me_writer_restored_same_endpoint_total 1377
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 5002
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 48542112 (46.29 MB)
telemt_user_octets_to_client{user="hello"} 700305620 (667.86 MB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 6168.6 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5921
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 90
telemt_upstream_connect_attempt_total 1630
telemt_upstream_connect_success_total 1629
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1305
telemt_me_reconnect_success_total 1294
telemt_me_reader_eof_total 1376
telemt_me_idle_close_by_peer_total 1376
telemt_me_route_drop_no_conn_total 1924
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5587
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1297
telemt_me_writer_restored_same_endpoint_total 1290
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 5568
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 1024885040 (977.41 MB)
telemt_user_octets_to_client{user="hello"} 8902797008 (8.29 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 6168.4 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5542
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 1514
telemt_upstream_connect_success_total 1513
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1193
telemt_me_reconnect_success_total 1187
telemt_me_reader_eof_total 1236
telemt_me_idle_close_by_peer_total 1236
telemt_me_route_drop_no_conn_total 2463
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5349
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1191
telemt_me_writer_restored_same_endpoint_total 1176
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 5349
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 143037356 (136.41 MB)
telemt_user_octets_to_client{user="hello"} 5399578960 (5.03 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 6168.6 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7616
telemt_connections_bad_total 1392
telemt_handshake_timeouts_total 330
telemt_upstream_connect_attempt_total 2130
telemt_upstream_connect_success_total 2106
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1850
telemt_me_reconnect_success_total 1780
telemt_me_reader_eof_total 1831
telemt_me_idle_close_by_peer_total 1831
telemt_me_route_drop_no_conn_total 1775
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5754
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1776
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1768
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 5749
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 50344576 (48.01 MB)
telemt_user_octets_to_client{user="hello"} 3778183736 (3.52 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 6167.5 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19606
telemt_connections_bad_total 370
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 1419
telemt_upstream_connect_success_total 1413
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 721
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1088
telemt_me_reconnect_success_total 1086
telemt_me_reader_eof_total 1109
telemt_me_idle_close_by_peer_total 1109
telemt_me_route_drop_no_conn_total 10667
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19086
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1067
telemt_me_writer_restored_same_endpoint_total 1059
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 18611
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 354364804 (337.95 MB)
telemt_user_octets_to_client{user="hello"} 14609430608 (13.61 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 39
```