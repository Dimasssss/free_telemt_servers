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

# Server Metrics 2026-03-17 04:17:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 34303.9 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180394
telemt_connections_bad_total 2510
telemt_handshake_timeouts_total 6709
telemt_upstream_connect_attempt_total 7362
telemt_upstream_connect_success_total 7320
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 7362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3989
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5605
telemt_me_reconnect_success_total 5588
telemt_me_reader_eof_total 5942
telemt_me_idle_close_by_peer_total 5942
telemt_me_route_drop_no_conn_total 57197
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163382
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1047
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 680
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5640
telemt_me_writer_restored_same_endpoint_total 5567
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 163186
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 2366169628 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 75348188828 (70.17 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 34555.2 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100251
telemt_connections_bad_total 2005
telemt_handshake_timeouts_total 3491
telemt_upstream_connect_attempt_total 9752
telemt_upstream_connect_success_total 9628
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 9752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_reconnect_attempts_total 9074
telemt_me_reconnect_success_total 7905
telemt_me_reader_eof_total 8361
telemt_me_idle_close_by_peer_total 8361
telemt_me_route_drop_no_conn_total 41766
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90660
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8015
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7889
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 90647
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1251190868 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 41299225972 (38.46 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 34331.8 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65307
telemt_connections_bad_total 817
telemt_handshake_timeouts_total 2378
telemt_upstream_connect_attempt_total 9185
telemt_upstream_connect_success_total 9135
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 7430
telemt_me_reconnect_success_total 7388
telemt_me_reader_eof_total 7916
telemt_me_idle_close_by_peer_total 7916
telemt_me_route_drop_no_conn_total 21573
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55473
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
telemt_me_writer_removed_unexpected_total 7480
telemt_me_writer_restored_same_endpoint_total 7377
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 55456
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 5730696060 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 18738708500 (17.45 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 34390.6 (9h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103624
telemt_connections_bad_total 3416
telemt_handshake_timeouts_total 2205
telemt_upstream_connect_attempt_total 7939
telemt_upstream_connect_success_total 7872
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 7939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 6171
telemt_me_reconnect_success_total 6125
telemt_me_reader_eof_total 6522
telemt_me_idle_close_by_peer_total 6522
telemt_me_route_drop_no_conn_total 35296
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94956
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6214
telemt_me_writer_restored_same_endpoint_total 6118
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 94935
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 1059196372 (1010.13 MB)
telemt_user_octets_to_client{user="hello"} 45266442408 (42.16 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 34362.7 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75898
telemt_connections_bad_total 16933
telemt_handshake_timeouts_total 1391
telemt_upstream_connect_attempt_total 10112
telemt_upstream_connect_success_total 9984
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 10112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_reconnect_attempts_total 10496
telemt_me_reconnect_success_total 8244
telemt_me_reader_eof_total 8704
telemt_me_idle_close_by_peer_total 8704
telemt_me_route_drop_no_conn_total 22024
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55444
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
telemt_me_writer_removed_unexpected_total 8432
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 8236
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 55440
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 631103260 (601.87 MB)
telemt_user_octets_to_client{user="hello"} 22697326872 (21.14 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 34523.5 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201787
telemt_connections_bad_total 25395
telemt_handshake_timeouts_total 1211
telemt_upstream_connect_attempt_total 7239
telemt_upstream_connect_success_total 7199
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 7239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5492
telemt_me_reconnect_success_total 5470
telemt_me_reader_eof_total 5865
telemt_me_idle_close_by_peer_total 5865
telemt_me_route_drop_no_conn_total 188510
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246988
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 170
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5545
telemt_me_writer_restored_same_endpoint_total 5460
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 169242
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 2612154772 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 135138793540 (125.86 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 22530.2 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 11328
telemt_upstream_connect_success_total 11328
telemt_upstream_connect_attempts_per_request{bucket="1"} 11328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 10211
telemt_me_reconnect_success_total 10154
telemt_me_reader_eof_total 11142
telemt_me_idle_close_by_peer_total 11142
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 10254
telemt_me_writer_restored_same_endpoint_total 10154
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```