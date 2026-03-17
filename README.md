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

# Server Metrics 2026-03-17 19:50:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 90320.5 (25h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1119008
telemt_connections_bad_total 7968
telemt_handshake_timeouts_total 30207
telemt_upstream_connect_attempt_total 20821
telemt_upstream_connect_success_total 20333
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 20821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30627
telemt_me_reconnect_success_total 13499
telemt_me_reader_eof_total 14683
telemt_me_idle_close_by_peer_total 14682
telemt_me_route_drop_no_conn_total 502764
telemt_me_route_drop_channel_closed_total 151
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1024681
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6755
telemt_desync_full_logged_total 1932
telemt_desync_suppressed_total 4823
telemt_desync_frames_bucket_total{bucket="1_2"} 1821
telemt_desync_frames_bucket_total{bucket="3_10"} 2567
telemt_desync_frames_bucket_total{bucket="gt_10"} 2367
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14232
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13477
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 733
telemt_user_connections_total{user="hello"} 1018921
telemt_user_connections_current{user="hello"} 879
telemt_user_octets_from_client{user="hello"} 15387922671 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 356203891547 (331.74 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 90572.2 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1112312
telemt_connections_bad_total 56706
telemt_handshake_timeouts_total 39390
telemt_upstream_connect_attempt_total 456405
telemt_upstream_connect_success_total 455530
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 456405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57145
telemt_me_reconnect_success_total 13994
telemt_me_reader_eof_total 15921
telemt_me_idle_close_by_peer_total 15921
telemt_me_route_drop_no_conn_total 275298
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 519515
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2143
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1457
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 901
telemt_desync_frames_bucket_total{bucket="gt_10"} 799
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 15513
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13978
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1519
telemt_user_connections_total{user="hello"} 955952
telemt_user_connections_current{user="hello"} 1556
telemt_user_octets_from_client{user="hello"} 13295497566 (12.38 GB)
telemt_user_octets_to_client{user="hello"} 295915829294 (275.59 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 90348.3 (25h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592485
telemt_connections_bad_total 24573
telemt_handshake_timeouts_total 21983
telemt_upstream_connect_attempt_total 22036
telemt_upstream_connect_success_total 21907
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 22036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 37996
telemt_me_reconnect_success_total 17324
telemt_me_reader_eof_total 18923
telemt_me_idle_close_by_peer_total 18916
telemt_me_route_drop_no_conn_total 263759
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517482
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1525
telemt_desync_full_logged_total 452
telemt_desync_suppressed_total 1073
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 18207
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17312
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 883
telemt_user_connections_total{user="hello"} 515772
telemt_user_connections_current{user="hello"} 969
telemt_user_octets_from_client{user="hello"} 27715838404 (25.81 GB)
telemt_user_octets_to_client{user="hello"} 205040268928 (190.96 GB)
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 90407.6 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1093461
telemt_connections_bad_total 28415
telemt_handshake_timeouts_total 20608
telemt_upstream_connect_attempt_total 81602
telemt_upstream_connect_success_total 81197
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 81602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33595
telemt_me_reconnect_success_total 13288
telemt_me_reader_eof_total 14659
telemt_me_idle_close_by_peer_total 14658
telemt_me_route_drop_no_conn_total 451959
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 887671
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2980
telemt_desync_full_logged_total 957
telemt_desync_suppressed_total 2023
telemt_desync_frames_bucket_total{bucket="1_2"} 711
telemt_desync_frames_bucket_total{bucket="3_10"} 1295
telemt_desync_frames_bucket_total{bucket="gt_10"} 974
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14168
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13279
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 880
telemt_user_connections_total{user="hello"} 950730
telemt_user_connections_current{user="hello"} 1278
telemt_user_octets_from_client{user="hello"} 13616315655 (12.68 GB)
telemt_user_octets_to_client{user="hello"} 367771103365 (342.51 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 90379.5 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645567
telemt_connections_bad_total 77100
telemt_handshake_timeouts_total 5524
telemt_upstream_connect_attempt_total 40272
telemt_upstream_connect_success_total 39736
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 40272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51193
telemt_me_reconnect_success_total 18709
telemt_me_reader_eof_total 20401
telemt_me_idle_close_by_peer_total 20399
telemt_me_route_drop_no_conn_total 202103
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 510634
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2304
telemt_desync_full_logged_total 640
telemt_desync_suppressed_total 1664
telemt_desync_frames_bucket_total{bucket="1_2"} 817
telemt_desync_frames_bucket_total{bucket="3_10"} 911
telemt_desync_frames_bucket_total{bucket="gt_10"} 576
telemt_pool_swap_total 45
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20044
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18701
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1335
telemt_user_connections_total{user="hello"} 527280
telemt_user_connections_current{user="hello"} 1202
telemt_user_octets_from_client{user="hello"} 10504572432 (9.78 GB)
telemt_user_octets_to_client{user="hello"} 244090055712 (227.33 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 90541.3 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 927388
telemt_connections_bad_total 61578
telemt_handshake_timeouts_total 8982
telemt_upstream_connect_attempt_total 17971
telemt_upstream_connect_success_total 17869
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 17971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24607
telemt_me_reconnect_success_total 13332
telemt_me_reader_eof_total 14492
telemt_me_idle_close_by_peer_total 14490
telemt_me_route_drop_no_conn_total 663158
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 941199
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1860
telemt_desync_full_logged_total 647
telemt_desync_suppressed_total 1213
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 75
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13909
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13318
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 804236
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 12313369204 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 348405696056 (324.48 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 38307.7 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257203
telemt_connections_bad_total 33951
telemt_handshake_timeouts_total 6538
telemt_upstream_connect_attempt_total 16430
telemt_upstream_connect_success_total 16280
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 16430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 25770
telemt_me_reconnect_success_total 14182
telemt_me_reader_eof_total 14991
telemt_me_idle_close_by_peer_total 14991
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 62524
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197723
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 591
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 435
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14711
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14156
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 197672
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 19318486105 (17.99 GB)
telemt_user_octets_to_client{user="hello"} 165757329226 (154.37 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 70
```