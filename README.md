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

# Server Metrics 2026-03-16 21:56:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 11479.7 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74814
telemt_connections_bad_total 704
telemt_handshake_timeouts_total 3319
telemt_upstream_connect_attempt_total 2122
telemt_upstream_connect_success_total 2107
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 1522
telemt_me_reconnect_success_total 1515
telemt_me_reader_eof_total 1579
telemt_me_idle_close_by_peer_total 1579
telemt_me_route_drop_no_conn_total 25572
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67418
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 346
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1519
telemt_me_writer_restored_same_endpoint_total 1494
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 67372
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 1250477800 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 44204142396 (41.17 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 11730.9 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57033
telemt_connections_bad_total 505
telemt_handshake_timeouts_total 2707
telemt_upstream_connect_attempt_total 2525
telemt_upstream_connect_success_total 2496
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 1912
telemt_me_reconnect_success_total 1907
telemt_me_reader_eof_total 1988
telemt_me_idle_close_by_peer_total 1988
telemt_me_route_drop_no_conn_total 22128
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51552
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1932
telemt_me_writer_restored_same_endpoint_total 1891
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 51534
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 767615284 (732.05 MB)
telemt_user_octets_to_client{user="hello"} 21930014412 (20.42 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 11507.2 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29711
telemt_connections_bad_total 371
telemt_handshake_timeouts_total 206
telemt_upstream_connect_attempt_total 2846
telemt_upstream_connect_success_total 2828
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2249
telemt_me_reconnect_success_total 2229
telemt_me_reader_eof_total 2347
telemt_me_idle_close_by_peer_total 2347
telemt_me_route_drop_no_conn_total 9946
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28383
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2252
telemt_me_writer_restored_same_endpoint_total 2218
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 28379
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 594213292 (566.69 MB)
telemt_user_octets_to_client{user="hello"} 10209634432 (9.51 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 11566.5 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57522
telemt_connections_bad_total 2961
telemt_handshake_timeouts_total 375
telemt_upstream_connect_attempt_total 2411
telemt_upstream_connect_success_total 2381
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 2411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 1801
telemt_me_reconnect_success_total 1781
telemt_me_reader_eof_total 1855
telemt_me_idle_close_by_peer_total 1855
telemt_me_route_drop_no_conn_total 18511
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52647
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 139
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1806
telemt_me_writer_restored_same_endpoint_total 1774
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 52634
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 731812976 (697.91 MB)
telemt_user_octets_to_client{user="hello"} 22876519108 (21.31 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 11538.4 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40258
telemt_connections_bad_total 12619
telemt_handshake_timeouts_total 192
telemt_upstream_connect_attempt_total 2961
telemt_upstream_connect_success_total 2908
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 2961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 3426
telemt_me_reconnect_success_total 2318
telemt_me_reader_eof_total 2391
telemt_me_idle_close_by_peer_total 2391
telemt_me_route_drop_no_conn_total 10579
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26239
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2414
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2310
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 26235
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 223271532 (212.93 MB)
telemt_user_octets_to_client{user="hello"} 7555412092 (7.04 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 11699.5 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83483
telemt_connections_bad_total 1045
telemt_handshake_timeouts_total 737
telemt_upstream_connect_attempt_total 2212
telemt_upstream_connect_success_total 2198
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1615
telemt_me_reconnect_success_total 1612
telemt_me_reader_eof_total 1698
telemt_me_idle_close_by_peer_total 1698
telemt_me_route_drop_no_conn_total 44252
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81202
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1634
telemt_me_writer_restored_same_endpoint_total 1602
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 78969
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 1625103228 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 42888607936 (39.94 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 46
```