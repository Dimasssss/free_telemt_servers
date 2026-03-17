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

# Server Metrics 2026-03-17 03:05:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 30030.9 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157093
telemt_connections_bad_total 2378
telemt_handshake_timeouts_total 5476
telemt_upstream_connect_attempt_total 6471
telemt_upstream_connect_success_total 6432
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4936
telemt_me_reconnect_success_total 4920
telemt_me_reader_eof_total 5234
telemt_me_idle_close_by_peer_total 5234
telemt_me_route_drop_no_conn_total 49273
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142353
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 825
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 419
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4962
telemt_me_writer_restored_same_endpoint_total 4899
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 142287
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 1913111140 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 63427502392 (59.07 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 30282.1 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87943
telemt_connections_bad_total 1359
telemt_handshake_timeouts_total 3007
telemt_upstream_connect_attempt_total 8334
telemt_upstream_connect_success_total 8224
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 8334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 7885
telemt_me_reconnect_success_total 6718
telemt_me_reader_eof_total 7105
telemt_me_idle_close_by_peer_total 7105
telemt_me_route_drop_no_conn_total 37366
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79975
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 186
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6821
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6702
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 79919
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 1154741012 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 37324807064 (34.76 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 30058.4 (8h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57201
telemt_connections_bad_total 785
telemt_handshake_timeouts_total 1946
telemt_upstream_connect_attempt_total 8108
telemt_upstream_connect_success_total 8062
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 6572
telemt_me_reconnect_success_total 6534
telemt_me_reader_eof_total 6990
telemt_me_idle_close_by_peer_total 6990
telemt_me_route_drop_no_conn_total 18124
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48267
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6618
telemt_me_writer_restored_same_endpoint_total 6523
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 48251
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 5570686284 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 17724661380 (16.51 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 30117.6 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89585
telemt_connections_bad_total 3377
telemt_handshake_timeouts_total 1291
telemt_upstream_connect_attempt_total 7017
telemt_upstream_connect_success_total 6955
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 7017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 5468
telemt_me_reconnect_success_total 5431
telemt_me_reader_eof_total 5771
telemt_me_idle_close_by_peer_total 5771
telemt_me_route_drop_no_conn_total 30871
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82401
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 153
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5506
telemt_me_writer_restored_same_endpoint_total 5424
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 82386
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 942434948 (898.78 MB)
telemt_user_octets_to_client{user="hello"} 38224025248 (35.60 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 30089.6 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68083
telemt_connections_bad_total 16072
telemt_handshake_timeouts_total 1064
telemt_upstream_connect_attempt_total 8882
telemt_upstream_connect_success_total 8768
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 8882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_reconnect_attempts_total 9497
telemt_me_reconnect_success_total 7247
telemt_me_reader_eof_total 7650
telemt_me_idle_close_by_peer_total 7650
telemt_me_route_drop_no_conn_total 19568
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49002
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
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
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 7428
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 7239
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 48996
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 569461932 (543.08 MB)
telemt_user_octets_to_client{user="hello"} 16718774464 (15.57 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 30250.6 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171394
telemt_connections_bad_total 13106
telemt_handshake_timeouts_total 1102
telemt_upstream_connect_attempt_total 6293
telemt_upstream_connect_success_total 6258
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 6293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3294
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 4767
telemt_me_reconnect_success_total 4751
telemt_me_reader_eof_total 5093
telemt_me_idle_close_by_peer_total 5093
telemt_me_route_drop_no_conn_total 179885
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229357
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4818
telemt_me_writer_restored_same_endpoint_total 4741
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 151610
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 2409955052 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 121401728116 (113.06 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 18257.0 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 9212
telemt_upstream_connect_success_total 9212
telemt_upstream_connect_attempts_per_request{bucket="1"} 9212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 8277
telemt_me_reconnect_success_total 8232
telemt_me_reader_eof_total 9044
telemt_me_idle_close_by_peer_total 9044
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 8315
telemt_me_writer_restored_same_endpoint_total 8232
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```