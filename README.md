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

# Server Metrics 2026-03-17 23:14:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 102566.7 (28h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1228785
telemt_connections_bad_total 9042
telemt_handshake_timeouts_total 32257
telemt_upstream_connect_attempt_total 23078
telemt_upstream_connect_success_total 22583
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 23078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32318
telemt_me_reconnect_success_total 15186
telemt_me_reader_eof_total 16494
telemt_me_idle_close_by_peer_total 16493
telemt_me_route_drop_no_conn_total 545372
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1128110
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7434
telemt_desync_full_logged_total 2161
telemt_desync_suppressed_total 5273
telemt_desync_frames_bucket_total{bucket="1_2"} 1990
telemt_desync_frames_bucket_total{bucket="3_10"} 2809
telemt_desync_frames_bucket_total{bucket="gt_10"} 2635
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15941
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15164
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 755
telemt_user_connections_total{user="hello"} 1122333
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 21343352487 (19.88 GB)
telemt_user_octets_to_client{user="hello"} 405407713443 (377.57 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 102818.3 (28h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1300212
telemt_connections_bad_total 60747
telemt_handshake_timeouts_total 45199
telemt_upstream_connect_attempt_total 458618
telemt_upstream_connect_success_total 457709
telemt_upstream_connect_fail_total 909
telemt_upstream_connect_attempts_per_request{bucket="1"} 458618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 909
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58719
telemt_me_reconnect_success_total 15562
telemt_me_reader_eof_total 17595
telemt_me_idle_close_by_peer_total 17595
telemt_me_route_drop_no_conn_total 337974
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692143
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3178
telemt_desync_full_logged_total 1039
telemt_desync_suppressed_total 2139
telemt_desync_frames_bucket_total{bucket="1_2"} 625
telemt_desync_frames_bucket_total{bucket="3_10"} 1300
telemt_desync_frames_bucket_total{bucket="gt_10"} 1253
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 17103
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15546
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1541
telemt_user_connections_total{user="hello"} 1128572
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 15535869846 (14.47 GB)
telemt_user_octets_to_client{user="hello"} 387119834542 (360.53 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 102594.2 (28h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 763789
telemt_connections_bad_total 47914
telemt_handshake_timeouts_total 23647
telemt_upstream_connect_attempt_total 24178
telemt_upstream_connect_success_total 24039
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39566
telemt_me_reconnect_success_total 18885
telemt_me_reader_eof_total 20586
telemt_me_idle_close_by_peer_total 20579
telemt_me_route_drop_no_conn_total 312736
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 649576
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2115
telemt_desync_full_logged_total 683
telemt_desync_suppressed_total 1432
telemt_desync_frames_bucket_total{bucket="1_2"} 594
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19790
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18873
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 905
telemt_user_connections_total{user="hello"} 647837
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 31592649264 (29.42 GB)
telemt_user_octets_to_client{user="hello"} 285826635256 (266.20 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 102653.6 (28h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1252410
telemt_connections_bad_total 45925
telemt_handshake_timeouts_total 21638
telemt_upstream_connect_attempt_total 83795
telemt_upstream_connect_success_total 83358
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 83795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35189
telemt_me_reconnect_success_total 14862
telemt_me_reader_eof_total 16370
telemt_me_idle_close_by_peer_total 16368
telemt_me_route_drop_no_conn_total 516284
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1023789
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3837
telemt_desync_full_logged_total 1261
telemt_desync_suppressed_total 2576
telemt_desync_frames_bucket_total{bucket="1_2"} 942
telemt_desync_frames_bucket_total{bucket="3_10"} 1613
telemt_desync_frames_bucket_total{bucket="gt_10"} 1282
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 15772
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14853
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 910
telemt_user_connections_total{user="hello"} 1086274
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 17089429043 (15.92 GB)
telemt_user_octets_to_client{user="hello"} 490301656013 (456.63 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 102625.6 (28h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809996
telemt_connections_bad_total 95951
telemt_handshake_timeouts_total 6462
telemt_upstream_connect_attempt_total 42981
telemt_upstream_connect_success_total 42395
telemt_upstream_connect_fail_total 586
telemt_upstream_connect_attempts_per_request{bucket="1"} 42981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 404
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 586
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55754
telemt_me_reconnect_success_total 20801
telemt_me_reader_eof_total 22636
telemt_me_idle_close_by_peer_total 22634
telemt_me_route_drop_no_conn_total 257350
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 650044
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3044
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 2151
telemt_desync_frames_bucket_total{bucket="1_2"} 975
telemt_desync_frames_bucket_total{bucket="3_10"} 1215
telemt_desync_frames_bucket_total{bucket="gt_10"} 854
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22242
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20793
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1441
telemt_user_connections_total{user="hello"} 666654
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 12703724380 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 330612310400 (307.91 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 102786.8 (28h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1042005
telemt_connections_bad_total 90610
telemt_handshake_timeouts_total 9534
telemt_upstream_connect_attempt_total 20361
telemt_upstream_connect_success_total 20246
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 20361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26380
telemt_me_reconnect_success_total 15100
telemt_me_reader_eof_total 16397
telemt_me_idle_close_by_peer_total 16395
telemt_me_route_drop_no_conn_total 699208
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1013079
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
telemt_pool_swap_total 89
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15699
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15086
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 599
telemt_user_connections_total{user="hello"} 876105
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 13976862892 (13.02 GB)
telemt_user_octets_to_client{user="hello"} 370822146440 (345.36 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 50553.7 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370382
telemt_connections_bad_total 44601
telemt_handshake_timeouts_total 10665
telemt_upstream_connect_attempt_total 19310
telemt_upstream_connect_success_total 19131
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 19310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28019
telemt_me_reconnect_success_total 16423
telemt_me_reader_eof_total 17367
telemt_me_idle_close_by_peer_total 17367
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 92993
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278703
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1010
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 693
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 421
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 30
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16978
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16394
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 278641
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 21423290729 (19.95 GB)
telemt_user_octets_to_client{user="hello"} 228904095774 (213.18 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 25
```