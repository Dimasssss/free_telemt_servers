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

# Server Metrics 2026-03-14 01:01:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 149268.1 (41h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593309
telemt_connections_bad_total 21350
telemt_handshake_timeouts_total 12856
telemt_upstream_connect_attempt_total 37961
telemt_upstream_connect_success_total 37773
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 37961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5478
telemt_me_reconnect_attempts_total 34620
telemt_me_reconnect_success_total 29948
telemt_me_reader_eof_total 31998
telemt_me_idle_close_by_peer_total 31997
telemt_me_route_drop_no_conn_total 194898
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508172
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1642
telemt_desync_full_logged_total 562
telemt_desync_suppressed_total 1080
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 673
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 30424
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 29932
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 508067
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 15480481238 (14.42 GB)
telemt_user_octets_to_client{user="hello"} 251027646716 (233.79 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 149161.1 (41h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304600
telemt_connections_bad_total 2235
telemt_handshake_timeouts_total 1933
telemt_upstream_connect_attempt_total 142647
telemt_upstream_connect_success_total 141549
telemt_upstream_connect_fail_total 1098
telemt_upstream_connect_attempts_per_request{bucket="1"} 142647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1098
telemt_me_keepalive_timeout_total 3782
telemt_me_reconnect_attempts_total 160429
telemt_me_reconnect_success_total 30797
telemt_me_reader_eof_total 35638
telemt_me_idle_close_by_peer_total 35638
telemt_me_route_drop_no_conn_total 94190
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185665
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 35133
telemt_me_refill_failed_total 4045
telemt_me_writer_restored_same_endpoint_total 30780
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4336
telemt_user_connections_total{user="hello"} 288777
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 3026359203 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 90273503499 (84.07 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 149124.8 (41h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356444
telemt_connections_bad_total 2777
telemt_handshake_timeouts_total 33211
telemt_upstream_connect_attempt_total 39558
telemt_upstream_connect_success_total 39552
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 39558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3254
telemt_me_reconnect_attempts_total 33339
telemt_me_reconnect_success_total 32076
telemt_me_reader_eof_total 34457
telemt_me_idle_close_by_peer_total 34457
telemt_me_route_drop_no_conn_total 126396
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308004
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
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 32456
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 32056
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 307905
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 12587009236 (11.72 GB)
telemt_user_octets_to_client{user="hello"} 126564728868 (117.87 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 149100.4 (41h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457809
telemt_connections_bad_total 15364
telemt_handshake_timeouts_total 4319
telemt_upstream_connect_attempt_total 67731
telemt_upstream_connect_success_total 57298
telemt_upstream_connect_fail_total 10433
telemt_upstream_connect_attempts_per_request{bucket="1"} 67731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10433
telemt_me_keepalive_timeout_total 5052
telemt_me_reconnect_attempts_total 135811
telemt_me_reconnect_success_total 30834
telemt_me_reader_eof_total 35017
telemt_me_idle_close_by_peer_total 35009
telemt_me_route_drop_no_conn_total 161335
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387801
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1692
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 34487
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 30824
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3653
telemt_user_connections_total{user="hello"} 406643
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 9054504895 (8.43 GB)
telemt_user_octets_to_client{user="hello"} 155254537508 (144.59 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 99271.9 (27h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166373
telemt_connections_bad_total 24283
telemt_handshake_timeouts_total 1553
telemt_upstream_connect_attempt_total 36564
telemt_upstream_connect_success_total 36231
telemt_upstream_connect_fail_total 333
telemt_upstream_connect_attempts_per_request{bucket="1"} 36564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 333
telemt_me_keepalive_timeout_total 1362
telemt_me_reconnect_attempts_total 39784
telemt_me_reconnect_success_total 26371
telemt_me_reader_eof_total 28207
telemt_me_idle_close_by_peer_total 28207
telemt_me_route_drop_no_conn_total 49529
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130794
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 27031
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 26353
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 135614
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 1794327565 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 64146317095 (59.74 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 149056.5 (41h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 874144
telemt_connections_bad_total 27387
telemt_handshake_timeouts_total 25317
telemt_upstream_connect_attempt_total 30714
telemt_upstream_connect_success_total 30548
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 30714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 3412
telemt_me_reconnect_attempts_total 27827
telemt_me_reconnect_success_total 23162
telemt_me_reader_eof_total 24824
telemt_me_idle_close_by_peer_total 24821
telemt_me_route_drop_no_conn_total 416267
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816750
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 23610
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23155
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 789506
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 14102911400 (13.13 GB)
telemt_user_octets_to_client{user="hello"} 404520301668 (376.74 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 34
```