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

# Server Metrics 2026-03-17 17:12:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 80837.2 (22h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 965213
telemt_connections_bad_total 6502
telemt_handshake_timeouts_total 27291
telemt_upstream_connect_attempt_total 19116
telemt_upstream_connect_success_total 18640
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 19116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29410
telemt_me_reconnect_success_total 12294
telemt_me_reader_eof_total 13408
telemt_me_idle_close_by_peer_total 13407
telemt_me_route_drop_no_conn_total 442864
telemt_me_route_drop_channel_closed_total 121
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 882282
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5892
telemt_desync_full_logged_total 1664
telemt_desync_suppressed_total 4228
telemt_desync_frames_bucket_total{bucket="1_2"} 1646
telemt_desync_frames_bucket_total{bucket="3_10"} 2276
telemt_desync_frames_bucket_total{bucket="gt_10"} 1970
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13000
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12272
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 706
telemt_user_connections_total{user="hello"} 876553
telemt_user_connections_current{user="hello"} 1216
telemt_user_octets_from_client{user="hello"} 13503656843 (12.58 GB)
telemt_user_octets_to_client{user="hello"} 296230583535 (275.89 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 81089.3 (22h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780406
telemt_connections_bad_total 47076
telemt_handshake_timeouts_total 30283
telemt_upstream_connect_attempt_total 280757
telemt_upstream_connect_success_total 280057
telemt_upstream_connect_fail_total 700
telemt_upstream_connect_attempts_per_request{bucket="1"} 280757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 231445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 700
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 48458
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15207
telemt_me_idle_close_by_peer_total 15207
telemt_me_route_drop_no_conn_total 225016
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405982
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1527
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 1044
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14818
telemt_me_refill_failed_total 1086
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1253
telemt_user_connections_total{user="hello"} 668302
telemt_user_connections_current{user="hello"} 2352
telemt_user_octets_from_client{user="hello"} 8809177049 (8.20 GB)
telemt_user_octets_to_client{user="hello"} 181229811655 (168.78 GB)
telemt_user_msgs_from_client{user="hello"} 4314765
telemt_user_msgs_to_client{user="hello"} 17798780
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 292
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 80865.7 (22h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396321
telemt_connections_bad_total 10626
telemt_handshake_timeouts_total 20422
telemt_upstream_connect_attempt_total 20385
telemt_upstream_connect_success_total 20272
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 20385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 36839
telemt_me_reconnect_success_total 16173
telemt_me_reader_eof_total 17693
telemt_me_idle_close_by_peer_total 17686
telemt_me_route_drop_no_conn_total 194893
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345844
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1005
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 699
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 441
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 17035
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16161
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 862
telemt_user_connections_total{user="hello"} 344006
telemt_user_connections_current{user="hello"} 1707
telemt_user_octets_from_client{user="hello"} 23503869424 (21.89 GB)
telemt_user_octets_to_client{user="hello"} 115526588180 (107.59 GB)
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 80924.7 (22h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 853413
telemt_connections_bad_total 17989
telemt_handshake_timeouts_total 16062
telemt_upstream_connect_attempt_total 80129
telemt_upstream_connect_success_total 79737
telemt_upstream_connect_fail_total 392
telemt_upstream_connect_attempts_per_request{bucket="1"} 80129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 319
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 392
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 32605
telemt_me_reconnect_success_total 12308
telemt_me_reader_eof_total 13602
telemt_me_idle_close_by_peer_total 13601
telemt_me_route_drop_no_conn_total 357461
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678951
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2168
telemt_desync_full_logged_total 707
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 672
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13159
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12299
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 851
telemt_user_connections_total{user="hello"} 742089
telemt_user_connections_current{user="hello"} 2429
telemt_user_octets_from_client{user="hello"} 8971347039 (8.36 GB)
telemt_user_octets_to_client{user="hello"} 233093593441 (217.09 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 80896.5 (22h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432696
telemt_connections_bad_total 69857
telemt_handshake_timeouts_total 4289
telemt_upstream_connect_attempt_total 38520
telemt_upstream_connect_success_total 38022
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 38520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48771
telemt_me_reconnect_success_total 17478
telemt_me_reader_eof_total 19051
telemt_me_idle_close_by_peer_total 19049
telemt_me_route_drop_no_conn_total 126306
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323327
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1454
telemt_desync_full_logged_total 346
telemt_desync_suppressed_total 1108
telemt_desync_frames_bucket_total{bucket="1_2"} 634
telemt_desync_frames_bucket_total{bucket="3_10"} 585
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18742
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17470
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1264
telemt_user_connections_total{user="hello"} 340032
telemt_user_connections_current{user="hello"} 1999
telemt_user_octets_from_client{user="hello"} 5499472880 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 148489893732 (138.29 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 81057.9 (22h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816883
telemt_connections_bad_total 60247
telemt_handshake_timeouts_total 7726
telemt_upstream_connect_attempt_total 16345
telemt_upstream_connect_success_total 16254
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 16345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 23448
telemt_me_reconnect_success_total 12180
telemt_me_reader_eof_total 13252
telemt_me_idle_close_by_peer_total 13250
telemt_me_route_drop_no_conn_total 614532
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 843581
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1441
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 934
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 563
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12735
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12166
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 706655
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 10325696228 (9.62 GB)
telemt_user_octets_to_client{user="hello"} 312987179728 (291.49 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 28824.7 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94135
telemt_connections_bad_total 6072
telemt_handshake_timeouts_total 661
telemt_upstream_connect_attempt_total 14131
telemt_upstream_connect_success_total 14013
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 14131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23978
telemt_me_reconnect_success_total 12403
telemt_me_reader_eof_total 13131
telemt_me_idle_close_by_peer_total 13131
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 24640
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81861
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 12910
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12383
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 507
telemt_user_connections_total{user="hello"} 81848
telemt_user_connections_current{user="hello"} 1301
telemt_user_octets_from_client{user="hello"} 3951075577 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 88776736198 (82.68 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 138
```