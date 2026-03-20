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

# Server Metrics 2026-03-20 10:31:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 857.0 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106080
telemt_connections_bad_total 2151
telemt_connections_current 1508
telemt_connections_me_current 1508
telemt_handshake_timeouts_total 738
telemt_upstream_connect_attempt_total 283
telemt_upstream_connect_success_total 277
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 169
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 223911
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92673
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 44
telemt_desync_total 143
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_me_writer_close_signal_drop_total 10
telemt_me_draining_writers_reap_progress_total 174
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 162
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 174
telemt_me_writer_teardown_success_total{mode="normal"} 173
telemt_me_writer_teardown_noop_total 174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 347
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.651841
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 347
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 10
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 92384
telemt_user_connections_current{user="hello"} 1508
telemt_user_octets_from_client{user="hello"} 474667656 (452.68 MB)
telemt_user_octets_to_client{user="hello"} 4123174384 (3.84 GB)
telemt_user_unique_ips_current{user="hello"} 563
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 839.5 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101090
telemt_connections_bad_total 13053
telemt_connections_current 4742
telemt_connections_me_current 4742
telemt_handshake_timeouts_total 3130
telemt_upstream_connect_attempt_total 255
telemt_upstream_connect_success_total 254
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 36274
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73564
telemt_me_endpoint_quarantine_total 5
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
telemt_me_writers_active_current 43
telemt_desync_total 216
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_me_draining_writers_reap_progress_total 153
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 147
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 153
telemt_me_writer_teardown_success_total{mode="normal"} 156
telemt_me_writer_teardown_noop_total 153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 309
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.008107
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 309
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 73585
telemt_user_connections_current{user="hello"} 4742
telemt_user_octets_from_client{user="hello"} 1142560468 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 19538753576 (18.20 GB)
telemt_user_unique_ips_current{user="hello"} 1624
telemt_user_unique_ips_recent_window{user="hello"} 732
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 827.9 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74375
telemt_connections_bad_total 10836
telemt_connections_current 2959
telemt_connections_me_current 2959
telemt_handshake_timeouts_total 809
telemt_upstream_connect_attempt_total 292
telemt_upstream_connect_success_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 134
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 26487
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55886
telemt_me_single_endpoint_shadow_rotate_total 5
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
telemt_desync_total 181
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_me_draining_writers_reap_progress_total 189
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 185
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 189
telemt_me_writer_teardown_success_total{mode="normal"} 192
telemt_me_writer_teardown_noop_total 189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 381
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.012728
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 381
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 55929
telemt_user_connections_current{user="hello"} 2959
telemt_user_octets_from_client{user="hello"} 925843312 (882.95 MB)
telemt_user_octets_to_client{user="hello"} 20682117488 (19.26 GB)
telemt_user_unique_ips_current{user="hello"} 1160
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 633.6 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102633
telemt_connections_bad_total 7784
telemt_connections_current 5427
telemt_connections_me_current 5427
telemt_handshake_timeouts_total 1881
telemt_upstream_connect_attempt_total 198
telemt_upstream_connect_success_total 197
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 51863
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86293
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
telemt_me_writers_active_current 43
telemt_desync_total 145
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_me_draining_writers_reap_progress_total 112
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 112
telemt_me_writer_teardown_success_total{mode="normal"} 112
telemt_me_writer_teardown_noop_total 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 224
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.037734
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 224
telemt_user_connections_total{user="hello"} 86301
telemt_user_connections_current{user="hello"} 5427
telemt_user_octets_from_client{user="hello"} 755962220 (720.94 MB)
telemt_user_octets_to_client{user="hello"} 23410103228 (21.80 GB)
telemt_user_unique_ips_current{user="hello"} 1777
telemt_user_unique_ips_recent_window{user="hello"} 783
```

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 618.9 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247487
telemt_connections_bad_total 2738
telemt_connections_current 6157
telemt_connections_me_current 6157
telemt_handshake_timeouts_total 1936
telemt_upstream_connect_attempt_total 222
telemt_upstream_connect_success_total 197
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 413410
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227991
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
telemt_desync_total 102
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_draining_writers_reap_progress_total 107
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 107
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 107
telemt_me_writer_teardown_success_total{mode="normal"} 109
telemt_me_writer_teardown_noop_total 107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 216
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.091408
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 216
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 227982
telemt_user_connections_current{user="hello"} 6157
telemt_user_octets_from_client{user="hello"} 1020436064 (973.16 MB)
telemt_user_octets_to_client{user="hello"} 7048794712 (6.56 GB)
telemt_user_unique_ips_current{user="hello"} 1747
telemt_user_unique_ips_recent_window{user="hello"} 1116
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 611.0 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192015
telemt_connections_bad_total 3993
telemt_connections_current 6937
telemt_connections_me_current 6937
telemt_handshake_timeouts_total 2845
telemt_upstream_connect_attempt_total 184
telemt_upstream_connect_success_total 181
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 247694
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166690
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
telemt_desync_total 422
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 103
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 102
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 102
telemt_me_writer_teardown_success_total{mode="normal"} 103
telemt_me_writer_teardown_noop_total 103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 206
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.003036
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 206
telemt_user_connections_total{user="hello"} 166693
telemt_user_connections_current{user="hello"} 6937
telemt_user_octets_from_client{user="hello"} 885761032 (844.73 MB)
telemt_user_octets_to_client{user="hello"} 12841074508 (11.96 GB)
telemt_user_unique_ips_current{user="hello"} 2077
telemt_user_unique_ips_recent_window{user="hello"} 1250
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 611.3 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15546
telemt_connections_bad_total 3517
telemt_connections_current 852
telemt_connections_me_current 852
telemt_handshake_timeouts_total 238
telemt_upstream_connect_attempt_total 236
telemt_upstream_connect_success_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 148
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 4872
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10872
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
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 152
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 151
telemt_me_writer_teardown_success_total{mode="normal"} 152
telemt_me_writer_teardown_noop_total 152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 303
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
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.015671
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 304
telemt_user_connections_total{user="hello"} 10873
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 87109952 (83.07 MB)
telemt_user_octets_to_client{user="hello"} 1579960504 (1.47 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 601.9 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121545
telemt_connections_bad_total 26899
telemt_connections_current 7185
telemt_connections_me_current 7185
telemt_handshake_timeouts_total 1368
telemt_upstream_connect_attempt_total 195
telemt_upstream_connect_success_total 184
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 57202
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88588
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
telemt_desync_total 231
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_me_draining_writers_reap_progress_total 107
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 105
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 107
telemt_me_writer_teardown_success_total{mode="normal"} 107
telemt_me_writer_teardown_noop_total 107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 214
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.007943
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 214
telemt_user_connections_total{user="hello"} 88597
telemt_user_connections_current{user="hello"} 7185
telemt_user_octets_from_client{user="hello"} 2770436816 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 24651536772 (22.96 GB)
telemt_user_unique_ips_current{user="hello"} 2161
telemt_user_unique_ips_recent_window{user="hello"} 972
```