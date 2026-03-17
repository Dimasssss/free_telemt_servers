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

# Server Metrics 2026-03-17 15:20:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 74102.8 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 813105
telemt_connections_bad_total 6059
telemt_handshake_timeouts_total 23842
telemt_upstream_connect_attempt_total 17693
telemt_upstream_connect_success_total 17232
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 17693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 25906
telemt_me_reconnect_success_total 11202
telemt_me_reader_eof_total 12216
telemt_me_idle_close_by_peer_total 12215
telemt_me_route_drop_no_conn_total 340877
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738647
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5163
telemt_desync_full_logged_total 1430
telemt_desync_suppressed_total 3733
telemt_desync_frames_bucket_total{bucket="1_2"} 1499
telemt_desync_frames_bucket_total{bucket="3_10"} 2043
telemt_desync_frames_bucket_total{bucket="gt_10"} 1621
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11814
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11180
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 740489
telemt_user_connections_current{user="hello"} 1032
telemt_user_octets_from_client{user="hello"} 11949389319 (11.13 GB)
telemt_user_octets_to_client{user="hello"} 245624709215 (228.76 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 74354.1 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528859
telemt_connections_bad_total 31808
telemt_handshake_timeouts_total 26806
telemt_upstream_connect_attempt_total 94814
telemt_upstream_connect_success_total 94278
telemt_upstream_connect_fail_total 534
telemt_upstream_connect_attempts_per_request{bucket="1"} 94812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6845
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 534
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 38714
telemt_me_reconnect_success_total 13455
telemt_me_reader_eof_total 14798
telemt_me_idle_close_by_peer_total 14798
telemt_me_route_drop_no_conn_total 192899
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368552
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1479
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 1014
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14407
telemt_me_refill_failed_total 785
telemt_me_writer_restored_same_endpoint_total 13439
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 952
telemt_user_connections_total{user="hello"} 445541
telemt_user_connections_current{user="hello"} 793
telemt_user_octets_from_client{user="hello"} 4958006747 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 129520189561 (120.63 GB)
telemt_user_msgs_from_client{user="hello"} 1124015
telemt_user_msgs_to_client{user="hello"} 3926188
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 74130.1 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272784
telemt_connections_bad_total 7838
telemt_handshake_timeouts_total 18126
telemt_upstream_connect_attempt_total 19411
telemt_upstream_connect_success_total 19309
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 19411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 29319
telemt_me_reconnect_success_total 15530
telemt_me_reader_eof_total 16824
telemt_me_idle_close_by_peer_total 16821
telemt_me_route_drop_no_conn_total 128214
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232766
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16169
telemt_me_refill_failed_total 428
telemt_me_writer_restored_same_endpoint_total 15519
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 639
telemt_user_connections_total{user="hello"} 232626
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 18331483164 (17.07 GB)
telemt_user_octets_to_client{user="hello"} 57438287060 (53.49 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 74189.4 (20h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630415
telemt_connections_bad_total 8665
telemt_handshake_timeouts_total 13702
telemt_upstream_connect_attempt_total 20042
telemt_upstream_connect_success_total 19863
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 20041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 28107
telemt_me_reconnect_success_total 11948
telemt_me_reader_eof_total 13102
telemt_me_idle_close_by_peer_total 13101
telemt_me_route_drop_no_conn_total 252679
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539229
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1864
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 836
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12661
telemt_me_refill_failed_total 500
telemt_me_writer_restored_same_endpoint_total 11939
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 713
telemt_user_connections_total{user="hello"} 543184
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 6588729221 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 168929799142 (157.33 GB)
telemt_user_msgs_from_client{user="hello"} 26853
telemt_user_msgs_to_client{user="hello"} 143994
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 74161.2 (20h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293434
telemt_connections_bad_total 57463
telemt_handshake_timeouts_total 3670
telemt_upstream_connect_attempt_total 21393
telemt_upstream_connect_success_total 20919
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 21393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 42629
telemt_me_reconnect_success_total 16781
telemt_me_reader_eof_total 18178
telemt_me_idle_close_by_peer_total 18176
telemt_me_route_drop_no_conn_total 83132
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219949
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17868
telemt_me_refill_failed_total 803
telemt_me_writer_restored_same_endpoint_total 16773
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1087
telemt_user_connections_total{user="hello"} 220452
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 2742187239 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 80522597667 (74.99 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 74322.9 (20h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 711925
telemt_connections_bad_total 56757
telemt_handshake_timeouts_total 7008
telemt_upstream_connect_attempt_total 14984
telemt_upstream_connect_success_total 14902
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 14984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7575
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 21459
telemt_me_reconnect_success_total 11163
telemt_me_reader_eof_total 12153
telemt_me_idle_close_by_peer_total 12153
telemt_me_route_drop_no_conn_total 517745
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 722552
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1049
telemt_desync_full_logged_total 374
telemt_desync_suppressed_total 675
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 421
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11659
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11149
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 612093
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 9003706364 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 273924237440 (255.11 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 22089.4 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17107
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 11963
telemt_upstream_connect_success_total 11864
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 11963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 22131
telemt_me_reconnect_success_total 10572
telemt_me_reader_eof_total 11211
telemt_me_idle_close_by_peer_total 11211
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 6322
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16300
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 11040
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 10557
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 16398
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 497752593 (474.69 MB)
telemt_user_octets_to_client{user="hello"} 23754303726 (22.12 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```