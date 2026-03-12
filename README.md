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

# Server Metrics 2026-03-12 07:41:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 491.1 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4011
telemt_handshake_timeouts_total 433
telemt_upstream_connect_attempt_total 151
telemt_upstream_connect_success_total 150
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 86
telemt_me_reconnect_success_total 86
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3374
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 20
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_me_writer_removed_unexpected_total 69
telemt_me_writer_restored_same_endpoint_total 70
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 3373
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 29090760 (27.74 MB)
telemt_user_octets_to_client{user="hello"} 694047684 (661.90 MB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 384.1 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 716
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 136
telemt_upstream_connect_success_total 131
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 69
telemt_me_reconnect_success_total 69
telemt_me_reader_eof_total 36
telemt_me_idle_close_by_peer_total 36
telemt_me_route_drop_no_conn_total 189
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 690
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 20
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 56
telemt_me_writer_restored_same_endpoint_total 54
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 24
telemt_user_connections_total{user="hello"} 690
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 3018788 (2.88 MB)
telemt_user_octets_to_client{user="hello"} 88167792 (84.08 MB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 347.7 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1209
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 134
telemt_upstream_connect_success_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 50
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 70
telemt_me_reconnect_success_total 70
telemt_me_reader_eof_total 33
telemt_me_idle_close_by_peer_total 33
telemt_me_route_drop_no_conn_total 168
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1158
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 50
telemt_me_writer_restored_same_endpoint_total 50
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_user_connections_total{user="hello"} 1158
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 6128412 (5.84 MB)
telemt_user_octets_to_client{user="hello"} 523775108 (499.51 MB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 323.7 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1564
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 96
telemt_upstream_connect_success_total 77
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 96
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 27
telemt_me_reconnect_success_total 11
telemt_me_route_drop_no_conn_total 334
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1384
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 18
telemt_me_writer_restored_same_endpoint_total 3
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 88
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1384
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 4518080 (4.31 MB)
telemt_user_octets_to_client{user="hello"} 292926900 (279.36 MB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 292.9 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517
telemt_connections_bad_total 96
telemt_upstream_connect_attempt_total 114
telemt_upstream_connect_success_total 108
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 46
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_me_writer_removed_unexpected_total 34
telemt_me_writer_restored_same_endpoint_total 35
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 399
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 1669160 (1.59 MB)
telemt_user_octets_to_client{user="hello"} 128448792 (122.50 MB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 279.8 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1224
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 85
telemt_upstream_connect_success_total 84
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 85
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 21
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 277
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1139
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 1140
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 61013104 (58.19 MB)
telemt_user_octets_to_client{user="hello"} 360417664 (343.72 MB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 37
```