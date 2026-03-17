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

# Server Metrics 2026-03-17 23:40:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 104092.9 (28h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1239349
telemt_connections_bad_total 9043
telemt_handshake_timeouts_total 32294
telemt_upstream_connect_attempt_total 23395
telemt_upstream_connect_success_total 22900
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 23395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32549
telemt_me_reconnect_success_total 15414
telemt_me_reader_eof_total 16741
telemt_me_idle_close_by_peer_total 16740
telemt_me_route_drop_no_conn_total 548887
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1138392
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7476
telemt_desync_full_logged_total 2179
telemt_desync_suppressed_total 5297
telemt_desync_frames_bucket_total{bucket="1_2"} 1998
telemt_desync_frames_bucket_total{bucket="3_10"} 2835
telemt_desync_frames_bucket_total{bucket="gt_10"} 2643
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 16175
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15392
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 1132613
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 22409915663 (20.87 GB)
telemt_user_octets_to_client{user="hello"} 408934417807 (380.85 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 104344.1 (28h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1312637
telemt_connections_bad_total 61107
telemt_handshake_timeouts_total 45400
telemt_upstream_connect_attempt_total 458932
telemt_upstream_connect_success_total 458020
telemt_upstream_connect_fail_total 912
telemt_upstream_connect_attempts_per_request{bucket="1"} 458932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 912
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58987
telemt_me_reconnect_success_total 15829
telemt_me_reader_eof_total 17876
telemt_me_idle_close_by_peer_total 17876
telemt_me_route_drop_no_conn_total 341844
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 702961
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3218
telemt_desync_full_logged_total 1056
telemt_desync_suppressed_total 2162
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 1317
telemt_desync_frames_bucket_total{bucket="gt_10"} 1274
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17373
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15813
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 1139389
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 15640434882 (14.57 GB)
telemt_user_octets_to_client{user="hello"} 390853227218 (364.01 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 104120.0 (28h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 773944
telemt_connections_bad_total 49088
telemt_handshake_timeouts_total 23740
telemt_upstream_connect_attempt_total 24523
telemt_upstream_connect_success_total 24380
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 24523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39821
telemt_me_reconnect_success_total 19140
telemt_me_reader_eof_total 20861
telemt_me_idle_close_by_peer_total 20854
telemt_me_route_drop_no_conn_total 315595
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 658040
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 695
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 20049
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19128
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 909
telemt_user_connections_total{user="hello"} 656276
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 31909659108 (29.72 GB)
telemt_user_octets_to_client{user="hello"} 290448129272 (270.50 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 104179.6 (28h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1261958
telemt_connections_bad_total 49339
telemt_handshake_timeouts_total 21666
telemt_upstream_connect_attempt_total 84121
telemt_upstream_connect_success_total 83684
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 84121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35445
telemt_me_reconnect_success_total 15117
telemt_me_reader_eof_total 16646
telemt_me_idle_close_by_peer_total 16644
telemt_me_route_drop_no_conn_total 519264
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1029723
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3884
telemt_desync_full_logged_total 1281
telemt_desync_suppressed_total 2603
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1632
telemt_desync_frames_bucket_total{bucket="gt_10"} 1302
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 16033
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15108
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 916
telemt_user_connections_total{user="hello"} 1092206
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 17180992179 (16.00 GB)
telemt_user_octets_to_client{user="hello"} 499540143417 (465.23 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 104151.6 (28h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818602
telemt_connections_bad_total 96226
telemt_handshake_timeouts_total 6636
telemt_upstream_connect_attempt_total 43365
telemt_upstream_connect_success_total 42775
telemt_upstream_connect_fail_total 590
telemt_upstream_connect_attempts_per_request{bucket="1"} 43365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 406
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 590
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56050
telemt_me_reconnect_success_total 21095
telemt_me_reader_eof_total 22961
telemt_me_idle_close_by_peer_total 22959
telemt_me_route_drop_no_conn_total 259999
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657943
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3106
telemt_desync_full_logged_total 916
telemt_desync_suppressed_total 2190
telemt_desync_frames_bucket_total{bucket="1_2"} 988
telemt_desync_frames_bucket_total{bucket="3_10"} 1239
telemt_desync_frames_bucket_total{bucket="gt_10"} 879
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22540
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21087
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1445
telemt_user_connections_total{user="hello"} 674552
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 13341214748 (12.42 GB)
telemt_user_octets_to_client{user="hello"} 335059119560 (312.05 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 104312.8 (28h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1052704
telemt_connections_bad_total 94676
telemt_handshake_timeouts_total 9549
telemt_upstream_connect_attempt_total 20649
telemt_upstream_connect_success_total 20534
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 20649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26625
telemt_me_reconnect_success_total 15344
telemt_me_reader_eof_total 16656
telemt_me_idle_close_by_peer_total 16654
telemt_me_route_drop_no_conn_total 703158
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1018660
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 90
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15947
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15330
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 881686
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 14255581808 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 372374279820 (346.80 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 52079.8 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377534
telemt_connections_bad_total 44617
telemt_handshake_timeouts_total 10742
telemt_upstream_connect_attempt_total 19735
telemt_upstream_connect_success_total 19556
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 19735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28401
telemt_me_reconnect_success_total 16803
telemt_me_reader_eof_total 17763
telemt_me_idle_close_by_peer_total 17763
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 95073
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282955
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1031
telemt_desync_full_logged_total 325
telemt_desync_suppressed_total 706
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 383
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17362
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16774
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 559
telemt_user_connections_total{user="hello"} 282893
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 22013019429 (20.50 GB)
telemt_user_octets_to_client{user="hello"} 232434864738 (216.47 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 19
```