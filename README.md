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

# Server Metrics 2026-03-18 06:52:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 130056.9 (36h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1675275
telemt_connections_bad_total 11571
telemt_handshake_timeouts_total 36912
telemt_upstream_connect_attempt_total 28190
telemt_upstream_connect_success_total 27667
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 28190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 36061
telemt_me_reconnect_success_total 18904
telemt_me_reader_eof_total 20487
telemt_me_idle_close_by_peer_total 20486
telemt_me_route_drop_no_conn_total 640074
telemt_me_route_drop_channel_closed_total 181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1402230
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8467
telemt_desync_full_logged_total 2558
telemt_desync_suppressed_total 5909
telemt_desync_frames_bucket_total{bucket="1_2"} 2199
telemt_desync_frames_bucket_total{bucket="3_10"} 3269
telemt_desync_frames_bucket_total{bucket="gt_10"} 2999
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19725
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18882
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 821
telemt_user_connections_total{user="hello"} 1396474
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 32778456243 (30.53 GB)
telemt_user_octets_to_client{user="hello"} 500295280579 (465.94 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 130308.2 (36h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1773671
telemt_connections_bad_total 90460
telemt_handshake_timeouts_total 56978
telemt_upstream_connect_attempt_total 471738
telemt_upstream_connect_success_total 470098
telemt_upstream_connect_fail_total 1640
telemt_upstream_connect_attempts_per_request{bucket="1"} 471738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1640
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 127439
telemt_me_reconnect_success_total 20704
telemt_me_reader_eof_total 23020
telemt_me_idle_close_by_peer_total 23007
telemt_me_route_drop_no_conn_total 477920
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1100204
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5039
telemt_desync_full_logged_total 1757
telemt_desync_suppressed_total 3282
telemt_desync_frames_bucket_total{bucket="1_2"} 955
telemt_desync_frames_bucket_total{bucket="3_10"} 2046
telemt_desync_frames_bucket_total{bucket="gt_10"} 2038
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22341
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20686
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1637
telemt_user_connections_total{user="hello"} 1542509
telemt_user_connections_current{user="hello"} 2177
telemt_user_octets_from_client{user="hello"} 23712272649 (22.08 GB)
telemt_user_octets_to_client{user="hello"} 605845494710 (564.24 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 720
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 130084.3 (36h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1267978
telemt_connections_bad_total 81690
telemt_handshake_timeouts_total 31845
telemt_upstream_connect_attempt_total 29411
telemt_upstream_connect_success_total 29246
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 29411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15680
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 43438
telemt_me_reconnect_success_total 22727
telemt_me_reader_eof_total 24692
telemt_me_idle_close_by_peer_total 24684
telemt_me_route_drop_no_conn_total 424014
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 947650
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3258
telemt_desync_full_logged_total 1057
telemt_desync_suppressed_total 2201
telemt_desync_frames_bucket_total{bucket="1_2"} 858
telemt_desync_frames_bucket_total{bucket="3_10"} 1258
telemt_desync_frames_bucket_total{bucket="gt_10"} 1142
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23688
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22715
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 961
telemt_user_connections_total{user="hello"} 945712
telemt_user_connections_current{user="hello"} 1508
telemt_user_octets_from_client{user="hello"} 48208062388 (44.90 GB)
telemt_user_octets_to_client{user="hello"} 465123012000 (433.18 GB)
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 130143.5 (36h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1661996
telemt_connections_bad_total 83682
telemt_handshake_timeouts_total 29678
telemt_upstream_connect_attempt_total 92518
telemt_upstream_connect_success_total 90063
telemt_upstream_connect_fail_total 2455
telemt_upstream_connect_attempts_per_request{bucket="1"} 92518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2455
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 39248
telemt_me_reconnect_success_total 18823
telemt_me_reader_eof_total 20623
telemt_me_idle_close_by_peer_total 20620
telemt_me_route_drop_no_conn_total 664611
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1365610
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5337
telemt_desync_full_logged_total 1703
telemt_desync_suppressed_total 3634
telemt_desync_frames_bucket_total{bucket="1_2"} 1258
telemt_desync_frames_bucket_total{bucket="3_10"} 2192
telemt_desync_frames_bucket_total{bucket="gt_10"} 1887
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19807
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18803
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 984
telemt_user_connections_total{user="hello"} 1428849
telemt_user_connections_current{user="hello"} 2219
telemt_user_octets_from_client{user="hello"} 23791813006 (22.16 GB)
telemt_user_octets_to_client{user="hello"} 684225137034 (637.23 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 130115.6 (36h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1191923
telemt_connections_bad_total 107341
telemt_handshake_timeouts_total 12777
telemt_upstream_connect_attempt_total 49580
telemt_upstream_connect_success_total 48898
telemt_upstream_connect_fail_total 682
telemt_upstream_connect_attempts_per_request{bucket="1"} 49580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 430
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 682
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 62104
telemt_me_reconnect_success_total 25946
telemt_me_reader_eof_total 28068
telemt_me_idle_close_by_peer_total 28065
telemt_me_route_drop_no_conn_total 385804
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 984044
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4238
telemt_desync_full_logged_total 1311
telemt_desync_suppressed_total 2927
telemt_desync_frames_bucket_total{bucket="1_2"} 1147
telemt_desync_frames_bucket_total{bucket="3_10"} 1633
telemt_desync_frames_bucket_total{bucket="gt_10"} 1458
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27477
telemt_me_refill_failed_total 1124
telemt_me_writer_restored_same_endpoint_total 25938
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1531
telemt_user_connections_total{user="hello"} 1000445
telemt_user_connections_current{user="hello"} 1749
telemt_user_octets_from_client{user="hello"} 18948206304 (17.65 GB)
telemt_user_octets_to_client{user="hello"} 505729115880 (471.00 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 130276.8 (36h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1266781
telemt_connections_bad_total 133247
telemt_handshake_timeouts_total 10837
telemt_upstream_connect_attempt_total 25837
telemt_upstream_connect_success_total 25684
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 25837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 30523
telemt_me_reconnect_success_total 19224
telemt_me_reader_eof_total 20812
telemt_me_idle_close_by_peer_total 20810
telemt_me_route_drop_no_conn_total 845827
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1237015
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2404
telemt_desync_full_logged_total 847
telemt_desync_suppressed_total 1557
telemt_desync_frames_bucket_total{bucket="1_2"} 534
telemt_desync_frames_bucket_total{bucket="3_10"} 922
telemt_desync_frames_bucket_total{bucket="gt_10"} 948
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19871
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19210
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 647
telemt_user_connections_total{user="hello"} 1045674
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 16414232720 (15.29 GB)
telemt_user_octets_to_client{user="hello"} 462664505732 (430.89 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 78043.5 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 668071
telemt_connections_bad_total 57994
telemt_handshake_timeouts_total 14780
telemt_upstream_connect_attempt_total 26438
telemt_upstream_connect_success_total 26159
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 26438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 33758
telemt_me_reconnect_success_total 22139
telemt_me_reader_eof_total 23389
telemt_me_idle_close_by_peer_total 23389
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 188742
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500919
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2144
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1407
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 934
telemt_desync_frames_bucket_total{bucket="gt_10"} 859
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22739
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22093
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 600
telemt_user_connections_total{user="hello"} 500636
telemt_user_connections_current{user="hello"} 1440
telemt_user_octets_from_client{user="hello"} 27721464249 (25.82 GB)
telemt_user_octets_to_client{user="hello"} 374227075478 (348.53 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 178
```