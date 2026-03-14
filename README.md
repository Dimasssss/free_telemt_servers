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

# Server Metrics 2026-03-14 22:56:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 2506.5 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5328
telemt_connections_bad_total 239
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 639
telemt_upstream_connect_success_total 636
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 486
telemt_me_reconnect_success_total 483
telemt_me_reader_eof_total 465
telemt_me_idle_close_by_peer_total 465
telemt_me_route_drop_no_conn_total 1270
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4781
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 36
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 470
telemt_me_writer_restored_same_endpoint_total 452
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 4781
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 52194236 (49.78 MB)
telemt_user_octets_to_client{user="hello"} 1413250648 (1.32 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 2513.3 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1493
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 747
telemt_upstream_connect_success_total 747
telemt_upstream_connect_attempts_per_request{bucket="1"} 747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 430
telemt_me_reconnect_attempts_total 592
telemt_me_reconnect_success_total 592
telemt_me_reader_eof_total 591
telemt_me_idle_close_by_peer_total 591
telemt_me_route_drop_no_conn_total 677
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1414
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 587
telemt_me_writer_restored_same_endpoint_total 576
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 1414
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 13388992 (12.77 MB)
telemt_user_octets_to_client{user="hello"} 343059072 (327.17 MB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 2505.8 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2476
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 668
telemt_upstream_connect_success_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 515
telemt_me_reconnect_success_total 510
telemt_me_reader_eof_total 518
telemt_me_idle_close_by_peer_total 518
telemt_me_route_drop_no_conn_total 729
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2335
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 500
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 2329
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 261714812 (249.59 MB)
telemt_user_octets_to_client{user="hello"} 2739358220 (2.55 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 2505.5 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2328
telemt_connections_bad_total 7
telemt_upstream_connect_attempt_total 600
telemt_upstream_connect_success_total 600
telemt_upstream_connect_attempts_per_request{bucket="1"} 600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 451
telemt_me_reconnect_success_total 449
telemt_me_reader_eof_total 441
telemt_me_idle_close_by_peer_total 441
telemt_me_route_drop_no_conn_total 984
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2258
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
telemt_me_writer_removed_unexpected_total 444
telemt_me_writer_restored_same_endpoint_total 438
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 2258
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 47385868 (45.19 MB)
telemt_user_octets_to_client{user="hello"} 4206491068 (3.92 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 2505.6 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3137
telemt_connections_bad_total 499
telemt_handshake_timeouts_total 61
telemt_upstream_connect_attempt_total 868
telemt_upstream_connect_success_total 855
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 771
telemt_me_reconnect_success_total 705
telemt_me_reader_eof_total 673
telemt_me_idle_close_by_peer_total 673
telemt_me_route_drop_no_conn_total 629
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2505
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 692
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 693
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 2503
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 27847652 (26.56 MB)
telemt_user_octets_to_client{user="hello"} 3308528684 (3.08 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 2504.6 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7617
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 596
telemt_upstream_connect_success_total 594
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 301
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 443
telemt_me_reconnect_success_total 442
telemt_me_reader_eof_total 418
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 3774
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7238
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
telemt_me_writer_removed_unexpected_total 421
telemt_me_writer_restored_same_endpoint_total 415
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 7238
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 119121568 (113.60 MB)
telemt_user_octets_to_client{user="hello"} 7372554512 (6.87 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 40
```