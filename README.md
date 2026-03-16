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

# Server Metrics 2026-03-16 18:53:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 479.5 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3823
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 149
telemt_upstream_connect_success_total 148
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 81
telemt_me_reconnect_success_total 81
telemt_me_reader_eof_total 45
telemt_me_idle_close_by_peer_total 45
telemt_me_route_drop_no_conn_total 1092
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3629
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 67
telemt_me_writer_restored_same_endpoint_total 60
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 3625
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 82862960 (79.02 MB)
telemt_user_octets_to_client{user="hello"} 2860331872 (2.66 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 731.0 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5506
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 106
telemt_upstream_connect_success_total 103
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 37
telemt_me_reconnect_success_total 37
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 2517
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5276
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 12
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_user_connections_total{user="hello"} 5276
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 55594832 (53.02 MB)
telemt_user_octets_to_client{user="hello"} 1560477656 (1.45 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 507.0 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1891
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 108
telemt_upstream_connect_success_total 107
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 40
telemt_me_reconnect_success_total 40
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 470
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1849
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 35
telemt_me_writer_restored_same_endpoint_total 29
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_user_connections_total{user="hello"} 1849
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 30410068 (29.00 MB)
telemt_user_octets_to_client{user="hello"} 823680316 (785.52 MB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 566.3 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4763
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 101
telemt_upstream_connect_success_total 100
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 30
telemt_me_reconnect_success_total 30
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 1091
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4489
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 26
telemt_me_writer_restored_same_endpoint_total 23
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_user_connections_total{user="hello"} 4489
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 43631256 (41.61 MB)
telemt_user_octets_to_client{user="hello"} 1179855208 (1.10 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 538.3 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2251
telemt_connections_bad_total 613
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 151
telemt_upstream_connect_success_total 148
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 83
telemt_me_reconnect_success_total 82
telemt_me_reader_eof_total 41
telemt_me_idle_close_by_peer_total 41
telemt_me_route_drop_no_conn_total 413
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1505
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 63
telemt_me_writer_restored_same_endpoint_total 74
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_user_connections_total{user="hello"} 1505
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 7406204 (7.06 MB)
telemt_user_octets_to_client{user="hello"} 264487452 (252.23 MB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 699.9 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7700
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 85
telemt_upstream_connect_success_total 83
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 85
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 18
telemt_me_route_drop_no_conn_total 2627
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7364
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 7362
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 56086152 (53.49 MB)
telemt_user_octets_to_client{user="hello"} 3409504268 (3.18 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 93
```