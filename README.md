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

# Server Metrics 2026-03-18 03:14:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 116923.7 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1339805
telemt_connections_bad_total 10367
telemt_handshake_timeouts_total 33338
telemt_upstream_connect_attempt_total 25855
telemt_upstream_connect_success_total 25346
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 25855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34389
telemt_me_reconnect_success_total 17247
telemt_me_reader_eof_total 18716
telemt_me_idle_close_by_peer_total 18715
telemt_me_route_drop_no_conn_total 576964
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1233571
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7834
telemt_desync_full_logged_total 2328
telemt_desync_suppressed_total 5506
telemt_desync_frames_bucket_total{bucket="1_2"} 2079
telemt_desync_frames_bucket_total{bucket="3_10"} 2992
telemt_desync_frames_bucket_total{bucket="gt_10"} 2763
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 18039
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17225
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 792
telemt_user_connections_total{user="hello"} 1227785
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 24812471999 (23.11 GB)
telemt_user_octets_to_client{user="hello"} 436650612767 (406.66 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 117175.2 (32h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1417623
telemt_connections_bad_total 64616
telemt_handshake_timeouts_total 47579
telemt_upstream_connect_attempt_total 469068
telemt_upstream_connect_success_total 467474
telemt_upstream_connect_fail_total 1594
telemt_upstream_connect_attempts_per_request{bucket="1"} 469068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1594
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125421
telemt_me_reconnect_success_total 18699
telemt_me_reader_eof_total 20927
telemt_me_idle_close_by_peer_total 20914
telemt_me_route_drop_no_conn_total 365415
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 791996
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3692
telemt_desync_full_logged_total 1270
telemt_desync_suppressed_total 2422
telemt_desync_frames_bucket_total{bucket="1_2"} 726
telemt_desync_frames_bucket_total{bucket="3_10"} 1536
telemt_desync_frames_bucket_total{bucket="gt_10"} 1430
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 20310
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 18681
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1611
telemt_user_connections_total{user="hello"} 1234341
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 16560298597 (15.42 GB)
telemt_user_octets_to_client{user="hello"} 436440666694 (406.47 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 116951.2 (32h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 864149
telemt_connections_bad_total 61023
telemt_handshake_timeouts_total 24867
telemt_upstream_connect_attempt_total 27176
telemt_upstream_connect_success_total 27020
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 27176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 41862
telemt_me_reconnect_success_total 21167
telemt_me_reader_eof_total 23023
telemt_me_idle_close_by_peer_total 23016
telemt_me_route_drop_no_conn_total 338168
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726494
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2282
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1542
telemt_desync_frames_bucket_total{bucket="1_2"} 654
telemt_desync_frames_bucket_total{bucket="3_10"} 884
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 22098
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21155
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 931
telemt_user_connections_total{user="hello"} 724609
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 44259606464 (41.22 GB)
telemt_user_octets_to_client{user="hello"} 324318238004 (302.04 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 117010.8 (32h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1341179
telemt_connections_bad_total 62057
telemt_handshake_timeouts_total 23503
telemt_upstream_connect_attempt_total 90035
telemt_upstream_connect_success_total 87611
telemt_upstream_connect_fail_total 2424
telemt_upstream_connect_attempts_per_request{bucket="1"} 90035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2424
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37441
telemt_me_reconnect_success_total 17036
telemt_me_reader_eof_total 18741
telemt_me_idle_close_by_peer_total 18738
telemt_me_route_drop_no_conn_total 548132
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1088803
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4024
telemt_desync_full_logged_total 1332
telemt_desync_suppressed_total 2692
telemt_desync_frames_bucket_total{bucket="1_2"} 991
telemt_desync_frames_bucket_total{bucket="3_10"} 1679
telemt_desync_frames_bucket_total{bucket="gt_10"} 1354
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17994
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17016
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 958
telemt_user_connections_total{user="hello"} 1152169
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 17945757642 (16.71 GB)
telemt_user_octets_to_client{user="hello"} 547996465162 (510.36 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 116982.5 (32h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 899085
telemt_connections_bad_total 101368
telemt_handshake_timeouts_total 7102
telemt_upstream_connect_attempt_total 46899
telemt_upstream_connect_success_total 46261
telemt_upstream_connect_fail_total 638
telemt_upstream_connect_attempts_per_request{bucket="1"} 46899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 638
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 58932
telemt_me_reconnect_success_total 23968
telemt_me_reader_eof_total 25966
telemt_me_idle_close_by_peer_total 25963
telemt_me_route_drop_no_conn_total 287253
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728235
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3317
telemt_desync_full_logged_total 1001
telemt_desync_suppressed_total 2316
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1324
telemt_desync_frames_bucket_total{bucket="gt_10"} 964
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25438
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23960
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1470
telemt_user_connections_total{user="hello"} 744753
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 14278104144 (13.30 GB)
telemt_user_octets_to_client{user="hello"} 367227364824 (342.01 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 117143.4 (32h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1145197
telemt_connections_bad_total 126836
telemt_handshake_timeouts_total 10132
telemt_upstream_connect_attempt_total 23337
telemt_upstream_connect_success_total 23201
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 23337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11926
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28645
telemt_me_reconnect_success_total 17353
telemt_me_reader_eof_total 18813
telemt_me_idle_close_by_peer_total 18811
telemt_me_route_drop_no_conn_total 791500
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1121267
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2129
telemt_desync_full_logged_total 742
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 809
telemt_desync_frames_bucket_total{bucket="gt_10"} 852
telemt_pool_swap_total 105
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17977
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17339
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 624
telemt_user_connections_total{user="hello"} 936898
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 15028770776 (14.00 GB)
telemt_user_octets_to_client{user="hello"} 411405452832 (383.15 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 64910.6 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446996
telemt_connections_bad_total 45040
telemt_handshake_timeouts_total 11817
telemt_upstream_connect_attempt_total 23620
telemt_upstream_connect_success_total 23381
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 23620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31587
telemt_me_reconnect_success_total 19978
telemt_me_reader_eof_total 21118
telemt_me_idle_close_by_peer_total 21118
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 109977
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323971
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1406
telemt_desync_full_logged_total 458
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 536
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20558
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19936
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 323765
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 22772123653 (21.21 GB)
telemt_user_octets_to_client{user="hello"} 271253008042 (252.62 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 50
```