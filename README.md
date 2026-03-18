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

# Server Metrics 2026-03-18 12:29:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 13682.6 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491723
telemt_connections_bad_total 6689
telemt_handshake_timeouts_total 13816
telemt_upstream_connect_attempt_total 65750
telemt_upstream_connect_success_total 64805
telemt_upstream_connect_fail_total 945
telemt_upstream_connect_attempts_per_request{bucket="1"} 65750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 945
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 510331
telemt_me_reconnect_success_total 2111
telemt_me_reader_eof_total 2153
telemt_me_idle_close_by_peer_total 2151
telemt_me_route_drop_no_conn_total 293133
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375433
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1564
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1051
telemt_desync_frames_bucket_total{bucket="1_2"} 454
telemt_desync_frames_bucket_total{bucket="3_10"} 554
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2165
telemt_me_refill_failed_total 16565
telemt_me_writer_restored_same_endpoint_total 2006
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 433686
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 5991444232 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 113847774457 (106.03 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 543
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 13712.9 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1366226
telemt_connections_bad_total 95292
telemt_handshake_timeouts_total 31227
telemt_upstream_connect_attempt_total 2414
telemt_upstream_connect_success_total 2402
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1673
telemt_me_reconnect_success_total 1624
telemt_me_reader_eof_total 1648
telemt_me_idle_close_by_peer_total 1647
telemt_me_route_drop_no_conn_total 1191554
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1178378
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3728
telemt_desync_full_logged_total 1097
telemt_desync_suppressed_total 2631
telemt_desync_frames_bucket_total{bucket="1_2"} 733
telemt_desync_frames_bucket_total{bucket="3_10"} 1499
telemt_desync_frames_bucket_total{bucket="gt_10"} 1496
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1630
telemt_me_writer_restored_same_endpoint_total 1623
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1177458
telemt_user_connections_current{user="hello"} 4083
telemt_user_octets_from_client{user="hello"} 29525133344 (27.50 GB)
telemt_user_octets_to_client{user="hello"} 343321953052 (319.74 GB)
telemt_user_unique_ips_current{user="hello"} 1251
telemt_user_unique_ips_recent_window{user="hello"} 576
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 13627.8 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 969288
telemt_connections_bad_total 71407
telemt_handshake_timeouts_total 23893
telemt_upstream_connect_attempt_total 10827
telemt_upstream_connect_success_total 10827
telemt_upstream_connect_attempts_per_request{bucket="1"} 10827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607557
telemt_me_reconnect_success_total 1863
telemt_me_reader_eof_total 1890
telemt_me_idle_close_by_peer_total 1889
telemt_me_route_drop_no_conn_total 416027
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 733467
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2107
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 750
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1873
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1828
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 740976
telemt_user_connections_current{user="hello"} 3170
telemt_user_octets_from_client{user="hello"} 8870895883 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 309475711712 (288.22 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 960
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 13658.3 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1538529
telemt_connections_bad_total 23119
telemt_handshake_timeouts_total 162454
telemt_upstream_connect_attempt_total 12372
telemt_upstream_connect_success_total 12190
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 12372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1267
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2827404
telemt_me_reconnect_success_total 1178
telemt_me_reader_eof_total 1645
telemt_me_idle_close_by_peer_total 1645
telemt_me_route_drop_no_conn_total 2216307
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1221710
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
telemt_desync_total 2567
telemt_desync_full_logged_total 830
telemt_desync_suppressed_total 1737
telemt_desync_frames_bucket_total{bucket="1_2"} 630
telemt_desync_frames_bucket_total{bucket="3_10"} 1053
telemt_desync_frames_bucket_total{bucket="gt_10"} 884
telemt_me_writer_removed_unexpected_total 1690
telemt_me_refill_failed_total 100057
telemt_me_writer_restored_same_endpoint_total 1083
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 1240348
telemt_user_connections_current{user="hello"} 3406
telemt_user_octets_from_client{user="hello"} 14490172282 (13.50 GB)
telemt_user_octets_to_client{user="hello"} 205112587513 (191.03 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 583
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 13553.1 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1004430
telemt_connections_bad_total 42183
telemt_handshake_timeouts_total 17741
telemt_upstream_connect_attempt_total 11797
telemt_upstream_connect_success_total 11796
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983544
telemt_me_reconnect_success_total 1580
telemt_me_reader_eof_total 1578
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 619813
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 855594
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2905
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 1938
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 1143
telemt_desync_frames_bucket_total{bucket="gt_10"} 1347
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1555
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1465
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 855820
telemt_user_connections_current{user="hello"} 3347
telemt_user_octets_from_client{user="hello"} 12921586097 (12.03 GB)
telemt_user_octets_to_client{user="hello"} 328300167713 (305.75 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1059
telemt_user_unique_ips_recent_window{user="hello"} 472
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 13438.4 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283581
telemt_connections_bad_total 25896
telemt_handshake_timeouts_total 2214
telemt_upstream_connect_attempt_total 2646
telemt_upstream_connect_success_total 2646
telemt_upstream_connect_attempts_per_request{bucket="1"} 2646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1402
telemt_me_reconnect_attempts_total 4370
telemt_me_reconnect_success_total 1922
telemt_me_reader_eof_total 2036
telemt_me_idle_close_by_peer_total 2035
telemt_me_route_drop_no_conn_total 143346
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244231
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 624
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 404
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2014
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1914
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 234526
telemt_user_connections_current{user="hello"} 1015
telemt_user_octets_from_client{user="hello"} 4214477504 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 52337883912 (48.74 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 13509.1 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 813592
telemt_connections_bad_total 110074
telemt_handshake_timeouts_total 17686
telemt_upstream_connect_attempt_total 2393
telemt_upstream_connect_success_total 2369
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1678
telemt_me_reconnect_success_total 1651
telemt_me_reader_eof_total 1689
telemt_me_idle_close_by_peer_total 1689
telemt_me_route_drop_no_conn_total 316711
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 621295
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2270
telemt_desync_full_logged_total 774
telemt_desync_suppressed_total 1496
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 794
telemt_desync_frames_bucket_total{bucket="gt_10"} 1092
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1659
telemt_me_writer_restored_same_endpoint_total 1641
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 620810
telemt_user_connections_current{user="hello"} 2931
telemt_user_octets_from_client{user="hello"} 13948939988 (12.99 GB)
telemt_user_octets_to_client{user="hello"} 317952236464 (296.12 GB)
telemt_user_unique_ips_current{user="hello"} 892
telemt_user_unique_ips_recent_window{user="hello"} 419
```