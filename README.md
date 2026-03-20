# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

# Server Metrics 2026-03-20 10:41:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 1469.4 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136535
telemt_connections_bad_total 3926
telemt_connections_current 1511
telemt_connections_me_current 1511
telemt_handshake_timeouts_total 1052
telemt_upstream_connect_attempt_total 521
telemt_upstream_connect_success_total 511
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 65
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 244829
telemt_me_route_drop_channel_closed_total 52
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117646
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 13
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 223
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 375
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 348
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 348
telemt_me_writer_teardown_success_total{mode="normal"} 383
telemt_me_writer_teardown_noop_total 375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 758
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.613560
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 758
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 117337
telemt_user_connections_current{user="hello"} 1511
telemt_user_octets_from_client{user="hello"} 655187976 (624.84 MB)
telemt_user_octets_to_client{user="hello"} 8321777636 (7.75 GB)
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 1452.1 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184204
telemt_connections_bad_total 21348
telemt_connections_current 4216
telemt_connections_me_current 4216
telemt_handshake_timeouts_total 5019
telemt_upstream_connect_attempt_total 567
telemt_upstream_connect_success_total 565
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 54
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 155697
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140489
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 86
telemt_desync_total 415
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 260
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 344
telemt_me_writer_removed_unexpected_total 51
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 328
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 344
telemt_me_writer_teardown_success_total{mode="normal"} 395
telemt_me_writer_teardown_noop_total 344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.022212
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_me_writer_restored_same_endpoint_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 140501
telemt_user_connections_current{user="hello"} 4216
telemt_user_octets_from_client{user="hello"} 1743279104 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 34256314592 (31.90 GB)
telemt_user_unique_ips_current{user="hello"} 1475
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 1440.2 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127779
telemt_connections_bad_total 14726
telemt_connections_current 3371
telemt_connections_me_current 3371
telemt_handshake_timeouts_total 1574
telemt_upstream_connect_attempt_total 500
telemt_upstream_connect_success_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 223
telemt_me_reconnect_attempts_total 59
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 46814
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100058
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 41
telemt_desync_total 277
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 366
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 342
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 339
telemt_me_writer_teardown_success_total{mode="normal"} 377
telemt_me_writer_teardown_noop_total 366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 743
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.053183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 743
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 100066
telemt_user_connections_current{user="hello"} 3371
telemt_user_octets_from_client{user="hello"} 1508737452 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 35879688560 (33.42 GB)
telemt_user_unique_ips_current{user="hello"} 1343
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 1246.1 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190565
telemt_connections_bad_total 17439
telemt_connections_current 5090
telemt_connections_me_current 5090
telemt_handshake_timeouts_total 3586
telemt_upstream_connect_attempt_total 379
telemt_upstream_connect_success_total 378
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 99397
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157950
telemt_me_endpoint_quarantine_total 8
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 236
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 283
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 266
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 249
telemt_me_writer_teardown_success_total{mode="normal"} 284
telemt_me_writer_teardown_noop_total 283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 567
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.776454
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 567
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 157632
telemt_user_connections_current{user="hello"} 5090
telemt_user_octets_from_client{user="hello"} 1585034792 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 49685356232 (46.27 GB)
telemt_user_unique_ips_current{user="hello"} 1732
telemt_user_unique_ips_recent_window{user="hello"} 642
```

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 1231.4 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486680
telemt_connections_bad_total 6663
telemt_connections_current 5596
telemt_connections_me_current 5596
telemt_handshake_timeouts_total 3753
telemt_upstream_connect_attempt_total 484
telemt_upstream_connect_success_total 429
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 51
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 47
telemt_me_idle_close_by_peer_total 47
telemt_me_route_drop_no_conn_total 985876
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448531
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 89
telemt_desync_total 198
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 232
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 232
telemt_me_writer_teardown_success_total{mode="normal"} 281
telemt_me_writer_teardown_noop_total 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 513
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.181161
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 513
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_writer_restored_same_endpoint_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 448500
telemt_user_connections_current{user="hello"} 5596
telemt_user_octets_from_client{user="hello"} 1652289720 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 13823985012 (12.87 GB)
telemt_user_unique_ips_current{user="hello"} 1725
telemt_user_unique_ips_recent_window{user="hello"} 975
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 1223.7 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412941
telemt_connections_bad_total 8850
telemt_connections_current 7044
telemt_connections_me_current 7044
telemt_handshake_timeouts_total 5027
telemt_upstream_connect_attempt_total 361
telemt_upstream_connect_success_total 356
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 652907
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366102
telemt_me_endpoint_quarantine_total 8
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 802
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 578
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 269
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 261
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 242
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 228
telemt_me_writer_teardown_success_total{mode="normal"} 264
telemt_me_writer_teardown_noop_total 261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 525
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.604933
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 525
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 366060
telemt_user_connections_current{user="hello"} 7044
telemt_user_octets_from_client{user="hello"} 2044304480 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 24999835476 (23.28 GB)
telemt_user_unique_ips_current{user="hello"} 2086
telemt_user_unique_ips_recent_window{user="hello"} 1083
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 1224.9 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30411
telemt_connections_bad_total 5401
telemt_connections_current 926
telemt_connections_me_current 926
telemt_handshake_timeouts_total 451
telemt_upstream_connect_attempt_total 541
telemt_upstream_connect_success_total 541
telemt_upstream_connect_attempts_per_request{bucket="1"} 541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_me_reconnect_attempts_total 92
telemt_me_reconnect_success_total 43
telemt_me_reader_eof_total 45
telemt_me_idle_close_by_peer_total 45
telemt_me_route_drop_no_conn_total 13198
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21822
telemt_me_endpoint_quarantine_total 7
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 85
telemt_desync_total 42
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 347
telemt_me_writer_removed_unexpected_total 45
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 332
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 346
telemt_me_writer_teardown_success_total{mode="normal"} 393
telemt_me_writer_teardown_noop_total 347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 740
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.271947
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 740
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 41
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 21823
telemt_user_connections_current{user="hello"} 926
telemt_user_octets_from_client{user="hello"} 272018540 (259.42 MB)
telemt_user_octets_to_client{user="hello"} 3634301080 (3.38 GB)
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 1214.4 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215433
telemt_connections_bad_total 36500
telemt_connections_current 6831
telemt_connections_me_current 6831
telemt_handshake_timeouts_total 3450
telemt_upstream_connect_attempt_total 419
telemt_upstream_connect_success_total 403
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 43
telemt_me_idle_close_by_peer_total 43
telemt_me_route_drop_no_conn_total 103923
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167558
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 88
telemt_desync_total 550
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 374
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_me_writer_close_signal_drop_total 2
telemt_me_draining_writers_reap_progress_total 233
telemt_me_writer_removed_unexpected_total 43
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 228
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 233
telemt_me_writer_teardown_success_total{mode="normal"} 276
telemt_me_writer_teardown_noop_total 233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 509
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.014453
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 509
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 2
telemt_me_writer_restored_same_endpoint_total 43
telemt_user_connections_total{user="hello"} 167563
telemt_user_connections_current{user="hello"} 6831
telemt_user_octets_from_client{user="hello"} 4457574356 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 54480852760 (50.74 GB)
telemt_user_unique_ips_current{user="hello"} 2156
telemt_user_unique_ips_recent_window{user="hello"} 862
```