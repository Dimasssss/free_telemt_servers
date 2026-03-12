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

# Server Metrics 2026-03-12 08:22:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2946.9 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17609
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1888
telemt_upstream_connect_attempt_total 639
telemt_upstream_connect_success_total 637
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 443
telemt_me_reconnect_success_total 442
telemt_me_reader_eof_total 429
telemt_me_idle_close_by_peer_total 429
telemt_me_route_drop_no_conn_total 4265
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14674
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 57
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_restored_same_endpoint_total 426
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 14671
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 125780732 (119.95 MB)
telemt_user_octets_to_client{user="hello"} 5534549056 (5.15 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2840.0 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5993
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 1115
telemt_upstream_connect_success_total 1089
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 751
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1503
telemt_me_reconnect_success_total 893
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 871
telemt_me_route_drop_no_conn_total 1835
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5688
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 894
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 878
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 5685
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 35392944 (33.75 MB)
telemt_user_octets_to_client{user="hello"} 1383992476 (1.29 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2803.5 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8896
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 83
telemt_upstream_connect_attempt_total 646
telemt_upstream_connect_success_total 646
telemt_upstream_connect_attempts_per_request{bucket="1"} 646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 453
telemt_me_reconnect_success_total 451
telemt_me_reader_eof_total 430
telemt_me_idle_close_by_peer_total 430
telemt_me_route_drop_no_conn_total 2605
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8439
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 429
telemt_me_writer_restored_same_endpoint_total 431
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 8439
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 95615064 (91.19 MB)
telemt_user_octets_to_client{user="hello"} 12701129416 (11.83 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2779.5 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10500
telemt_connections_bad_total 1012
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 696
telemt_upstream_connect_success_total 663
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 496
telemt_me_reconnect_success_total 476
telemt_me_reader_eof_total 465
telemt_me_idle_close_by_peer_total 465
telemt_me_route_drop_no_conn_total 2715
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8746
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 484
telemt_me_writer_restored_same_endpoint_total 468
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 8746
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 102401480 (97.66 MB)
telemt_user_octets_to_client{user="hello"} 2437562652 (2.27 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2748.7 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5284
telemt_connections_bad_total 573
telemt_handshake_timeouts_total 85
telemt_upstream_connect_attempt_total 892
telemt_upstream_connect_success_total 858
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 697
telemt_me_reconnect_success_total 695
telemt_me_reader_eof_total 669
telemt_me_idle_close_by_peer_total 669
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 1423
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4494
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 689
telemt_me_writer_restored_same_endpoint_total 682
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 4494
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 14178824 (13.52 MB)
telemt_user_octets_to_client{user="hello"} 662987320 (632.27 MB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 2735.5 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13033
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 138
telemt_upstream_connect_attempt_total 416
telemt_upstream_connect_success_total 412
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 254
telemt_me_reconnect_success_total 253
telemt_me_reader_eof_total 243
telemt_me_idle_close_by_peer_total 243
telemt_me_route_drop_no_conn_total 5919
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11803
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
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 257
telemt_me_writer_restored_same_endpoint_total 246
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 11777
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 349659384 (333.46 MB)
telemt_user_octets_to_client{user="hello"} 9774596864 (9.10 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 36
```