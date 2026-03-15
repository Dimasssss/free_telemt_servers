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

# Server Metrics 2026-03-15 08:30:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 36972.0 (10h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133776
telemt_connections_bad_total 1076
telemt_handshake_timeouts_total 3441
telemt_upstream_connect_attempt_total 8830
telemt_upstream_connect_success_total 8777
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 8830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6970
telemt_me_reconnect_success_total 6943
telemt_me_reader_eof_total 7430
telemt_me_idle_close_by_peer_total 7430
telemt_me_route_drop_no_conn_total 261118
telemt_me_route_drop_channel_closed_total 38
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161834
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 988
telemt_desync_full_logged_total 417
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 401
telemt_desync_frames_bucket_total{bucket="gt_10"} 417
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7005
telemt_me_writer_restored_same_endpoint_total 6912
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 124312
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 1698676948 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 116288239364 (108.30 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 36979.1 (10h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40677
telemt_connections_bad_total 266
telemt_handshake_timeouts_total 1783
telemt_upstream_connect_attempt_total 10058
telemt_upstream_connect_success_total 10058
telemt_upstream_connect_attempts_per_request{bucket="1"} 10058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8234
telemt_me_reconnect_success_total 8198
telemt_me_reader_eof_total 8769
telemt_me_idle_close_by_peer_total 8769
telemt_me_route_drop_no_conn_total 20860
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37206
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8279
telemt_me_writer_restored_same_endpoint_total 8182
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 37209
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 856629188 (816.95 MB)
telemt_user_octets_to_client{user="hello"} 13796284904 (12.85 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 36972.0 (10h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50761
telemt_connections_bad_total 481
telemt_handshake_timeouts_total 1907
telemt_upstream_connect_attempt_total 9837
telemt_upstream_connect_success_total 9836
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8009
telemt_me_reconnect_success_total 7971
telemt_me_reader_eof_total 8613
telemt_me_idle_close_by_peer_total 8613
telemt_me_route_drop_no_conn_total 17467
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46179
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8047
telemt_me_writer_restored_same_endpoint_total 7967
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 46113
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 8970245700 (8.35 GB)
telemt_user_octets_to_client{user="hello"} 29433374092 (27.41 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 36971.4 (10h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61182
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 397
telemt_upstream_connect_attempt_total 8801
telemt_upstream_connect_success_total 8800
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6976
telemt_me_reconnect_success_total 6948
telemt_me_reader_eof_total 7426
telemt_me_idle_close_by_peer_total 7426
telemt_me_route_drop_no_conn_total 26601
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55352
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 105
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7020
telemt_me_writer_restored_same_endpoint_total 6937
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 55284
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1107306280 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 34574614068 (32.20 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 12042.9 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19078
telemt_connections_bad_total 2302
telemt_handshake_timeouts_total 235
telemt_upstream_connect_attempt_total 4279
telemt_upstream_connect_success_total 4240
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 4279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 97846
telemt_me_reconnect_success_total 3446
telemt_me_reader_eof_total 3536
telemt_me_idle_close_by_peer_total 3536
telemt_me_route_drop_no_conn_total 5664
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15996
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3399
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3342
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 16136
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 126367809 (120.51 MB)
telemt_user_octets_to_client{user="hello"} 9951785287 (9.27 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 36970.7 (10h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160952
telemt_connections_bad_total 21107
telemt_handshake_timeouts_total 831
telemt_upstream_connect_attempt_total 8017
telemt_upstream_connect_success_total 7968
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 8017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 6142
telemt_me_reconnect_success_total 6112
telemt_me_reader_eof_total 6514
telemt_me_idle_close_by_peer_total 6514
telemt_me_route_drop_no_conn_total 76774
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134708
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6147
telemt_me_writer_restored_same_endpoint_total 6085
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 133249
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 3601021388 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 71172795680 (66.28 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 87
```