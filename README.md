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

# Server Metrics 2026-03-18 00:31:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 107146.7 (29h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1260850
telemt_connections_bad_total 9553
telemt_handshake_timeouts_total 32427
telemt_upstream_connect_attempt_total 23951
telemt_upstream_connect_success_total 23453
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 23951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32959
telemt_me_reconnect_success_total 15823
telemt_me_reader_eof_total 17185
telemt_me_idle_close_by_peer_total 17184
telemt_me_route_drop_no_conn_total 555949
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1158780
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7520
telemt_desync_full_logged_total 2203
telemt_desync_suppressed_total 5317
telemt_desync_frames_bucket_total{bucket="1_2"} 2011
telemt_desync_frames_bucket_total{bucket="3_10"} 2851
telemt_desync_frames_bucket_total{bucket="gt_10"} 2658
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16594
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15801
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 771
telemt_user_connections_total{user="hello"} 1152993
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 22719223571 (21.16 GB)
telemt_user_octets_to_client{user="hello"} 414716957351 (386.24 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 107398.1 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1338857
telemt_connections_bad_total 62101
telemt_handshake_timeouts_total 45963
telemt_upstream_connect_attempt_total 466566
telemt_upstream_connect_success_total 465020
telemt_upstream_connect_fail_total 1546
telemt_upstream_connect_attempts_per_request{bucket="1"} 466566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1546
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122158
telemt_me_reconnect_success_total 16729
telemt_me_reader_eof_total 18837
telemt_me_idle_close_by_peer_total 18827
telemt_me_route_drop_no_conn_total 346158
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 720170
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3286
telemt_desync_full_logged_total 1091
telemt_desync_suppressed_total 2195
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 1351
telemt_desync_frames_bucket_total{bucket="gt_10"} 1293
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 18273
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16711
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 1162519
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 15827592941 (14.74 GB)
telemt_user_octets_to_client{user="hello"} 398618732314 (371.24 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 107174.2 (29h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 792476
telemt_connections_bad_total 51460
telemt_handshake_timeouts_total 24038
telemt_upstream_connect_attempt_total 25169
telemt_upstream_connect_success_total 25024
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 25169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13450
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40305
telemt_me_reconnect_success_total 19622
telemt_me_reader_eof_total 21372
telemt_me_idle_close_by_peer_total 21365
telemt_me_route_drop_no_conn_total 320621
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 673413
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2164
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 715
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 20535
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19610
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 913
telemt_user_connections_total{user="hello"} 671614
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 32819474024 (30.57 GB)
telemt_user_octets_to_client{user="hello"} 297752689156 (277.30 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 107233.7 (29h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1278766
telemt_connections_bad_total 52506
telemt_handshake_timeouts_total 21802
telemt_upstream_connect_attempt_total 86322
telemt_upstream_connect_success_total 84903
telemt_upstream_connect_fail_total 1419
telemt_upstream_connect_attempts_per_request{bucket="1"} 86322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1419
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35880
telemt_me_reconnect_success_total 15520
telemt_me_reader_eof_total 17128
telemt_me_idle_close_by_peer_total 17126
telemt_me_route_drop_no_conn_total 523741
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1041048
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3917
telemt_desync_full_logged_total 1296
telemt_desync_suppressed_total 2621
telemt_desync_frames_bucket_total{bucket="1_2"} 955
telemt_desync_frames_bucket_total{bucket="3_10"} 1648
telemt_desync_frames_bucket_total{bucket="gt_10"} 1314
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 16448
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15510
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 928
telemt_user_connections_total{user="hello"} 1104173
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 17334873059 (16.14 GB)
telemt_user_octets_to_client{user="hello"} 514835862242 (479.48 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 107205.6 (29h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 836714
telemt_connections_bad_total 98963
telemt_handshake_timeouts_total 6750
telemt_upstream_connect_attempt_total 44244
telemt_upstream_connect_success_total 43631
telemt_upstream_connect_fail_total 613
telemt_upstream_connect_attempts_per_request{bucket="1"} 44244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 613
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56740
telemt_me_reconnect_success_total 21782
telemt_me_reader_eof_total 23670
telemt_me_idle_close_by_peer_total 23668
telemt_me_route_drop_no_conn_total 264966
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672743
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3178
telemt_desync_full_logged_total 942
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1272
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23230
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21774
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1448
telemt_user_connections_total{user="hello"} 689351
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 13557071708 (12.63 GB)
telemt_user_octets_to_client{user="hello"} 347052993392 (323.22 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 107366.5 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1075202
telemt_connections_bad_total 102817
telemt_handshake_timeouts_total 9606
telemt_upstream_connect_attempt_total 21354
telemt_upstream_connect_success_total 21235
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 21354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27152
telemt_me_reconnect_success_total 15870
telemt_me_reader_eof_total 17226
telemt_me_idle_close_by_peer_total 17224
telemt_me_route_drop_no_conn_total 720348
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1037981
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
telemt_pool_swap_total 94
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16477
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15856
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 607
telemt_user_connections_total{user="hello"} 893807
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 14368135824 (13.38 GB)
telemt_user_octets_to_client{user="hello"} 378087500752 (352.12 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 55133.8 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391448
telemt_connections_bad_total 44682
telemt_handshake_timeouts_total 10832
telemt_upstream_connect_attempt_total 20732
telemt_upstream_connect_success_total 20543
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 20732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29216
telemt_me_reconnect_success_total 17617
telemt_me_reader_eof_total 18643
telemt_me_idle_close_by_peer_total 18643
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 98137
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289511
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1100
telemt_desync_full_logged_total 346
telemt_desync_suppressed_total 754
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 472
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18180
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17586
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 563
telemt_user_connections_total{user="hello"} 289452
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 22201056041 (20.68 GB)
telemt_user_octets_to_client{user="hello"} 238940875130 (222.53 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 20
```