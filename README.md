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

# Server Metrics 2026-03-15 01:23:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 11359.3 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23769
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 265
telemt_upstream_connect_attempt_total 2910
telemt_upstream_connect_success_total 2894
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2314
telemt_me_reconnect_success_total 2303
telemt_me_reader_eof_total 2432
telemt_me_idle_close_by_peer_total 2432
telemt_me_route_drop_no_conn_total 6572
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22405
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 130
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2306
telemt_me_writer_restored_same_endpoint_total 2272
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 22403
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 238388364 (227.34 MB)
telemt_user_octets_to_client{user="hello"} 8437763312 (7.86 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 11365.8 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10895
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 3161
telemt_upstream_connect_success_total 3161
telemt_upstream_connect_attempts_per_request{bucket="1"} 3161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1763
telemt_me_reconnect_attempts_total 2575
telemt_me_reconnect_success_total 2566
telemt_me_reader_eof_total 2727
telemt_me_idle_close_by_peer_total 2727
telemt_me_route_drop_no_conn_total 3857
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10293
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2579
telemt_me_writer_restored_same_endpoint_total 2550
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 10296
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 144253860 (137.57 MB)
telemt_user_octets_to_client{user="hello"} 1816359344 (1.69 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 11358.4 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11257
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 214
telemt_upstream_connect_attempt_total 3014
telemt_upstream_connect_success_total 3013
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2431
telemt_me_reconnect_success_total 2418
telemt_me_reader_eof_total 2599
telemt_me_idle_close_by_peer_total 2599
telemt_me_route_drop_no_conn_total 3763
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10627
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2432
telemt_me_writer_restored_same_endpoint_total 2414
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 10590
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 4431750800 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 11585135940 (10.79 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 11358.3 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11441
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 2763
telemt_upstream_connect_success_total 2762
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2184
telemt_me_reconnect_success_total 2173
telemt_me_reader_eof_total 2302
telemt_me_idle_close_by_peer_total 2302
telemt_me_route_drop_no_conn_total 4545
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11037
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2188
telemt_me_writer_restored_same_endpoint_total 2162
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 11035
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 303212856 (289.17 MB)
telemt_user_octets_to_client{user="hello"} 8627398244 (8.03 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 11358.3 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14381
telemt_connections_bad_total 2336
telemt_handshake_timeouts_total 381
telemt_upstream_connect_attempt_total 3676
telemt_upstream_connect_success_total 3628
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 3676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 3114
telemt_me_reconnect_success_total 3035
telemt_me_reader_eof_total 3170
telemt_me_idle_close_by_peer_total 3170
telemt_me_route_drop_no_conn_total 3947
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11385
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3043
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 3023
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 11373
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 173330776 (165.30 MB)
telemt_user_octets_to_client{user="hello"} 6414408316 (5.97 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 11357.3 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36312
telemt_connections_bad_total 994
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 2506
telemt_upstream_connect_success_total 2489
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 1906
telemt_me_reconnect_success_total 1899
telemt_me_reader_eof_total 1988
telemt_me_idle_close_by_peer_total 1988
telemt_me_route_drop_no_conn_total 20477
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35662
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1890
telemt_me_writer_restored_same_endpoint_total 1872
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 34231
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 691985660 (659.93 MB)
telemt_user_octets_to_client{user="hello"} 23407265148 (21.80 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 31
```