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

# Server Metrics 2026-03-18 22:38:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 3010.8 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36001
telemt_connections_bad_total 3150
telemt_connections_current 792
telemt_connections_me_current 792
telemt_handshake_timeouts_total 387
telemt_upstream_connect_attempt_total 553
telemt_upstream_connect_success_total 545
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 354
telemt_me_reconnect_success_total 353
telemt_me_reader_eof_total 337
telemt_me_idle_close_by_peer_total 337
telemt_me_route_drop_no_conn_total 14493
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33176
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 343
telemt_me_writer_restored_same_endpoint_total 343
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 30423
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 368745344 (351.66 MB)
telemt_user_octets_to_client{user="hello"} 15041286744 (14.01 GB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 3014.6 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90802
telemt_connections_bad_total 2415
telemt_connections_current 1829
telemt_connections_me_current 1829
telemt_handshake_timeouts_total 714
telemt_upstream_connect_attempt_total 502
telemt_upstream_connect_success_total 491
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 294
telemt_me_reconnect_success_total 293
telemt_me_reader_eof_total 291
telemt_me_idle_close_by_peer_total 291
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 33010
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82799
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 273
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 302
telemt_me_writer_restored_same_endpoint_total 283
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 82800
telemt_user_connections_current{user="hello"} 1829
telemt_user_octets_from_client{user="hello"} 4171826316 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 34031234440 (31.69 GB)
telemt_user_unique_ips_current{user="hello"} 680
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 3011.6 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77148
telemt_connections_bad_total 10580
telemt_connections_current 1402
telemt_connections_me_current 1402
telemt_handshake_timeouts_total 2026
telemt_upstream_connect_attempt_total 601
telemt_upstream_connect_success_total 601
telemt_upstream_connect_attempts_per_request{bucket="1"} 601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 267
telemt_me_reconnect_attempts_total 404
telemt_me_reconnect_success_total 404
telemt_me_reader_eof_total 395
telemt_me_idle_close_by_peer_total 395
telemt_me_route_drop_no_conn_total 27162
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62420
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 235
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 404
telemt_me_writer_restored_same_endpoint_total 388
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_user_connections_total{user="hello"} 62425
telemt_user_connections_current{user="hello"} 1402
telemt_user_octets_from_client{user="hello"} 797979316 (761.01 MB)
telemt_user_octets_to_client{user="hello"} 40880675188 (38.07 GB)
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 3064.9 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83184
telemt_connections_bad_total 9463
telemt_connections_current 1213
telemt_connections_me_current 1213
telemt_handshake_timeouts_total 1456
telemt_upstream_connect_attempt_total 573
telemt_upstream_connect_success_total 573
telemt_upstream_connect_attempts_per_request{bucket="1"} 573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 380
telemt_me_reconnect_success_total 378
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 41421
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68278
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 383
telemt_me_writer_restored_same_endpoint_total 354
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 68209
telemt_user_connections_current{user="hello"} 1213
telemt_user_octets_from_client{user="hello"} 786923328 (750.47 MB)
telemt_user_octets_to_client{user="hello"} 23313021524 (21.71 GB)
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 3008.5 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79942
telemt_connections_bad_total 3511
telemt_connections_current 1399
telemt_connections_me_current 1399
telemt_handshake_timeouts_total 2307
telemt_upstream_connect_attempt_total 557
telemt_upstream_connect_success_total 551
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 353
telemt_me_reconnect_success_total 351
telemt_me_reader_eof_total 339
telemt_me_idle_close_by_peer_total 339
telemt_me_route_drop_no_conn_total 23228
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63379
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 286
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 347
telemt_me_writer_restored_same_endpoint_total 327
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 63343
telemt_user_connections_current{user="hello"} 1399
telemt_user_octets_from_client{user="hello"} 750768744 (715.99 MB)
telemt_user_octets_to_client{user="hello"} 39137844884 (36.45 GB)
telemt_user_unique_ips_current{user="hello"} 594
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 3019.9 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18839
telemt_connections_bad_total 4589
telemt_connections_current 420
telemt_connections_me_current 420
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 893
telemt_upstream_connect_success_total 862
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 322
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 1471
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 659
telemt_me_idle_close_by_peer_total 659
telemt_me_route_drop_no_conn_total 5625
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13749
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 662
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 639
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 13749
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 210929856 (201.16 MB)
telemt_user_octets_to_client{user="hello"} 7902526208 (7.36 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 3010.7 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64096
telemt_connections_bad_total 10357
telemt_connections_current 1343
telemt_connections_me_current 1343
telemt_handshake_timeouts_total 1746
telemt_upstream_connect_attempt_total 550
telemt_upstream_connect_success_total 549
telemt_upstream_connect_attempts_per_request{bucket="1"} 549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 244
telemt_me_reconnect_attempts_total 352
telemt_me_reconnect_success_total 351
telemt_me_reader_eof_total 348
telemt_me_idle_close_by_peer_total 348
telemt_me_route_drop_no_conn_total 17502
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50438
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 440
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 355
telemt_me_writer_restored_same_endpoint_total 336
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 50443
telemt_user_connections_current{user="hello"} 1343
telemt_user_octets_from_client{user="hello"} 619000104 (590.32 MB)
telemt_user_octets_to_client{user="hello"} 32533920212 (30.30 GB)
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 138
```