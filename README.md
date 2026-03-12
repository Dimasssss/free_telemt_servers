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

# Server Metrics 2026-03-12 08:02:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1719.0 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11787
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 1875
telemt_upstream_connect_attempt_total 347
telemt_upstream_connect_success_total 345
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 238
telemt_me_reconnect_success_total 238
telemt_me_reader_eof_total 208
telemt_me_idle_close_by_peer_total 208
telemt_me_route_drop_no_conn_total 2658
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9303
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 50
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 228
telemt_me_writer_restored_same_endpoint_total 222
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 9302
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 76184524 (72.66 MB)
telemt_user_octets_to_client{user="hello"} 2743005284 (2.55 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 1611.9 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3471
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 525
telemt_upstream_connect_success_total 511
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 406
telemt_me_reconnect_success_total 405
telemt_me_reader_eof_total 359
telemt_me_idle_close_by_peer_total 359
telemt_me_route_drop_no_conn_total 1134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3338
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 382
telemt_me_writer_restored_same_endpoint_total 390
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_user_connections_total{user="hello"} 3336
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 13041352 (12.44 MB)
telemt_user_octets_to_client{user="hello"} 687456980 (655.61 MB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 1575.6 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4876
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 356
telemt_upstream_connect_success_total 356
telemt_upstream_connect_attempts_per_request{bucket="1"} 356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 162
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 249
telemt_me_reconnect_success_total 248
telemt_me_reader_eof_total 212
telemt_me_idle_close_by_peer_total 212
telemt_me_route_drop_no_conn_total 1420
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4669
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 225
telemt_me_writer_restored_same_endpoint_total 228
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 4667
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 41037880 (39.14 MB)
telemt_user_octets_to_client{user="hello"} 6148143736 (5.73 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 1551.5 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5843
telemt_connections_bad_total 337
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 276
telemt_upstream_connect_success_total 251
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 158
telemt_me_reconnect_success_total 139
telemt_me_reader_eof_total 127
telemt_me_idle_close_by_peer_total 127
telemt_me_route_drop_no_conn_total 1487
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5000
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 146
telemt_me_writer_restored_same_endpoint_total 131
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 5000
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 34950116 (33.33 MB)
telemt_user_octets_to_client{user="hello"} 967658380 (922.83 MB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1520.7 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2656
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 388
telemt_upstream_connect_success_total 370
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 265
telemt_me_reconnect_success_total 264
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 579
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2175
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 254
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 2175
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 8073660 (7.70 MB)
telemt_user_octets_to_client{user="hello"} 382108004 (364.41 MB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 1507.7 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6928
telemt_connections_bad_total 490
telemt_handshake_timeouts_total 65
telemt_upstream_connect_attempt_total 213
telemt_upstream_connect_success_total 211
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 105
telemt_me_reconnect_success_total 104
telemt_me_reader_eof_total 84
telemt_me_idle_close_by_peer_total 84
telemt_me_route_drop_no_conn_total 2928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6058
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 106
telemt_me_writer_restored_same_endpoint_total 97
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 6057
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 208403836 (198.75 MB)
telemt_user_octets_to_client{user="hello"} 1373121200 (1.28 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 48
```