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

# Server Metrics 2026-03-13 01:09:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 63374.2 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261563
telemt_connections_bad_total 2766
telemt_handshake_timeouts_total 5596
telemt_upstream_connect_attempt_total 16006
telemt_upstream_connect_success_total 15937
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 16006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1505
telemt_me_reconnect_attempts_total 16207
telemt_me_reconnect_success_total 12733
telemt_me_reader_eof_total 13587
telemt_me_idle_close_by_peer_total 13586
telemt_me_route_drop_no_conn_total 81360
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216533
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 12981
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 12717
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 216301
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 3923513272 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 109067623396 (101.58 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 63267.1 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121308
telemt_connections_bad_total 732
telemt_handshake_timeouts_total 971
telemt_upstream_connect_attempt_total 35721
telemt_upstream_connect_success_total 35291
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 35721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 456
telemt_me_reconnect_attempts_total 59812
telemt_me_reconnect_success_total 15601
telemt_me_reader_eof_total 17405
telemt_me_idle_close_by_peer_total 17405
telemt_me_route_drop_no_conn_total 43284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98632
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 17097
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 15586
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1496
telemt_user_connections_total{user="hello"} 115132
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 1239553372 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 34746984711 (32.36 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 63230.7 (17h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146602
telemt_connections_bad_total 1684
telemt_handshake_timeouts_total 2333
telemt_upstream_connect_attempt_total 17474
telemt_upstream_connect_success_total 17472
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 363
telemt_me_reconnect_attempts_total 15396
telemt_me_reconnect_success_total 14241
telemt_me_reader_eof_total 15221
telemt_me_idle_close_by_peer_total 15221
telemt_me_route_drop_no_conn_total 55740
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137076
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14401
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14221
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 137040
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2630453740 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 62324313060 (58.04 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 63206.4 (17h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209981
telemt_connections_bad_total 13297
telemt_handshake_timeouts_total 1426
telemt_upstream_connect_attempt_total 29496
telemt_upstream_connect_success_total 19732
telemt_upstream_connect_fail_total 9764
telemt_upstream_connect_attempts_per_request{bucket="1"} 29496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9764
telemt_me_keepalive_timeout_total 3209
telemt_me_reconnect_attempts_total 50574
telemt_me_reconnect_success_total 13677
telemt_me_reader_eof_total 15312
telemt_me_idle_close_by_peer_total 15305
telemt_me_route_drop_no_conn_total 75486
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173753
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 15033
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 13667
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1356
telemt_user_connections_total{user="hello"} 176505
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 3020163602 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 72509674521 (67.53 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13378.0 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12126
telemt_connections_bad_total 2545
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 4159
telemt_upstream_connect_success_total 4122
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 4159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 3452
telemt_me_reconnect_success_total 3443
telemt_me_reader_eof_total 3666
telemt_me_idle_close_by_peer_total 3666
telemt_me_route_drop_no_conn_total 3662
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9175
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3462
telemt_me_writer_restored_same_endpoint_total 3427
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 9175
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 36163648 (34.49 MB)
telemt_user_octets_to_client{user="hello"} 2803501224 (2.61 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 63162.9 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352327
telemt_connections_bad_total 6544
telemt_handshake_timeouts_total 2598
telemt_upstream_connect_attempt_total 13378
telemt_upstream_connect_success_total 13306
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 13378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 1335
telemt_me_reconnect_attempts_total 13752
telemt_me_reconnect_success_total 10134
telemt_me_reader_eof_total 10873
telemt_me_idle_close_by_peer_total 10871
telemt_me_route_drop_no_conn_total 157352
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344764
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10371
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10127
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 333066
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 5638284376 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 180345442084 (167.96 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 34
```