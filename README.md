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

# Server Metrics 2026-03-20 10:36:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 1164.0 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122178
telemt_connections_bad_total 3415
telemt_connections_current 1379
telemt_connections_me_current 1379
telemt_handshake_timeouts_total 917
telemt_upstream_connect_attempt_total 424
telemt_upstream_connect_success_total 414
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 60
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 237782
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105725
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
telemt_me_writers_active_current 43
telemt_desync_total 179
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 308
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 281
telemt_me_writer_teardown_success_total{mode="normal"} 312
telemt_me_writer_teardown_noop_total 308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.608294
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 105418
telemt_user_connections_current{user="hello"} 1379
telemt_user_octets_from_client{user="hello"} 552531364 (526.93 MB)
telemt_user_octets_to_client{user="hello"} 6175787836 (5.75 GB)
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 1146.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152328
telemt_connections_bad_total 18507
telemt_connections_current 4411
telemt_connections_me_current 4411
telemt_handshake_timeouts_total 4135
telemt_upstream_connect_attempt_total 428
telemt_upstream_connect_success_total 426
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 50
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 46
telemt_me_idle_close_by_peer_total 46
telemt_me_route_drop_no_conn_total 120650
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115143
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
telemt_desync_total 337
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_me_writer_close_signal_drop_total 2
telemt_me_draining_writers_reap_progress_total 233
telemt_me_writer_removed_unexpected_total 47
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 222
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 233
telemt_me_writer_teardown_success_total{mode="normal"} 280
telemt_me_writer_teardown_noop_total 233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 513
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
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.016236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 513
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 2
telemt_me_writer_restored_same_endpoint_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 115156
telemt_user_connections_current{user="hello"} 4411
telemt_user_octets_from_client{user="hello"} 1471976380 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 25865073888 (24.09 GB)
telemt_user_unique_ips_current{user="hello"} 1512
telemt_user_unique_ips_recent_window{user="hello"} 763
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 1135.0 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101921
telemt_connections_bad_total 12714
telemt_connections_current 2974
telemt_connections_me_current 2974
telemt_handshake_timeouts_total 1204
telemt_upstream_connect_attempt_total 428
telemt_upstream_connect_success_total 428
telemt_upstream_connect_attempts_per_request{bucket="1"} 428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 195
telemt_me_reconnect_attempts_total 57
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 38131
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78815
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 11
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
telemt_desync_total 236
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_draining_writers_reap_progress_total 318
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 297
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 291
telemt_me_writer_teardown_success_total{mode="normal"} 327
telemt_me_writer_teardown_noop_total 318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 645
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.047522
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 645
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 78817
telemt_user_connections_current{user="hello"} 2974
telemt_user_octets_from_client{user="hello"} 1112769656 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 28026411688 (26.10 GB)
telemt_user_unique_ips_current{user="hello"} 1233
telemt_user_unique_ips_recent_window{user="hello"} 581
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 925.9 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372831
telemt_connections_bad_total 4491
telemt_connections_current 6930
telemt_connections_me_current 6930
telemt_handshake_timeouts_total 2950
telemt_upstream_connect_attempt_total 289
telemt_upstream_connect_success_total 263
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 721372
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343404
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 7
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
telemt_me_writers_active_current 46
telemt_desync_total 132
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 159
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 154
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 159
telemt_me_writer_teardown_success_total{mode="normal"} 163
telemt_me_writer_teardown_noop_total 159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 322
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.122939
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 322
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 343399
telemt_user_connections_current{user="hello"} 6930
telemt_user_octets_from_client{user="hello"} 1340077848 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 10431900444 (9.72 GB)
telemt_user_unique_ips_current{user="hello"} 1803
telemt_user_unique_ips_recent_window{user="hello"} 1259
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 918.1 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311569
telemt_connections_bad_total 5565
telemt_connections_current 7363
telemt_connections_me_current 7363
telemt_handshake_timeouts_total 3960
telemt_upstream_connect_attempt_total 238
telemt_upstream_connect_success_total 235
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 501744
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274201
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 44
telemt_desync_total 617
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 442
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 142
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 141
telemt_me_writer_teardown_success_total{mode="normal"} 144
telemt_me_writer_teardown_noop_total 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 286
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.004397
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 286
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 274232
telemt_user_connections_current{user="hello"} 7363
telemt_user_octets_from_client{user="hello"} 1387419748 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 18791773432 (17.50 GB)
telemt_user_unique_ips_current{user="hello"} 2150
telemt_user_unique_ips_recent_window{user="hello"} 1317
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 916.6 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24345
telemt_connections_bad_total 5378
telemt_connections_current 872
telemt_connections_me_current 872
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 330
telemt_upstream_connect_success_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 222
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 9074
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16455
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 45
telemt_desync_total 37
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 227
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 224
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 226
telemt_me_writer_teardown_success_total{mode="normal"} 230
telemt_me_writer_teardown_noop_total 227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 457
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.037115
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 457
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 16456
telemt_user_connections_current{user="hello"} 871
telemt_user_octets_from_client{user="hello"} 177817492 (169.58 MB)
telemt_user_octets_to_client{user="hello"} 2651334732 (2.47 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 909.0 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173623
telemt_connections_bad_total 35802
telemt_connections_current 7206
telemt_connections_me_current 7206
telemt_handshake_timeouts_total 2020
telemt_upstream_connect_attempt_total 246
telemt_upstream_connect_success_total 235
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 83495
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129236
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 45
telemt_desync_total 431
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 302
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_me_draining_writers_reap_progress_total 152
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 152
telemt_me_writer_teardown_success_total{mode="normal"} 152
telemt_me_writer_teardown_noop_total 152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 304
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.008949
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 304
telemt_user_connections_total{user="hello"} 129245
telemt_user_connections_current{user="hello"} 7206
telemt_user_octets_from_client{user="hello"} 3462826280 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 39605189844 (36.89 GB)
telemt_user_unique_ips_current{user="hello"} 2224
telemt_user_unique_ips_recent_window{user="hello"} 947
```