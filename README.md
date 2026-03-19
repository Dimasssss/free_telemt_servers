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

# Server Metrics 2026-03-19 01:06:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 11909.1 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135602
telemt_connections_bad_total 16554
telemt_connections_current 682
telemt_connections_me_current 682
telemt_handshake_timeouts_total 1361
telemt_upstream_connect_attempt_total 2437
telemt_upstream_connect_success_total 2394
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 2437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1772
telemt_me_reconnect_success_total 1767
telemt_me_reader_eof_total 1835
telemt_me_idle_close_by_peer_total 1835
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 41460
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111763
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 637
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 461
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1771
telemt_me_writer_restored_same_endpoint_total 1754
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 108996
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 1041639544 (993.38 MB)
telemt_user_octets_to_client{user="hello"} 38485951340 (35.84 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 11912.8 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274530
telemt_connections_bad_total 19783
telemt_connections_current 1465
telemt_connections_me_current 1465
telemt_handshake_timeouts_total 3723
telemt_upstream_connect_attempt_total 2276
telemt_upstream_connect_success_total 2227
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 1599
telemt_me_reconnect_success_total 1594
telemt_me_reader_eof_total 1677
telemt_me_idle_close_by_peer_total 1677
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 82099
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235124
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 880
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 586
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 313
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1620
telemt_me_writer_restored_same_endpoint_total 1581
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 235164
telemt_user_connections_current{user="hello"} 1465
telemt_user_octets_from_client{user="hello"} 10926809664 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 89275489188 (83.14 GB)
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 11910.1 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218866
telemt_connections_bad_total 37364
telemt_connections_current 1003
telemt_connections_me_current 1003
telemt_handshake_timeouts_total 5623
telemt_upstream_connect_attempt_total 2340
telemt_upstream_connect_success_total 2340
telemt_upstream_connect_attempts_per_request{bucket="1"} 2340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1711
telemt_me_reconnect_success_total 1706
telemt_me_reader_eof_total 1792
telemt_me_idle_close_by_peer_total 1792
telemt_me_route_drop_no_conn_total 70403
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169183
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 799
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 502
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 313
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1730
telemt_me_writer_restored_same_endpoint_total 1690
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 169183
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 2154509168 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 101073178048 (94.13 GB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 11963.4 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236393
telemt_connections_bad_total 27440
telemt_connections_current 940
telemt_connections_me_current 940
telemt_handshake_timeouts_total 4299
telemt_upstream_connect_attempt_total 2215
telemt_upstream_connect_success_total 2215
telemt_upstream_connect_attempts_per_request{bucket="1"} 2215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1587
telemt_me_reconnect_success_total 1581
telemt_me_reader_eof_total 1654
telemt_me_idle_close_by_peer_total 1654
telemt_me_route_drop_no_conn_total 76513
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172068
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 475
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 304
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1599
telemt_me_writer_restored_same_endpoint_total 1557
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 171986
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 1702043372 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 59208708552 (55.14 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 11906.7 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240516
telemt_connections_bad_total 13965
telemt_connections_current 1131
telemt_connections_me_current 1131
telemt_handshake_timeouts_total 7974
telemt_upstream_connect_attempt_total 2251
telemt_upstream_connect_success_total 2238
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1610
telemt_me_reconnect_success_total 1600
telemt_me_reader_eof_total 1674
telemt_me_idle_close_by_peer_total 1674
telemt_me_route_drop_no_conn_total 75310
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183700
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 713
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 434
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1606
telemt_me_writer_restored_same_endpoint_total 1576
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 183626
telemt_user_connections_current{user="hello"} 1131
telemt_user_octets_from_client{user="hello"} 2318367788 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 108339124988 (100.90 GB)
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 11918.2 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60089
telemt_connections_bad_total 9062
telemt_connections_current 329
telemt_connections_me_current 329
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 3504
telemt_upstream_connect_success_total 3394
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 3504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1783
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 4595
telemt_me_reconnect_success_total 2768
telemt_me_reader_eof_total 2891
telemt_me_idle_close_by_peer_total 2891
telemt_me_route_drop_no_conn_total 22531
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49334
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
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2815
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2738
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 49334
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 699507368 (667.10 MB)
telemt_user_octets_to_client{user="hello"} 31714954448 (29.54 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 11909.0 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170657
telemt_connections_bad_total 20207
telemt_connections_current 1028
telemt_connections_me_current 1028
telemt_handshake_timeouts_total 7353
telemt_upstream_connect_attempt_total 2536
telemt_upstream_connect_success_total 2536
telemt_upstream_connect_attempts_per_request{bucket="1"} 2536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 1908
telemt_me_reconnect_success_total 1902
telemt_me_reader_eof_total 1996
telemt_me_idle_close_by_peer_total 1996
telemt_me_route_drop_no_conn_total 51050
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139517
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 942
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 566
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 376
telemt_desync_frames_bucket_total{bucket="gt_10"} 394
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1924
telemt_me_writer_restored_same_endpoint_total 1887
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 139540
telemt_user_connections_current{user="hello"} 1028
telemt_user_octets_from_client{user="hello"} 1408179592 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 72555948296 (67.57 GB)
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 79
```