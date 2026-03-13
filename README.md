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

# Server Metrics 2026-03-13 18:39:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 126349.8 (35h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 534397
telemt_connections_bad_total 10708
telemt_handshake_timeouts_total 12204
telemt_upstream_connect_attempt_total 31719
telemt_upstream_connect_success_total 31564
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 31719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3498
telemt_me_reconnect_attempts_total 29878
telemt_me_reconnect_success_total 25236
telemt_me_reader_eof_total 26957
telemt_me_idle_close_by_peer_total 26956
telemt_me_route_drop_no_conn_total 175118
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 463234
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1475
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 543
telemt_desync_frames_bucket_total{bucket="gt_10"} 609
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 25661
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25220
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 462803
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 8505957064 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 219926761040 (204.82 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 126242.5 (35h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265628
telemt_connections_bad_total 1954
telemt_handshake_timeouts_total 1843
telemt_upstream_connect_attempt_total 117800
telemt_upstream_connect_success_total 116938
telemt_upstream_connect_fail_total 862
telemt_upstream_connect_attempts_per_request{bucket="1"} 117800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1815
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 862
telemt_me_keepalive_timeout_total 1536
telemt_me_reconnect_attempts_total 131456
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 30081
telemt_me_idle_close_by_peer_total 30081
telemt_me_route_drop_no_conn_total 83119
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167315
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29551
telemt_me_refill_failed_total 3290
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3518
telemt_user_connections_total{user="hello"} 251693
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 2616366744 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 76913354204 (71.63 GB)
telemt_user_msgs_from_client{user="hello"} 1335194
telemt_user_msgs_to_client{user="hello"} 7631278
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 126206.4 (35h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313478
telemt_connections_bad_total 2630
telemt_handshake_timeouts_total 19853
telemt_upstream_connect_attempt_total 33619
telemt_upstream_connect_success_total 33614
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 33619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17999
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2705
telemt_me_reconnect_attempts_total 28486
telemt_me_reconnect_success_total 27253
telemt_me_reader_eof_total 29233
telemt_me_idle_close_by_peer_total 29233
telemt_me_route_drop_no_conn_total 111548
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280010
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 27557
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27233
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 279919
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 10357806052 (9.65 GB)
telemt_user_octets_to_client{user="hello"} 115731357388 (107.78 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 126181.9 (35h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418198
telemt_connections_bad_total 15141
telemt_handshake_timeouts_total 3888
telemt_upstream_connect_attempt_total 61072
telemt_upstream_connect_success_total 50805
telemt_upstream_connect_fail_total 10267
telemt_upstream_connect_attempts_per_request{bucket="1"} 61072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10267
telemt_me_keepalive_timeout_total 4685
telemt_me_reconnect_attempts_total 115114
telemt_me_reconnect_success_total 25455
telemt_me_reader_eof_total 28989
telemt_me_idle_close_by_peer_total 28982
telemt_me_route_drop_no_conn_total 144278
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350012
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1365
telemt_desync_full_logged_total 409
telemt_desync_suppressed_total 956
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 28581
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 25445
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3126
telemt_user_connections_total{user="hello"} 368893
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 8411256427 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 131197608908 (122.19 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 76353.4 (21h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127751
telemt_connections_bad_total 15787
telemt_handshake_timeouts_total 1408
telemt_upstream_connect_attempt_total 29728
telemt_upstream_connect_success_total 29450
telemt_upstream_connect_fail_total 278
telemt_upstream_connect_attempts_per_request{bucket="1"} 29728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 278
telemt_me_keepalive_timeout_total 1203
telemt_me_reconnect_attempts_total 34128
telemt_me_reconnect_success_total 20738
telemt_me_reader_eof_total 22231
telemt_me_idle_close_by_peer_total 22231
telemt_me_route_drop_no_conn_total 39872
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101511
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 494
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 21347
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20720
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 609
telemt_user_connections_total{user="hello"} 106407
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 1232210413 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 35753638107 (33.30 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 126138.9 (35h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 772405
telemt_connections_bad_total 24774
telemt_handshake_timeouts_total 24728
telemt_upstream_connect_attempt_total 26159
telemt_upstream_connect_success_total 26020
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 26159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 3004
telemt_me_reconnect_attempts_total 24384
telemt_me_reconnect_success_total 19740
telemt_me_reader_eof_total 21184
telemt_me_idle_close_by_peer_total 21181
telemt_me_route_drop_no_conn_total 367086
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 724704
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 689
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 20145
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19733
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 405
telemt_user_connections_total{user="hello"} 697576
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 12198871640 (11.36 GB)
telemt_user_octets_to_client{user="hello"} 345238873320 (321.53 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 75
```