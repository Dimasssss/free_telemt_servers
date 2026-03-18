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

# Server Metrics 2026-03-18 11:33:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 10324.3 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368244
telemt_connections_bad_total 4556
telemt_handshake_timeouts_total 9271
telemt_upstream_connect_attempt_total 65047
telemt_upstream_connect_success_total 64112
telemt_upstream_connect_fail_total 935
telemt_upstream_connect_attempts_per_request{bucket="1"} 65047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 935
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509398
telemt_me_reconnect_success_total 1598
telemt_me_reader_eof_total 1612
telemt_me_idle_close_by_peer_total 1610
telemt_me_route_drop_no_conn_total 198823
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265190
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1104
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 748
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 391
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1633
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1493
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 323589
telemt_user_connections_current{user="hello"} 1840
telemt_user_octets_from_client{user="hello"} 4177361856 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 85393419977 (79.53 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 544
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 10355.1 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1097155
telemt_connections_bad_total 86102
telemt_handshake_timeouts_total 25025
telemt_upstream_connect_attempt_total 1847
telemt_upstream_connect_success_total 1835
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1286
telemt_me_reconnect_success_total 1243
telemt_me_reader_eof_total 1247
telemt_me_idle_close_by_peer_total 1246
telemt_me_route_drop_no_conn_total 1076378
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 938318
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2990
telemt_desync_full_logged_total 854
telemt_desync_suppressed_total 2136
telemt_desync_frames_bucket_total{bucket="1_2"} 608
telemt_desync_frames_bucket_total{bucket="3_10"} 1196
telemt_desync_frames_bucket_total{bucket="gt_10"} 1186
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1239
telemt_me_writer_restored_same_endpoint_total 1242
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 937629
telemt_user_connections_current{user="hello"} 4089
telemt_user_octets_from_client{user="hello"} 23854414172 (22.22 GB)
telemt_user_octets_to_client{user="hello"} 250324782868 (233.13 GB)
telemt_user_unique_ips_current{user="hello"} 1210
telemt_user_unique_ips_recent_window{user="hello"} 542
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 10270.2 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 720130
telemt_connections_bad_total 51075
telemt_handshake_timeouts_total 18131
telemt_upstream_connect_attempt_total 10322
telemt_upstream_connect_success_total 10322
telemt_upstream_connect_attempts_per_request{bucket="1"} 10322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 607227
telemt_me_reconnect_success_total 1538
telemt_me_reader_eof_total 1542
telemt_me_idle_close_by_peer_total 1541
telemt_me_route_drop_no_conn_total 339395
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541180
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1332
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 864
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1539
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1503
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 548917
telemt_user_connections_current{user="hello"} 2805
telemt_user_octets_from_client{user="hello"} 6549274147 (6.10 GB)
telemt_user_octets_to_client{user="hello"} 219790399452 (204.70 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 901
telemt_user_unique_ips_recent_window{user="hello"} 411
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 10300.2 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1227290
telemt_connections_bad_total 15458
telemt_handshake_timeouts_total 149656
telemt_upstream_connect_attempt_total 12138
telemt_upstream_connect_success_total 11986
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 12138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2822918
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 1469
telemt_me_idle_close_by_peer_total 1469
telemt_me_route_drop_no_conn_total 1894431
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 954827
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1824
telemt_desync_full_logged_total 579
telemt_desync_suppressed_total 1245
telemt_desync_frames_bucket_total{bucket="1_2"} 452
telemt_desync_frames_bucket_total{bucket="3_10"} 735
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_me_writer_removed_unexpected_total 1513
telemt_me_refill_failed_total 99918
telemt_me_writer_restored_same_endpoint_total 1045
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 973613
telemt_user_connections_current{user="hello"} 3263
telemt_user_octets_from_client{user="hello"} 6859855526 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 152656664861 (142.17 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 927
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 10195.1 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 751634
telemt_connections_bad_total 28758
telemt_handshake_timeouts_total 11416
telemt_upstream_connect_attempt_total 11333
telemt_upstream_connect_success_total 11332
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983227
telemt_me_reconnect_success_total 1268
telemt_me_reader_eof_total 1251
telemt_me_idle_close_by_peer_total 1251
telemt_me_route_drop_no_conn_total 500029
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 643271
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2189
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1470
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 855
telemt_desync_frames_bucket_total{bucket="gt_10"} 995
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1234
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1153
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 643656
telemt_user_connections_current{user="hello"} 3219
telemt_user_octets_from_client{user="hello"} 9244306005 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 247570385897 (230.57 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1018
telemt_user_unique_ips_recent_window{user="hello"} 478
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 10080.0 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216468
telemt_connections_bad_total 22208
telemt_handshake_timeouts_total 1702
telemt_upstream_connect_attempt_total 1924
telemt_upstream_connect_success_total 1924
telemt_upstream_connect_attempts_per_request{bucket="1"} 1924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 917
telemt_me_reconnect_attempts_total 1355
telemt_me_reconnect_success_total 1341
telemt_me_reader_eof_total 1372
telemt_me_idle_close_by_peer_total 1371
telemt_me_route_drop_no_conn_total 106755
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184789
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 446
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1348
telemt_me_writer_restored_same_endpoint_total 1333
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 175113
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 2728217796 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 41059658016 (38.24 GB)
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 10151.2 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537904
telemt_connections_bad_total 26835
telemt_handshake_timeouts_total 12810
telemt_upstream_connect_attempt_total 1863
telemt_upstream_connect_success_total 1842
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 1863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 1282
telemt_me_reconnect_success_total 1262
telemt_me_reader_eof_total 1276
telemt_me_idle_close_by_peer_total 1276
telemt_me_route_drop_no_conn_total 248515
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 454433
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1691
telemt_desync_full_logged_total 588
telemt_desync_suppressed_total 1103
telemt_desync_frames_bucket_total{bucket="1_2"} 297
telemt_desync_frames_bucket_total{bucket="3_10"} 609
telemt_desync_frames_bucket_total{bucket="gt_10"} 785
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1263
telemt_me_writer_restored_same_endpoint_total 1252
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 454069
telemt_user_connections_current{user="hello"} 2854
telemt_user_octets_from_client{user="hello"} 8898311052 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 231602254072 (215.70 GB)
telemt_user_unique_ips_current{user="hello"} 846
telemt_user_unique_ips_recent_window{user="hello"} 360
```