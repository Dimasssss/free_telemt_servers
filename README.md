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

# Server Metrics 2026-03-18 07:54:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 133724.0 (37h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1873628
telemt_connections_bad_total 11809
telemt_handshake_timeouts_total 38625
telemt_upstream_connect_attempt_total 28990
telemt_upstream_connect_success_total 28465
telemt_upstream_connect_fail_total 525
telemt_upstream_connect_attempts_per_request{bucket="1"} 28990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 525
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 36681
telemt_me_reconnect_success_total 19511
telemt_me_reader_eof_total 21115
telemt_me_idle_close_by_peer_total 21114
telemt_me_route_drop_no_conn_total 679722
telemt_me_route_drop_channel_closed_total 201
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1481552
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8891
telemt_desync_full_logged_total 2704
telemt_desync_suppressed_total 6187
telemt_desync_frames_bucket_total{bucket="1_2"} 2299
telemt_desync_frames_bucket_total{bucket="3_10"} 3428
telemt_desync_frames_bucket_total{bucket="gt_10"} 3164
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20343
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19489
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 832
telemt_user_connections_total{user="hello"} 1475798
telemt_user_connections_current{user="hello"} 1279
telemt_user_octets_from_client{user="hello"} 33938365219 (31.61 GB)
telemt_user_octets_to_client{user="hello"} 520584344403 (484.83 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 133975.8 (37h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1971281
telemt_connections_bad_total 102954
telemt_handshake_timeouts_total 61630
telemt_upstream_connect_attempt_total 472446
telemt_upstream_connect_success_total 470794
telemt_upstream_connect_fail_total 1652
telemt_upstream_connect_attempts_per_request{bucket="1"} 472446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1652
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 412
telemt_me_reconnect_attempts_total 133230
telemt_me_reconnect_success_total 21214
telemt_me_reader_eof_total 23693
telemt_me_idle_close_by_peer_total 23680
telemt_me_route_drop_no_conn_total 588120
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1273620
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5866
telemt_desync_full_logged_total 2031
telemt_desync_suppressed_total 3835
telemt_desync_frames_bucket_total{bucket="1_2"} 1102
telemt_desync_frames_bucket_total{bucket="3_10"} 2375
telemt_desync_frames_bucket_total{bucket="gt_10"} 2389
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 23019
telemt_me_refill_failed_total 3494
telemt_me_writer_restored_same_endpoint_total 21196
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1805
telemt_user_connections_total{user="hello"} 1716037
telemt_user_connections_current{user="hello"} 2827
telemt_user_octets_from_client{user="hello"} 28655917277 (26.69 GB)
telemt_user_octets_to_client{user="hello"} 674764762718 (628.42 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 858
telemt_user_unique_ips_recent_window{user="hello"} 398
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 133751.8 (37h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1482309
telemt_connections_bad_total 90426
telemt_handshake_timeouts_total 34811
telemt_upstream_connect_attempt_total 30207
telemt_upstream_connect_success_total 30039
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 30207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16029
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 44047
telemt_me_reconnect_success_total 23321
telemt_me_reader_eof_total 25311
telemt_me_idle_close_by_peer_total 25303
telemt_me_route_drop_no_conn_total 555347
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1080234
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3906
telemt_desync_full_logged_total 1311
telemt_desync_suppressed_total 2595
telemt_desync_frames_bucket_total{bucket="1_2"} 1070
telemt_desync_frames_bucket_total{bucket="3_10"} 1493
telemt_desync_frames_bucket_total{bucket="gt_10"} 1343
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24297
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 23309
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 976
telemt_user_connections_total{user="hello"} 1078217
telemt_user_connections_current{user="hello"} 1719
telemt_user_octets_from_client{user="hello"} 50114910572 (46.67 GB)
telemt_user_octets_to_client{user="hello"} 513400272552 (478.14 GB)
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 133810.9 (37h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1913437
telemt_connections_bad_total 87772
telemt_handshake_timeouts_total 34777
telemt_upstream_connect_attempt_total 93282
telemt_upstream_connect_success_total 90821
telemt_upstream_connect_fail_total 2461
telemt_upstream_connect_attempts_per_request{bucket="1"} 93282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2461
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 40920
telemt_me_reconnect_success_total 19388
telemt_me_reader_eof_total 21245
telemt_me_idle_close_by_peer_total 21242
telemt_me_route_drop_no_conn_total 947095
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1592413
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6280
telemt_desync_full_logged_total 1924
telemt_desync_suppressed_total 4356
telemt_desync_frames_bucket_total{bucket="1_2"} 1428
telemt_desync_frames_bucket_total{bucket="3_10"} 2576
telemt_desync_frames_bucket_total{bucket="gt_10"} 2276
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20424
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19368
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1036
telemt_user_connections_total{user="hello"} 1655513
telemt_user_connections_current{user="hello"} 2627
telemt_user_octets_from_client{user="hello"} 26668568210 (24.84 GB)
telemt_user_octets_to_client{user="hello"} 732179939774 (681.90 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 730
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 133782.8 (37h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1369461
telemt_connections_bad_total 120402
telemt_handshake_timeouts_total 15482
telemt_upstream_connect_attempt_total 50020
telemt_upstream_connect_success_total 49325
telemt_upstream_connect_fail_total 695
telemt_upstream_connect_attempts_per_request{bucket="1"} 50020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 695
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 67697
telemt_me_reconnect_success_total 26193
telemt_me_reader_eof_total 28481
telemt_me_idle_close_by_peer_total 28478
telemt_me_route_drop_no_conn_total 504610
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1132853
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4952
telemt_desync_full_logged_total 1530
telemt_desync_suppressed_total 3422
telemt_desync_frames_bucket_total{bucket="1_2"} 1270
telemt_desync_frames_bucket_total{bucket="3_10"} 1929
telemt_desync_frames_bucket_total{bucket="gt_10"} 1753
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27895
telemt_me_refill_failed_total 1291
telemt_me_writer_restored_same_endpoint_total 26185
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1702
telemt_user_connections_total{user="hello"} 1149149
telemt_user_connections_current{user="hello"} 2322
telemt_user_octets_from_client{user="hello"} 22503936832 (20.96 GB)
telemt_user_octets_to_client{user="hello"} 569101109048 (530.02 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 713
telemt_user_unique_ips_recent_window{user="hello"} 331
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 133944.1 (37h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1324867
telemt_connections_bad_total 136306
telemt_handshake_timeouts_total 11091
telemt_upstream_connect_attempt_total 26666
telemt_upstream_connect_success_total 26508
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 26666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 31171
telemt_me_reconnect_success_total 19864
telemt_me_reader_eof_total 21481
telemt_me_idle_close_by_peer_total 21478
telemt_me_route_drop_no_conn_total 878131
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1288690
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2553
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 1657
telemt_desync_frames_bucket_total{bucket="1_2"} 551
telemt_desync_frames_bucket_total{bucket="3_10"} 993
telemt_desync_frames_bucket_total{bucket="gt_10"} 1009
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20519
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19850
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 655
telemt_user_connections_total{user="hello"} 1097341
telemt_user_connections_current{user="hello"} 1014
telemt_user_octets_from_client{user="hello"} 16908703220 (15.75 GB)
telemt_user_octets_to_client{user="hello"} 474471546988 (441.89 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 81711.0 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788741
telemt_connections_bad_total 76950
telemt_handshake_timeouts_total 16785
telemt_upstream_connect_attempt_total 27268
telemt_upstream_connect_success_total 26977
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 27268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 35580
telemt_me_reconnect_success_total 22773
telemt_me_reader_eof_total 24077
telemt_me_idle_close_by_peer_total 24077
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 234475
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 593861
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2416
telemt_desync_full_logged_total 830
telemt_desync_suppressed_total 1586
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 1004
telemt_desync_frames_bucket_total{bucket="gt_10"} 999
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23421
telemt_me_refill_failed_total 396
telemt_me_writer_restored_same_endpoint_total 22726
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 648
telemt_user_connections_total{user="hello"} 593510
telemt_user_connections_current{user="hello"} 1807
telemt_user_octets_from_client{user="hello"} 29759890405 (27.72 GB)
telemt_user_octets_to_client{user="hello"} 425957438038 (396.70 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 234
```