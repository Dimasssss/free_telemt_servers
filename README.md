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

# Server Metrics 2026-03-17 16:16:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 77472.0 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 886989
telemt_connections_bad_total 6359
telemt_handshake_timeouts_total 25381
telemt_upstream_connect_attempt_total 18499
telemt_upstream_connect_success_total 18027
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 18499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 27732
telemt_me_reconnect_success_total 11835
telemt_me_reader_eof_total 12887
telemt_me_idle_close_by_peer_total 12886
telemt_me_route_drop_no_conn_total 408883
telemt_me_route_drop_channel_closed_total 98
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 814690
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5509
telemt_desync_full_logged_total 1525
telemt_desync_suppressed_total 3984
telemt_desync_frames_bucket_total{bucket="1_2"} 1584
telemt_desync_frames_bucket_total{bucket="3_10"} 2134
telemt_desync_frames_bucket_total{bucket="gt_10"} 1791
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12493
telemt_me_refill_failed_total 491
telemt_me_writer_restored_same_endpoint_total 11813
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 658
telemt_user_connections_total{user="hello"} 809130
telemt_user_connections_current{user="hello"} 1413
telemt_user_octets_from_client{user="hello"} 12686953475 (11.82 GB)
telemt_user_octets_to_client{user="hello"} 265912134795 (247.65 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 77724.1 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 596168
telemt_connections_bad_total 32457
telemt_handshake_timeouts_total 28811
telemt_upstream_connect_attempt_total 148244
telemt_upstream_connect_success_total 147660
telemt_upstream_connect_fail_total 581
telemt_upstream_connect_attempts_per_request{bucket="1"} 148241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 581
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 44292
telemt_me_reconnect_success_total 13529
telemt_me_reader_eof_total 15043
telemt_me_idle_close_by_peer_total 15043
telemt_me_route_drop_no_conn_total 198416
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378044
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1494
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 507
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14653
telemt_me_refill_failed_total 957
telemt_me_writer_restored_same_endpoint_total 13513
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1124
telemt_user_connections_total{user="hello"} 508166
telemt_user_connections_current{user="hello"} 907
telemt_user_octets_from_client{user="hello"} 5585724409 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 140242642768 (130.61 GB)
telemt_user_msgs_from_client{user="hello"} 1888565
telemt_user_msgs_to_client{user="hello"} 7099068
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 77499.6 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296070
telemt_connections_bad_total 7909
telemt_handshake_timeouts_total 19169
telemt_upstream_connect_attempt_total 19913
telemt_upstream_connect_success_total 19809
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 19913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 33746
telemt_me_reconnect_success_total 15859
telemt_me_reader_eof_total 17278
telemt_me_idle_close_by_peer_total 17275
telemt_me_route_drop_no_conn_total 141579
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253948
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 829
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16627
telemt_me_refill_failed_total 556
telemt_me_writer_restored_same_endpoint_total 15848
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 768
telemt_user_connections_total{user="hello"} 253795
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 19862567308 (18.50 GB)
telemt_user_octets_to_client{user="hello"} 60663776832 (56.50 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 77558.9 (21h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 711572
telemt_connections_bad_total 11397
telemt_handshake_timeouts_total 14927
telemt_upstream_connect_attempt_total 79706
telemt_upstream_connect_success_total 79318
telemt_upstream_connect_fail_total 388
telemt_upstream_connect_attempts_per_request{bucket="1"} 79706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 313
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 388
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 32315
telemt_me_reconnect_success_total 12023
telemt_me_reader_eof_total 13296
telemt_me_idle_close_by_peer_total 13295
telemt_me_route_drop_no_conn_total 264071
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552386
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1875
telemt_desync_full_logged_total 636
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 476
telemt_desync_frames_bucket_total{bucket="3_10"} 842
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12865
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12014
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 842
telemt_user_connections_total{user="hello"} 615536
telemt_user_connections_current{user="hello"} 902
telemt_user_octets_from_client{user="hello"} 7216622099 (6.72 GB)
telemt_user_octets_to_client{user="hello"} 181760609437 (169.28 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 77530.8 (21h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313463
telemt_connections_bad_total 58278
telemt_handshake_timeouts_total 3780
telemt_upstream_connect_attempt_total 21859
telemt_upstream_connect_success_total 21376
telemt_upstream_connect_fail_total 483
telemt_upstream_connect_attempts_per_request{bucket="1"} 21859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 483
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 47296
telemt_me_reconnect_success_total 17064
telemt_me_reader_eof_total 18597
telemt_me_idle_close_by_peer_total 18595
telemt_me_route_drop_no_conn_total 91228
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238257
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1146
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 18289
telemt_me_refill_failed_total 940
telemt_me_writer_restored_same_endpoint_total 17056
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1225
telemt_user_connections_total{user="hello"} 238841
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 2900087331 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 86654884471 (80.70 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 77692.5 (21h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 765065
telemt_connections_bad_total 60193
telemt_handshake_timeouts_total 7209
telemt_upstream_connect_attempt_total 15662
telemt_upstream_connect_success_total 15577
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 15662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 21958
telemt_me_reconnect_success_total 11654
telemt_me_reader_eof_total 12676
telemt_me_idle_close_by_peer_total 12674
telemt_me_route_drop_no_conn_total 569260
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 784255
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1230
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 795
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 462
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12165
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11640
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 511
telemt_user_connections_total{user="hello"} 659418
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 9537503408 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 295881675416 (275.56 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 25459.0 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20147
telemt_connections_bad_total 91
telemt_handshake_timeouts_total 315
telemt_upstream_connect_attempt_total 13557
telemt_upstream_connect_success_total 13440
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 13557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23535
telemt_me_reconnect_success_total 11963
telemt_me_reader_eof_total 12661
telemt_me_idle_close_by_peer_total 12661
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 9903
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19247
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 12459
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 11943
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 19301
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 662884569 (632.18 MB)
telemt_user_octets_to_client{user="hello"} 26599259434 (24.77 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 21
```