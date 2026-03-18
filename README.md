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

# Server Metrics 2026-03-18 01:16:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 109897.0 (30h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1283033
telemt_connections_bad_total 9605
telemt_handshake_timeouts_total 32506
telemt_upstream_connect_attempt_total 24564
telemt_upstream_connect_success_total 24063
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 24564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33411
telemt_me_reconnect_success_total 16274
telemt_me_reader_eof_total 17668
telemt_me_idle_close_by_peer_total 17667
telemt_me_route_drop_no_conn_total 561551
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1180366
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7581
telemt_desync_full_logged_total 2228
telemt_desync_suppressed_total 5353
telemt_desync_frames_bucket_total{bucket="1_2"} 2026
telemt_desync_frames_bucket_total{bucket="3_10"} 2878
telemt_desync_frames_bucket_total{bucket="gt_10"} 2677
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17050
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16252
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 776
telemt_user_connections_total{user="hello"} 1174579
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 22845330711 (21.28 GB)
telemt_user_octets_to_client{user="hello"} 418765788791 (390.01 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 110148.4 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1359857
telemt_connections_bad_total 63783
telemt_handshake_timeouts_total 46472
telemt_upstream_connect_attempt_total 467164
telemt_upstream_connect_success_total 465613
telemt_upstream_connect_fail_total 1551
telemt_upstream_connect_attempts_per_request{bucket="1"} 467164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32802
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1551
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122622
telemt_me_reconnect_success_total 17192
telemt_me_reader_eof_total 19332
telemt_me_idle_close_by_peer_total 19322
telemt_me_route_drop_no_conn_total 350575
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738135
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3426
telemt_desync_full_logged_total 1145
telemt_desync_suppressed_total 2281
telemt_desync_frames_bucket_total{bucket="1_2"} 670
telemt_desync_frames_bucket_total{bucket="3_10"} 1413
telemt_desync_frames_bucket_total{bucket="gt_10"} 1343
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 18740
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17174
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1548
telemt_user_connections_total{user="hello"} 1180485
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 16048707249 (14.95 GB)
telemt_user_octets_to_client{user="hello"} 406240743470 (378.34 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 109924.4 (30h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808428
telemt_connections_bad_total 54094
telemt_handshake_timeouts_total 24235
telemt_upstream_connect_attempt_total 25767
telemt_upstream_connect_success_total 25620
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 25767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13770
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40760
telemt_me_reconnect_success_total 20074
telemt_me_reader_eof_total 21863
telemt_me_idle_close_by_peer_total 21856
telemt_me_route_drop_no_conn_total 324703
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 686030
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2190
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1479
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 721
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 20993
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20062
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 919
telemt_user_connections_total{user="hello"} 684149
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 38601002520 (35.95 GB)
telemt_user_octets_to_client{user="hello"} 302483666620 (281.71 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 109983.8 (30h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1291810
telemt_connections_bad_total 55129
telemt_handshake_timeouts_total 21932
telemt_upstream_connect_attempt_total 86878
telemt_upstream_connect_success_total 85454
telemt_upstream_connect_fail_total 1424
telemt_upstream_connect_attempts_per_request{bucket="1"} 86878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1424
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36303
telemt_me_reconnect_success_total 15941
telemt_me_reader_eof_total 17584
telemt_me_idle_close_by_peer_total 17582
telemt_me_route_drop_no_conn_total 527593
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1051049
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3954
telemt_desync_full_logged_total 1307
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1660
telemt_desync_frames_bucket_total{bucket="gt_10"} 1328
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16875
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15931
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 934
telemt_user_connections_total{user="hello"} 1114168
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 17477231819 (16.28 GB)
telemt_user_octets_to_client{user="hello"} 527093308186 (490.89 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 109955.7 (30h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 850925
telemt_connections_bad_total 99601
telemt_handshake_timeouts_total 6816
telemt_upstream_connect_attempt_total 45204
telemt_upstream_connect_success_total 44581
telemt_upstream_connect_fail_total 623
telemt_upstream_connect_attempts_per_request{bucket="1"} 45204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 623
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57553
telemt_me_reconnect_success_total 22594
telemt_me_reader_eof_total 24511
telemt_me_idle_close_by_peer_total 24509
telemt_me_route_drop_no_conn_total 270823
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 685633
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3182
telemt_desync_full_logged_total 946
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1006
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 903
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24046
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22586
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1452
telemt_user_connections_total{user="hello"} 702239
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 13646325040 (12.71 GB)
telemt_user_octets_to_client{user="hello"} 350244418356 (326.19 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 110116.7 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1096185
telemt_connections_bad_total 110163
telemt_handshake_timeouts_total 9672
telemt_upstream_connect_attempt_total 21917
telemt_upstream_connect_success_total 21796
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 21917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27583
telemt_me_reconnect_success_total 16299
telemt_me_reader_eof_total 17694
telemt_me_idle_close_by_peer_total 17692
telemt_me_route_drop_no_conn_total 742218
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1063465
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
telemt_pool_swap_total 97
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16912
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16285
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 906116
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 14713073696 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 389153623224 (362.43 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 57883.9 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404139
telemt_connections_bad_total 44693
telemt_handshake_timeouts_total 10921
telemt_upstream_connect_attempt_total 21677
telemt_upstream_connect_success_total 21478
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 21677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30022
telemt_me_reconnect_success_total 18421
telemt_me_reader_eof_total 19488
telemt_me_idle_close_by_peer_total 19488
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 100829
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296349
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1212
telemt_desync_full_logged_total 372
telemt_desync_suppressed_total 840
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 463
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18989
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18388
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 296285
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 22389487797 (20.85 GB)
telemt_user_octets_to_client{user="hello"} 246626162090 (229.69 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 25
```