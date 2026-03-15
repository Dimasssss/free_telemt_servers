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

# Server Metrics 2026-03-15 05:58:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 27818.2 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71264
telemt_connections_bad_total 407
telemt_handshake_timeouts_total 1427
telemt_upstream_connect_attempt_total 6885
telemt_upstream_connect_success_total 6843
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 6885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5483
telemt_me_reconnect_success_total 5464
telemt_me_reader_eof_total 5847
telemt_me_idle_close_by_peer_total 5847
telemt_me_route_drop_no_conn_total 21738
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66816
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 555
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 303
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5505
telemt_me_writer_restored_same_endpoint_total 5433
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 66812
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 851469184 (812.02 MB)
telemt_user_octets_to_client{user="hello"} 24630229528 (22.94 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 27825.4 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25147
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 7558
telemt_upstream_connect_success_total 7558
telemt_upstream_connect_attempts_per_request{bucket="1"} 7558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6193
telemt_me_reconnect_success_total 6167
telemt_me_reader_eof_total 6628
telemt_me_idle_close_by_peer_total 6628
telemt_me_route_drop_no_conn_total 12879
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23910
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6223
telemt_me_writer_restored_same_endpoint_total 6151
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 23913
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 704747960 (672.10 MB)
telemt_user_octets_to_client{user="hello"} 8722354572 (8.12 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 27818.5 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33090
telemt_connections_bad_total 430
telemt_handshake_timeouts_total 1757
telemt_upstream_connect_attempt_total 7401
telemt_upstream_connect_success_total 7400
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6041
telemt_me_reconnect_success_total 6014
telemt_me_reader_eof_total 6497
telemt_me_idle_close_by_peer_total 6497
telemt_me_route_drop_no_conn_total 11377
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29824
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6068
telemt_me_writer_restored_same_endpoint_total 6010
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 29773
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 8759841500 (8.16 GB)
telemt_user_octets_to_client{user="hello"} 17166621488 (15.99 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 27817.9 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33837
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 6566
telemt_upstream_connect_success_total 6565
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5210
telemt_me_reconnect_success_total 5191
telemt_me_reader_eof_total 5554
telemt_me_idle_close_by_peer_total 5554
telemt_me_route_drop_no_conn_total 15499
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31518
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5245
telemt_me_writer_restored_same_endpoint_total 5180
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 31437
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 597903212 (570.20 MB)
telemt_user_octets_to_client{user="hello"} 20720515716 (19.30 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 2889.4 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4069
telemt_connections_bad_total 571
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 1376
telemt_upstream_connect_success_total 1348
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 95393
telemt_me_reconnect_success_total 1005
telemt_me_reader_eof_total 954
telemt_me_idle_close_by_peer_total 954
telemt_me_route_drop_no_conn_total 1023
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3227
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 928
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 901
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 3372
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 20241937 (19.30 MB)
telemt_user_octets_to_client{user="hello"} 1237513763 (1.15 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 27817.2 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89628
telemt_connections_bad_total 1716
telemt_handshake_timeouts_total 398
telemt_upstream_connect_attempt_total 6141
telemt_upstream_connect_success_total 6105
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 6141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 4743
telemt_me_reconnect_success_total 4722
telemt_me_reader_eof_total 5022
telemt_me_idle_close_by_peer_total 5022
telemt_me_route_drop_no_conn_total 48487
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85967
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4741
telemt_me_writer_restored_same_endpoint_total 4695
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 84528
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 2144614312 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 47202603572 (43.96 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 50
```