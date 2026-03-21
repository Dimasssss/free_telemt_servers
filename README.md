# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
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

## rdp-onedash.ru (2 сервера)
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

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-21 07:49:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 40415.6 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964290
telemt_connections_bad_total 50456
telemt_connections_current 1540
telemt_connections_me_current 1540
telemt_handshake_timeouts_total 44230
telemt_upstream_connect_attempt_total 15998
telemt_upstream_connect_success_total 15927
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 15975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 523
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 268
telemt_me_idle_close_by_peer_total 268
telemt_me_route_drop_no_conn_total 302960
telemt_me_route_drop_channel_closed_total 114
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 698229
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 281
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 328
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 3063
telemt_desync_full_logged_total 1102
telemt_desync_suppressed_total 1961
telemt_desync_frames_bucket_total{bucket="1_2"} 640
telemt_desync_frames_bucket_total{bucket="3_10"} 1178
telemt_desync_frames_bucket_total{bucket="gt_10"} 1245
telemt_pool_swap_total 44
telemt_pool_force_close_total 1220
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 14439
telemt_me_writer_removed_unexpected_total 251
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1076
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13570
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13219
telemt_me_writer_teardown_success_total{mode="normal"} 14646
telemt_me_writer_teardown_noop_total 14440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29086
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.251572
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29086
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 228
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 697454
telemt_user_connections_current{user="hello"} 1540
telemt_user_octets_from_client{user="hello"} 9119656880 (8.49 GB)
telemt_user_octets_to_client{user="hello"} 218118085580 (203.14 GB)
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 40416.8 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2359408
telemt_connections_bad_total 261524
telemt_connections_current 4415
telemt_connections_me_current 4415
telemt_handshake_timeouts_total 70077
telemt_upstream_connect_attempt_total 14992
telemt_upstream_connect_success_total 14923
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 14971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 886
telemt_me_reconnect_success_total 326
telemt_me_reader_eof_total 324
telemt_me_idle_close_by_peer_total 323
telemt_me_route_drop_no_conn_total 533494
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1478037
telemt_me_endpoint_quarantine_total 266
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 320
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 6400
telemt_desync_full_logged_total 2222
telemt_desync_suppressed_total 4178
telemt_desync_frames_bucket_total{bucket="1_2"} 1309
telemt_desync_frames_bucket_total{bucket="3_10"} 2502
telemt_desync_frames_bucket_total{bucket="gt_10"} 2589
telemt_pool_swap_total 43
telemt_pool_force_close_total 1285
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 13425
telemt_me_writer_removed_unexpected_total 303
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1208
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12514
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1218
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12140
telemt_me_writer_teardown_success_total{mode="normal"} 13722
telemt_me_writer_teardown_noop_total 13425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27147
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.530745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27147
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 266
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 1474815
telemt_user_connections_current{user="hello"} 4415
telemt_user_octets_from_client{user="hello"} 20174172432 (18.79 GB)
telemt_user_octets_to_client{user="hello"} 596651276132 (555.67 GB)
telemt_user_unique_ips_current{user="hello"} 1539
telemt_user_unique_ips_recent_window{user="hello"} 587
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 40413.2 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1634626
telemt_connections_bad_total 182377
telemt_connections_current 4061
telemt_connections_me_current 4061
telemt_handshake_timeouts_total 69990
telemt_upstream_connect_attempt_total 16064
telemt_upstream_connect_success_total 16054
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 493
telemt_me_reconnect_success_total 261
telemt_me_reader_eof_total 270
telemt_me_idle_close_by_peer_total 270
telemt_me_route_drop_no_conn_total 437379
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1273419
telemt_me_endpoint_quarantine_total 283
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 321
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 5265
telemt_desync_full_logged_total 1876
telemt_desync_suppressed_total 3389
telemt_desync_frames_bucket_total{bucket="1_2"} 1179
telemt_desync_frames_bucket_total{bucket="3_10"} 2005
telemt_desync_frames_bucket_total{bucket="gt_10"} 2081
telemt_pool_swap_total 44
telemt_pool_force_close_total 1243
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 14631
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1141
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13656
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1225
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13388
telemt_me_writer_teardown_success_total{mode="normal"} 14797
telemt_me_writer_teardown_noop_total 14634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29431
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.224523
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29431
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 224
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1271019
telemt_user_connections_current{user="hello"} 4061
telemt_user_octets_from_client{user="hello"} 17620075688 (16.41 GB)
telemt_user_octets_to_client{user="hello"} 553450395040 (515.44 GB)
telemt_user_unique_ips_current{user="hello"} 1539
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 40414.3 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1405879
telemt_connections_bad_total 164177
telemt_connections_current 3199
telemt_connections_me_current 3199
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 63165
telemt_upstream_connect_attempt_total 20930
telemt_upstream_connect_success_total 20702
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 20822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 735
telemt_me_reconnect_success_total 316
telemt_me_reader_eof_total 300
telemt_me_idle_close_by_peer_total 300
telemt_me_route_drop_no_conn_total 400412
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 975647
telemt_me_endpoint_quarantine_total 290
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 324
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 4471
telemt_desync_full_logged_total 1592
telemt_desync_suppressed_total 2879
telemt_desync_frames_bucket_total{bucket="1_2"} 1031
telemt_desync_frames_bucket_total{bucket="3_10"} 1862
telemt_desync_frames_bucket_total{bucket="gt_10"} 1578
telemt_pool_swap_total 44
telemt_pool_force_close_total 1134
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 14521
telemt_me_writer_removed_unexpected_total 292
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1104
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13723
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1104
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13387
telemt_me_writer_teardown_success_total{mode="normal"} 14827
telemt_me_writer_teardown_noop_total 14522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29349
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.746830
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29349
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 978357
telemt_user_connections_current{user="hello"} 3199
telemt_user_octets_from_client{user="hello"} 17002958549 (15.84 GB)
telemt_user_octets_to_client{user="hello"} 462945951499 (431.15 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1175
telemt_user_unique_ips_recent_window{user="hello"} 415
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 40378.3 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1346505
telemt_connections_bad_total 153075
telemt_connections_current 3054
telemt_connections_me_current 3054
telemt_handshake_timeouts_total 47251
telemt_upstream_connect_attempt_total 16879
telemt_upstream_connect_success_total 16870
telemt_upstream_connect_attempts_per_request{bucket="1"} 16870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 330
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 247
telemt_me_idle_close_by_peer_total 247
telemt_me_route_drop_no_conn_total 295192
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 966767
telemt_me_endpoint_quarantine_total 326
telemt_me_single_endpoint_shadow_rotate_total 317
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 4634
telemt_desync_full_logged_total 1671
telemt_desync_suppressed_total 2963
telemt_desync_frames_bucket_total{bucket="1_2"} 1165
telemt_desync_frames_bucket_total{bucket="3_10"} 1809
telemt_desync_frames_bucket_total{bucket="gt_10"} 1660
telemt_pool_swap_total 44
telemt_pool_force_close_total 1108
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 15296
telemt_me_writer_removed_unexpected_total 227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1015
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14530
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14188
telemt_me_writer_teardown_success_total{mode="normal"} 15545
telemt_me_writer_teardown_noop_total 15299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30844
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.485791
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30844
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 965099
telemt_user_connections_current{user="hello"} 3054
telemt_user_octets_from_client{user="hello"} 25570520620 (23.81 GB)
telemt_user_octets_to_client{user="hello"} 505177521516 (470.48 GB)
telemt_user_unique_ips_current{user="hello"} 1177
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 40417.6 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3341144
telemt_connections_bad_total 199983
telemt_connections_current 5636
telemt_connections_me_current 5636
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 178474
telemt_upstream_connect_attempt_total 42395
telemt_upstream_connect_success_total 40482
telemt_upstream_connect_fail_total 1354
telemt_upstream_connect_attempts_per_request{bucket="1"} 41836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1354
telemt_me_reconnect_attempts_total 1983
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 430
telemt_me_idle_close_by_peer_total 429
telemt_me_route_drop_no_conn_total 4067391
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2733828
telemt_me_endpoint_quarantine_total 320
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 324
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_me_writers_active_current 52
telemt_desync_total 6263
telemt_desync_full_logged_total 2206
telemt_desync_suppressed_total 4057
telemt_desync_frames_bucket_total{bucket="1_2"} 1409
telemt_desync_frames_bucket_total{bucket="3_10"} 2652
telemt_desync_frames_bucket_total{bucket="gt_10"} 2202
telemt_pool_swap_total 43
telemt_pool_force_close_total 1220
telemt_me_writer_close_signal_drop_total 201
telemt_me_draining_writers_reap_progress_total 13623
telemt_me_writer_removed_unexpected_total 646
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1596
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12637
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12403
telemt_me_writer_teardown_success_total{mode="normal"} 14233
telemt_me_writer_teardown_noop_total 13628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27861
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.308497
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27861
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 201
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 433
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 2756284
telemt_user_connections_current{user="hello"} 5637
telemt_user_octets_from_client{user="hello"} 37525808950 (34.95 GB)
telemt_user_octets_to_client{user="hello"} 497017671010 (462.88 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1803
telemt_user_unique_ips_recent_window{user="hello"} 1273
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 40385.1 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1437867
telemt_connections_bad_total 204719
telemt_connections_current 3188
telemt_connections_me_current 3188
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 28921
telemt_upstream_connect_attempt_total 18669
telemt_upstream_connect_success_total 18504
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 18653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_reconnect_attempts_total 1640
telemt_me_reconnect_success_total 512
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 361745
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1046904
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 323
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 4498
telemt_desync_full_logged_total 1696
telemt_desync_suppressed_total 2802
telemt_desync_frames_bucket_total{bucket="1_2"} 873
telemt_desync_frames_bucket_total{bucket="3_10"} 1815
telemt_desync_frames_bucket_total{bucket="gt_10"} 1810
telemt_pool_swap_total 42
telemt_pool_force_close_total 1058
telemt_me_writer_close_signal_drop_total 65
telemt_me_draining_writers_reap_progress_total 15395
telemt_me_writer_removed_unexpected_total 507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1316
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14607
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14337
telemt_me_writer_teardown_success_total{mode="normal"} 15923
telemt_me_writer_teardown_noop_total 15395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31318
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.104671
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31318
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 65
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 433
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 1044292
telemt_user_connections_current{user="hello"} 3188
telemt_user_octets_from_client{user="hello"} 17311918936 (16.12 GB)
telemt_user_octets_to_client{user="hello"} 503655984966 (469.07 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1244
telemt_user_unique_ips_recent_window{user="hello"} 465
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 40379.6 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1857199
telemt_connections_bad_total 123187
telemt_connections_current 2936
telemt_connections_me_current 2936
telemt_handshake_timeouts_total 682694
telemt_upstream_connect_attempt_total 17498
telemt_upstream_connect_success_total 17470
telemt_upstream_connect_attempts_per_request{bucket="1"} 17470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 271
telemt_me_reconnect_attempts_total 365
telemt_me_reconnect_success_total 256
telemt_me_reader_eof_total 265
telemt_me_idle_close_by_peer_total 265
telemt_me_route_drop_no_conn_total 325970
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 925888
telemt_me_endpoint_quarantine_total 337
telemt_me_single_endpoint_shadow_rotate_total 326
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 4483
telemt_desync_full_logged_total 1590
telemt_desync_suppressed_total 2893
telemt_desync_frames_bucket_total{bucket="1_2"} 779
telemt_desync_frames_bucket_total{bucket="3_10"} 1831
telemt_desync_frames_bucket_total{bucket="gt_10"} 1873
telemt_pool_swap_total 44
telemt_pool_force_close_total 1036
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 15682
telemt_me_writer_removed_unexpected_total 248
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 941
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15007
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14646
telemt_me_writer_teardown_success_total{mode="normal"} 15948
telemt_me_writer_teardown_noop_total 15682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.589962
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 230
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 922735
telemt_user_connections_current{user="hello"} 2936
telemt_user_octets_from_client{user="hello"} 15886742732 (14.80 GB)
telemt_user_octets_to_client{user="hello"} 472592850276 (440.14 GB)
telemt_user_unique_ips_current{user="hello"} 1157
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 38371.1 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378461
telemt_connections_bad_total 12807
telemt_connections_current 630
telemt_connections_me_current 630
telemt_handshake_timeouts_total 114080
telemt_upstream_connect_attempt_total 19224
telemt_upstream_connect_success_total 19223
telemt_upstream_connect_attempts_per_request{bucket="1"} 19223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 731
telemt_me_reconnect_success_total 300
telemt_me_reader_eof_total 304
telemt_me_idle_close_by_peer_total 304
telemt_me_route_drop_no_conn_total 86549
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225322
telemt_me_endpoint_quarantine_total 377
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 332
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 1408
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 791
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 559
telemt_pool_swap_total 42
telemt_pool_force_close_total 875
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 52
telemt_me_draining_writers_reap_progress_total 17163
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1209
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16243
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 875
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16288
telemt_me_writer_teardown_success_total{mode="normal"} 17452
telemt_me_writer_teardown_noop_total 17163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.331854
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 52
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 252
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 225535
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 2886512807 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 95432380173 (88.88 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 40389.5 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1457891
telemt_connections_bad_total 115271
telemt_connections_current 3292
telemt_connections_me_current 3292
telemt_handshake_timeouts_total 37978
telemt_upstream_connect_attempt_total 17992
telemt_upstream_connect_success_total 17911
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 17963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 603
telemt_me_reconnect_success_total 359
telemt_me_reader_eof_total 341
telemt_me_idle_close_by_peer_total 341
telemt_me_route_drop_no_conn_total 331679
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1143741
telemt_me_endpoint_quarantine_total 326
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 323
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 4634
telemt_desync_full_logged_total 1546
telemt_desync_suppressed_total 3088
telemt_desync_frames_bucket_total{bucket="1_2"} 1168
telemt_desync_frames_bucket_total{bucket="3_10"} 1743
telemt_desync_frames_bucket_total{bucket="gt_10"} 1723
telemt_pool_swap_total 44
telemt_pool_force_close_total 1049
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 83
telemt_me_draining_writers_reap_progress_total 16245
telemt_me_writer_removed_unexpected_total 341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1148
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15446
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1039
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15196
telemt_me_writer_teardown_success_total{mode="normal"} 16594
telemt_me_writer_teardown_noop_total 16245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32839
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.670253
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32839
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 83
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 326
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 1138995
telemt_user_connections_current{user="hello"} 3292
telemt_user_octets_from_client{user="hello"} 18812969456 (17.52 GB)
telemt_user_octets_to_client{user="hello"} 527092058668 (490.89 GB)
telemt_user_unique_ips_current{user="hello"} 1257
telemt_user_unique_ips_recent_window{user="hello"} 482
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 40386.3 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1395430
telemt_connections_bad_total 102189
telemt_connections_current 3492
telemt_connections_me_current 3492
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 36163
telemt_upstream_connect_attempt_total 26429
telemt_upstream_connect_success_total 26237
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 2631
telemt_me_reconnect_success_total 472
telemt_me_reader_eof_total 415
telemt_me_idle_close_by_peer_total 415
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 336554
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1113466
telemt_me_endpoint_quarantine_total 387
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 320
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 4429
telemt_desync_full_logged_total 1408
telemt_desync_suppressed_total 3021
telemt_desync_frames_bucket_total{bucket="1_2"} 1265
telemt_desync_frames_bucket_total{bucket="3_10"} 1609
telemt_desync_frames_bucket_total{bucket="gt_10"} 1555
telemt_pool_swap_total 44
telemt_pool_force_close_total 1016
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 15355
telemt_me_writer_removed_unexpected_total 427
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1344
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14460
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 995
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14339
telemt_me_writer_teardown_success_total{mode="normal"} 15804
telemt_me_writer_teardown_noop_total 15355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31159
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.003851
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31159
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 123
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1117987
telemt_user_connections_current{user="hello"} 3492
telemt_user_octets_from_client{user="hello"} 14588297275 (13.59 GB)
telemt_user_octets_to_client{user="hello"} 495789705011 (461.74 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1305
telemt_user_unique_ips_recent_window{user="hello"} 482
```