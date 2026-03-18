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

# Server Metrics 2026-03-18 00:56:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 108673.8 (30h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1272293
telemt_connections_bad_total 9599
telemt_handshake_timeouts_total 32465
telemt_upstream_connect_attempt_total 24302
telemt_upstream_connect_success_total 23803
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 24302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33237
telemt_me_reconnect_success_total 16100
telemt_me_reader_eof_total 17480
telemt_me_idle_close_by_peer_total 17479
telemt_me_route_drop_no_conn_total 559228
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1169900
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7548
telemt_desync_full_logged_total 2215
telemt_desync_suppressed_total 5333
telemt_desync_frames_bucket_total{bucket="1_2"} 2021
telemt_desync_frames_bucket_total{bucket="3_10"} 2861
telemt_desync_frames_bucket_total{bucket="gt_10"} 2666
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 16872
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16078
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 772
telemt_user_connections_total{user="hello"} 1164113
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 22785428503 (21.22 GB)
telemt_user_octets_to_client{user="hello"} 416887846435 (388.26 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 108925.3 (30h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1349874
telemt_connections_bad_total 62106
telemt_handshake_timeouts_total 46258
telemt_upstream_connect_attempt_total 466833
telemt_upstream_connect_success_total 465287
telemt_upstream_connect_fail_total 1546
telemt_upstream_connect_attempts_per_request{bucket="1"} 466833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1546
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122382
telemt_me_reconnect_success_total 16952
telemt_me_reader_eof_total 19069
telemt_me_idle_close_by_peer_total 19059
telemt_me_route_drop_no_conn_total 348680
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 730517
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3354
telemt_desync_full_logged_total 1118
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 656
telemt_desync_frames_bucket_total{bucket="3_10"} 1383
telemt_desync_frames_bucket_total{bucket="gt_10"} 1315
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 18498
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16934
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1546
telemt_user_connections_total{user="hello"} 1172866
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 15882294421 (14.79 GB)
telemt_user_octets_to_client{user="hello"} 401648035370 (374.06 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 108701.3 (30h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 801005
telemt_connections_bad_total 53151
telemt_handshake_timeouts_total 24164
telemt_upstream_connect_attempt_total 25508
telemt_upstream_connect_success_total 25363
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 25508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40589
telemt_me_reconnect_success_total 19904
telemt_me_reader_eof_total 21679
telemt_me_idle_close_by_peer_total 21672
telemt_me_route_drop_no_conn_total 322716
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680046
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2170
telemt_desync_full_logged_total 706
telemt_desync_suppressed_total 1464
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 837
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 20821
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19892
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 917
telemt_user_connections_total{user="hello"} 678180
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 35299076128 (32.87 GB)
telemt_user_octets_to_client{user="hello"} 299674803960 (279.09 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 108760.7 (30h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1286279
telemt_connections_bad_total 53965
telemt_handshake_timeouts_total 21864
telemt_upstream_connect_attempt_total 86621
telemt_upstream_connect_success_total 85199
telemt_upstream_connect_fail_total 1422
telemt_upstream_connect_attempts_per_request{bucket="1"} 86621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1422
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36134
telemt_me_reconnect_success_total 15772
telemt_me_reader_eof_total 17399
telemt_me_idle_close_by_peer_total 17397
telemt_me_route_drop_no_conn_total 525772
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1046855
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3942
telemt_desync_full_logged_total 1304
telemt_desync_suppressed_total 2638
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1657
telemt_desync_frames_bucket_total{bucket="gt_10"} 1319
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 16703
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15762
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 931
telemt_user_connections_total{user="hello"} 1109974
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 17430254611 (16.23 GB)
telemt_user_octets_to_client{user="hello"} 522584439194 (486.69 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 108732.7 (30h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 844873
telemt_connections_bad_total 99379
telemt_handshake_timeouts_total 6771
telemt_upstream_connect_attempt_total 44747
telemt_upstream_connect_success_total 44133
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 44747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57191
telemt_me_reconnect_success_total 22232
telemt_me_reader_eof_total 24147
telemt_me_idle_close_by_peer_total 24145
telemt_me_route_drop_no_conn_total 268080
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 679961
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3180
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23682
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22224
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1450
telemt_user_connections_total{user="hello"} 696568
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 13610134936 (12.68 GB)
telemt_user_octets_to_client{user="hello"} 348863750432 (324.90 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 108893.7 (30h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1087613
telemt_connections_bad_total 106898
telemt_handshake_timeouts_total 9655
telemt_upstream_connect_attempt_total 21633
telemt_upstream_connect_success_total 21514
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 21633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27388
telemt_me_reconnect_success_total 16105
telemt_me_reader_eof_total 17476
telemt_me_idle_close_by_peer_total 17474
telemt_me_route_drop_no_conn_total 735861
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1054970
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
telemt_pool_swap_total 95
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16716
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16091
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 901023
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 14593849580 (13.59 GB)
telemt_user_octets_to_client{user="hello"} 384003187576 (357.63 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 56660.8 (15h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398568
telemt_connections_bad_total 44686
telemt_handshake_timeouts_total 10880
telemt_upstream_connect_attempt_total 21277
telemt_upstream_connect_success_total 21083
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 21277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29713
telemt_me_reconnect_success_total 18113
telemt_me_reader_eof_total 19143
telemt_me_idle_close_by_peer_total 19143
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 99541
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293308
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1138
telemt_desync_full_logged_total 355
telemt_desync_suppressed_total 783
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 428
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18680
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18082
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 567
telemt_user_connections_total{user="hello"} 293248
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 22269183637 (20.74 GB)
telemt_user_octets_to_client{user="hello"} 243771164174 (227.03 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 20
```