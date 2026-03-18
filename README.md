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

# Server Metrics 2026-03-18 00:15:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 106230.4 (29h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1254635
telemt_connections_bad_total 9418
telemt_handshake_timeouts_total 32398
telemt_upstream_connect_attempt_total 23781
telemt_upstream_connect_success_total 23284
telemt_upstream_connect_fail_total 497
telemt_upstream_connect_attempts_per_request{bucket="1"} 23781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 497
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32840
telemt_me_reconnect_success_total 15705
telemt_me_reader_eof_total 17055
telemt_me_idle_close_by_peer_total 17054
telemt_me_route_drop_no_conn_total 553885
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1152821
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7505
telemt_desync_full_logged_total 2197
telemt_desync_suppressed_total 5308
telemt_desync_frames_bucket_total{bucket="1_2"} 2007
telemt_desync_frames_bucket_total{bucket="3_10"} 2844
telemt_desync_frames_bucket_total{bucket="gt_10"} 2654
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16472
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15683
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 767
telemt_user_connections_total{user="hello"} 1147035
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 22680481655 (21.12 GB)
telemt_user_octets_to_client{user="hello"} 412742167027 (384.40 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 106482.1 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1332582
telemt_connections_bad_total 61903
telemt_handshake_timeouts_total 45834
telemt_upstream_connect_attempt_total 466383
telemt_upstream_connect_success_total 464838
telemt_upstream_connect_fail_total 1545
telemt_upstream_connect_attempts_per_request{bucket="1"} 466383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1545
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122019
telemt_me_reconnect_success_total 16591
telemt_me_reader_eof_total 18689
telemt_me_idle_close_by_peer_total 18679
telemt_me_route_drop_no_conn_total 344891
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 714517
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3262
telemt_desync_full_logged_total 1078
telemt_desync_suppressed_total 2184
telemt_desync_frames_bucket_total{bucket="1_2"} 634
telemt_desync_frames_bucket_total{bucket="3_10"} 1340
telemt_desync_frames_bucket_total{bucket="gt_10"} 1288
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 18135
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16573
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 1156867
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 15748133653 (14.67 GB)
telemt_user_octets_to_client{user="hello"} 396471583634 (369.24 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 106258.2 (29h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 787237
telemt_connections_bad_total 50742
telemt_handshake_timeouts_total 23838
telemt_upstream_connect_attempt_total 24949
telemt_upstream_connect_success_total 24805
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 24949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40137
telemt_me_reconnect_success_total 19455
telemt_me_reader_eof_total 21195
telemt_me_idle_close_by_peer_total 21188
telemt_me_route_drop_no_conn_total 319275
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 669157
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2137
telemt_desync_full_logged_total 697
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 704
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 20367
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19443
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 912
telemt_user_connections_total{user="hello"} 667375
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 32052926524 (29.85 GB)
telemt_user_octets_to_client{user="hello"} 295025580788 (274.76 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 106317.7 (29h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1274593
telemt_connections_bad_total 51624
telemt_handshake_timeouts_total 21727
telemt_upstream_connect_attempt_total 86128
telemt_upstream_connect_success_total 84711
telemt_upstream_connect_fail_total 1417
telemt_upstream_connect_attempts_per_request{bucket="1"} 86128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1417
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35731
telemt_me_reconnect_success_total 15371
telemt_me_reader_eof_total 16969
telemt_me_idle_close_by_peer_total 16967
telemt_me_route_drop_no_conn_total 522343
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1037909
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3911
telemt_desync_full_logged_total 1293
telemt_desync_suppressed_total 2618
telemt_desync_frames_bucket_total{bucket="1_2"} 954
telemt_desync_frames_bucket_total{bucket="3_10"} 1644
telemt_desync_frames_bucket_total{bucket="gt_10"} 1313
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 16298
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15361
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 927
telemt_user_connections_total{user="hello"} 1101034
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 17288006615 (16.10 GB)
telemt_user_octets_to_client{user="hello"} 509571955810 (474.58 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 106289.5 (29h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 831347
telemt_connections_bad_total 98184
telemt_handshake_timeouts_total 6713
telemt_upstream_connect_attempt_total 43953
telemt_upstream_connect_success_total 43344
telemt_upstream_connect_fail_total 609
telemt_upstream_connect_attempts_per_request{bucket="1"} 43953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 410
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 609
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56508
telemt_me_reconnect_success_total 21551
telemt_me_reader_eof_total 23438
telemt_me_idle_close_by_peer_total 23436
telemt_me_route_drop_no_conn_total 263590
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668297
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3165
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 2227
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1266
telemt_desync_frames_bucket_total{bucket="gt_10"} 897
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22998
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21543
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1447
telemt_user_connections_total{user="hello"} 684905
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 13494206860 (12.57 GB)
telemt_user_octets_to_client{user="hello"} 344574691828 (320.91 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 106450.4 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1068626
telemt_connections_bad_total 100384
telemt_handshake_timeouts_total 9580
telemt_upstream_connect_attempt_total 21152
telemt_upstream_connect_success_total 21034
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26994
telemt_me_reconnect_success_total 15712
telemt_me_reader_eof_total 17057
telemt_me_idle_close_by_peer_total 17055
telemt_me_route_drop_no_conn_total 718470
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1034498
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
telemt_pool_swap_total 93
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16317
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15698
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 605
telemt_user_connections_total{user="hello"} 890325
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 14324880004 (13.34 GB)
telemt_user_octets_to_client{user="hello"} 377332176588 (351.42 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 54217.7 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387472
telemt_connections_bad_total 44672
telemt_handshake_timeouts_total 10806
telemt_upstream_connect_attempt_total 20438
telemt_upstream_connect_success_total 20252
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 20438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28968
telemt_me_reconnect_success_total 17369
telemt_me_reader_eof_total 18379
telemt_me_idle_close_by_peer_total 18379
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 96982
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287331
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1076
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 736
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 405
telemt_pool_swap_total 34
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17930
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17339
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 287272
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 22080307637 (20.56 GB)
telemt_user_octets_to_client{user="hello"} 236266479146 (220.04 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 22
```