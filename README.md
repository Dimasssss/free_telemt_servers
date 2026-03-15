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

# Server Metrics 2026-03-15 04:40:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 23150.8 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55950
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 945
telemt_upstream_connect_attempt_total 5847
telemt_upstream_connect_success_total 5812
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 5847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4669
telemt_me_reconnect_success_total 4652
telemt_me_reader_eof_total 4974
telemt_me_idle_close_by_peer_total 4974
telemt_me_route_drop_no_conn_total 16938
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52687
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 395
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4682
telemt_me_writer_restored_same_endpoint_total 4621
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 52685
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 523049708 (498.82 MB)
telemt_user_octets_to_client{user="hello"} 17056463128 (15.89 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 23157.4 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19746
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 6420
telemt_upstream_connect_success_total 6420
telemt_upstream_connect_attempts_per_request{bucket="1"} 6420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5271
telemt_me_reconnect_success_total 5247
telemt_me_reader_eof_total 5633
telemt_me_idle_close_by_peer_total 5633
telemt_me_route_drop_no_conn_total 10443
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18680
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5293
telemt_me_writer_restored_same_endpoint_total 5231
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 18685
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 619891748 (591.17 MB)
telemt_user_octets_to_client{user="hello"} 5824585848 (5.42 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 23150.0 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24921
telemt_connections_bad_total 427
telemt_handshake_timeouts_total 1680
telemt_upstream_connect_attempt_total 6201
telemt_upstream_connect_success_total 6200
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5057
telemt_me_reconnect_success_total 5033
telemt_me_reader_eof_total 5433
telemt_me_idle_close_by_peer_total 5433
telemt_me_route_drop_no_conn_total 8193
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22101
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5076
telemt_me_writer_restored_same_endpoint_total 5029
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 22052
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 8709042808 (8.11 GB)
telemt_user_octets_to_client{user="hello"} 15909954376 (14.82 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 23149.9 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25837
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 110
telemt_upstream_connect_attempt_total 5476
telemt_upstream_connect_success_total 5475
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4335
telemt_me_reconnect_success_total 4319
telemt_me_reader_eof_total 4617
telemt_me_idle_close_by_peer_total 4617
telemt_me_route_drop_no_conn_total 12063
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24200
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4361
telemt_me_writer_restored_same_endpoint_total 4308
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 24122
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 499946404 (476.79 MB)
telemt_user_octets_to_client{user="hello"} 14580118232 (13.58 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 23149.0 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70194
telemt_connections_bad_total 1524
telemt_handshake_timeouts_total 293
telemt_upstream_connect_attempt_total 5194
telemt_upstream_connect_success_total 5164
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 5194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 4019
telemt_me_reconnect_success_total 4000
telemt_me_reader_eof_total 4245
telemt_me_idle_close_by_peer_total 4245
telemt_me_route_drop_no_conn_total 38360
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67845
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4011
telemt_me_writer_restored_same_endpoint_total 3973
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 66404
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 1953363376 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 42703269560 (39.77 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 32
```