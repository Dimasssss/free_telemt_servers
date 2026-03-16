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

# Server Metrics 2026-03-16 13:41:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 231.5 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4654
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 112
telemt_upstream_connect_success_total 111
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 880
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4252
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_restored_same_endpoint_total 43
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 4205
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 39267680 (37.45 MB)
telemt_user_octets_to_client{user="hello"} 1154809368 (1.08 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 17.6 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 599
telemt_connections_bad_total 23
telemt_upstream_connect_attempt_total 563
telemt_upstream_connect_success_total 563
telemt_upstream_connect_attempts_per_request{bucket="1"} 563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 561
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 597563 (583.56 KB)
telemt_user_octets_to_client{user="hello"} 17481932 (16.67 MB)
telemt_user_msgs_from_client{user="hello"} 1925
telemt_user_msgs_to_client{user="hello"} 7718
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 344.6 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2482
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 771
telemt_upstream_connect_success_total 753
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 498
telemt_me_reconnect_success_total 321
telemt_me_reader_eof_total 205
telemt_me_idle_close_by_peer_total 205
telemt_me_route_drop_no_conn_total 507
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1848
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 20
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 224
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 277
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 856
telemt_user_connections_total{user="hello"} 2208
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 9280787 (8.85 MB)
telemt_user_octets_to_client{user="hello"} 324449861 (309.42 MB)
telemt_user_msgs_from_client{user="hello"} 1400
telemt_user_msgs_to_client{user="hello"} 3646
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 480.6 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5359
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 163
telemt_upstream_connect_success_total 162
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 92
telemt_me_reconnect_success_total 88
telemt_me_reader_eof_total 47
telemt_me_idle_close_by_peer_total 47
telemt_me_route_drop_no_conn_total 1365
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5105
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_me_writer_removed_unexpected_total 62
telemt_me_writer_restored_same_endpoint_total 84
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 5090
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 36946604 (35.24 MB)
telemt_user_octets_to_client{user="hello"} 642848652 (613.07 MB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 469.9 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3157
telemt_connections_bad_total 873
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 124
telemt_upstream_connect_success_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 64
telemt_me_reconnect_attempts_total 51
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 29
telemt_me_idle_close_by_peer_total 29
telemt_me_route_drop_no_conn_total 432
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2112
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 43
telemt_me_writer_restored_same_endpoint_total 49
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 12
telemt_user_connections_total{user="hello"} 2101
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 23409540 (22.33 MB)
telemt_user_octets_to_client{user="hello"} 164437980 (156.82 MB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 48.3 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1521
telemt_upstream_connect_attempt_total 103
telemt_upstream_connect_success_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_me_reconnect_attempts_total 37
telemt_me_reconnect_success_total 36
telemt_me_route_drop_no_conn_total 2089
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1557
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 32
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_user_connections_total{user="hello"} 1438
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 3085260 (2.94 MB)
telemt_user_octets_to_client{user="hello"} 69306796 (66.10 MB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 222
```