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

# Server Metrics 2026-03-14 22:51:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 2201.4 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4935
telemt_connections_bad_total 235
telemt_handshake_timeouts_total 102
telemt_upstream_connect_attempt_total 574
telemt_upstream_connect_success_total 571
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 421
telemt_me_reconnect_success_total 418
telemt_me_reader_eof_total 398
telemt_me_idle_close_by_peer_total 398
telemt_me_route_drop_no_conn_total 1179
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4411
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
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 403
telemt_me_writer_restored_same_endpoint_total 387
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 4411
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 47531288 (45.33 MB)
telemt_user_octets_to_client{user="hello"} 1030297592 (982.57 MB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 2207.8 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1381
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 677
telemt_upstream_connect_success_total 677
telemt_upstream_connect_attempts_per_request{bucket="1"} 677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 386
telemt_me_reconnect_attempts_total 522
telemt_me_reconnect_success_total 522
telemt_me_reader_eof_total 519
telemt_me_idle_close_by_peer_total 519
telemt_me_route_drop_no_conn_total 663
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1313
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 515
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 1313
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 11929512 (11.38 MB)
telemt_user_octets_to_client{user="hello"} 302583460 (288.57 MB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 2200.2 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2201
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 600
telemt_upstream_connect_success_total 600
telemt_upstream_connect_attempts_per_request{bucket="1"} 600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 447
telemt_me_reconnect_success_total 443
telemt_me_reader_eof_total 451
telemt_me_idle_close_by_peer_total 451
telemt_me_route_drop_no_conn_total 595
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2076
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 433
telemt_me_writer_restored_same_endpoint_total 439
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 2072
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 172353200 (164.37 MB)
telemt_user_octets_to_client{user="hello"} 1470552332 (1.37 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 2200.1 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2128
telemt_connections_bad_total 6
telemt_upstream_connect_attempt_total 545
telemt_upstream_connect_success_total 545
telemt_upstream_connect_attempts_per_request{bucket="1"} 545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 396
telemt_me_reconnect_success_total 394
telemt_me_reader_eof_total 386
telemt_me_idle_close_by_peer_total 386
telemt_me_route_drop_no_conn_total 845
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2065
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
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 389
telemt_me_writer_restored_same_endpoint_total 383
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 2065
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 45676772 (43.56 MB)
telemt_user_octets_to_client{user="hello"} 4176140788 (3.89 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 2200.1 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2679
telemt_connections_bad_total 444
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 745
telemt_upstream_connect_success_total 732
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 648
telemt_me_reconnect_success_total 583
telemt_me_reader_eof_total 550
telemt_me_idle_close_by_peer_total 550
telemt_me_route_drop_no_conn_total 518
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2165
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 569
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 2163
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 26447784 (25.22 MB)
telemt_user_octets_to_client{user="hello"} 3221631404 (3.00 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 2199.2 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6694
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 541
telemt_upstream_connect_success_total 539
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 269
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 388
telemt_me_reconnect_success_total 387
telemt_me_reader_eof_total 362
telemt_me_idle_close_by_peer_total 362
telemt_me_route_drop_no_conn_total 3249
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6359
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
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 365
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 6359
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 109124252 (104.07 MB)
telemt_user_octets_to_client{user="hello"} 6511804772 (6.06 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 36
```