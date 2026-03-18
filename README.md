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

# Server Metrics 2026-03-18 21:57:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 554.4 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7443
telemt_connections_bad_total 469
telemt_connections_current 672
telemt_connections_me_current 672
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 111
telemt_upstream_connect_success_total 109
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 47
telemt_me_reconnect_success_total 47
telemt_me_reader_eof_total 13
telemt_me_idle_close_by_peer_total 13
telemt_me_route_drop_no_conn_total 1366
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6448
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_me_writer_removed_unexpected_total 35
telemt_me_writer_restored_same_endpoint_total 37
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 6447
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 70138108 (66.89 MB)
telemt_user_octets_to_client{user="hello"} 1570683796 (1.46 GB)
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 558.0 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21961
telemt_connections_bad_total 906
telemt_connections_current 2230
telemt_connections_me_current 2230
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 86
telemt_upstream_connect_success_total 84
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 18
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 9132
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20016
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 20017
telemt_user_connections_current{user="hello"} 2230
telemt_user_octets_from_client{user="hello"} 492217404 (469.42 MB)
telemt_user_octets_to_client{user="hello"} 4086568916 (3.81 GB)
telemt_user_unique_ips_current{user="hello"} 755
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 555.3 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18586
telemt_connections_bad_total 1339
telemt_connections_current 1782
telemt_connections_me_current 1782
telemt_handshake_timeouts_total 317
telemt_upstream_connect_attempt_total 167
telemt_upstream_connect_success_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 64
telemt_me_reconnect_attempts_total 100
telemt_me_reconnect_success_total 100
telemt_me_reader_eof_total 66
telemt_me_idle_close_by_peer_total 66
telemt_me_route_drop_no_conn_total 5948
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16361
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 88
telemt_me_writer_restored_same_endpoint_total 84
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_user_connections_total{user="hello"} 16352
telemt_user_connections_current{user="hello"} 1782
telemt_user_octets_from_client{user="hello"} 198268376 (189.08 MB)
telemt_user_octets_to_client{user="hello"} 8473828412 (7.89 GB)
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 608.5 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24325
telemt_connections_bad_total 1252
telemt_connections_current 1505
telemt_connections_me_current 1505
telemt_handshake_timeouts_total 254
telemt_upstream_connect_attempt_total 162
telemt_upstream_connect_success_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 98
telemt_me_reconnect_success_total 98
telemt_me_reader_eof_total 70
telemt_me_idle_close_by_peer_total 70
telemt_me_route_drop_no_conn_total 17481
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21882
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_removed_unexpected_total 92
telemt_me_writer_restored_same_endpoint_total 74
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_user_connections_total{user="hello"} 21882
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 187761332 (179.06 MB)
telemt_user_octets_to_client{user="hello"} 2790322800 (2.60 GB)
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 552.0 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17945
telemt_connections_bad_total 684
telemt_connections_current 1666
telemt_connections_me_current 1666
telemt_handshake_timeouts_total 405
telemt_upstream_connect_attempt_total 114
telemt_upstream_connect_success_total 113
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 3603
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14426
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 61
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_removed_unexpected_total 38
telemt_me_writer_restored_same_endpoint_total 20
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 14417
telemt_user_connections_current{user="hello"} 1666
telemt_user_octets_from_client{user="hello"} 138581348 (132.16 MB)
telemt_user_octets_to_client{user="hello"} 9877524448 (9.20 GB)
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 563.3 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4358
telemt_connections_bad_total 1147
telemt_connections_current 399
telemt_connections_me_current 399
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 177
telemt_upstream_connect_success_total 173
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 112
telemt_me_reconnect_success_total 112
telemt_me_reader_eof_total 51
telemt_me_idle_close_by_peer_total 51
telemt_me_route_drop_no_conn_total 926
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3121
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 23
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 73
telemt_me_writer_restored_same_endpoint_total 82
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 3122
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 43080400 (41.08 MB)
telemt_user_octets_to_client{user="hello"} 1451218908 (1.35 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 554.3 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14387
telemt_connections_bad_total 1839
telemt_connections_current 1617
telemt_connections_me_current 1617
telemt_handshake_timeouts_total 332
telemt_upstream_connect_attempt_total 113
telemt_upstream_connect_success_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 24
telemt_me_idle_close_by_peer_total 24
telemt_me_route_drop_no_conn_total 2573
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11686
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 46
telemt_me_writer_restored_same_endpoint_total 30
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 11686
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 122172060 (116.51 MB)
telemt_user_octets_to_client{user="hello"} 5906708436 (5.50 GB)
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 181
```