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

# Server Metrics 2026-03-17 18:03:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 83900.3 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1017040
telemt_connections_bad_total 6678
telemt_handshake_timeouts_total 28004
telemt_upstream_connect_attempt_total 19734
telemt_upstream_connect_success_total 19253
telemt_upstream_connect_fail_total 481
telemt_upstream_connect_attempts_per_request{bucket="1"} 19734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 481
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 29850
telemt_me_reconnect_success_total 12732
telemt_me_reader_eof_total 13871
telemt_me_idle_close_by_peer_total 13870
telemt_me_route_drop_no_conn_total 464494
telemt_me_route_drop_channel_closed_total 128
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 931097
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6184
telemt_desync_full_logged_total 1752
telemt_desync_suppressed_total 4432
telemt_desync_frames_bucket_total{bucket="1_2"} 1695
telemt_desync_frames_bucket_total{bucket="3_10"} 2385
telemt_desync_frames_bucket_total{bucket="gt_10"} 2104
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13447
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12710
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 715
telemt_user_connections_total{user="hello"} 925346
telemt_user_connections_current{user="hello"} 1090
telemt_user_octets_from_client{user="hello"} 14140034947 (13.17 GB)
telemt_user_octets_to_client{user="hello"} 320123791479 (298.14 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 84152.2 (23h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 916476
telemt_connections_bad_total 52955
telemt_handshake_timeouts_total 32611
telemt_upstream_connect_attempt_total 383357
telemt_upstream_connect_success_total 382549
telemt_upstream_connect_fail_total 803
telemt_upstream_connect_attempts_per_request{bucket="1"} 383352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 318802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26970
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36775
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 803
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 53962
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15380
telemt_me_idle_close_by_peer_total 15380
telemt_me_route_drop_no_conn_total 238988
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421672
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1575
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1074
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 687
telemt_desync_frames_bucket_total{bucket="gt_10"} 528
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14990
telemt_me_refill_failed_total 1258
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1425
telemt_user_connections_total{user="hello"} 786327
telemt_user_connections_current{user="hello"} 1787
telemt_user_octets_from_client{user="hello"} 10649772109 (9.92 GB)
telemt_user_octets_to_client{user="hello"} 210949451836 (196.46 GB)
telemt_user_msgs_from_client{user="hello"} 6217348
telemt_user_msgs_to_client{user="hello"} 26246478
telemt_user_unique_ips_current{user="hello"} 439
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 83928.0 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472654
telemt_connections_bad_total 16649
telemt_handshake_timeouts_total 20920
telemt_upstream_connect_attempt_total 20898
telemt_upstream_connect_success_total 20780
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37171
telemt_me_reconnect_success_total 16503
telemt_me_reader_eof_total 18051
telemt_me_idle_close_by_peer_total 18044
telemt_me_route_drop_no_conn_total 220254
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411848
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1166
telemt_desync_full_logged_total 350
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 17370
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16491
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 867
telemt_user_connections_total{user="hello"} 410062
telemt_user_connections_current{user="hello"} 1336
telemt_user_octets_from_client{user="hello"} 26047574652 (24.26 GB)
telemt_user_octets_to_client{user="hello"} 147889674036 (137.73 GB)
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 83987.6 (23h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 949479
telemt_connections_bad_total 23457
telemt_handshake_timeouts_total 18510
telemt_upstream_connect_attempt_total 80644
telemt_upstream_connect_success_total 80245
telemt_upstream_connect_fail_total 399
telemt_upstream_connect_attempts_per_request{bucket="1"} 80644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 333
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 399
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 32944
telemt_me_reconnect_success_total 12643
telemt_me_reader_eof_total 13963
telemt_me_idle_close_by_peer_total 13962
telemt_me_route_drop_no_conn_total 400312
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762182
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2429
telemt_desync_full_logged_total 778
telemt_desync_suppressed_total 1651
telemt_desync_frames_bucket_total{bucket="1_2"} 590
telemt_desync_frames_bucket_total{bucket="3_10"} 1081
telemt_desync_frames_bucket_total{bucket="gt_10"} 758
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13506
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12634
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 863
telemt_user_connections_total{user="hello"} 825279
telemt_user_connections_current{user="hello"} 1737
telemt_user_octets_from_client{user="hello"} 10182835083 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 282789423117 (263.37 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 83959.1 (23h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525668
telemt_connections_bad_total 75001
telemt_handshake_timeouts_total 4774
telemt_upstream_connect_attempt_total 39064
telemt_upstream_connect_success_total 38553
telemt_upstream_connect_fail_total 511
telemt_upstream_connect_attempts_per_request{bucket="1"} 39064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 511
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50311
telemt_me_reconnect_success_total 17831
telemt_me_reader_eof_total 19461
telemt_me_idle_close_by_peer_total 19459
telemt_me_route_drop_no_conn_total 154726
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398392
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1776
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 1326
telemt_desync_frames_bucket_total{bucket="1_2"} 704
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19145
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17823
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1314
telemt_user_connections_total{user="hello"} 415075
telemt_user_connections_current{user="hello"} 1502
telemt_user_octets_from_client{user="hello"} 7412107096 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 189643218552 (176.62 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 84121.5 (23h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857434
telemt_connections_bad_total 60838
telemt_handshake_timeouts_total 8180
telemt_upstream_connect_attempt_total 16863
telemt_upstream_connect_success_total 16769
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8680
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 23810
telemt_me_reconnect_success_total 12539
telemt_me_reader_eof_total 13646
telemt_me_idle_close_by_peer_total 13644
telemt_me_route_drop_no_conn_total 632444
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879029
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1599
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 1051
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 13104
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12525
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 565
telemt_user_connections_total{user="hello"} 742088
telemt_user_connections_current{user="hello"} 880
telemt_user_octets_from_client{user="hello"} 11268851876 (10.49 GB)
telemt_user_octets_to_client{user="hello"} 324194498256 (301.93 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 31887.3 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160299
telemt_connections_bad_total 18627
telemt_handshake_timeouts_total 5158
telemt_upstream_connect_attempt_total 14769
telemt_upstream_connect_success_total 14640
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 14769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24433
telemt_me_reconnect_success_total 12855
telemt_me_reader_eof_total 13614
telemt_me_idle_close_by_peer_total 13614
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 38452
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127145
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 249
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 13369
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12832
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 127099
telemt_user_connections_current{user="hello"} 1079
telemt_user_octets_from_client{user="hello"} 10959650457 (10.21 GB)
telemt_user_octets_to_client{user="hello"} 120782213506 (112.49 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 110
```