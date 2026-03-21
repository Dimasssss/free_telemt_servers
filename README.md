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

# Server Metrics 2026-03-21 11:23:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 53264.4 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1618905
telemt_connections_bad_total 81024
telemt_connections_current 1527
telemt_connections_me_current 1527
telemt_handshake_timeouts_total 64288
telemt_upstream_connect_attempt_total 20844
telemt_upstream_connect_success_total 20737
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 20806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1055
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 449
telemt_me_idle_close_by_peer_total 449
telemt_me_route_drop_no_conn_total 995613
telemt_me_route_drop_channel_closed_total 378
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1245253
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 422
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_me_writers_active_current 42
telemt_desync_total 5034
telemt_desync_full_logged_total 1765
telemt_desync_suppressed_total 3269
telemt_desync_frames_bucket_total{bucket="1_2"} 1055
telemt_desync_frames_bucket_total{bucket="3_10"} 1949
telemt_desync_frames_bucket_total{bucket="gt_10"} 2030
telemt_pool_swap_total 58
telemt_pool_force_close_total 1669
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 297
telemt_me_draining_writers_reap_progress_total 18606
telemt_me_writer_removed_unexpected_total 429
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1516
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17378
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1608
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16937
telemt_me_writer_teardown_success_total{mode="normal"} 18894
telemt_me_writer_teardown_noop_total 18610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37504
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 121.454834
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37504
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 297
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 397
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1244363
telemt_user_connections_current{user="hello"} 1527
telemt_user_octets_from_client{user="hello"} 17488118483 (16.29 GB)
telemt_user_octets_to_client{user="hello"} 340715910691 (317.32 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 577
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1155.4 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100107
telemt_connections_bad_total 4098
telemt_connections_current 1223
telemt_connections_me_current 1223
telemt_handshake_timeouts_total 3232
telemt_upstream_connect_attempt_total 443
telemt_upstream_connect_success_total 442
telemt_upstream_connect_attempts_per_request{bucket="1"} 442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 71480
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87480
telemt_me_endpoint_quarantine_total 11
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
telemt_me_writers_active_current 45
telemt_desync_total 327
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 328
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 296
telemt_me_writer_teardown_success_total{mode="normal"} 337
telemt_me_writer_teardown_noop_total 328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 665
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.149053
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 665
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_writer_restored_same_endpoint_total 7
telemt_user_connections_total{user="hello"} 87444
telemt_user_connections_current{user="hello"} 1223
telemt_user_octets_from_client{user="hello"} 1092279612 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 20033386956 (18.66 GB)
telemt_user_unique_ips_current{user="hello"} 723
telemt_user_unique_ips_recent_window{user="hello"} 393
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 53262.2 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3085307
telemt_connections_bad_total 335610
telemt_connections_current 4278
telemt_connections_me_current 4278
telemt_handshake_timeouts_total 112096
telemt_upstream_connect_attempt_total 20335
telemt_upstream_connect_success_total 20322
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 690
telemt_me_reconnect_success_total 385
telemt_me_reader_eof_total 396
telemt_me_idle_close_by_peer_total 396
telemt_me_route_drop_no_conn_total 1335184
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2453800
telemt_me_endpoint_quarantine_total 350
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 413
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 10726
telemt_desync_full_logged_total 3621
telemt_desync_suppressed_total 7105
telemt_desync_frames_bucket_total{bucket="1_2"} 2222
telemt_desync_frames_bucket_total{bucket="3_10"} 4210
telemt_desync_frames_bucket_total{bucket="gt_10"} 4294
telemt_pool_swap_total 58
telemt_pool_force_close_total 1743
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 244
telemt_me_draining_writers_reap_progress_total 18474
telemt_me_writer_removed_unexpected_total 373
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1522
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17185
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16731
telemt_me_writer_teardown_success_total{mode="normal"} 18707
telemt_me_writer_teardown_noop_total 18487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37194
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.080975
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37194
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 244
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 2450381
telemt_user_connections_current{user="hello"} 4278
telemt_user_octets_from_client{user="hello"} 39910385768 (37.17 GB)
telemt_user_octets_to_client{user="hello"} 897194979252 (835.58 GB)
telemt_user_unique_ips_current{user="hello"} 1777
telemt_user_unique_ips_recent_window{user="hello"} 539
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 53263.4 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2555262
telemt_connections_bad_total 283555
telemt_connections_current 3473
telemt_connections_me_current 3473
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 106192
telemt_upstream_connect_attempt_total 25292
telemt_upstream_connect_success_total 25036
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 25167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 428
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1068
telemt_me_reconnect_success_total 496
telemt_me_reader_eof_total 455
telemt_me_idle_close_by_peer_total 455
telemt_me_route_drop_no_conn_total 745440
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1801396
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 411
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
telemt_desync_total 8231
telemt_desync_full_logged_total 2825
telemt_desync_suppressed_total 5406
telemt_desync_frames_bucket_total{bucket="1_2"} 2057
telemt_desync_frames_bucket_total{bucket="3_10"} 3223
telemt_desync_frames_bucket_total{bucket="gt_10"} 2951
telemt_pool_swap_total 58
telemt_pool_force_close_total 1579
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 122
telemt_me_draining_writers_reap_progress_total 18270
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1526
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17207
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 105
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16691
telemt_me_writer_teardown_success_total{mode="normal"} 18733
telemt_me_writer_teardown_noop_total 18271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37004
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.997782
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37004
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 122
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 416
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1802931
telemt_user_connections_current{user="hello"} 3473
telemt_user_octets_from_client{user="hello"} 34515674969 (32.15 GB)
telemt_user_octets_to_client{user="hello"} 865741382951 (806.28 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1341
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 53227.2 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2492569
telemt_connections_bad_total 282728
telemt_connections_current 3250
telemt_connections_me_current 3250
telemt_handshake_timeouts_total 73759
telemt_upstream_connect_attempt_total 21684
telemt_upstream_connect_success_total 21629
telemt_upstream_connect_attempts_per_request{bucket="1"} 21629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 783
telemt_me_reconnect_success_total 529
telemt_me_reader_eof_total 470
telemt_me_idle_close_by_peer_total 470
telemt_me_route_drop_no_conn_total 724636
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1793425
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 404
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 8454
telemt_desync_full_logged_total 2866
telemt_desync_suppressed_total 5588
telemt_desync_frames_bucket_total{bucket="1_2"} 2237
telemt_desync_frames_bucket_total{bucket="3_10"} 3230
telemt_desync_frames_bucket_total{bucket="gt_10"} 2987
telemt_pool_swap_total 57
telemt_pool_force_close_total 1553
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 19412
telemt_me_writer_removed_unexpected_total 446
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1540
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18350
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1436
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17859
telemt_me_writer_teardown_success_total{mode="normal"} 19890
telemt_me_writer_teardown_noop_total 19415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39305
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.389308
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39305
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1790672
telemt_user_connections_current{user="hello"} 3250
telemt_user_octets_from_client{user="hello"} 40850874572 (38.05 GB)
telemt_user_octets_to_client{user="hello"} 872248124944 (812.34 GB)
telemt_user_unique_ips_current{user="hello"} 1310
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 53266.5 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7905448
telemt_connections_bad_total 534804
telemt_connections_current 5181
telemt_connections_me_current 5181
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 279629
telemt_upstream_connect_attempt_total 63661
telemt_upstream_connect_success_total 59960
telemt_upstream_connect_fail_total 2945
telemt_upstream_connect_attempts_per_request{bucket="1"} 62905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2945
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3164
telemt_me_reconnect_success_total 1092
telemt_me_reader_eof_total 789
telemt_me_idle_close_by_peer_total 788
telemt_me_route_drop_no_conn_total 13652761
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6581470
telemt_me_endpoint_quarantine_total 418
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 121
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 121
telemt_me_single_endpoint_shadow_rotate_total 419
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 12577
telemt_desync_full_logged_total 4049
telemt_desync_suppressed_total 8528
telemt_desync_frames_bucket_total{bucket="1_2"} 2737
telemt_desync_frames_bucket_total{bucket="3_10"} 5538
telemt_desync_frames_bucket_total{bucket="gt_10"} 4302
telemt_pool_swap_total 54
telemt_pool_force_close_total 1664
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 345
telemt_me_draining_writers_reap_progress_total 17796
telemt_me_writer_removed_unexpected_total 1055
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2291
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16132
telemt_me_writer_teardown_success_total{mode="normal"} 18747
telemt_me_writer_teardown_noop_total 17805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.450781
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 345
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 768
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 6617264
telemt_user_connections_current{user="hello"} 5181
telemt_user_octets_from_client{user="hello"} 55441343028 (51.63 GB)
telemt_user_octets_to_client{user="hello"} 639299613139 (595.39 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1867
telemt_user_unique_ips_recent_window{user="hello"} 961
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 53234.3 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2501375
telemt_connections_bad_total 301387
telemt_connections_current 3880
telemt_connections_me_current 3880
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 54223
telemt_upstream_connect_attempt_total 23139
telemt_upstream_connect_success_total 22895
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 23114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_reconnect_attempts_total 2229
telemt_me_reconnect_success_total 752
telemt_me_reader_eof_total 748
telemt_me_idle_close_by_peer_total 748
telemt_me_route_drop_no_conn_total 859977
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1896133
telemt_me_endpoint_quarantine_total 342
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 409
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 8694
telemt_desync_full_logged_total 3140
telemt_desync_suppressed_total 5554
telemt_desync_frames_bucket_total{bucket="1_2"} 1673
telemt_desync_frames_bucket_total{bucket="3_10"} 3505
telemt_desync_frames_bucket_total{bucket="gt_10"} 3516
telemt_pool_swap_total 55
telemt_pool_force_close_total 1483
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 19224
telemt_me_writer_removed_unexpected_total 724
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1801
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18171
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17741
telemt_me_writer_teardown_success_total{mode="normal"} 19972
telemt_me_writer_teardown_noop_total 19224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39196
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.936206
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39196
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 631
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1881544
telemt_user_connections_current{user="hello"} 3880
telemt_user_octets_from_client{user="hello"} 34222668012 (31.87 GB)
telemt_user_octets_to_client{user="hello"} 846489068374 (788.35 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1525
telemt_user_unique_ips_recent_window{user="hello"} 747
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 53228.7 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3697415
telemt_connections_bad_total 193978
telemt_connections_current 2517
telemt_connections_me_current 2517
telemt_handshake_timeouts_total 1585980
telemt_upstream_connect_attempt_total 21723
telemt_upstream_connect_success_total 21689
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 770
telemt_me_reconnect_success_total 387
telemt_me_reader_eof_total 386
telemt_me_idle_close_by_peer_total 386
telemt_me_route_drop_no_conn_total 709859
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1683205
telemt_me_endpoint_quarantine_total 410
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 417
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
telemt_desync_total 8237
telemt_desync_full_logged_total 2942
telemt_desync_suppressed_total 5295
telemt_desync_frames_bucket_total{bucket="1_2"} 1504
telemt_desync_frames_bucket_total{bucket="3_10"} 3281
telemt_desync_frames_bucket_total{bucket="gt_10"} 3452
telemt_pool_swap_total 58
telemt_pool_force_close_total 1433
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 19411
telemt_me_writer_removed_unexpected_total 374
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1295
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18511
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1386
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17978
telemt_me_writer_teardown_success_total{mode="normal"} 19806
telemt_me_writer_teardown_noop_total 19411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39217
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.041207
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39217
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 1677739
telemt_user_connections_current{user="hello"} 2517
telemt_user_octets_from_client{user="hello"} 29816215364 (27.77 GB)
telemt_user_octets_to_client{user="hello"} 814313232356 (758.39 GB)
telemt_user_unique_ips_current{user="hello"} 1035
telemt_user_unique_ips_recent_window{user="hello"} 639
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 51220.1 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768361
telemt_connections_bad_total 43105
telemt_connections_current 709
telemt_connections_me_current 709
telemt_handshake_timeouts_total 281660
telemt_upstream_connect_attempt_total 24641
telemt_upstream_connect_success_total 24639
telemt_upstream_connect_attempts_per_request{bucket="1"} 24639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1073
telemt_me_reconnect_success_total 406
telemt_me_reader_eof_total 401
telemt_me_idle_close_by_peer_total 401
telemt_me_route_drop_no_conn_total 160988
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382468
telemt_me_endpoint_quarantine_total 479
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 437
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
telemt_desync_total 2594
telemt_desync_full_logged_total 1003
telemt_desync_suppressed_total 1591
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 931
telemt_desync_frames_bucket_total{bucket="gt_10"} 1250
telemt_pool_swap_total 56
telemt_pool_force_close_total 1242
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 22062
telemt_me_writer_removed_unexpected_total 382
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1608
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20840
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20820
telemt_me_writer_teardown_success_total{mode="normal"} 22448
telemt_me_writer_teardown_noop_total 22062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44510
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.463930
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44510
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 328
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 382552
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 5670066683 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 147860613965 (137.71 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 53238.6 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2656121
telemt_connections_bad_total 247078
telemt_connections_current 4004
telemt_connections_me_current 4004
telemt_handshake_timeouts_total 65083
telemt_upstream_connect_attempt_total 22482
telemt_upstream_connect_success_total 22387
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 22452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 920
telemt_me_reconnect_success_total 504
telemt_me_reader_eof_total 470
telemt_me_idle_close_by_peer_total 470
telemt_me_route_drop_no_conn_total 703864
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2102484
telemt_me_endpoint_quarantine_total 419
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 416
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
telemt_me_writers_active_current 44
telemt_desync_total 8377
telemt_desync_full_logged_total 2791
telemt_desync_suppressed_total 5586
telemt_desync_frames_bucket_total{bucket="1_2"} 2009
telemt_desync_frames_bucket_total{bucket="3_10"} 3123
telemt_desync_frames_bucket_total{bucket="gt_10"} 3245
telemt_pool_swap_total 59
telemt_pool_force_close_total 1453
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 20190
telemt_me_writer_removed_unexpected_total 462
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1537
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19131
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1426
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18737
telemt_me_writer_teardown_success_total{mode="normal"} 20668
telemt_me_writer_teardown_noop_total 20190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40858
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.455056
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40858
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 449
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2096163
telemt_user_connections_current{user="hello"} 4004
telemt_user_octets_from_client{user="hello"} 44264642352 (41.22 GB)
telemt_user_octets_to_client{user="hello"} 980787925260 (913.43 GB)
telemt_user_unique_ips_current{user="hello"} 1537
telemt_user_unique_ips_recent_window{user="hello"} 768
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 53235.2 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2432530
telemt_connections_bad_total 190492
telemt_connections_current 3544
telemt_connections_me_current 3544
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 63996
telemt_upstream_connect_attempt_total 38617
telemt_upstream_connect_success_total 38382
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 38574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12814
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 584
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_reconnect_attempts_total 3201
telemt_me_reconnect_success_total 658
telemt_me_reader_eof_total 577
telemt_me_idle_close_by_peer_total 577
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 708678
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1963916
telemt_me_endpoint_quarantine_total 465
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 414
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 7365
telemt_desync_full_logged_total 2519
telemt_desync_suppressed_total 4846
telemt_desync_frames_bucket_total{bucket="1_2"} 1930
telemt_desync_frames_bucket_total{bucket="3_10"} 2739
telemt_desync_frames_bucket_total{bucket="gt_10"} 2696
telemt_pool_swap_total 58
telemt_pool_force_close_total 1408
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 19342
telemt_me_writer_removed_unexpected_total 588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1808
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18150
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1316
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17934
telemt_me_writer_teardown_success_total{mode="normal"} 19958
telemt_me_writer_teardown_noop_total 19343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39301
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.741544
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39301
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 500
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1974834
telemt_user_connections_current{user="hello"} 3544
telemt_user_octets_from_client{user="hello"} 35648442165 (33.20 GB)
telemt_user_octets_to_client{user="hello"} 869139677732 (809.45 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1283
telemt_user_unique_ips_recent_window{user="hello"} 763
```