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

# Server Metrics 2026-03-15 03:41:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 19603.7 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45612
telemt_connections_bad_total 375
telemt_handshake_timeouts_total 320
telemt_upstream_connect_attempt_total 4972
telemt_upstream_connect_success_total 4942
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3972
telemt_me_reconnect_success_total 3956
telemt_me_reader_eof_total 4216
telemt_me_idle_close_by_peer_total 4216
telemt_me_route_drop_no_conn_total 13609
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43485
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 260
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3977
telemt_me_writer_restored_same_endpoint_total 3925
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 43483
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 470076800 (448.30 MB)
telemt_user_octets_to_client{user="hello"} 14098448432 (13.13 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 19610.2 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16762
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 5492
telemt_upstream_connect_success_total 5492
telemt_upstream_connect_attempts_per_request{bucket="1"} 5492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 4518
telemt_me_reconnect_success_total 4499
telemt_me_reader_eof_total 4819
telemt_me_idle_close_by_peer_total 4819
telemt_me_route_drop_no_conn_total 8500
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15833
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4537
telemt_me_writer_restored_same_endpoint_total 4483
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 15837
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 591808492 (564.39 MB)
telemt_user_octets_to_client{user="hello"} 4160944956 (3.88 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 19602.7 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18541
telemt_connections_bad_total 424
telemt_handshake_timeouts_total 311
telemt_upstream_connect_attempt_total 5258
telemt_upstream_connect_success_total 5257
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4288
telemt_me_reconnect_success_total 4267
telemt_me_reader_eof_total 4600
telemt_me_idle_close_by_peer_total 4600
telemt_me_route_drop_no_conn_total 6510
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17219
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4300
telemt_me_writer_restored_same_endpoint_total 4263
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 17174
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 8685458536 (8.09 GB)
telemt_user_octets_to_client{user="hello"} 14543276108 (13.54 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 19602.4 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20860
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 4693
telemt_upstream_connect_success_total 4692
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3726
telemt_me_reconnect_success_total 3713
telemt_me_reader_eof_total 3961
telemt_me_idle_close_by_peer_total 3961
telemt_me_route_drop_no_conn_total 9836
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19864
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3748
telemt_me_writer_restored_same_endpoint_total 3702
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 19787
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 449869144 (429.03 MB)
telemt_user_octets_to_client{user="hello"} 12518163184 (11.66 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 19601.6 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59249
telemt_connections_bad_total 1454
telemt_handshake_timeouts_total 235
telemt_upstream_connect_attempt_total 4419
telemt_upstream_connect_success_total 4395
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 4419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 3423
telemt_me_reconnect_success_total 3409
telemt_me_reader_eof_total 3605
telemt_me_idle_close_by_peer_total 3605
telemt_me_route_drop_no_conn_total 32115
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57365
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3413
telemt_me_writer_restored_same_endpoint_total 3382
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 55924
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 1737335296 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 36822651368 (34.29 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 32
```