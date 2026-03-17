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

# Server Metrics 2026-03-17 04:27:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 34915.9 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184397
telemt_connections_bad_total 2510
telemt_handshake_timeouts_total 6918
telemt_upstream_connect_attempt_total 7468
telemt_upstream_connect_success_total 7426
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 7468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5711
telemt_me_reconnect_success_total 5693
telemt_me_reader_eof_total 6054
telemt_me_idle_close_by_peer_total 6054
telemt_me_route_drop_no_conn_total 58408
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166945
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1059
telemt_desync_full_logged_total 374
telemt_desync_suppressed_total 685
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5747
telemt_me_writer_restored_same_endpoint_total 5672
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 166749
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 2388683468 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 76439353012 (71.19 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 35167.1 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102367
telemt_connections_bad_total 2019
telemt_handshake_timeouts_total 3549
telemt_upstream_connect_attempt_total 9861
telemt_upstream_connect_success_total 9734
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 9860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_reconnect_attempts_total 9163
telemt_me_reconnect_success_total 7993
telemt_me_reader_eof_total 8450
telemt_me_idle_close_by_peer_total 8450
telemt_me_route_drop_no_conn_total 42283
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92641
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 246
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8104
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7977
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 92632
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 1270152732 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 42352632160 (39.44 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 34943.7 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66573
telemt_connections_bad_total 817
telemt_handshake_timeouts_total 2392
telemt_upstream_connect_attempt_total 9311
telemt_upstream_connect_success_total 9261
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 7556
telemt_me_reconnect_success_total 7513
telemt_me_reader_eof_total 8049
telemt_me_idle_close_by_peer_total 8049
telemt_me_route_drop_no_conn_total 22079
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56626
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7608
telemt_me_writer_restored_same_endpoint_total 7502
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 56609
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 5736393376 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 18893249836 (17.60 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 35002.7 (9h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106514
telemt_connections_bad_total 3416
telemt_handshake_timeouts_total 2424
telemt_upstream_connect_attempt_total 8055
telemt_upstream_connect_success_total 7987
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 8055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_reconnect_attempts_total 6247
telemt_me_reconnect_success_total 6199
telemt_me_reader_eof_total 6599
telemt_me_idle_close_by_peer_total 6599
telemt_me_route_drop_no_conn_total 36147
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97483
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 164
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6291
telemt_me_writer_restored_same_endpoint_total 6192
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 97501
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 1072312590 (1022.64 MB)
telemt_user_octets_to_client{user="hello"} 45936245693 (42.78 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 34974.6 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77230
telemt_connections_bad_total 17044
telemt_handshake_timeouts_total 1397
telemt_upstream_connect_attempt_total 10355
telemt_upstream_connect_success_total 10227
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 10355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_reconnect_attempts_total 10739
telemt_me_reconnect_success_total 8487
telemt_me_reader_eof_total 8947
telemt_me_idle_close_by_peer_total 8947
telemt_me_route_drop_no_conn_total 22517
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56612
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 8675
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 8479
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 56608
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 645706588 (615.79 MB)
telemt_user_octets_to_client{user="hello"} 22864994576 (21.29 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 35135.6 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206564
telemt_connections_bad_total 27115
telemt_handshake_timeouts_total 1225
telemt_upstream_connect_attempt_total 7325
telemt_upstream_connect_success_total 7285
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 7325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5569
telemt_me_reconnect_success_total 5546
telemt_me_reader_eof_total 5943
telemt_me_idle_close_by_peer_total 5943
telemt_me_route_drop_no_conn_total 189894
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249953
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5623
telemt_me_writer_restored_same_endpoint_total 5536
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 172207
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 2632736308 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 136481896284 (127.11 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 23142.1 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 11648
telemt_upstream_connect_success_total 11648
telemt_upstream_connect_attempts_per_request{bucket="1"} 11648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 10496
telemt_me_reconnect_success_total 10436
telemt_me_reader_eof_total 11462
telemt_me_idle_close_by_peer_total 11462
telemt_me_route_drop_no_conn_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 10537
telemt_me_writer_restored_same_endpoint_total 10436
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 157584760 (150.28 MB)
telemt_user_octets_to_client{user="hello"} 24357516 (23.23 MB)
```