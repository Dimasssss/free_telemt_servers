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

# Server Metrics 2026-03-16 23:01:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 15377.8 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93682
telemt_connections_bad_total 1475
telemt_handshake_timeouts_total 4410
telemt_upstream_connect_attempt_total 2962
telemt_upstream_connect_success_total 2941
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2167
telemt_me_reconnect_success_total 2158
telemt_me_reader_eof_total 2268
telemt_me_idle_close_by_peer_total 2268
telemt_me_route_drop_no_conn_total 30664
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83654
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 498
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2171
telemt_me_writer_restored_same_endpoint_total 2137
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 83611
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 1462705768 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 49057444788 (45.69 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 15628.2 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64906
telemt_connections_bad_total 833
telemt_handshake_timeouts_total 2754
telemt_upstream_connect_attempt_total 3598
telemt_upstream_connect_success_total 3552
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 3598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 2753
telemt_me_reconnect_success_total 2747
telemt_me_reader_eof_total 2888
telemt_me_idle_close_by_peer_total 2888
telemt_me_route_drop_no_conn_total 25902
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58566
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2782
telemt_me_writer_restored_same_endpoint_total 2731
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 58516
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 844975068 (805.83 MB)
telemt_user_octets_to_client{user="hello"} 26636366120 (24.81 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 15404.4 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34720
telemt_connections_bad_total 421
telemt_handshake_timeouts_total 464
telemt_upstream_connect_attempt_total 3909
telemt_upstream_connect_success_total 3884
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 3090
telemt_me_reconnect_success_total 3067
telemt_me_reader_eof_total 3254
telemt_me_idle_close_by_peer_total 3254
telemt_me_route_drop_no_conn_total 12044
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32968
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3097
telemt_me_writer_restored_same_endpoint_total 3056
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 32964
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 628414516 (599.30 MB)
telemt_user_octets_to_client{user="hello"} 13448195496 (12.52 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 15463.9 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65080
telemt_connections_bad_total 2991
telemt_handshake_timeouts_total 445
telemt_upstream_connect_attempt_total 3374
telemt_upstream_connect_success_total 3334
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 3374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 2539
telemt_me_reconnect_success_total 2516
telemt_me_reader_eof_total 2650
telemt_me_idle_close_by_peer_total 2650
telemt_me_route_drop_no_conn_total 20985
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59803
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2547
telemt_me_writer_restored_same_endpoint_total 2509
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 59789
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 778962204 (742.88 MB)
telemt_user_octets_to_client{user="hello"} 26350316144 (24.54 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 15436.8 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46383
telemt_connections_bad_total 13324
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 4226
telemt_upstream_connect_success_total 4160
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 4463
telemt_me_reconnect_success_total 3352
telemt_me_reader_eof_total 3488
telemt_me_idle_close_by_peer_total 3488
telemt_me_route_drop_no_conn_total 12306
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31435
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3455
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 3344
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 31431
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 257596836 (245.66 MB)
telemt_user_octets_to_client{user="hello"} 12051987864 (11.22 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 15596.9 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103502
telemt_connections_bad_total 1167
telemt_handshake_timeouts_total 868
telemt_upstream_connect_attempt_total 3061
telemt_upstream_connect_success_total 3042
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 2244
telemt_me_reconnect_success_total 2240
telemt_me_reader_eof_total 2379
telemt_me_idle_close_by_peer_total 2379
telemt_me_route_drop_no_conn_total 91432
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131246
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 93
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2273
telemt_me_writer_restored_same_endpoint_total 2230
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 97891
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 1856591968 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 63066419180 (58.74 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 3603.2 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90
telemt_connections_bad_total 54
telemt_upstream_connect_attempt_total 1461
telemt_upstream_connect_success_total 1460
telemt_upstream_connect_attempts_per_request{bucket="1"} 1460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1264
telemt_me_reconnect_success_total 1258
telemt_me_reader_eof_total 1344
telemt_me_idle_close_by_peer_total 1344
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1266
telemt_me_writer_restored_same_endpoint_total 1258
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```