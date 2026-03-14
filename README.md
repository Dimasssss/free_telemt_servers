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

# Server Metrics 2026-03-14 01:16:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 150184.7 (41h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 595178
telemt_connections_bad_total 21585
telemt_handshake_timeouts_total 12872
telemt_upstream_connect_attempt_total 38197
telemt_upstream_connect_success_total 38009
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 38197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5480
telemt_me_reconnect_attempts_total 34812
telemt_me_reconnect_success_total 30139
telemt_me_reader_eof_total 32202
telemt_me_idle_close_by_peer_total 32201
telemt_me_route_drop_no_conn_total 195436
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509754
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 675
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 30615
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 30123
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 509649
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 15502052630 (14.44 GB)
telemt_user_octets_to_client{user="hello"} 251508755456 (234.24 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 150077.9 (41h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305085
telemt_connections_bad_total 2235
telemt_handshake_timeouts_total 1935
telemt_upstream_connect_attempt_total 142818
telemt_upstream_connect_success_total 141714
telemt_upstream_connect_fail_total 1104
telemt_upstream_connect_attempts_per_request{bucket="1"} 142818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1104
telemt_me_keepalive_timeout_total 3789
telemt_me_reconnect_attempts_total 161863
telemt_me_reconnect_success_total 30918
telemt_me_reader_eof_total 35802
telemt_me_idle_close_by_peer_total 35802
telemt_me_route_drop_no_conn_total 95295
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186117
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
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
telemt_me_writer_removed_unexpected_total 35297
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 30901
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4379
telemt_user_connections_total{user="hello"} 289229
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 3028389547 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 90317084387 (84.11 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 150041.4 (41h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357330
telemt_connections_bad_total 2821
telemt_handshake_timeouts_total 33211
telemt_upstream_connect_attempt_total 39805
telemt_upstream_connect_success_total 39799
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 39805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3257
telemt_me_reconnect_attempts_total 33542
telemt_me_reconnect_success_total 32279
telemt_me_reader_eof_total 34676
telemt_me_idle_close_by_peer_total 34676
telemt_me_route_drop_no_conn_total 126770
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308826
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
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 32660
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 32259
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 308724
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 12591609580 (11.73 GB)
telemt_user_octets_to_client{user="hello"} 126730060488 (118.03 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 150017.1 (41h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458655
telemt_connections_bad_total 15368
telemt_handshake_timeouts_total 4321
telemt_upstream_connect_attempt_total 68089
telemt_upstream_connect_success_total 57645
telemt_upstream_connect_fail_total 10444
telemt_upstream_connect_attempts_per_request{bucket="1"} 68089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10444
telemt_me_keepalive_timeout_total 5062
telemt_me_reconnect_attempts_total 136115
telemt_me_reconnect_success_total 31136
telemt_me_reader_eof_total 35323
telemt_me_idle_close_by_peer_total 35315
telemt_me_route_drop_no_conn_total 161879
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388618
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1699
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 398
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 656
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 34793
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 31126
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3657
telemt_user_connections_total{user="hello"} 407460
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 9059240355 (8.44 GB)
telemt_user_octets_to_client{user="hello"} 155342551740 (144.67 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 100188.7 (27h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167246
telemt_connections_bad_total 24464
telemt_handshake_timeouts_total 1553
telemt_upstream_connect_attempt_total 36839
telemt_upstream_connect_success_total 36502
telemt_upstream_connect_fail_total 337
telemt_upstream_connect_attempts_per_request{bucket="1"} 36839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 337
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 40012
telemt_me_reconnect_success_total 26600
telemt_me_reader_eof_total 28452
telemt_me_idle_close_by_peer_total 28452
telemt_me_route_drop_no_conn_total 49900
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131465
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
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 27260
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 26582
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 136283
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 1830170213 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 64186371619 (59.78 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 149973.1 (41h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 877105
telemt_connections_bad_total 27475
telemt_handshake_timeouts_total 25321
telemt_upstream_connect_attempt_total 30902
telemt_upstream_connect_success_total 30736
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 30902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 3414
telemt_me_reconnect_attempts_total 27972
telemt_me_reconnect_success_total 23307
telemt_me_reader_eof_total 24980
telemt_me_idle_close_by_peer_total 24977
telemt_me_route_drop_no_conn_total 417640
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 819537
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
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 23756
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23300
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 792293
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 14114754996 (13.15 GB)
telemt_user_octets_to_client{user="hello"} 404958349144 (377.15 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 33
```