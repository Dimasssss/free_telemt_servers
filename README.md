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

# Server Metrics 2026-03-17 04:22:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 34610.4 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182456
telemt_connections_bad_total 2510
telemt_handshake_timeouts_total 6892
telemt_upstream_connect_attempt_total 7426
telemt_upstream_connect_success_total 7384
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 7426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5669
telemt_me_reconnect_success_total 5651
telemt_me_reader_eof_total 6012
telemt_me_idle_close_by_peer_total 6012
telemt_me_route_drop_no_conn_total 57845
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165165
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1055
telemt_desync_full_logged_total 373
telemt_desync_suppressed_total 682
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 536
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5705
telemt_me_writer_restored_same_endpoint_total 5630
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 164969
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 2377486016 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 75682270664 (70.48 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 34861.4 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101310
telemt_connections_bad_total 2019
telemt_handshake_timeouts_total 3497
telemt_upstream_connect_attempt_total 9802
telemt_upstream_connect_success_total 9678
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 9802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_reconnect_attempts_total 9124
telemt_me_reconnect_success_total 7955
telemt_me_reader_eof_total 8411
telemt_me_idle_close_by_peer_total 8411
telemt_me_route_drop_no_conn_total 42066
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91668
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 246
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8065
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7939
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 91655
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1263704828 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 41905911144 (39.03 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 34637.7 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65986
telemt_connections_bad_total 817
telemt_handshake_timeouts_total 2385
telemt_upstream_connect_attempt_total 9257
telemt_upstream_connect_success_total 9207
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5072
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 7502
telemt_me_reconnect_success_total 7460
telemt_me_reader_eof_total 7993
telemt_me_idle_close_by_peer_total 7993
telemt_me_route_drop_no_conn_total 21799
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56076
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7552
telemt_me_writer_restored_same_endpoint_total 7449
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 56059
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 5733836168 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 18801142340 (17.51 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 34696.9 (9h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105037
telemt_connections_bad_total 3416
telemt_handshake_timeouts_total 2285
telemt_upstream_connect_attempt_total 7986
telemt_upstream_connect_success_total 7918
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 7986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_reconnect_attempts_total 6218
telemt_me_reconnect_success_total 6170
telemt_me_reader_eof_total 6568
telemt_me_idle_close_by_peer_total 6568
telemt_me_route_drop_no_conn_total 35725
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96241
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 164
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6260
telemt_me_writer_restored_same_endpoint_total 6163
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 96220
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 1066866736 (1017.44 MB)
telemt_user_octets_to_client{user="hello"} 45724408316 (42.58 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 34668.8 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76595
telemt_connections_bad_total 16989
telemt_handshake_timeouts_total 1396
telemt_upstream_connect_attempt_total 10257
telemt_upstream_connect_success_total 10129
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 10257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_reconnect_attempts_total 10641
telemt_me_reconnect_success_total 8390
telemt_me_reader_eof_total 8849
telemt_me_idle_close_by_peer_total 8849
telemt_me_route_drop_no_conn_total 22285
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56059
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 8577
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 8382
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 56055
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 641222528 (611.52 MB)
telemt_user_octets_to_client{user="hello"} 22830307420 (21.26 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 34829.9 (9h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204217
telemt_connections_bad_total 26262
telemt_handshake_timeouts_total 1214
telemt_upstream_connect_attempt_total 7285
telemt_upstream_connect_success_total 7245
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 7285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3796
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5538
telemt_me_reconnect_success_total 5515
telemt_me_reader_eof_total 5912
telemt_me_idle_close_by_peer_total 5912
telemt_me_route_drop_no_conn_total 189250
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248513
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 171
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5592
telemt_me_writer_restored_same_endpoint_total 5505
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 170767
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 2622867900 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 135904978168 (126.57 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 22836.3 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 11508
telemt_upstream_connect_success_total 11508
telemt_upstream_connect_attempts_per_request{bucket="1"} 11508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 10356
telemt_me_reconnect_success_total 10299
telemt_me_reader_eof_total 11324
telemt_me_idle_close_by_peer_total 11324
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 10399
telemt_me_writer_restored_same_endpoint_total 10299
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```