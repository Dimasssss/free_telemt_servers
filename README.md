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

# Server Metrics 2026-03-18 22:02:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 861.2 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10815
telemt_connections_bad_total 730
telemt_connections_current 706
telemt_connections_me_current 706
telemt_handshake_timeouts_total 106
telemt_upstream_connect_attempt_total 115
telemt_upstream_connect_success_total 113
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 51
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 2361
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9443
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 35
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_me_writer_removed_unexpected_total 39
telemt_me_writer_restored_same_endpoint_total 41
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 9442
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 101519028 (96.82 MB)
telemt_user_octets_to_client{user="hello"} 2307607400 (2.15 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 865.0 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31553
telemt_connections_bad_total 1016
telemt_connections_current 2071
telemt_connections_me_current 2071
telemt_handshake_timeouts_total 272
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
telemt_me_route_drop_no_conn_total 13900
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29028
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 74
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 29026
telemt_user_connections_current{user="hello"} 2071
telemt_user_octets_from_client{user="hello"} 628508152 (599.39 MB)
telemt_user_octets_to_client{user="hello"} 6197627144 (5.77 GB)
telemt_user_unique_ips_current{user="hello"} 741
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 862.2 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26888
telemt_connections_bad_total 2119
telemt_connections_current 1651
telemt_connections_me_current 1651
telemt_handshake_timeouts_total 494
telemt_upstream_connect_attempt_total 185
telemt_upstream_connect_success_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 71
telemt_me_reconnect_attempts_total 118
telemt_me_reconnect_success_total 118
telemt_me_reader_eof_total 94
telemt_me_idle_close_by_peer_total 94
telemt_me_route_drop_no_conn_total 9301
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23457
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 83
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_me_writer_removed_unexpected_total 116
telemt_me_writer_restored_same_endpoint_total 102
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_user_connections_total{user="hello"} 23448
telemt_user_connections_current{user="hello"} 1651
telemt_user_octets_from_client{user="hello"} 290178204 (276.74 MB)
telemt_user_octets_to_client{user="hello"} 12854075476 (11.97 GB)
telemt_user_unique_ips_current{user="hello"} 633
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 915.5 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34341
telemt_connections_bad_total 2747
telemt_connections_current 1544
telemt_connections_me_current 1544
telemt_handshake_timeouts_total 373
telemt_upstream_connect_attempt_total 168
telemt_upstream_connect_success_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 104
telemt_me_reconnect_success_total 104
telemt_me_reader_eof_total 83
telemt_me_idle_close_by_peer_total 83
telemt_me_route_drop_no_conn_total 23903
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30034
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_restored_same_endpoint_total 80
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 30034
telemt_user_connections_current{user="hello"} 1544
telemt_user_octets_from_client{user="hello"} 241483296 (230.30 MB)
telemt_user_octets_to_client{user="hello"} 4137391972 (3.85 GB)
telemt_user_unique_ips_current{user="hello"} 573
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 859.0 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26943
telemt_connections_bad_total 1021
telemt_connections_current 1728
telemt_connections_me_current 1728
telemt_handshake_timeouts_total 619
telemt_upstream_connect_attempt_total 122
telemt_upstream_connect_success_total 121
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 52
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 23
telemt_me_idle_close_by_peer_total 23
telemt_me_route_drop_no_conn_total 6432
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21775
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 93
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 46
telemt_me_writer_restored_same_endpoint_total 28
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 21765
telemt_user_connections_current{user="hello"} 1728
telemt_user_octets_from_client{user="hello"} 202228876 (192.86 MB)
telemt_user_octets_to_client{user="hello"} 15994176392 (14.90 GB)
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 870.3 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6397
telemt_connections_bad_total 1944
telemt_connections_current 393
telemt_connections_me_current 393
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 206
telemt_upstream_connect_success_total 202
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 141
telemt_me_reconnect_success_total 140
telemt_me_reader_eof_total 79
telemt_me_idle_close_by_peer_total 79
telemt_me_route_drop_no_conn_total 1392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4310
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
telemt_me_writer_removed_unexpected_total 101
telemt_me_writer_restored_same_endpoint_total 110
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 4310
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 149000068 (142.10 MB)
telemt_user_octets_to_client{user="hello"} 1964299692 (1.83 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 861.3 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21975
telemt_connections_bad_total 3242
telemt_connections_current 1542
telemt_connections_me_current 1542
telemt_handshake_timeouts_total 519
telemt_upstream_connect_attempt_total 122
telemt_upstream_connect_success_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_me_reconnect_attempts_total 54
telemt_me_reconnect_success_total 54
telemt_me_reader_eof_total 34
telemt_me_idle_close_by_peer_total 34
telemt_me_route_drop_no_conn_total 4540
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17510
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 148
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_me_writer_removed_unexpected_total 56
telemt_me_writer_restored_same_endpoint_total 39
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 17510
telemt_user_connections_current{user="hello"} 1542
telemt_user_octets_from_client{user="hello"} 208957196 (199.28 MB)
telemt_user_octets_to_client{user="hello"} 10114133224 (9.42 GB)
telemt_user_unique_ips_current{user="hello"} 596
telemt_user_unique_ips_recent_window{user="hello"} 166
```