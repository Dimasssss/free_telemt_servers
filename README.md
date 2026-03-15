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

# Server Metrics 2026-03-15 02:04:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 13802.5 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29232
telemt_connections_bad_total 368
telemt_handshake_timeouts_total 274
telemt_upstream_connect_attempt_total 3537
telemt_upstream_connect_success_total 3515
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 2804
telemt_me_reconnect_success_total 2790
telemt_me_reader_eof_total 2961
telemt_me_idle_close_by_peer_total 2961
telemt_me_route_drop_no_conn_total 8467
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27720
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2800
telemt_me_writer_restored_same_endpoint_total 2759
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 27718
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 299668680 (285.79 MB)
telemt_user_octets_to_client{user="hello"} 10498585784 (9.78 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 13808.9 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13111
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 3861
telemt_upstream_connect_success_total 3861
telemt_upstream_connect_attempts_per_request{bucket="1"} 3861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3146
telemt_me_reconnect_success_total 3133
telemt_me_reader_eof_total 3344
telemt_me_idle_close_by_peer_total 3344
telemt_me_route_drop_no_conn_total 5248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12391
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3153
telemt_me_writer_restored_same_endpoint_total 3117
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 12395
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 504884364 (481.50 MB)
telemt_user_octets_to_client{user="hello"} 2197876476 (2.05 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 13801.1 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13194
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 240
telemt_upstream_connect_attempt_total 3716
telemt_upstream_connect_success_total 3715
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3004
telemt_me_reconnect_success_total 2988
telemt_me_reader_eof_total 3223
telemt_me_idle_close_by_peer_total 3223
telemt_me_route_drop_no_conn_total 4592
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12351
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3012
telemt_me_writer_restored_same_endpoint_total 2984
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 12310
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 8615450588 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 13610485120 (12.68 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 13801.0 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14577
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 3357
telemt_upstream_connect_success_total 3356
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2649
telemt_me_reconnect_success_total 2637
telemt_me_reader_eof_total 2802
telemt_me_idle_close_by_peer_total 2802
telemt_me_route_drop_no_conn_total 5623
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13838
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2658
telemt_me_writer_restored_same_endpoint_total 2626
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 13836
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 395048032 (376.75 MB)
telemt_user_octets_to_client{user="hello"} 10486163460 (9.77 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 13801.3 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16888
telemt_connections_bad_total 2774
telemt_handshake_timeouts_total 388
telemt_upstream_connect_attempt_total 4457
telemt_upstream_connect_success_total 4399
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 4457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 3756
telemt_me_reconnect_success_total 3677
telemt_me_reader_eof_total 3879
telemt_me_idle_close_by_peer_total 3879
telemt_me_route_drop_no_conn_total 4955
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13410
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3688
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 3665
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 13396
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 187193204 (178.52 MB)
telemt_user_octets_to_client{user="hello"} 7036152940 (6.55 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 13800.3 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43639
telemt_connections_bad_total 1121
telemt_handshake_timeouts_total 174
telemt_upstream_connect_attempt_total 3067
telemt_upstream_connect_success_total 3048
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 2334
telemt_me_reconnect_success_total 2326
telemt_me_reader_eof_total 2437
telemt_me_idle_close_by_peer_total 2437
telemt_me_route_drop_no_conn_total 24196
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42668
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2319
telemt_me_writer_restored_same_endpoint_total 2299
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 41237
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1501030344 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 26543379756 (24.72 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 34
```