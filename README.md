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

# Server Metrics 2026-03-18 16:34:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4163.3 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134814
telemt_connections_bad_total 11204
telemt_handshake_timeouts_total 4697
telemt_upstream_connect_attempt_total 563
telemt_upstream_connect_success_total 563
telemt_upstream_connect_attempts_per_request{bucket="1"} 563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 321
telemt_me_reconnect_success_total 319
telemt_me_reader_eof_total 321
telemt_me_idle_close_by_peer_total 321
telemt_me_route_drop_no_conn_total 77266
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109912
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 660
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 469
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 332
telemt_me_writer_restored_same_endpoint_total 308
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 109864
telemt_user_connections_current{user="hello"} 1554
telemt_user_octets_from_client{user="hello"} 1493403864 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 38531069636 (35.88 GB)
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 8991.3 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 947123
telemt_connections_bad_total 60465
telemt_connections_current 4069
telemt_connections_me_current 4069
telemt_handshake_timeouts_total 14925
telemt_upstream_connect_attempt_total 1646
telemt_upstream_connect_success_total 1637
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1175
telemt_me_reconnect_success_total 1165
telemt_me_reader_eof_total 1106
telemt_me_idle_close_by_peer_total 1105
telemt_me_route_drop_no_conn_total 972142
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 825458
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2288
telemt_desync_full_logged_total 709
telemt_desync_suppressed_total 1579
telemt_desync_frames_bucket_total{bucket="1_2"} 455
telemt_desync_frames_bucket_total{bucket="3_10"} 925
telemt_desync_frames_bucket_total{bucket="gt_10"} 908
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1097
telemt_me_writer_restored_same_endpoint_total 1163
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 824625
telemt_user_connections_current{user="hello"} 4069
telemt_user_octets_from_client{user="hello"} 10166977140 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 229181436540 (213.44 GB)
telemt_user_unique_ips_current{user="hello"} 1155
telemt_user_unique_ips_recent_window{user="hello"} 586
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 8920.0 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627968
telemt_connections_bad_total 42954
telemt_connections_current 3246
telemt_connections_me_current 3246
telemt_handshake_timeouts_total 13799
telemt_upstream_connect_attempt_total 1254
telemt_upstream_connect_success_total 1249
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 786
telemt_me_reconnect_success_total 776
telemt_me_reader_eof_total 813
telemt_me_idle_close_by_peer_total 813
telemt_me_route_drop_no_conn_total 325067
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531447
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2147
telemt_desync_full_logged_total 616
telemt_desync_suppressed_total 1531
telemt_desync_frames_bucket_total{bucket="1_2"} 476
telemt_desync_frames_bucket_total{bucket="3_10"} 815
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 801
telemt_me_writer_restored_same_endpoint_total 759
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 531162
telemt_user_connections_current{user="hello"} 3246
telemt_user_octets_from_client{user="hello"} 9847472748 (9.17 GB)
telemt_user_octets_to_client{user="hello"} 210265391144 (195.82 GB)
telemt_user_unique_ips_current{user="hello"} 991
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 9634.3 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872039
telemt_connections_bad_total 16533
telemt_connections_current 2639
telemt_connections_me_current 2639
telemt_handshake_timeouts_total 11461
telemt_upstream_connect_attempt_total 1552
telemt_upstream_connect_success_total 1540
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1029
telemt_me_reconnect_success_total 1019
telemt_me_reader_eof_total 1025
telemt_me_idle_close_by_peer_total 1024
telemt_me_route_drop_no_conn_total 1410060
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 785972
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3003
telemt_desync_full_logged_total 770
telemt_desync_suppressed_total 2233
telemt_desync_frames_bucket_total{bucket="1_2"} 678
telemt_desync_frames_bucket_total{bucket="3_10"} 1362
telemt_desync_frames_bucket_total{bucket="gt_10"} 963
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1011
telemt_me_writer_restored_same_endpoint_total 1008
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 785937
telemt_user_connections_current{user="hello"} 2639
telemt_user_octets_from_client{user="hello"} 7299363344 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 147286000984 (137.17 GB)
telemt_user_unique_ips_current{user="hello"} 823
telemt_user_unique_ips_recent_window{user="hello"} 441
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4149.0 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334542
telemt_connections_bad_total 70692
telemt_handshake_timeouts_total 3399
telemt_upstream_connect_attempt_total 781
telemt_upstream_connect_success_total 754
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 1506
telemt_me_reconnect_success_total 508
telemt_me_reader_eof_total 517
telemt_me_idle_close_by_peer_total 517
telemt_me_route_drop_no_conn_total 136889
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234171
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 810
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 532
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 420
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 540
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 482
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 233851
telemt_user_connections_current{user="hello"} 3063
telemt_user_octets_from_client{user="hello"} 3564595464 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 88926193292 (82.82 GB)
telemt_user_unique_ips_current{user="hello"} 1016
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 9083.2 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172500
telemt_connections_bad_total 7239
telemt_connections_current 894
telemt_connections_me_current 894
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1595
telemt_upstream_connect_attempt_total 5775
telemt_upstream_connect_success_total 5764
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 5775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 330901
telemt_me_reconnect_success_total 1440
telemt_me_reader_eof_total 1390
telemt_me_idle_close_by_peer_total 1390
telemt_me_route_drop_no_conn_total 95529
telemt_me_route_drop_channel_closed_total 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151806
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 343
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1373
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1429
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 155534
telemt_user_connections_current{user="hello"} 894
telemt_user_octets_from_client{user="hello"} 2345209393 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 33367337293 (31.08 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 8153.5 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497242
telemt_connections_bad_total 18512
telemt_connections_current 2572
telemt_connections_me_current 2572
telemt_handshake_timeouts_total 8890
telemt_upstream_connect_attempt_total 1535
telemt_upstream_connect_success_total 1535
telemt_upstream_connect_attempts_per_request{bucket="1"} 1535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 16594
telemt_me_reconnect_success_total 1084
telemt_me_reader_eof_total 1039
telemt_me_idle_close_by_peer_total 1039
telemt_me_route_drop_no_conn_total 341174
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430133
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1290
telemt_desync_full_logged_total 472
telemt_desync_suppressed_total 818
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 571
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1040
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1023
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 429221
telemt_user_connections_current{user="hello"} 2572
telemt_user_octets_from_client{user="hello"} 7215380040 (6.72 GB)
telemt_user_octets_to_client{user="hello"} 188298719216 (175.37 GB)
telemt_user_unique_ips_current{user="hello"} 823
telemt_user_unique_ips_recent_window{user="hello"} 346
```