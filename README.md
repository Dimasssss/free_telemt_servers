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

# Server Metrics 2026-03-18 12:03:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 12154.7 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433548
telemt_connections_bad_total 5732
telemt_handshake_timeouts_total 11887
telemt_upstream_connect_attempt_total 65375
telemt_upstream_connect_success_total 64439
telemt_upstream_connect_fail_total 936
telemt_upstream_connect_attempts_per_request{bucket="1"} 65375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 936
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509638
telemt_me_reconnect_success_total 1836
telemt_me_reader_eof_total 1862
telemt_me_idle_close_by_peer_total 1860
telemt_me_route_drop_no_conn_total 231843
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323363
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1321
telemt_desync_full_logged_total 429
telemt_desync_suppressed_total 892
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 463
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1874
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1731
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 381662
telemt_user_connections_current{user="hello"} 1707
telemt_user_octets_from_client{user="hello"} 5231042432 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 101321512041 (94.36 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 12186.7 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1237772
telemt_connections_bad_total 90724
telemt_handshake_timeouts_total 28609
telemt_upstream_connect_attempt_total 2107
telemt_upstream_connect_success_total 2095
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1459
telemt_me_reconnect_success_total 1416
telemt_me_reader_eof_total 1433
telemt_me_idle_close_by_peer_total 1432
telemt_me_route_drop_no_conn_total 1137596
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1064230
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3379
telemt_desync_full_logged_total 977
telemt_desync_suppressed_total 2402
telemt_desync_frames_bucket_total{bucket="1_2"} 663
telemt_desync_frames_bucket_total{bucket="3_10"} 1372
telemt_desync_frames_bucket_total{bucket="gt_10"} 1344
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1415
telemt_me_writer_restored_same_endpoint_total 1415
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 1063509
telemt_user_connections_current{user="hello"} 4229
telemt_user_octets_from_client{user="hello"} 25756555668 (23.99 GB)
telemt_user_octets_to_client{user="hello"} 301648930940 (280.93 GB)
telemt_user_unique_ips_current{user="hello"} 1214
telemt_user_unique_ips_recent_window{user="hello"} 632
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 12101.6 (3h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857301
telemt_connections_bad_total 62173
telemt_handshake_timeouts_total 21197
telemt_upstream_connect_attempt_total 10561
telemt_upstream_connect_success_total 10561
telemt_upstream_connect_attempts_per_request{bucket="1"} 10561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607380
telemt_me_reconnect_success_total 1688
telemt_me_reader_eof_total 1704
telemt_me_idle_close_by_peer_total 1703
telemt_me_route_drop_no_conn_total 376146
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 640969
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1658
telemt_desync_full_logged_total 583
telemt_desync_suppressed_total 1075
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 632
telemt_desync_frames_bucket_total{bucket="gt_10"} 606
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1694
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 648602
telemt_user_connections_current{user="hello"} 3451
telemt_user_octets_from_client{user="hello"} 7768449311 (7.23 GB)
telemt_user_octets_to_client{user="hello"} 266075311092 (247.80 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1056
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 12131.7 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1357890
telemt_connections_bad_total 19723
telemt_handshake_timeouts_total 156934
telemt_upstream_connect_attempt_total 12282
telemt_upstream_connect_success_total 12110
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 12282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2825708
telemt_me_reconnect_success_total 1178
telemt_me_reader_eof_total 1593
telemt_me_idle_close_by_peer_total 1593
telemt_me_route_drop_no_conn_total 1966603
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062988
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
telemt_desync_total 2180
telemt_desync_full_logged_total 707
telemt_desync_suppressed_total 1473
telemt_desync_frames_bucket_total{bucket="1_2"} 541
telemt_desync_frames_bucket_total{bucket="3_10"} 857
telemt_desync_frames_bucket_total{bucket="gt_10"} 782
telemt_me_writer_removed_unexpected_total 1637
telemt_me_refill_failed_total 100004
telemt_me_writer_restored_same_endpoint_total 1083
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 459
telemt_user_connections_total{user="hello"} 1081693
telemt_user_connections_current{user="hello"} 3452
telemt_user_octets_from_client{user="hello"} 7739273162 (7.21 GB)
telemt_user_octets_to_client{user="hello"} 185718767613 (172.96 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 950
telemt_user_unique_ips_recent_window{user="hello"} 512
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 12026.7 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 884539
telemt_connections_bad_total 37851
telemt_handshake_timeouts_total 15289
telemt_upstream_connect_attempt_total 11570
telemt_upstream_connect_success_total 11569
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983378
telemt_me_reconnect_success_total 1415
telemt_me_reader_eof_total 1411
telemt_me_idle_close_by_peer_total 1411
telemt_me_route_drop_no_conn_total 543499
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 753493
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2607
telemt_desync_full_logged_total 849
telemt_desync_suppressed_total 1758
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 1024
telemt_desync_frames_bucket_total{bucket="gt_10"} 1199
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1387
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1300
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 753745
telemt_user_connections_current{user="hello"} 3580
telemt_user_octets_from_client{user="hello"} 10584361701 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 290688006229 (270.72 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1056
telemt_user_unique_ips_recent_window{user="hello"} 598
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 11911.7 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250680
telemt_connections_bad_total 23162
telemt_handshake_timeouts_total 1952
telemt_upstream_connect_attempt_total 2393
telemt_upstream_connect_success_total 2393
telemt_upstream_connect_attempts_per_request{bucket="1"} 2393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1213
telemt_me_reconnect_attempts_total 2371
telemt_me_reconnect_success_total 1715
telemt_me_reader_eof_total 1770
telemt_me_idle_close_by_peer_total 1769
telemt_me_route_drop_no_conn_total 120900
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216023
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 554
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 364
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1747
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1707
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 206327
telemt_user_connections_current{user="hello"} 1032
telemt_user_octets_from_client{user="hello"} 4008301720 (3.73 GB)
telemt_user_octets_to_client{user="hello"} 47687271448 (44.41 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 11982.8 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691760
telemt_connections_bad_total 83485
telemt_handshake_timeouts_total 15501
telemt_upstream_connect_attempt_total 2214
telemt_upstream_connect_success_total 2192
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 1544
telemt_me_reconnect_success_total 1519
telemt_me_reader_eof_total 1549
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 286953
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541520
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2004
telemt_desync_full_logged_total 699
telemt_desync_suppressed_total 1305
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 954
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1522
telemt_me_writer_restored_same_endpoint_total 1509
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 541091
telemt_user_connections_current{user="hello"} 3266
telemt_user_octets_from_client{user="hello"} 11339297708 (10.56 GB)
telemt_user_octets_to_client{user="hello"} 276106977728 (257.14 GB)
telemt_user_unique_ips_current{user="hello"} 947
telemt_user_unique_ips_recent_window{user="hello"} 482
```