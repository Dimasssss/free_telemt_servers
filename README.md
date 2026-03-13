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

# Server Metrics 2026-03-13 16:31:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 118713.8 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494811
telemt_connections_bad_total 4219
telemt_handshake_timeouts_total 8907
telemt_upstream_connect_attempt_total 29521
telemt_upstream_connect_success_total 29377
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 29521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2585
telemt_me_reconnect_attempts_total 26994
telemt_me_reconnect_success_total 23455
telemt_me_reader_eof_total 25058
telemt_me_idle_close_by_peer_total 25057
telemt_me_route_drop_no_conn_total 161979
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434570
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1400
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 909
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 590
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 23815
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23439
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 360
telemt_user_connections_total{user="hello"} 434142
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 7675340996 (7.15 GB)
telemt_user_octets_to_client{user="hello"} 201724731688 (187.87 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 118606.7 (32h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240873
telemt_connections_bad_total 1885
telemt_handshake_timeouts_total 1755
telemt_upstream_connect_attempt_total 96889
telemt_upstream_connect_success_total 96083
telemt_upstream_connect_fail_total 806
telemt_upstream_connect_attempts_per_request{bucket="1"} 96889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1267
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 806
telemt_me_keepalive_timeout_total 1437
telemt_me_reconnect_attempts_total 119069
telemt_me_reconnect_success_total 26030
telemt_me_reader_eof_total 29691
telemt_me_idle_close_by_peer_total 29691
telemt_me_route_drop_no_conn_total 81846
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163996
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 28
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
telemt_me_writer_removed_unexpected_total 29161
telemt_me_refill_failed_total 2903
telemt_me_writer_restored_same_endpoint_total 26013
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3131
telemt_user_connections_total{user="hello"} 227917
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 2407549621 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 71087211886 (66.21 GB)
telemt_user_msgs_from_client{user="hello"} 1008188
telemt_user_msgs_to_client{user="hello"} 5978735
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 118570.5 (32h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288001
telemt_connections_bad_total 2446
telemt_handshake_timeouts_total 14422
telemt_upstream_connect_attempt_total 31721
telemt_upstream_connect_success_total 31717
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2460
telemt_me_reconnect_attempts_total 26977
telemt_me_reconnect_success_total 25754
telemt_me_reader_eof_total 27590
telemt_me_idle_close_by_peer_total 27590
telemt_me_route_drop_no_conn_total 103632
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260952
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 26041
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25734
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 260864
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 10083756196 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 109703722508 (102.17 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 118546.1 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390423
telemt_connections_bad_total 15068
telemt_handshake_timeouts_total 3826
telemt_upstream_connect_attempt_total 45573
telemt_upstream_connect_success_total 35375
telemt_upstream_connect_fail_total 10198
telemt_upstream_connect_attempts_per_request{bucket="1"} 45573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10198
telemt_me_keepalive_timeout_total 4179
telemt_me_reconnect_attempts_total 108466
telemt_me_reconnect_success_total 24264
telemt_me_reader_eof_total 27603
telemt_me_idle_close_by_peer_total 27596
telemt_me_route_drop_no_conn_total 139206
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337386
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27202
telemt_me_refill_failed_total 2626
telemt_me_writer_restored_same_endpoint_total 24254
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2938
telemt_user_connections_total{user="hello"} 342446
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 7829240767 (7.29 GB)
telemt_user_octets_to_client{user="hello"} 126062987867 (117.41 GB)
telemt_user_msgs_from_client{user="hello"} 170321
telemt_user_msgs_to_client{user="hello"} 214103
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 68717.4 (19h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109557
telemt_connections_bad_total 14307
telemt_handshake_timeouts_total 1364
telemt_upstream_connect_attempt_total 27534
telemt_upstream_connect_success_total 27288
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 27534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 1097
telemt_me_reconnect_attempts_total 30110
telemt_me_reconnect_success_total 18934
telemt_me_reader_eof_total 20291
telemt_me_idle_close_by_peer_total 20291
telemt_me_route_drop_no_conn_total 33471
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85473
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 19447
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18916
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 90372
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 1032515361 (984.68 MB)
telemt_user_octets_to_client{user="hello"} 28143629435 (26.21 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 118503.1 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 721508
telemt_connections_bad_total 24639
telemt_handshake_timeouts_total 23999
telemt_upstream_connect_attempt_total 24747
telemt_upstream_connect_success_total 24622
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 24747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 2623
telemt_me_reconnect_attempts_total 23369
telemt_me_reconnect_success_total 18738
telemt_me_reader_eof_total 20109
telemt_me_idle_close_by_peer_total 20106
telemt_me_route_drop_no_conn_total 340776
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 676370
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19121
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18731
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 649260
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 11323546196 (10.55 GB)
telemt_user_octets_to_client{user="hello"} 331522846228 (308.75 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 62
```