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

# Server Metrics 2026-03-14 22:46:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 1895.9 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4483
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 479
telemt_upstream_connect_success_total 476
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 328
telemt_me_reconnect_success_total 325
telemt_me_reader_eof_total 290
telemt_me_idle_close_by_peer_total 290
telemt_me_route_drop_no_conn_total 1021
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4003
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 310
telemt_me_writer_restored_same_endpoint_total 294
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 4003
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 43445648 (41.43 MB)
telemt_user_octets_to_client{user="hello"} 777998048 (741.96 MB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 1902.6 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1217
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 579
telemt_upstream_connect_success_total 579
telemt_upstream_connect_attempts_per_request{bucket="1"} 579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 337
telemt_me_reconnect_attempts_total 424
telemt_me_reconnect_success_total 424
telemt_me_reader_eof_total 409
telemt_me_idle_close_by_peer_total 409
telemt_me_route_drop_no_conn_total 488
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1153
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 417
telemt_me_writer_restored_same_endpoint_total 408
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 1153
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 9099828 (8.68 MB)
telemt_user_octets_to_client{user="hello"} 290821224 (277.35 MB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 1895.1 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1953
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 513
telemt_upstream_connect_success_total 513
telemt_upstream_connect_attempts_per_request{bucket="1"} 513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 360
telemt_me_reconnect_success_total 356
telemt_me_reader_eof_total 346
telemt_me_idle_close_by_peer_total 346
telemt_me_route_drop_no_conn_total 493
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1839
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 346
telemt_me_writer_restored_same_endpoint_total 352
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 1838
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 102549996 (97.80 MB)
telemt_user_octets_to_client{user="hello"} 1287156948 (1.20 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 1894.8 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1869
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 455
telemt_upstream_connect_success_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 307
telemt_me_reconnect_success_total 305
telemt_me_reader_eof_total 286
telemt_me_idle_close_by_peer_total 286
telemt_me_route_drop_no_conn_total 679
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1812
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 300
telemt_me_writer_restored_same_endpoint_total 294
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 1812
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 37349196 (35.62 MB)
telemt_user_octets_to_client{user="hello"} 3421442332 (3.19 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 1894.9 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2327
telemt_connections_bad_total 362
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 553
telemt_upstream_connect_success_total 540
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 405
telemt_me_reconnect_success_total 404
telemt_me_reader_eof_total 369
telemt_me_idle_close_by_peer_total 369
telemt_me_route_drop_no_conn_total 438
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1912
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 388
telemt_me_writer_restored_same_endpoint_total 392
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 1912
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 21435848 (20.44 MB)
telemt_user_octets_to_client{user="hello"} 1965574900 (1.83 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 1893.9 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5945
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 462
telemt_upstream_connect_success_total 460
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 315
telemt_me_reconnect_success_total 314
telemt_me_reader_eof_total 277
telemt_me_idle_close_by_peer_total 277
telemt_me_route_drop_no_conn_total 2623
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5637
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 292
telemt_me_writer_restored_same_endpoint_total 287
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 5637
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 98330588 (93.78 MB)
telemt_user_octets_to_client{user="hello"} 5573103332 (5.19 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 28
```