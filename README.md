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

# Server Metrics 2026-03-17 21:58:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 97974.8 (27h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1196512
telemt_connections_bad_total 8648
telemt_handshake_timeouts_total 31592
telemt_upstream_connect_attempt_total 22199
telemt_upstream_connect_success_total 21708
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 22199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31658
telemt_me_reconnect_success_total 14527
telemt_me_reader_eof_total 15788
telemt_me_idle_close_by_peer_total 15787
telemt_me_route_drop_no_conn_total 533510
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1097608
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7277
telemt_desync_full_logged_total 2099
telemt_desync_suppressed_total 5178
telemt_desync_frames_bucket_total{bucket="1_2"} 1941
telemt_desync_frames_bucket_total{bucket="3_10"} 2755
telemt_desync_frames_bucket_total{bucket="gt_10"} 2581
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 15278
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14505
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 751
telemt_user_connections_total{user="hello"} 1091840
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 19610269955 (18.26 GB)
telemt_user_octets_to_client{user="hello"} 390013709299 (363.23 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 98226.2 (27h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1257973
telemt_connections_bad_total 59826
telemt_handshake_timeouts_total 44653
telemt_upstream_connect_attempt_total 457666
telemt_upstream_connect_success_total 456770
telemt_upstream_connect_fail_total 896
telemt_upstream_connect_attempts_per_request{bucket="1"} 457666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 896
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57996
telemt_me_reconnect_success_total 14841
telemt_me_reader_eof_total 16826
telemt_me_idle_close_by_peer_total 16826
telemt_me_route_drop_no_conn_total 322582
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 652003
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2929
telemt_desync_full_logged_total 940
telemt_desync_suppressed_total 1989
telemt_desync_frames_bucket_total{bucket="1_2"} 557
telemt_desync_frames_bucket_total{bucket="3_10"} 1201
telemt_desync_frames_bucket_total{bucket="gt_10"} 1171
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 16375
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14825
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1534
telemt_user_connections_total{user="hello"} 1088433
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 14989136282 (13.96 GB)
telemt_user_octets_to_client{user="hello"} 365867914918 (340.74 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 98001.9 (27h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 717678
telemt_connections_bad_total 43772
telemt_handshake_timeouts_total 22724
telemt_upstream_connect_attempt_total 23273
telemt_upstream_connect_success_total 23136
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 23273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38880
telemt_me_reconnect_success_total 18203
telemt_me_reader_eof_total 19856
telemt_me_idle_close_by_peer_total 19849
telemt_me_route_drop_no_conn_total 300377
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 617191
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2008
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1396
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 789
telemt_desync_frames_bucket_total{bucket="gt_10"} 657
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 19097
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18191
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 894
telemt_user_connections_total{user="hello"} 615461
telemt_user_connections_current{user="hello"} 835
telemt_user_octets_from_client{user="hello"} 30643561796 (28.54 GB)
telemt_user_octets_to_client{user="hello"} 268824225304 (250.36 GB)
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 98061.6 (27h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1215768
telemt_connections_bad_total 40149
telemt_handshake_timeouts_total 21538
telemt_upstream_connect_attempt_total 82895
telemt_upstream_connect_success_total 82467
telemt_upstream_connect_fail_total 428
telemt_upstream_connect_attempts_per_request{bucket="1"} 82895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 428
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34528
telemt_me_reconnect_success_total 14206
telemt_me_reader_eof_total 15668
telemt_me_idle_close_by_peer_total 15666
telemt_me_route_drop_no_conn_total 503820
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 994045
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3564
telemt_desync_full_logged_total 1154
telemt_desync_suppressed_total 2410
telemt_desync_frames_bucket_total{bucket="1_2"} 873
telemt_desync_frames_bucket_total{bucket="3_10"} 1499
telemt_desync_frames_bucket_total{bucket="gt_10"} 1192
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 15105
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14197
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 899
telemt_user_connections_total{user="hello"} 1056543
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 16593932043 (15.45 GB)
telemt_user_octets_to_client{user="hello"} 457801525925 (426.36 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 98033.4 (27h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 771117
telemt_connections_bad_total 91638
telemt_handshake_timeouts_total 6389
telemt_upstream_connect_attempt_total 41865
telemt_upstream_connect_success_total 41305
telemt_upstream_connect_fail_total 560
telemt_upstream_connect_attempts_per_request{bucket="1"} 41865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 560
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 53633
telemt_me_reconnect_success_total 19930
telemt_me_reader_eof_total 21699
telemt_me_idle_close_by_peer_total 21697
telemt_me_route_drop_no_conn_total 243207
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 616417
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2810
telemt_desync_full_logged_total 829
telemt_desync_suppressed_total 1981
telemt_desync_frames_bucket_total{bucket="1_2"} 897
telemt_desync_frames_bucket_total{bucket="3_10"} 1127
telemt_desync_frames_bucket_total{bucket="gt_10"} 786
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21320
telemt_me_refill_failed_total 1048
telemt_me_writer_restored_same_endpoint_total 19922
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1390
telemt_user_connections_total{user="hello"} 633028
telemt_user_connections_current{user="hello"} 840
telemt_user_octets_from_client{user="hello"} 12340195896 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 311108245112 (289.74 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 98194.3 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1007703
telemt_connections_bad_total 78270
telemt_handshake_timeouts_total 9452
telemt_upstream_connect_attempt_total 19401
telemt_upstream_connect_success_total 19289
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 19401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25639
telemt_me_reconnect_success_total 14361
telemt_me_reader_eof_total 15597
telemt_me_idle_close_by_peer_total 15595
telemt_me_route_drop_no_conn_total 688549
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 994144
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2061
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1344
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 779
telemt_desync_frames_bucket_total{bucket="gt_10"} 821
telemt_pool_swap_total 84
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 14951
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14347
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 590
telemt_user_connections_total{user="hello"} 857173
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 13326400120 (12.41 GB)
telemt_user_octets_to_client{user="hello"} 365517140260 (340.41 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 45961.5 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345248
telemt_connections_bad_total 44255
telemt_handshake_timeouts_total 10536
telemt_upstream_connect_attempt_total 18127
telemt_upstream_connect_success_total 17958
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 18127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27084
telemt_me_reconnect_success_total 15490
telemt_me_reader_eof_total 16370
telemt_me_idle_close_by_peer_total 16370
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 84990
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262331
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 877
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 619
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16033
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15461
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 262271
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 21209605397 (19.75 GB)
telemt_user_octets_to_client{user="hello"} 218586495558 (203.57 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 46
```