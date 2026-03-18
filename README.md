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

# Server Metrics 2026-03-18 18:07:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9702.9 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273490
telemt_connections_bad_total 17301
telemt_handshake_timeouts_total 6739
telemt_upstream_connect_attempt_total 1597
telemt_upstream_connect_success_total 1597
telemt_upstream_connect_attempts_per_request{bucket="1"} 1597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1096
telemt_me_reconnect_success_total 1092
telemt_me_reader_eof_total 1121
telemt_me_idle_close_by_peer_total 1121
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 124190
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232993
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1229
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 848
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 397
telemt_desync_frames_bucket_total{bucket="gt_10"} 553
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1115
telemt_me_writer_restored_same_endpoint_total 1077
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 232892
telemt_user_connections_current{user="hello"} 1350
telemt_user_octets_from_client{user="hello"} 3313641876 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 79350401616 (73.90 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 14531.4 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1457399
telemt_connections_bad_total 96657
telemt_connections_current 3644
telemt_connections_me_current 3644
telemt_handshake_timeouts_total 27635
telemt_upstream_connect_attempt_total 2489
telemt_upstream_connect_success_total 2476
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1713
telemt_me_reconnect_success_total 1698
telemt_me_reader_eof_total 1672
telemt_me_idle_close_by_peer_total 1671
telemt_me_route_drop_no_conn_total 1485453
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1261574
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3897
telemt_desync_full_logged_total 1232
telemt_desync_suppressed_total 2665
telemt_desync_frames_bucket_total{bucket="1_2"} 688
telemt_desync_frames_bucket_total{bucket="3_10"} 1539
telemt_desync_frames_bucket_total{bucket="gt_10"} 1670
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1639
telemt_me_writer_restored_same_endpoint_total 1696
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1256871
telemt_user_connections_current{user="hello"} 3644
telemt_user_octets_from_client{user="hello"} 16404383308 (15.28 GB)
telemt_user_octets_to_client{user="hello"} 374353462096 (348.64 GB)
telemt_user_unique_ips_current{user="hello"} 1133
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 14458.7 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1031226
telemt_connections_bad_total 83998
telemt_connections_current 3389
telemt_connections_me_current 3389
telemt_handshake_timeouts_total 22496
telemt_upstream_connect_attempt_total 2024
telemt_upstream_connect_success_total 2012
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1270
telemt_me_reconnect_success_total 1255
telemt_me_reader_eof_total 1329
telemt_me_idle_close_by_peer_total 1329
telemt_me_route_drop_no_conn_total 456002
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 849980
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3727
telemt_desync_full_logged_total 1137
telemt_desync_suppressed_total 2590
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 1386
telemt_desync_frames_bucket_total{bucket="gt_10"} 1398
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1293
telemt_me_writer_restored_same_endpoint_total 1238
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 849608
telemt_user_connections_current{user="hello"} 3389
telemt_user_octets_from_client{user="hello"} 20078143012 (18.70 GB)
telemt_user_octets_to_client{user="hello"} 371851227144 (346.31 GB)
telemt_user_unique_ips_current{user="hello"} 1076
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 15173.7 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1535355
telemt_connections_bad_total 35108
telemt_connections_current 3053
telemt_connections_me_current 3053
telemt_handshake_timeouts_total 16813
telemt_upstream_connect_attempt_total 2305
telemt_upstream_connect_success_total 2289
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1521
telemt_me_reconnect_success_total 1501
telemt_me_reader_eof_total 1540
telemt_me_idle_close_by_peer_total 1539
telemt_me_route_drop_no_conn_total 2589982
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1374183
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5296
telemt_desync_full_logged_total 1306
telemt_desync_suppressed_total 3990
telemt_desync_frames_bucket_total{bucket="1_2"} 1186
telemt_desync_frames_bucket_total{bucket="3_10"} 2501
telemt_desync_frames_bucket_total{bucket="gt_10"} 1609
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1504
telemt_me_writer_restored_same_endpoint_total 1490
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 1374109
telemt_user_connections_current{user="hello"} 3053
telemt_user_octets_from_client{user="hello"} 13181800400 (12.28 GB)
telemt_user_octets_to_client{user="hello"} 225080116300 (209.62 GB)
telemt_user_unique_ips_current{user="hello"} 921
telemt_user_unique_ips_recent_window{user="hello"} 441
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9688.6 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 734148
telemt_connections_bad_total 134278
telemt_handshake_timeouts_total 7183
telemt_upstream_connect_attempt_total 1720
telemt_upstream_connect_success_total 1666
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 1720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 3247
telemt_me_reconnect_success_total 1157
telemt_me_reader_eof_total 1237
telemt_me_idle_close_by_peer_total 1237
telemt_me_route_drop_no_conn_total 309378
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 535773
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1933
telemt_desync_full_logged_total 661
telemt_desync_suppressed_total 1272
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 920
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1238
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1131
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 535277
telemt_user_connections_current{user="hello"} 3538
telemt_user_octets_from_client{user="hello"} 8449315920 (7.87 GB)
telemt_user_octets_to_client{user="hello"} 225992784192 (210.47 GB)
telemt_user_unique_ips_current{user="hello"} 1097
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 14623.2 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265743
telemt_connections_bad_total 10057
telemt_connections_current 774
telemt_connections_me_current 774
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2833
telemt_upstream_connect_attempt_total 6627
telemt_upstream_connect_success_total 6611
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 331474
telemt_me_reconnect_success_total 2008
telemt_me_reader_eof_total 2003
telemt_me_idle_close_by_peer_total 2003
telemt_me_route_drop_no_conn_total 174493
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235468
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 453
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 12
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 1952
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1997
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 239183
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 3465126681 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 48699972473 (45.36 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 13693.0 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820272
telemt_connections_bad_total 55992
telemt_connections_current 2853
telemt_connections_me_current 2853
telemt_handshake_timeouts_total 14805
telemt_upstream_connect_attempt_total 2390
telemt_upstream_connect_success_total 2389
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17167
telemt_me_reconnect_success_total 1652
telemt_me_reader_eof_total 1648
telemt_me_idle_close_by_peer_total 1648
telemt_me_route_drop_no_conn_total 431879
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 691322
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2764
telemt_desync_full_logged_total 951
telemt_desync_suppressed_total 1813
telemt_desync_frames_bucket_total{bucket="1_2"} 662
telemt_desync_frames_bucket_total{bucket="3_10"} 990
telemt_desync_frames_bucket_total{bucket="gt_10"} 1112
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1617
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1591
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 690340
telemt_user_connections_current{user="hello"} 2853
telemt_user_octets_from_client{user="hello"} 13362403532 (12.44 GB)
telemt_user_octets_to_client{user="hello"} 350881158748 (326.78 GB)
telemt_user_unique_ips_current{user="hello"} 884
telemt_user_unique_ips_recent_window{user="hello"} 427
```