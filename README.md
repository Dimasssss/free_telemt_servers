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

# Server Metrics 2026-03-19 02:18:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 16203.0 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195859
telemt_connections_bad_total 23772
telemt_connections_current 707
telemt_connections_me_current 707
telemt_handshake_timeouts_total 10080
telemt_upstream_connect_attempt_total 3218
telemt_upstream_connect_success_total 3165
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 3218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2371
telemt_me_reconnect_success_total 2361
telemt_me_reader_eof_total 2465
telemt_me_idle_close_by_peer_total 2465
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 54300
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153428
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1040
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 766
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2370
telemt_me_writer_restored_same_endpoint_total 2347
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 150654
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 1634583280 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 48896656692 (45.54 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 16206.8 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355068
telemt_connections_bad_total 22954
telemt_connections_current 1531
telemt_connections_me_current 1531
telemt_handshake_timeouts_total 7628
telemt_upstream_connect_attempt_total 3118
telemt_upstream_connect_success_total 3063
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 3118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 2261
telemt_me_reconnect_success_total 2251
telemt_me_reader_eof_total 2366
telemt_me_idle_close_by_peer_total 2366
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 109589
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303763
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1121
telemt_desync_full_logged_total 374
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 437
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2289
telemt_me_writer_restored_same_endpoint_total 2236
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 303801
telemt_user_connections_current{user="hello"} 1531
telemt_user_octets_from_client{user="hello"} 11688941240 (10.89 GB)
telemt_user_octets_to_client{user="hello"} 118737583896 (110.58 GB)
telemt_user_unique_ips_current{user="hello"} 616
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 16203.9 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288882
telemt_connections_bad_total 54901
telemt_connections_current 1214
telemt_connections_me_current 1214
telemt_handshake_timeouts_total 6775
telemt_upstream_connect_attempt_total 3101
telemt_upstream_connect_success_total 3101
telemt_upstream_connect_attempts_per_request{bucket="1"} 3101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2297
telemt_me_reconnect_success_total 2289
telemt_me_reader_eof_total 2416
telemt_me_idle_close_by_peer_total 2416
telemt_me_route_drop_no_conn_total 87452
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218879
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1102
telemt_desync_full_logged_total 404
telemt_desync_suppressed_total 698
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 458
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2324
telemt_me_writer_restored_same_endpoint_total 2273
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 218865
telemt_user_connections_current{user="hello"} 1214
telemt_user_octets_from_client{user="hello"} 2734218992 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 127593490864 (118.83 GB)
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 16257.5 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337070
telemt_connections_bad_total 34001
telemt_connections_current 985
telemt_connections_me_current 985
telemt_handshake_timeouts_total 5287
telemt_upstream_connect_attempt_total 2971
telemt_upstream_connect_success_total 2971
telemt_upstream_connect_attempts_per_request{bucket="1"} 2971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2148
telemt_me_reconnect_success_total 2138
telemt_me_reader_eof_total 2250
telemt_me_idle_close_by_peer_total 2250
telemt_me_route_drop_no_conn_total 99688
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219354
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 577
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 363
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2167
telemt_me_writer_restored_same_endpoint_total 2114
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 219266
telemt_user_connections_current{user="hello"} 985
telemt_user_octets_from_client{user="hello"} 1999539952 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 74988600388 (69.84 GB)
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 16200.7 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310583
telemt_connections_bad_total 17964
telemt_connections_current 1229
telemt_connections_me_current 1229
telemt_handshake_timeouts_total 10172
telemt_upstream_connect_attempt_total 3051
telemt_upstream_connect_success_total 3035
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2235
telemt_me_reconnect_success_total 2222
telemt_me_reader_eof_total 2337
telemt_me_idle_close_by_peer_total 2337
telemt_me_route_drop_no_conn_total 94906
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239503
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 990
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 619
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 362
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2234
telemt_me_writer_restored_same_endpoint_total 2198
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 239427
telemt_user_connections_current{user="hello"} 1229
telemt_user_octets_from_client{user="hello"} 7733707580 (7.20 GB)
telemt_user_octets_to_client{user="hello"} 132332430780 (123.24 GB)
telemt_user_unique_ips_current{user="hello"} 540
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 16212.2 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77361
telemt_connections_bad_total 9330
telemt_connections_current 319
telemt_connections_me_current 319
telemt_handshake_timeouts_total 327
telemt_upstream_connect_attempt_total 4724
telemt_upstream_connect_success_total 4585
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 4724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_reconnect_attempts_total 5613
telemt_me_reconnect_success_total 3780
telemt_me_reader_eof_total 3934
telemt_me_idle_close_by_peer_total 3934
telemt_me_route_drop_no_conn_total 30737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65407
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3832
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3750
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 65406
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 1506111692 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 47702304504 (44.43 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 16203.1 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219232
telemt_connections_bad_total 23515
telemt_connections_current 1118
telemt_connections_me_current 1118
telemt_handshake_timeouts_total 10577
telemt_upstream_connect_attempt_total 3452
telemt_upstream_connect_success_total 3452
telemt_upstream_connect_attempts_per_request{bucket="1"} 3452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2651
telemt_me_reconnect_success_total 2642
telemt_me_reader_eof_total 2775
telemt_me_idle_close_by_peer_total 2775
telemt_me_route_drop_no_conn_total 64663
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179862
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1069
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 654
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 433
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2672
telemt_me_writer_restored_same_endpoint_total 2627
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 179886
telemt_user_connections_current{user="hello"} 1118
telemt_user_octets_from_client{user="hello"} 1864911188 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 92026418884 (85.71 GB)
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 105
```