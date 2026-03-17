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

# Server Metrics 2026-03-17 21:27:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 96135.6 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1181992
telemt_connections_bad_total 8636
telemt_handshake_timeouts_total 31517
telemt_upstream_connect_attempt_total 21830
telemt_upstream_connect_success_total 21339
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 21830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31375
telemt_me_reconnect_success_total 14245
telemt_me_reader_eof_total 15479
telemt_me_idle_close_by_peer_total 15478
telemt_me_route_drop_no_conn_total 527822
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1083482
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7176
telemt_desync_full_logged_total 2067
telemt_desync_suppressed_total 5109
telemt_desync_frames_bucket_total{bucket="1_2"} 1924
telemt_desync_frames_bucket_total{bucket="3_10"} 2721
telemt_desync_frames_bucket_total{bucket="gt_10"} 2531
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 14990
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14223
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 745
telemt_user_connections_total{user="hello"} 1077715
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 19215823151 (17.90 GB)
telemt_user_octets_to_client{user="hello"} 382809439115 (356.52 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 96387.2 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1232722
telemt_connections_bad_total 59578
telemt_handshake_timeouts_total 44070
telemt_upstream_connect_attempt_total 457331
telemt_upstream_connect_success_total 456440
telemt_upstream_connect_fail_total 891
telemt_upstream_connect_attempts_per_request{bucket="1"} 457331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 891
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57762
telemt_me_reconnect_success_total 14609
telemt_me_reader_eof_total 16575
telemt_me_idle_close_by_peer_total 16575
telemt_me_route_drop_no_conn_total 314008
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628243
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2784
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 1891
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 1162
telemt_desync_frames_bucket_total{bucket="gt_10"} 1101
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16139
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14593
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1530
telemt_user_connections_total{user="hello"} 1064672
telemt_user_connections_current{user="hello"} 1193
telemt_user_octets_from_client{user="hello"} 14744476274 (13.73 GB)
telemt_user_octets_to_client{user="hello"} 355402275038 (330.99 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 96163.3 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 694914
telemt_connections_bad_total 39996
telemt_handshake_timeouts_total 22619
telemt_upstream_connect_attempt_total 22937
telemt_upstream_connect_success_total 22804
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 22937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38634
telemt_me_reconnect_success_total 17959
telemt_me_reader_eof_total 19599
telemt_me_idle_close_by_peer_total 19592
telemt_me_route_drop_no_conn_total 293223
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 599014
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1925
telemt_desync_full_logged_total 585
telemt_desync_suppressed_total 1340
telemt_desync_frames_bucket_total{bucket="1_2"} 535
telemt_desync_frames_bucket_total{bucket="3_10"} 762
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 18851
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17947
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 892
telemt_user_connections_total{user="hello"} 597286
telemt_user_connections_current{user="hello"} 907
telemt_user_octets_from_client{user="hello"} 30342623152 (28.26 GB)
telemt_user_octets_to_client{user="hello"} 257823538088 (240.12 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 96222.6 (26h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1196595
telemt_connections_bad_total 37735
telemt_handshake_timeouts_total 21290
telemt_upstream_connect_attempt_total 82582
telemt_upstream_connect_success_total 82158
telemt_upstream_connect_fail_total 424
telemt_upstream_connect_attempts_per_request{bucket="1"} 82582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 424
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34303
telemt_me_reconnect_success_total 13984
telemt_me_reader_eof_total 15429
telemt_me_idle_close_by_peer_total 15427
telemt_me_route_drop_no_conn_total 496582
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 977966
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3381
telemt_desync_full_logged_total 1081
telemt_desync_suppressed_total 2300
telemt_desync_frames_bucket_total{bucket="1_2"} 832
telemt_desync_frames_bucket_total{bucket="3_10"} 1427
telemt_desync_frames_bucket_total{bucket="gt_10"} 1122
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14880
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13975
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 1040476
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 15606750211 (14.53 GB)
telemt_user_octets_to_client{user="hello"} 441983511253 (411.63 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 96194.2 (26h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 751392
telemt_connections_bad_total 91261
telemt_handshake_timeouts_total 6334
telemt_upstream_connect_attempt_total 41383
telemt_upstream_connect_success_total 40832
telemt_upstream_connect_fail_total 551
telemt_upstream_connect_attempts_per_request{bucket="1"} 41383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 396
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 551
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 52030
telemt_me_reconnect_success_total 19544
telemt_me_reader_eof_total 21273
telemt_me_idle_close_by_peer_total 21271
telemt_me_route_drop_no_conn_total 235789
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597442
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2739
telemt_desync_full_logged_total 798
telemt_desync_suppressed_total 1941
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1098
telemt_desync_frames_bucket_total{bucket="gt_10"} 753
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20891
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19536
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1347
telemt_user_connections_total{user="hello"} 614056
telemt_user_connections_current{user="hello"} 934
telemt_user_octets_from_client{user="hello"} 11936863140 (11.12 GB)
telemt_user_octets_to_client{user="hello"} 302057941988 (281.31 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 96355.1 (26h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 990595
telemt_connections_bad_total 73324
telemt_handshake_timeouts_total 9342
telemt_upstream_connect_attempt_total 19026
telemt_upstream_connect_success_total 18914
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 19026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25371
telemt_me_reconnect_success_total 14094
telemt_me_reader_eof_total 15309
telemt_me_idle_close_by_peer_total 15307
telemt_me_route_drop_no_conn_total 683824
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 983634
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2028
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1320
telemt_desync_frames_bucket_total{bucket="1_2"} 458
telemt_desync_frames_bucket_total{bucket="3_10"} 769
telemt_desync_frames_bucket_total{bucket="gt_10"} 801
telemt_pool_swap_total 81
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14680
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14080
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 586
telemt_user_connections_total{user="hello"} 846666
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 13196341376 (12.29 GB)
telemt_user_octets_to_client{user="hello"} 363014526172 (338.08 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 44122.4 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327822
telemt_connections_bad_total 42237
telemt_handshake_timeouts_total 10109
telemt_upstream_connect_attempt_total 17673
telemt_upstream_connect_success_total 17510
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 17673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26742
telemt_me_reconnect_success_total 15149
telemt_me_reader_eof_total 16007
telemt_me_idle_close_by_peer_total 16007
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 80719
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250594
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 203
telemt_desync_frames_bucket_total{bucket="3_10"} 308
telemt_desync_frames_bucket_total{bucket="gt_10"} 295
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15689
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15121
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 250536
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 20971451009 (19.53 GB)
telemt_user_octets_to_client{user="hello"} 209669566506 (195.27 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 67
```