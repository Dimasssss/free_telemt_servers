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

# Server Metrics 2026-03-13 04:13:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 74426.0 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285570
telemt_connections_bad_total 3015
telemt_handshake_timeouts_total 5766
telemt_upstream_connect_attempt_total 18806
telemt_upstream_connect_success_total 18721
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 18806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1534
telemt_me_reconnect_attempts_total 18473
telemt_me_reconnect_success_total 14984
telemt_me_reader_eof_total 16015
telemt_me_idle_close_by_peer_total 16014
telemt_me_route_drop_no_conn_total 88903
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239062
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 794
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 498
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 15255
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14968
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 239001
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 4160573820 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 117474466492 (109.41 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 74319.0 (20h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131543
telemt_connections_bad_total 748
telemt_handshake_timeouts_total 983
telemt_upstream_connect_attempt_total 40205
telemt_upstream_connect_success_total 39709
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 40205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 504
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_timeout_total 537
telemt_me_reconnect_attempts_total 66048
telemt_me_reconnect_success_total 19487
telemt_me_reader_eof_total 21515
telemt_me_idle_close_by_peer_total 21515
telemt_me_route_drop_no_conn_total 48086
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108482
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 21090
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 19472
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1603
telemt_user_connections_total{user="hello"} 124982
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 1298700520 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 37582115219 (35.00 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 74282.6 (20h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158503
telemt_connections_bad_total 1843
telemt_handshake_timeouts_total 2579
telemt_upstream_connect_attempt_total 20576
telemt_upstream_connect_success_total 20574
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 407
telemt_me_reconnect_attempts_total 17975
telemt_me_reconnect_success_total 16812
telemt_me_reader_eof_total 18000
telemt_me_idle_close_by_peer_total 18000
telemt_me_route_drop_no_conn_total 61330
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148237
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16996
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 16792
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 148162
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 2787161380 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 69585438268 (64.81 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 74258.3 (20h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228025
telemt_connections_bad_total 13471
telemt_handshake_timeouts_total 1448
telemt_upstream_connect_attempt_total 33042
telemt_upstream_connect_success_total 23187
telemt_upstream_connect_fail_total 9855
telemt_upstream_connect_attempts_per_request{bucket="1"} 33042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9855
telemt_me_keepalive_timeout_total 3308
telemt_me_reconnect_attempts_total 61286
telemt_me_reconnect_success_total 16606
telemt_me_reader_eof_total 18525
telemt_me_idle_close_by_peer_total 18518
telemt_me_route_drop_no_conn_total 83293
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190581
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18226
telemt_me_refill_failed_total 1392
telemt_me_writer_restored_same_endpoint_total 16596
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1620
telemt_user_connections_total{user="hello"} 193329
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 3203778902 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 78243378589 (72.87 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 24429.9 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24394
telemt_connections_bad_total 4579
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 7603
telemt_upstream_connect_success_total 7529
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 7603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 171
telemt_me_reconnect_attempts_total 6300
telemt_me_reconnect_success_total 6278
telemt_me_reader_eof_total 6727
telemt_me_idle_close_by_peer_total 6727
telemt_me_route_drop_no_conn_total 6832
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19027
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6332
telemt_me_writer_restored_same_endpoint_total 6260
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 19027
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 139520844 (133.06 MB)
telemt_user_octets_to_client{user="hello"} 8911162568 (8.30 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 74214.6 (20h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384061
telemt_connections_bad_total 7640
telemt_handshake_timeouts_total 2907
telemt_upstream_connect_attempt_total 15804
telemt_upstream_connect_success_total 15718
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 15804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1427
telemt_me_reconnect_attempts_total 15645
telemt_me_reconnect_success_total 12018
telemt_me_reader_eof_total 12907
telemt_me_idle_close_by_peer_total 12904
telemt_me_route_drop_no_conn_total 171708
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374504
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 12286
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12011
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 362750
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 6054218652 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 217304339068 (202.38 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 39
```