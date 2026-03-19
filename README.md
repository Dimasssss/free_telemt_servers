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

# Server Metrics 2026-03-19 00:36:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 10069.5 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115469
telemt_connections_bad_total 13269
telemt_connections_current 635
telemt_connections_me_current 635
telemt_handshake_timeouts_total 1151
telemt_upstream_connect_attempt_total 1991
telemt_upstream_connect_success_total 1954
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 1991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1418
telemt_me_reconnect_success_total 1413
telemt_me_reader_eof_total 1457
telemt_me_idle_close_by_peer_total 1457
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 36074
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95998
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 568
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1414
telemt_me_writer_restored_same_endpoint_total 1401
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 93230
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 878701060 (837.99 MB)
telemt_user_octets_to_client{user="hello"} 35385293792 (32.96 GB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 10072.8 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243703
telemt_connections_bad_total 19166
telemt_connections_current 1601
telemt_connections_me_current 1601
telemt_handshake_timeouts_total 2601
telemt_upstream_connect_attempt_total 1899
telemt_upstream_connect_success_total 1858
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 1316
telemt_me_reconnect_success_total 1314
telemt_me_reader_eof_total 1376
telemt_me_idle_close_by_peer_total 1376
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 74274
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208142
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 531
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1336
telemt_me_writer_restored_same_endpoint_total 1301
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 208186
telemt_user_connections_current{user="hello"} 1601
telemt_user_octets_from_client{user="hello"} 10670466832 (9.94 GB)
telemt_user_octets_to_client{user="hello"} 78495222200 (73.10 GB)
telemt_user_unique_ips_current{user="hello"} 608
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 10069.9 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191555
telemt_connections_bad_total 30664
telemt_connections_current 1080
telemt_connections_me_current 1080
telemt_handshake_timeouts_total 5394
telemt_upstream_connect_attempt_total 1982
telemt_upstream_connect_success_total 1982
telemt_upstream_connect_attempts_per_request{bucket="1"} 1982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1440
telemt_me_reconnect_success_total 1436
telemt_me_reader_eof_total 1501
telemt_me_idle_close_by_peer_total 1501
telemt_me_route_drop_no_conn_total 63058
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149641
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 678
telemt_desync_full_logged_total 255
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 269
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1454
telemt_me_writer_restored_same_endpoint_total 1420
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 149644
telemt_user_connections_current{user="hello"} 1080
telemt_user_octets_from_client{user="hello"} 1952057208 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 86780581360 (80.82 GB)
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 10123.5 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198217
telemt_connections_bad_total 26356
telemt_connections_current 845
telemt_connections_me_current 845
telemt_handshake_timeouts_total 3547
telemt_upstream_connect_attempt_total 1887
telemt_upstream_connect_success_total 1887
telemt_upstream_connect_attempts_per_request{bucket="1"} 1887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1346
telemt_me_reconnect_success_total 1340
telemt_me_reader_eof_total 1398
telemt_me_idle_close_by_peer_total 1398
telemt_me_route_drop_no_conn_total 71754
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153713
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 407
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1356
telemt_me_writer_restored_same_endpoint_total 1316
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 153634
telemt_user_connections_current{user="hello"} 845
telemt_user_octets_from_client{user="hello"} 1601757636 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 54299178320 (50.57 GB)
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 10066.8 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208668
telemt_connections_bad_total 10013
telemt_connections_current 1108
telemt_connections_me_current 1108
telemt_handshake_timeouts_total 7022
telemt_upstream_connect_attempt_total 1896
telemt_upstream_connect_success_total 1884
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1342
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 1393
telemt_me_idle_close_by_peer_total 1393
telemt_me_route_drop_no_conn_total 67041
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161601
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 635
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 383
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1340
telemt_me_writer_restored_same_endpoint_total 1310
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 161531
telemt_user_connections_current{user="hello"} 1108
telemt_user_octets_from_client{user="hello"} 2098358808 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 99624136688 (92.78 GB)
telemt_user_unique_ips_current{user="hello"} 497
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 10078.3 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52580
telemt_connections_bad_total 9020
telemt_connections_current 375
telemt_connections_me_current 375
telemt_handshake_timeouts_total 159
telemt_upstream_connect_attempt_total 3024
telemt_upstream_connect_success_total 2927
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 3024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1492
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_reconnect_attempts_total 4214
telemt_me_reconnect_success_total 2387
telemt_me_reader_eof_total 2483
telemt_me_idle_close_by_peer_total 2483
telemt_me_route_drop_no_conn_total 19348
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42159
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
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2427
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2357
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 42159
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 504883092 (481.49 MB)
telemt_user_octets_to_client{user="hello"} 27384114844 (25.50 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 10069.0 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151628
telemt_connections_bad_total 18616
telemt_connections_current 959
telemt_connections_me_current 959
telemt_handshake_timeouts_total 5875
telemt_upstream_connect_attempt_total 2102
telemt_upstream_connect_success_total 2102
telemt_upstream_connect_attempts_per_request{bucket="1"} 2102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1560
telemt_me_reconnect_success_total 1555
telemt_me_reader_eof_total 1626
telemt_me_idle_close_by_peer_total 1626
telemt_me_route_drop_no_conn_total 45493
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124237
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 862
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 521
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 366
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1573
telemt_me_writer_restored_same_endpoint_total 1540
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 124260
telemt_user_connections_current{user="hello"} 959
telemt_user_octets_from_client{user="hello"} 1228505480 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 66672305612 (62.09 GB)
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 74
```