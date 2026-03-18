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

# Server Metrics 2026-03-18 19:08:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13392.8 (3h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355124
telemt_connections_bad_total 21779
telemt_handshake_timeouts_total 7932
telemt_upstream_connect_attempt_total 2261
telemt_upstream_connect_success_total 2261
telemt_upstream_connect_attempts_per_request{bucket="1"} 2261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1587
telemt_me_reconnect_success_total 1580
telemt_me_reader_eof_total 1635
telemt_me_idle_close_by_peer_total 1635
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 154452
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305408
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1857
telemt_desync_full_logged_total 527
telemt_desync_suppressed_total 1330
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 580
telemt_desync_frames_bucket_total{bucket="gt_10"} 830
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1610
telemt_me_writer_restored_same_endpoint_total 1564
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 305287
telemt_user_connections_current{user="hello"} 1203
telemt_user_octets_from_client{user="hello"} 5628382136 (5.24 GB)
telemt_user_octets_to_client{user="hello"} 102185552032 (95.17 GB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 18220.7 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1775184
telemt_connections_bad_total 119528
telemt_connections_current 3856
telemt_connections_me_current 3856
telemt_handshake_timeouts_total 31448
telemt_upstream_connect_attempt_total 2969
telemt_upstream_connect_success_total 2955
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2020
telemt_me_reconnect_success_total 2003
telemt_me_reader_eof_total 2004
telemt_me_idle_close_by_peer_total 2003
telemt_me_route_drop_no_conn_total 1685871
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1536552
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5092
telemt_desync_full_logged_total 1626
telemt_desync_suppressed_total 3466
telemt_desync_frames_bucket_total{bucket="1_2"} 890
telemt_desync_frames_bucket_total{bucket="3_10"} 2021
telemt_desync_frames_bucket_total{bucket="gt_10"} 2181
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 1952
telemt_me_writer_restored_same_endpoint_total 2001
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1531715
telemt_user_connections_current{user="hello"} 3856
telemt_user_octets_from_client{user="hello"} 23536156936 (21.92 GB)
telemt_user_octets_to_client{user="hello"} 479217735700 (446.31 GB)
telemt_user_unique_ips_current{user="hello"} 1235
telemt_user_unique_ips_recent_window{user="hello"} 517
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 18149.2 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1344550
telemt_connections_bad_total 115760
telemt_connections_current 3584
telemt_connections_me_current 3584
telemt_handshake_timeouts_total 27863
telemt_upstream_connect_attempt_total 2546
telemt_upstream_connect_success_total 2532
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1596
telemt_me_reconnect_success_total 1581
telemt_me_reader_eof_total 1680
telemt_me_idle_close_by_peer_total 1680
telemt_me_route_drop_no_conn_total 550441
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1069503
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5086
telemt_desync_full_logged_total 1568
telemt_desync_suppressed_total 3518
telemt_desync_frames_bucket_total{bucket="1_2"} 1262
telemt_desync_frames_bucket_total{bucket="3_10"} 1932
telemt_desync_frames_bucket_total{bucket="gt_10"} 1892
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 1627
telemt_me_writer_restored_same_endpoint_total 1564
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1068805
telemt_user_connections_current{user="hello"} 3584
telemt_user_octets_from_client{user="hello"} 23629100136 (22.01 GB)
telemt_user_octets_to_client{user="hello"} 496644720560 (462.54 GB)
telemt_user_unique_ips_current{user="hello"} 1088
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 18863.7 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1981285
telemt_connections_bad_total 46597
telemt_connections_current 2849
telemt_connections_me_current 2849
telemt_handshake_timeouts_total 20321
telemt_upstream_connect_attempt_total 2806
telemt_upstream_connect_success_total 2785
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1845
telemt_me_reconnect_success_total 1823
telemt_me_reader_eof_total 1885
telemt_me_idle_close_by_peer_total 1884
telemt_me_route_drop_no_conn_total 3491541
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1776140
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6539
telemt_desync_full_logged_total 1612
telemt_desync_suppressed_total 4927
telemt_desync_frames_bucket_total{bucket="1_2"} 1457
telemt_desync_frames_bucket_total{bucket="3_10"} 3098
telemt_desync_frames_bucket_total{bucket="gt_10"} 1984
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 1832
telemt_me_writer_restored_same_endpoint_total 1812
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 1776057
telemt_user_connections_current{user="hello"} 2849
telemt_user_octets_from_client{user="hello"} 16025679824 (14.93 GB)
telemt_user_octets_to_client{user="hello"} 277826673200 (258.75 GB)
telemt_user_unique_ips_current{user="hello"} 934
telemt_user_unique_ips_recent_window{user="hello"} 441
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13378.7 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 985538
telemt_connections_bad_total 170589
telemt_handshake_timeouts_total 9126
telemt_upstream_connect_attempt_total 2309
telemt_upstream_connect_success_total 2236
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 2309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 3645
telemt_me_reconnect_success_total 1550
telemt_me_reader_eof_total 1650
telemt_me_idle_close_by_peer_total 1650
telemt_me_route_drop_no_conn_total 423906
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 729140
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2530
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 1652
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 1175
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1639
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1524
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 728564
telemt_user_connections_current{user="hello"} 3372
telemt_user_octets_from_client{user="hello"} 12538957496 (11.68 GB)
telemt_user_octets_to_client{user="hello"} 328525924076 (305.96 GB)
telemt_user_unique_ips_current{user="hello"} 1094
telemt_user_unique_ips_recent_window{user="hello"} 426
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 18311.5 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311492
telemt_connections_bad_total 10459
telemt_connections_current 726
telemt_connections_me_current 726
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3270
telemt_upstream_connect_attempt_total 7235
telemt_upstream_connect_success_total 7212
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 7235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 331903
telemt_me_reconnect_success_total 2434
telemt_me_reader_eof_total 2462
telemt_me_idle_close_by_peer_total 2462
telemt_me_route_drop_no_conn_total 195553
telemt_me_route_drop_channel_closed_total 93
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277566
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 537
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 338
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2386
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2423
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 281254
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 3934988373 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 59497618421 (55.41 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 17382.8 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1047043
telemt_connections_bad_total 76633
telemt_connections_current 3072
telemt_connections_me_current 3072
telemt_handshake_timeouts_total 19966
telemt_upstream_connect_attempt_total 2941
telemt_upstream_connect_success_total 2940
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17546
telemt_me_reconnect_success_total 2027
telemt_me_reader_eof_total 2050
telemt_me_idle_close_by_peer_total 2050
telemt_me_route_drop_no_conn_total 498193
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 876267
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3634
telemt_desync_full_logged_total 1230
telemt_desync_suppressed_total 2404
telemt_desync_frames_bucket_total{bucket="1_2"} 853
telemt_desync_frames_bucket_total{bucket="3_10"} 1266
telemt_desync_frames_bucket_total{bucket="gt_10"} 1515
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2001
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1966
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 875210
telemt_user_connections_current{user="hello"} 3072
telemt_user_octets_from_client{user="hello"} 17314780704 (16.13 GB)
telemt_user_octets_to_client{user="hello"} 487402840560 (453.93 GB)
telemt_user_unique_ips_current{user="hello"} 935
telemt_user_unique_ips_recent_window{user="hello"} 367
```