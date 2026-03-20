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

# Server Metrics 2026-03-20 10:26:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 548.9 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87836
telemt_connections_bad_total 1187
telemt_connections_current 1600
telemt_connections_me_current 1600
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 204
telemt_upstream_connect_success_total 198
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 203497
telemt_me_route_drop_channel_closed_total 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77226
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
telemt_desync_total 74
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 116
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 116
telemt_me_writer_teardown_success_total{mode="normal"} 113
telemt_me_writer_teardown_noop_total 116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 229
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.854699
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 229
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_user_connections_total{user="hello"} 76939
telemt_user_connections_current{user="hello"} 1600
telemt_user_octets_from_client{user="hello"} 404383412 (385.65 MB)
telemt_user_octets_to_client{user="hello"} 2081099532 (1.94 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 531.7 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68330
telemt_connections_bad_total 9603
telemt_connections_current 4682
telemt_connections_me_current 4682
telemt_handshake_timeouts_total 2030
telemt_upstream_connect_attempt_total 191
telemt_upstream_connect_success_total 190
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 23090
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49534
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
telemt_desync_total 138
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 87
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_me_draining_writers_reap_progress_total 107
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 103
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 107
telemt_me_writer_teardown_success_total{mode="normal"} 107
telemt_me_writer_teardown_noop_total 107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 214
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
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.005543
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 214
telemt_user_connections_total{user="hello"} 49557
telemt_user_connections_current{user="hello"} 4682
telemt_user_octets_from_client{user="hello"} 766132692 (730.64 MB)
telemt_user_octets_to_client{user="hello"} 12842767080 (11.96 GB)
telemt_user_unique_ips_current{user="hello"} 1656
telemt_user_unique_ips_recent_window{user="hello"} 602
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 520.3 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43653
telemt_connections_bad_total 3987
telemt_connections_current 2797
telemt_connections_me_current 2797
telemt_handshake_timeouts_total 541
telemt_upstream_connect_attempt_total 209
telemt_upstream_connect_success_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 15361
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35478
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
telemt_desync_total 103
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_me_draining_writers_reap_progress_total 126
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 126
telemt_me_writer_teardown_success_total{mode="normal"} 126
telemt_me_writer_teardown_noop_total 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 252
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.009774
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 252
telemt_user_connections_total{user="hello"} 35504
telemt_user_connections_current{user="hello"} 2797
telemt_user_octets_from_client{user="hello"} 671853952 (640.73 MB)
telemt_user_octets_to_client{user="hello"} 13252619308 (12.34 GB)
telemt_user_unique_ips_current{user="hello"} 1061
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 326.8 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59975
telemt_connections_bad_total 2654
telemt_connections_current 5494
telemt_connections_me_current 5494
telemt_handshake_timeouts_total 899
telemt_upstream_connect_attempt_total 145
telemt_upstream_connect_success_total 144
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 32886
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52516
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
telemt_desync_total 51
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_draining_writers_reap_progress_total 63
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63
telemt_me_writer_teardown_success_total{mode="normal"} 63
telemt_me_writer_teardown_noop_total 63
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.028519
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126
telemt_user_connections_total{user="hello"} 52528
telemt_user_connections_current{user="hello"} 5494
telemt_user_octets_from_client{user="hello"} 351066232 (334.80 MB)
telemt_user_octets_to_client{user="hello"} 10121262432 (9.43 GB)
telemt_user_unique_ips_current{user="hello"} 1746
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 315.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132000
telemt_connections_bad_total 1193
telemt_connections_current 4682
telemt_connections_me_current 4682
telemt_handshake_timeouts_total 910
telemt_upstream_connect_attempt_total 156
telemt_upstream_connect_success_total 137
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 66
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 193202
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122754
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
telemt_desync_total 45
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_draining_writers_reap_progress_total 59
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59
telemt_me_writer_teardown_success_total{mode="normal"} 59
telemt_me_writer_teardown_noop_total 59
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.069841
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118
telemt_user_connections_total{user="hello"} 122750
telemt_user_connections_current{user="hello"} 4682
telemt_user_octets_from_client{user="hello"} 396181988 (377.83 MB)
telemt_user_octets_to_client{user="hello"} 3578899716 (3.33 GB)
telemt_user_unique_ips_current{user="hello"} 1569
telemt_user_unique_ips_recent_window{user="hello"} 1147
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 303.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99452
telemt_connections_bad_total 1890
telemt_connections_current 6603
telemt_connections_me_current 6603
telemt_handshake_timeouts_total 1194
telemt_upstream_connect_attempt_total 136
telemt_upstream_connect_success_total 133
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 65
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 106213
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84250
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
telemt_desync_total 224
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 55
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54
telemt_me_writer_teardown_success_total{mode="normal"} 55
telemt_me_writer_teardown_noop_total 55
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.001745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110
telemt_user_connections_total{user="hello"} 84246
telemt_user_connections_current{user="hello"} 6603
telemt_user_octets_from_client{user="hello"} 415835244 (396.57 MB)
telemt_user_octets_to_client{user="hello"} 6165293424 (5.74 GB)
telemt_user_unique_ips_current{user="hello"} 1999
telemt_user_unique_ips_recent_window{user="hello"} 926
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 301.3 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7583
telemt_connections_bad_total 1273
telemt_connections_current 809
telemt_connections_me_current 809
telemt_handshake_timeouts_total 62
telemt_upstream_connect_attempt_total 155
telemt_upstream_connect_success_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 87
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 2191
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5746
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
telemt_desync_total 11
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 71
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70
telemt_me_writer_teardown_success_total{mode="normal"} 71
telemt_me_writer_teardown_noop_total 71
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.003866
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142
telemt_user_connections_total{user="hello"} 5746
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 31159808 (29.72 MB)
telemt_user_octets_to_client{user="hello"} 685556340 (653.80 MB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 293.9 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56560
telemt_connections_bad_total 3519
telemt_connections_current 6669
telemt_connections_me_current 6669
telemt_handshake_timeouts_total 754
telemt_upstream_connect_attempt_total 144
telemt_upstream_connect_success_total 133
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 33002
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49998
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
telemt_desync_total 98
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_me_draining_writers_reap_progress_total 56
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56
telemt_me_writer_teardown_success_total{mode="normal"} 56
telemt_me_writer_teardown_noop_total 56
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.002347
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112
telemt_user_connections_total{user="hello"} 49996
telemt_user_connections_current{user="hello"} 6669
telemt_user_octets_from_client{user="hello"} 1237411700 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 10727229228 (9.99 GB)
telemt_user_unique_ips_current{user="hello"} 2033
telemt_user_unique_ips_recent_window{user="hello"} 809
```