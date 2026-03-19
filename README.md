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

# Server Metrics 2026-03-19 01:52:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 14668.7 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172175
telemt_connections_bad_total 20730
telemt_connections_current 672
telemt_connections_me_current 672
telemt_handshake_timeouts_total 6215
telemt_upstream_connect_attempt_total 2975
telemt_upstream_connect_success_total 2926
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2175
telemt_me_reconnect_success_total 2167
telemt_me_reader_eof_total 2261
telemt_me_idle_close_by_peer_total 2261
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 49356
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137721
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 900
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 664
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2173
telemt_me_writer_restored_same_endpoint_total 2153
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 134952
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 1422289684 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 44573776724 (41.51 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 14672.5 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324701
telemt_connections_bad_total 21289
telemt_connections_current 1432
telemt_connections_me_current 1432
telemt_handshake_timeouts_total 6067
telemt_upstream_connect_attempt_total 2894
telemt_upstream_connect_success_total 2839
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 2894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 2080
telemt_me_reconnect_success_total 2071
telemt_me_reader_eof_total 2181
telemt_me_idle_close_by_peer_total 2181
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 101359
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278528
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1019
telemt_desync_full_logged_total 342
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2107
telemt_me_writer_restored_same_endpoint_total 2058
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 278573
telemt_user_connections_current{user="hello"} 1432
telemt_user_octets_from_client{user="hello"} 11354607472 (10.57 GB)
telemt_user_octets_to_client{user="hello"} 106533470800 (99.22 GB)
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 14669.7 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261911
telemt_connections_bad_total 48909
telemt_connections_current 1068
telemt_connections_me_current 1068
telemt_handshake_timeouts_total 6387
telemt_upstream_connect_attempt_total 2858
telemt_upstream_connect_success_total 2858
telemt_upstream_connect_attempts_per_request{bucket="1"} 2858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2098
telemt_me_reconnect_success_total 2091
telemt_me_reader_eof_total 2206
telemt_me_idle_close_by_peer_total 2206
telemt_me_route_drop_no_conn_total 80297
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199098
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 971
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 415
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2121
telemt_me_writer_restored_same_endpoint_total 2075
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 199089
telemt_user_connections_current{user="hello"} 1068
telemt_user_octets_from_client{user="hello"} 2412033296 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 118362877620 (110.23 GB)
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 14722.9 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294755
telemt_connections_bad_total 28069
telemt_connections_current 934
telemt_connections_me_current 934
telemt_handshake_timeouts_total 5018
telemt_upstream_connect_attempt_total 2727
telemt_upstream_connect_success_total 2727
telemt_upstream_connect_attempts_per_request{bucket="1"} 2727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1970
telemt_me_reconnect_success_total 1962
telemt_me_reader_eof_total 2061
telemt_me_idle_close_by_peer_total 2061
telemt_me_route_drop_no_conn_total 94226
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200921
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 559
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 354
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 1985
telemt_me_writer_restored_same_endpoint_total 1938
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 200837
telemt_user_connections_current{user="hello"} 934
telemt_user_octets_from_client{user="hello"} 1866671224 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 67150068832 (62.54 GB)
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 14666.3 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283898
telemt_connections_bad_total 16933
telemt_connections_current 1276
telemt_connections_me_current 1276
telemt_handshake_timeouts_total 9427
telemt_upstream_connect_attempt_total 2791
telemt_upstream_connect_success_total 2775
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2018
telemt_me_reconnect_success_total 2007
telemt_me_reader_eof_total 2111
telemt_me_idle_close_by_peer_total 2111
telemt_me_route_drop_no_conn_total 87565
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217406
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 865
telemt_desync_full_logged_total 330
telemt_desync_suppressed_total 535
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2018
telemt_me_writer_restored_same_endpoint_total 1983
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 217329
telemt_user_connections_current{user="hello"} 1276
telemt_user_octets_from_client{user="hello"} 6686316748 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 120704947072 (112.42 GB)
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 14677.7 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71156
telemt_connections_bad_total 9267
telemt_connections_current 291
telemt_connections_me_current 291
telemt_handshake_timeouts_total 257
telemt_upstream_connect_attempt_total 4200
telemt_upstream_connect_success_total 4071
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 4200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_reconnect_attempts_total 5142
telemt_me_reconnect_success_total 3310
telemt_me_reader_eof_total 3461
telemt_me_idle_close_by_peer_total 3461
telemt_me_route_drop_no_conn_total 27982
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59656
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
telemt_me_writer_removed_unexpected_total 3359
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3280
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 59656
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 849717664 (810.35 MB)
telemt_user_octets_to_client{user="hello"} 40973578948 (38.16 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 14668.7 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200729
telemt_connections_bad_total 22439
telemt_connections_current 1112
telemt_connections_me_current 1112
telemt_handshake_timeouts_total 9403
telemt_upstream_connect_attempt_total 3173
telemt_upstream_connect_success_total 3173
telemt_upstream_connect_attempts_per_request{bucket="1"} 3173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2415
telemt_me_reconnect_success_total 2407
telemt_me_reader_eof_total 2532
telemt_me_idle_close_by_peer_total 2532
telemt_me_route_drop_no_conn_total 59610
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164020
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1022
telemt_desync_full_logged_total 399
telemt_desync_suppressed_total 623
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 413
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2435
telemt_me_writer_restored_same_endpoint_total 2392
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 164045
telemt_user_connections_current{user="hello"} 1112
telemt_user_octets_from_client{user="hello"} 1672641084 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 85137579832 (79.29 GB)
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 84
```