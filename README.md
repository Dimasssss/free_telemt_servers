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

# Server Metrics 2026-03-14 13:24:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 485.9 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2923
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 123
telemt_upstream_connect_success_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 57
telemt_me_reconnect_success_total 55
telemt_me_reader_eof_total 30
telemt_me_idle_close_by_peer_total 30
telemt_me_route_drop_no_conn_total 641
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2685
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 7
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 52
telemt_me_writer_restored_same_endpoint_total 37
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_user_connections_total{user="hello"} 2685
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 16295124 (15.54 MB)
telemt_user_octets_to_client{user="hello"} 632417184 (603.12 MB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 484.2 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1217
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 94
telemt_upstream_connect_success_total 77
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 94
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 28
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 397
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1136
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1121
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 9648172 (9.20 MB)
telemt_user_octets_to_client{user="hello"} 263206324 (251.01 MB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 488.1 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1264
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 836
telemt_upstream_connect_success_total 834
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 88366
telemt_me_reconnect_success_total 444
telemt_me_reader_eof_total 333
telemt_me_idle_close_by_peer_total 333
telemt_me_route_drop_no_conn_total 213
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 850
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 345
telemt_me_refill_failed_total 2859
telemt_me_writer_restored_same_endpoint_total 406
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_user_connections_total{user="hello"} 1160
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 30816197 (29.39 MB)
telemt_user_octets_to_client{user="hello"} 940128466 (896.58 MB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 493.2 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2226
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 124
telemt_upstream_connect_success_total 123
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 60
telemt_me_reconnect_success_total 58
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2048
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_restored_same_endpoint_total 56
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_user_connections_total{user="hello"} 2038
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 38013624 (36.25 MB)
telemt_user_octets_to_client{user="hello"} 478309480 (456.15 MB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 486.3 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1250
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 120
telemt_upstream_connect_success_total 117
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 53
telemt_me_reconnect_success_total 53
telemt_me_reader_eof_total 29
telemt_me_idle_close_by_peer_total 29
telemt_me_route_drop_no_conn_total 334
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1073
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_me_writer_removed_unexpected_total 42
telemt_me_writer_restored_same_endpoint_total 49
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_user_connections_total{user="hello"} 1069
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 5480328 (5.23 MB)
telemt_user_octets_to_client{user="hello"} 127655752 (121.74 MB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 485.7 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4537
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 136
telemt_upstream_connect_success_total 118
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 63
telemt_me_reconnect_success_total 47
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 1550
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4146
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 35
telemt_me_writer_restored_same_endpoint_total 43
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 4096
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 49496676 (47.20 MB)
telemt_user_octets_to_client{user="hello"} 1750077116 (1.63 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 66
```