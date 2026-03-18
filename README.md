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

# Server Metrics 2026-03-18 07:48:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 133418.6 (37h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1856065
telemt_connections_bad_total 11807
telemt_handshake_timeouts_total 38367
telemt_upstream_connect_attempt_total 28930
telemt_upstream_connect_success_total 28405
telemt_upstream_connect_fail_total 525
telemt_upstream_connect_attempts_per_request{bucket="1"} 28930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 525
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 36622
telemt_me_reconnect_success_total 19455
telemt_me_reader_eof_total 21056
telemt_me_idle_close_by_peer_total 21055
telemt_me_route_drop_no_conn_total 674352
telemt_me_route_drop_channel_closed_total 198
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1474237
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8836
telemt_desync_full_logged_total 2686
telemt_desync_suppressed_total 6150
telemt_desync_frames_bucket_total{bucket="1_2"} 2277
telemt_desync_frames_bucket_total{bucket="3_10"} 3414
telemt_desync_frames_bucket_total{bucket="gt_10"} 3145
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20284
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19433
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 829
telemt_user_connections_total{user="hello"} 1468496
telemt_user_connections_current{user="hello"} 1280
telemt_user_octets_from_client{user="hello"} 33734408295 (31.42 GB)
telemt_user_octets_to_client{user="hello"} 519037492871 (483.39 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 133670.3 (37h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1951944
telemt_connections_bad_total 101217
telemt_handshake_timeouts_total 61047
telemt_upstream_connect_attempt_total 472410
telemt_upstream_connect_success_total 470758
telemt_upstream_connect_fail_total 1652
telemt_upstream_connect_attempts_per_request{bucket="1"} 472410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1652
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 412
telemt_me_reconnect_attempts_total 133194
telemt_me_reconnect_success_total 21179
telemt_me_reader_eof_total 23658
telemt_me_idle_close_by_peer_total 23645
telemt_me_route_drop_no_conn_total 577340
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1257316
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5816
telemt_desync_full_logged_total 2010
telemt_desync_suppressed_total 3806
telemt_desync_frames_bucket_total{bucket="1_2"} 1098
telemt_desync_frames_bucket_total{bucket="3_10"} 2354
telemt_desync_frames_bucket_total{bucket="gt_10"} 2364
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22984
telemt_me_refill_failed_total 3494
telemt_me_writer_restored_same_endpoint_total 21161
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1805
telemt_user_connections_total{user="hello"} 1699751
telemt_user_connections_current{user="hello"} 2759
telemt_user_octets_from_client{user="hello"} 28069273093 (26.14 GB)
telemt_user_octets_to_client{user="hello"} 666461137114 (620.69 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 854
telemt_user_unique_ips_recent_window{user="hello"} 386
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 133446.0 (37h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1468784
telemt_connections_bad_total 89382
telemt_handshake_timeouts_total 34422
telemt_upstream_connect_attempt_total 30141
telemt_upstream_connect_success_total 29973
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 30141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 43981
telemt_me_reconnect_success_total 23255
telemt_me_reader_eof_total 25246
telemt_me_idle_close_by_peer_total 25238
telemt_me_route_drop_no_conn_total 548085
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1069354
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3822
telemt_desync_full_logged_total 1291
telemt_desync_suppressed_total 2531
telemt_desync_frames_bucket_total{bucket="1_2"} 1051
telemt_desync_frames_bucket_total{bucket="3_10"} 1452
telemt_desync_frames_bucket_total{bucket="gt_10"} 1319
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24231
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 23243
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 976
telemt_user_connections_total{user="hello"} 1067341
telemt_user_connections_current{user="hello"} 1887
telemt_user_octets_from_client{user="hello"} 49961119136 (46.53 GB)
telemt_user_octets_to_client{user="hello"} 508395123808 (473.48 GB)
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 133505.3 (37h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1896397
telemt_connections_bad_total 87097
telemt_handshake_timeouts_total 33638
telemt_upstream_connect_attempt_total 93234
telemt_upstream_connect_success_total 90774
telemt_upstream_connect_fail_total 2460
telemt_upstream_connect_attempts_per_request{bucket="1"} 93234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2460
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 40872
telemt_me_reconnect_success_total 19344
telemt_me_reader_eof_total 21202
telemt_me_idle_close_by_peer_total 21199
telemt_me_route_drop_no_conn_total 938883
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1578196
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6232
telemt_desync_full_logged_total 1906
telemt_desync_suppressed_total 4326
telemt_desync_frames_bucket_total{bucket="1_2"} 1419
telemt_desync_frames_bucket_total{bucket="3_10"} 2560
telemt_desync_frames_bucket_total{bucket="gt_10"} 2253
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20380
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19324
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1036
telemt_user_connections_total{user="hello"} 1641309
telemt_user_connections_current{user="hello"} 2576
telemt_user_octets_from_client{user="hello"} 26533298254 (24.71 GB)
telemt_user_octets_to_client{user="hello"} 727954495294 (677.96 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 694
telemt_user_unique_ips_recent_window{user="hello"} 326
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 133477.2 (37h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1353676
telemt_connections_bad_total 119375
telemt_handshake_timeouts_total 15077
telemt_upstream_connect_attempt_total 50008
telemt_upstream_connect_success_total 49313
telemt_upstream_connect_fail_total 695
telemt_upstream_connect_attempts_per_request{bucket="1"} 50008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 695
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 67685
telemt_me_reconnect_success_total 26181
telemt_me_reader_eof_total 28470
telemt_me_idle_close_by_peer_total 28467
telemt_me_route_drop_no_conn_total 489218
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1119605
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4899
telemt_desync_full_logged_total 1508
telemt_desync_suppressed_total 3391
telemt_desync_frames_bucket_total{bucket="1_2"} 1263
telemt_desync_frames_bucket_total{bucket="3_10"} 1902
telemt_desync_frames_bucket_total{bucket="gt_10"} 1734
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27883
telemt_me_refill_failed_total 1291
telemt_me_writer_restored_same_endpoint_total 26173
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1702
telemt_user_connections_total{user="hello"} 1135921
telemt_user_connections_current{user="hello"} 2408
telemt_user_octets_from_client{user="hello"} 22343871948 (20.81 GB)
telemt_user_octets_to_client{user="hello"} 563579853048 (524.87 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 726
telemt_user_unique_ips_recent_window{user="hello"} 345
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 133638.8 (37h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1316858
telemt_connections_bad_total 135375
telemt_handshake_timeouts_total 11077
telemt_upstream_connect_attempt_total 26623
telemt_upstream_connect_success_total 26465
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 26623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 31128
telemt_me_reconnect_success_total 19821
telemt_me_reader_eof_total 21438
telemt_me_idle_close_by_peer_total 21435
telemt_me_route_drop_no_conn_total 868420
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1281989
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2541
telemt_desync_full_logged_total 894
telemt_desync_suppressed_total 1647
telemt_desync_frames_bucket_total{bucket="1_2"} 551
telemt_desync_frames_bucket_total{bucket="3_10"} 983
telemt_desync_frames_bucket_total{bucket="gt_10"} 1007
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20476
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19807
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 655
telemt_user_connections_total{user="hello"} 1090642
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 16866784744 (15.71 GB)
telemt_user_octets_to_client{user="hello"} 473864320212 (441.32 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 81405.3 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 777241
telemt_connections_bad_total 74707
telemt_handshake_timeouts_total 16387
telemt_upstream_connect_attempt_total 27236
telemt_upstream_connect_success_total 26945
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 27236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 35548
telemt_me_reconnect_success_total 22741
telemt_me_reader_eof_total 24046
telemt_me_idle_close_by_peer_total 24046
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 228986
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585656
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2392
telemt_desync_full_logged_total 821
telemt_desync_suppressed_total 1571
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 997
telemt_desync_frames_bucket_total{bucket="gt_10"} 990
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23389
telemt_me_refill_failed_total 396
telemt_me_writer_restored_same_endpoint_total 22694
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 648
telemt_user_connections_total{user="hello"} 585310
telemt_user_connections_current{user="hello"} 1777
telemt_user_octets_from_client{user="hello"} 29611349797 (27.58 GB)
telemt_user_octets_to_client{user="hello"} 420299714470 (391.43 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 234
```