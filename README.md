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

# Server Metrics 2026-03-19 02:13:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 15896.1 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191749
telemt_connections_bad_total 23303
telemt_connections_current 665
telemt_connections_me_current 665
telemt_handshake_timeouts_total 9899
telemt_upstream_connect_attempt_total 3189
telemt_upstream_connect_success_total 3136
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 3189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2342
telemt_me_reconnect_success_total 2333
telemt_me_reader_eof_total 2437
telemt_me_idle_close_by_peer_total 2437
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 53276
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150205
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 994
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 733
telemt_desync_frames_bucket_total{bucket="1_2"} 372
telemt_desync_frames_bucket_total{bucket="3_10"} 422
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2342
telemt_me_writer_restored_same_endpoint_total 2319
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 147432
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 1612519068 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 48073062528 (44.77 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 15899.9 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348947
telemt_connections_bad_total 22788
telemt_connections_current 1564
telemt_connections_me_current 1564
telemt_handshake_timeouts_total 7091
telemt_upstream_connect_attempt_total 3086
telemt_upstream_connect_success_total 3031
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 3086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 2229
telemt_me_reconnect_success_total 2219
telemt_me_reader_eof_total 2334
telemt_me_idle_close_by_peer_total 2334
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 108076
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298719
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1100
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 729
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 423
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2257
telemt_me_writer_restored_same_endpoint_total 2204
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 298763
telemt_user_connections_current{user="hello"} 1564
telemt_user_octets_from_client{user="hello"} 11644660892 (10.84 GB)
telemt_user_octets_to_client{user="hello"} 116213140200 (108.23 GB)
telemt_user_unique_ips_current{user="hello"} 640
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 15896.9 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283847
telemt_connections_bad_total 53869
telemt_connections_current 1197
telemt_connections_me_current 1197
telemt_handshake_timeouts_total 6669
telemt_upstream_connect_attempt_total 3071
telemt_upstream_connect_success_total 3071
telemt_upstream_connect_attempts_per_request{bucket="1"} 3071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1520
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2267
telemt_me_reconnect_success_total 2259
telemt_me_reader_eof_total 2384
telemt_me_idle_close_by_peer_total 2384
telemt_me_route_drop_no_conn_total 85984
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215083
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1047
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 670
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 422
telemt_desync_frames_bucket_total{bucket="gt_10"} 442
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2292
telemt_me_writer_restored_same_endpoint_total 2243
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 215071
telemt_user_connections_current{user="hello"} 1197
telemt_user_octets_from_client{user="hello"} 2604740520 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 125269223944 (116.67 GB)
telemt_user_unique_ips_current{user="hello"} 506
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 15950.4 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327465
telemt_connections_bad_total 33226
telemt_connections_current 952
telemt_connections_me_current 952
telemt_handshake_timeouts_total 5226
telemt_upstream_connect_attempt_total 2929
telemt_upstream_connect_success_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 2929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2128
telemt_me_reconnect_success_total 2119
telemt_me_reader_eof_total 2228
telemt_me_idle_close_by_peer_total 2228
telemt_me_route_drop_no_conn_total 98549
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215537
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 575
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2145
telemt_me_writer_restored_same_endpoint_total 2095
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 215450
telemt_user_connections_current{user="hello"} 952
telemt_user_octets_from_client{user="hello"} 1975930548 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 73970011240 (68.89 GB)
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 15893.7 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305611
telemt_connections_bad_total 17766
telemt_connections_current 1275
telemt_connections_me_current 1275
telemt_handshake_timeouts_total 9985
telemt_upstream_connect_attempt_total 3018
telemt_upstream_connect_success_total 3002
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2202
telemt_me_reconnect_success_total 2189
telemt_me_reader_eof_total 2304
telemt_me_idle_close_by_peer_total 2304
telemt_me_route_drop_no_conn_total 93625
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235489
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 965
telemt_desync_full_logged_total 364
telemt_desync_suppressed_total 601
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2201
telemt_me_writer_restored_same_endpoint_total 2165
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 235413
telemt_user_connections_current{user="hello"} 1275
telemt_user_octets_from_client{user="hello"} 7204732592 (6.71 GB)
telemt_user_octets_to_client{user="hello"} 129701183788 (120.79 GB)
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 15905.1 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76117
telemt_connections_bad_total 9281
telemt_connections_current 354
telemt_connections_me_current 354
telemt_handshake_timeouts_total 319
telemt_upstream_connect_attempt_total 4630
telemt_upstream_connect_success_total 4491
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 4630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_reconnect_attempts_total 5519
telemt_me_reconnect_success_total 3686
telemt_me_reader_eof_total 3838
telemt_me_idle_close_by_peer_total 3838
telemt_me_route_drop_no_conn_total 30279
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64294
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
telemt_me_writer_removed_unexpected_total 3736
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3656
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 64293
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 1353549776 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 46344499748 (43.16 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 15896.1 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215454
telemt_connections_bad_total 23319
telemt_connections_current 1129
telemt_connections_me_current 1129
telemt_handshake_timeouts_total 10261
telemt_upstream_connect_attempt_total 3421
telemt_upstream_connect_success_total 3421
telemt_upstream_connect_attempts_per_request{bucket="1"} 3421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2620
telemt_me_reconnect_success_total 2611
telemt_me_reader_eof_total 2744
telemt_me_idle_close_by_peer_total 2744
telemt_me_route_drop_no_conn_total 63704
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176696
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1062
telemt_desync_full_logged_total 412
telemt_desync_suppressed_total 650
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 438
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2641
telemt_me_writer_restored_same_endpoint_total 2596
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 176720
telemt_user_connections_current{user="hello"} 1129
telemt_user_octets_from_client{user="hello"} 1824215972 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 89907147044 (83.73 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 101
```