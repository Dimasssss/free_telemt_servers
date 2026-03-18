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

# Server Metrics 2026-03-18 12:13:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 12765.9 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458919
telemt_connections_bad_total 6177
telemt_handshake_timeouts_total 12696
telemt_upstream_connect_attempt_total 65515
telemt_upstream_connect_success_total 64574
telemt_upstream_connect_fail_total 941
telemt_upstream_connect_attempts_per_request{bucket="1"} 65515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 941
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509728
telemt_me_reconnect_success_total 1926
telemt_me_reader_eof_total 1954
telemt_me_idle_close_by_peer_total 1952
telemt_me_route_drop_no_conn_total 264241
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346510
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1439
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 976
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 495
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1966
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1821
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 404795
telemt_user_connections_current{user="hello"} 1696
telemt_user_octets_from_client{user="hello"} 5610430864 (5.23 GB)
telemt_user_octets_to_client{user="hello"} 107087148849 (99.73 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 541
telemt_user_unique_ips_recent_window{user="hello"} 279
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 12797.4 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1291088
telemt_connections_bad_total 92457
telemt_handshake_timeouts_total 29796
telemt_upstream_connect_attempt_total 2220
telemt_upstream_connect_success_total 2208
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1527
telemt_me_reconnect_success_total 1483
telemt_me_reader_eof_total 1503
telemt_me_idle_close_by_peer_total 1502
telemt_me_route_drop_no_conn_total 1159605
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1112124
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3502
telemt_desync_full_logged_total 1031
telemt_desync_suppressed_total 2471
telemt_desync_frames_bucket_total{bucket="1_2"} 683
telemt_desync_frames_bucket_total{bucket="3_10"} 1420
telemt_desync_frames_bucket_total{bucket="gt_10"} 1399
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1485
telemt_me_writer_restored_same_endpoint_total 1482
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 1111263
telemt_user_connections_current{user="hello"} 4475
telemt_user_octets_from_client{user="hello"} 26806641476 (24.97 GB)
telemt_user_octets_to_client{user="hello"} 320033673520 (298.05 GB)
telemt_user_unique_ips_current{user="hello"} 1261
telemt_user_unique_ips_recent_window{user="hello"} 622
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 12712.1 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 905786
telemt_connections_bad_total 67121
telemt_handshake_timeouts_total 22475
telemt_upstream_connect_attempt_total 10627
telemt_upstream_connect_success_total 10627
telemt_upstream_connect_attempts_per_request{bucket="1"} 10627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607413
telemt_me_reconnect_success_total 1720
telemt_me_reader_eof_total 1737
telemt_me_idle_close_by_peer_total 1736
telemt_me_route_drop_no_conn_total 395207
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680601
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1860
telemt_desync_full_logged_total 661
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 698
telemt_desync_frames_bucket_total{bucket="gt_10"} 682
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1728
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1685
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 688214
telemt_user_connections_current{user="hello"} 3542
telemt_user_octets_from_client{user="hello"} 8296305795 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 285895880468 (266.26 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1016
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 12742.2 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1410380
telemt_connections_bad_total 21028
telemt_handshake_timeouts_total 159355
telemt_upstream_connect_attempt_total 12330
telemt_upstream_connect_success_total 12153
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 12330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2826124
telemt_me_reconnect_success_total 1178
telemt_me_reader_eof_total 1606
telemt_me_idle_close_by_peer_total 1606
telemt_me_route_drop_no_conn_total 2009770
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1107044
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2315
telemt_desync_full_logged_total 755
telemt_desync_suppressed_total 1560
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 924
telemt_desync_frames_bucket_total{bucket="gt_10"} 820
telemt_me_writer_removed_unexpected_total 1650
telemt_me_refill_failed_total 100017
telemt_me_writer_restored_same_endpoint_total 1083
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 1125717
telemt_user_connections_current{user="hello"} 3663
telemt_user_octets_from_client{user="hello"} 8672663606 (8.08 GB)
telemt_user_octets_to_client{user="hello"} 195895181733 (182.44 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 997
telemt_user_unique_ips_recent_window{user="hello"} 571
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 12637.1 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937184
telemt_connections_bad_total 40276
telemt_handshake_timeouts_total 16338
telemt_upstream_connect_attempt_total 11604
telemt_upstream_connect_success_total 11603
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983407
telemt_me_reconnect_success_total 1443
telemt_me_reader_eof_total 1441
telemt_me_idle_close_by_peer_total 1441
telemt_me_route_drop_no_conn_total 575063
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797430
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2755
telemt_desync_full_logged_total 905
telemt_desync_suppressed_total 1850
telemt_desync_frames_bucket_total{bucket="1_2"} 402
telemt_desync_frames_bucket_total{bucket="3_10"} 1080
telemt_desync_frames_bucket_total{bucket="gt_10"} 1273
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1417
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1328
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 797667
telemt_user_connections_current{user="hello"} 3465
telemt_user_octets_from_client{user="hello"} 11608607621 (10.81 GB)
telemt_user_octets_to_client{user="hello"} 307067894289 (285.98 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1095
telemt_user_unique_ips_recent_window{user="hello"} 636
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 12522.6 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264056
telemt_connections_bad_total 24100
telemt_handshake_timeouts_total 2024
telemt_upstream_connect_attempt_total 2495
telemt_upstream_connect_success_total 2495
telemt_upstream_connect_attempts_per_request{bucket="1"} 2495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1298
telemt_me_reconnect_attempts_total 2985
telemt_me_reconnect_success_total 1817
telemt_me_reader_eof_total 1889
telemt_me_idle_close_by_peer_total 1888
telemt_me_route_drop_no_conn_total 130053
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227786
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 588
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1866
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1809
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 218089
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 4113146020 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 49889135436 (46.46 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 12593.2 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 754747
telemt_connections_bad_total 105021
telemt_handshake_timeouts_total 16376
telemt_upstream_connect_attempt_total 2253
telemt_upstream_connect_success_total 2231
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 1583
telemt_me_reconnect_success_total 1557
telemt_me_reader_eof_total 1589
telemt_me_idle_close_by_peer_total 1589
telemt_me_route_drop_no_conn_total 298464
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575660
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2096
telemt_desync_full_logged_total 726
telemt_desync_suppressed_total 1370
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 748
telemt_desync_frames_bucket_total{bucket="gt_10"} 1001
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1562
telemt_me_writer_restored_same_endpoint_total 1547
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 575211
telemt_user_connections_current{user="hello"} 3227
telemt_user_octets_from_client{user="hello"} 11774336504 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 294000762236 (273.81 GB)
telemt_user_unique_ips_current{user="hello"} 958
telemt_user_unique_ips_recent_window{user="hello"} 449
```