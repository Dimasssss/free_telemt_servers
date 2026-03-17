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

# Server Metrics 2026-03-17 21:32:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 96442.2 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1184611
telemt_connections_bad_total 8636
telemt_handshake_timeouts_total 31543
telemt_upstream_connect_attempt_total 21920
telemt_upstream_connect_success_total 21429
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 21920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31422
telemt_me_reconnect_success_total 14292
telemt_me_reader_eof_total 15529
telemt_me_idle_close_by_peer_total 15528
telemt_me_route_drop_no_conn_total 528831
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1085985
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7191
telemt_desync_full_logged_total 2073
telemt_desync_suppressed_total 5118
telemt_desync_frames_bucket_total{bucket="1_2"} 1927
telemt_desync_frames_bucket_total{bucket="3_10"} 2725
telemt_desync_frames_bucket_total{bucket="gt_10"} 2539
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15037
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14270
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 745
telemt_user_connections_total{user="hello"} 1080218
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 19236553487 (17.92 GB)
telemt_user_octets_to_client{user="hello"} 383451207327 (357.12 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 96693.4 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1237276
telemt_connections_bad_total 59606
telemt_handshake_timeouts_total 44144
telemt_upstream_connect_attempt_total 457403
telemt_upstream_connect_success_total 456512
telemt_upstream_connect_fail_total 891
telemt_upstream_connect_attempts_per_request{bucket="1"} 457403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 891
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57824
telemt_me_reconnect_success_total 14671
telemt_me_reader_eof_total 16644
telemt_me_idle_close_by_peer_total 16644
telemt_me_route_drop_no_conn_total 315472
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632556
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2792
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 1896
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 1163
telemt_desync_frames_bucket_total{bucket="gt_10"} 1103
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 16201
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14655
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1530
telemt_user_connections_total{user="hello"} 1068985
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 14783179166 (13.77 GB)
telemt_user_octets_to_client{user="hello"} 357224288042 (332.69 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 96469.5 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 698937
telemt_connections_bad_total 40696
telemt_handshake_timeouts_total 22644
telemt_upstream_connect_attempt_total 23019
telemt_upstream_connect_success_total 22884
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12314
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38671
telemt_me_reconnect_success_total 17995
telemt_me_reader_eof_total 19639
telemt_me_idle_close_by_peer_total 19632
telemt_me_route_drop_no_conn_total 294356
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602203
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1931
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1342
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 763
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18888
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17983
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 893
telemt_user_connections_total{user="hello"} 600475
telemt_user_connections_current{user="hello"} 853
telemt_user_octets_from_client{user="hello"} 30413626216 (28.32 GB)
telemt_user_octets_to_client{user="hello"} 260481121148 (242.59 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 96528.9 (26h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1200057
telemt_connections_bad_total 38027
telemt_handshake_timeouts_total 21293
telemt_upstream_connect_attempt_total 82674
telemt_upstream_connect_success_total 82249
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 82674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34351
telemt_me_reconnect_success_total 14032
telemt_me_reader_eof_total 15488
telemt_me_idle_close_by_peer_total 15486
telemt_me_route_drop_no_conn_total 497697
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 981069
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3413
telemt_desync_full_logged_total 1095
telemt_desync_suppressed_total 2318
telemt_desync_frames_bucket_total{bucket="1_2"} 846
telemt_desync_frames_bucket_total{bucket="3_10"} 1433
telemt_desync_frames_bucket_total{bucket="gt_10"} 1134
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 14930
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14023
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 898
telemt_user_connections_total{user="hello"} 1043579
telemt_user_connections_current{user="hello"} 993
telemt_user_octets_from_client{user="hello"} 15655173227 (14.58 GB)
telemt_user_octets_to_client{user="hello"} 444872444681 (414.32 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 96500.9 (26h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755163
telemt_connections_bad_total 91317
telemt_handshake_timeouts_total 6343
telemt_upstream_connect_attempt_total 41517
telemt_upstream_connect_success_total 40960
telemt_upstream_connect_fail_total 557
telemt_upstream_connect_attempts_per_request{bucket="1"} 41517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 397
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 557
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 52115
telemt_me_reconnect_success_total 19628
telemt_me_reader_eof_total 21358
telemt_me_idle_close_by_peer_total 21356
telemt_me_route_drop_no_conn_total 236916
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601118
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2747
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 1945
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1105
telemt_desync_frames_bucket_total{bucket="gt_10"} 754
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20976
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19620
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1348
telemt_user_connections_total{user="hello"} 617732
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 11993312016 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 303451298964 (282.61 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 96661.8 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 993641
telemt_connections_bad_total 74143
telemt_handshake_timeouts_total 9371
telemt_upstream_connect_attempt_total 19111
telemt_upstream_connect_success_total 18999
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 19111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9814
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25435
telemt_me_reconnect_success_total 14157
telemt_me_reader_eof_total 15382
telemt_me_idle_close_by_peer_total 15380
telemt_me_route_drop_no_conn_total 684556
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 985569
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2035
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1324
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 771
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 82
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 14745
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14143
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 848601
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 13204945936 (12.30 GB)
telemt_user_octets_to_client{user="hello"} 363340403576 (338.39 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 44429.0 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331419
telemt_connections_bad_total 42587
telemt_handshake_timeouts_total 10340
telemt_upstream_connect_attempt_total 17793
telemt_upstream_connect_success_total 17628
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 17792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26818
telemt_me_reconnect_success_total 15224
telemt_me_reader_eof_total 16091
telemt_me_idle_close_by_peer_total 16091
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 81362
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253070
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 815
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 577
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15765
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15196
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 541
telemt_user_connections_total{user="hello"} 253012
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 21012849765 (19.57 GB)
telemt_user_octets_to_client{user="hello"} 211927005258 (197.37 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 63
```