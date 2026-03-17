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

# Server Metrics 2026-03-17 06:14:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 41341.1 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240230
telemt_connections_bad_total 3350
telemt_handshake_timeouts_total 7980
telemt_upstream_connect_attempt_total 8630
telemt_upstream_connect_success_total 8584
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6567
telemt_me_reconnect_success_total 6543
telemt_me_reader_eof_total 6964
telemt_me_idle_close_by_peer_total 6964
telemt_me_route_drop_no_conn_total 74556
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217119
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1556
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 1063
telemt_desync_frames_bucket_total{bucket="1_2"} 359
telemt_desync_frames_bucket_total{bucket="3_10"} 809
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6609
telemt_me_writer_restored_same_endpoint_total 6522
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 216909
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 2941692696 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 95200674196 (88.66 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 41592.2 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136858
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 10499
telemt_upstream_connect_attempt_total 11445
telemt_upstream_connect_success_total 11298
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 11445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 10399
telemt_me_reconnect_success_total 9223
telemt_me_reader_eof_total 9765
telemt_me_idle_close_by_peer_total 9765
telemt_me_route_drop_no_conn_total 51640
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119153
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 315
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9343
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9207
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 119162
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 1471230528 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 50901913892 (47.41 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 41368.7 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81841
telemt_connections_bad_total 1110
telemt_handshake_timeouts_total 2658
telemt_upstream_connect_attempt_total 11107
telemt_upstream_connect_success_total 11049
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 11107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9037
telemt_me_reconnect_success_total 8988
telemt_me_reader_eof_total 9615
telemt_me_idle_close_by_peer_total 9615
telemt_me_route_drop_no_conn_total 27882
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70521
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 9096
telemt_me_writer_restored_same_endpoint_total 8977
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 70504
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 6091110016 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 22833058688 (21.26 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 41427.7 (11h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143475
telemt_connections_bad_total 3785
telemt_handshake_timeouts_total 5951
telemt_upstream_connect_attempt_total 9354
telemt_upstream_connect_success_total 9274
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 9354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_reconnect_attempts_total 7230
telemt_me_reconnect_success_total 7175
telemt_me_reader_eof_total 7637
telemt_me_idle_close_by_peer_total 7637
telemt_me_route_drop_no_conn_total 47750
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129528
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7279
telemt_me_writer_restored_same_endpoint_total 7168
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 129545
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 1393607538 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 62740562981 (58.43 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 41399.7 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109038
telemt_connections_bad_total 31821
telemt_handshake_timeouts_total 2055
telemt_upstream_connect_attempt_total 12338
telemt_upstream_connect_success_total 12175
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 12338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 12280
telemt_me_reconnect_success_total 10013
telemt_me_reader_eof_total 10569
telemt_me_idle_close_by_peer_total 10569
telemt_me_route_drop_no_conn_total 27945
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72249
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10215
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 10005
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 72346
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 771640967 (735.89 MB)
telemt_user_octets_to_client{user="hello"} 31381627690 (29.23 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 41561.0 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262874
telemt_connections_bad_total 36131
telemt_handshake_timeouts_total 2123
telemt_upstream_connect_attempt_total 8542
telemt_upstream_connect_success_total 8497
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6442
telemt_me_reconnect_success_total 6413
telemt_me_reader_eof_total 6872
telemt_me_idle_close_by_peer_total 6872
telemt_me_route_drop_no_conn_total 218235
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292892
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6508
telemt_me_writer_restored_same_endpoint_total 6403
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 214834
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 3221742812 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 151537864092 (141.13 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 29567.2 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 797
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 14545
telemt_upstream_connect_success_total 14545
telemt_upstream_connect_attempts_per_request{bucket="1"} 14545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 13089
telemt_me_reconnect_success_total 13016
telemt_me_reader_eof_total 14282
telemt_me_idle_close_by_peer_total 14282
telemt_me_route_drop_no_conn_total 87
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 13132
telemt_me_writer_restored_same_endpoint_total 13016
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 598
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 190662428 (181.83 MB)
telemt_user_octets_to_client{user="hello"} 9909617892 (9.23 GB)
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```