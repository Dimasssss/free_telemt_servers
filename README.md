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

# Server Metrics 2026-03-13 12:06:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 102813.4 (28h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417433
telemt_connections_bad_total 3209
telemt_handshake_timeouts_total 8315
telemt_upstream_connect_attempt_total 26003
telemt_upstream_connect_success_total 25880
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 26003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2284
telemt_me_reconnect_attempts_total 24232
telemt_me_reconnect_success_total 20708
telemt_me_reader_eof_total 22104
telemt_me_idle_close_by_peer_total 22103
telemt_me_route_drop_no_conn_total 132653
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361979
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1223
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 788
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 21034
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 20692
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 361574
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 6427721472 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 155451911732 (144.78 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 102705.8 (28h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192323
telemt_connections_bad_total 1653
telemt_handshake_timeouts_total 1461
telemt_upstream_connect_attempt_total 54767
telemt_upstream_connect_success_total 54072
telemt_upstream_connect_fail_total 695
telemt_upstream_connect_attempts_per_request{bucket="1"} 54767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 695
telemt_me_keepalive_timeout_total 1317
telemt_me_reconnect_attempts_total 94201
telemt_me_reconnect_success_total 25938
telemt_me_reader_eof_total 28831
telemt_me_idle_close_by_peer_total 28831
telemt_me_route_drop_no_conn_total 78950
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158557
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 23
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
telemt_me_writer_removed_unexpected_total 28295
telemt_me_refill_failed_total 2129
telemt_me_writer_restored_same_endpoint_total 25921
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2357
telemt_user_connections_total{user="hello"} 181322
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 1847662982 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 58851623802 (54.81 GB)
telemt_user_msgs_from_client{user="hello"} 331680
telemt_user_msgs_to_client{user="hello"} 2358041
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 102669.6 (28h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233836
telemt_connections_bad_total 2059
telemt_handshake_timeouts_total 6930
telemt_upstream_connect_attempt_total 27925
telemt_upstream_connect_success_total 27920
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 27924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2096
telemt_me_reconnect_attempts_total 23934
telemt_me_reconnect_success_total 22722
telemt_me_reader_eof_total 24339
telemt_me_idle_close_by_peer_total 24339
telemt_me_route_drop_no_conn_total 86789
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216331
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 22974
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 22702
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 216245
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 9327873920 (8.69 GB)
telemt_user_octets_to_client{user="hello"} 96063663656 (89.47 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 102645.1 (28h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326232
telemt_connections_bad_total 13762
telemt_handshake_timeouts_total 2359
telemt_upstream_connect_attempt_total 39831
telemt_upstream_connect_success_total 29766
telemt_upstream_connect_fail_total 10065
telemt_upstream_connect_attempts_per_request{bucket="1"} 39831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14517
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10065
telemt_me_keepalive_timeout_total 4025
telemt_me_reconnect_attempts_total 91759
telemt_me_reconnect_success_total 21583
telemt_me_reader_eof_total 24422
telemt_me_idle_close_by_peer_total 24415
telemt_me_route_drop_no_conn_total 117928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281315
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 982
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 690
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 24044
telemt_me_refill_failed_total 2188
telemt_me_writer_restored_same_endpoint_total 21573
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2461
telemt_user_connections_total{user="hello"} 284229
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 5910824650 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 107274009121 (99.91 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 52816.6 (14h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76388
telemt_connections_bad_total 10458
telemt_handshake_timeouts_total 802
telemt_upstream_connect_attempt_total 23056
telemt_upstream_connect_success_total 22877
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 23056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 834
telemt_me_reconnect_attempts_total 25230
telemt_me_reconnect_success_total 15314
telemt_me_reader_eof_total 16436
telemt_me_idle_close_by_peer_total 16436
telemt_me_route_drop_no_conn_total 22545
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57767
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 93
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 15756
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15296
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 62678
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 549671273 (524.21 MB)
telemt_user_octets_to_client{user="hello"} 17408533059 (16.21 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 102601.5 (28h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 583911
telemt_connections_bad_total 17423
telemt_handshake_timeouts_total 13297
telemt_upstream_connect_attempt_total 21774
telemt_upstream_connect_success_total 21661
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 21774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 2390
telemt_me_reconnect_attempts_total 21189
telemt_me_reconnect_success_total 16569
telemt_me_reader_eof_total 17784
telemt_me_idle_close_by_peer_total 17781
telemt_me_route_drop_no_conn_total 289017
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560143
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 16931
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16562
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 533202
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 9534377396 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 286359514772 (266.69 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 60
```