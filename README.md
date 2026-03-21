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

# Server Metrics 2026-03-21 15:07:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 66709.4 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2331544
telemt_connections_bad_total 115839
telemt_connections_current 1440
telemt_connections_me_current 1440
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 76587
telemt_upstream_connect_attempt_total 28575
telemt_upstream_connect_success_total 28450
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1642
telemt_me_reconnect_success_total 654
telemt_me_reader_eof_total 628
telemt_me_idle_close_by_peer_total 628
telemt_me_route_drop_no_conn_total 1968993
telemt_me_route_drop_channel_closed_total 620
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1865346
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 471
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 517
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
telemt_me_writers_active_current 43
telemt_desync_total 7296
telemt_desync_full_logged_total 2519
telemt_desync_suppressed_total 4777
telemt_desync_frames_bucket_total{bucket="1_2"} 1598
telemt_desync_frames_bucket_total{bucket="3_10"} 2778
telemt_desync_frames_bucket_total{bucket="gt_10"} 2920
telemt_pool_swap_total 72
telemt_pool_force_close_total 2156
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 489
telemt_me_draining_writers_reap_progress_total 22805
telemt_me_writer_removed_unexpected_total 606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1956
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20649
telemt_me_writer_teardown_success_total{mode="normal"} 23197
telemt_me_writer_teardown_noop_total 22811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46008
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.139925
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46008
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 489
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1866923
telemt_user_connections_current{user="hello"} 1440
telemt_user_octets_from_client{user="hello"} 26517140577 (24.70 GB)
telemt_user_octets_to_client{user="hello"} 464874208714 (432.95 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 577
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 802.7 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2245
telemt_connections_bad_total 6
telemt_connections_current 156
telemt_connections_me_current 156
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 563
telemt_upstream_connect_success_total 559
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 837
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2120
telemt_me_endpoint_quarantine_total 1
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 33
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 11
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 441
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 435
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 440
telemt_me_writer_teardown_success_total{mode="normal"} 443
telemt_me_writer_teardown_noop_total 441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 884
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.004310
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 884
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 2098
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 26806224 (25.56 MB)
telemt_user_octets_to_client{user="hello"} 1520282880 (1.42 GB)
telemt_user_unique_ips_current{user="hello"} 112
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 66706.9 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4631124
telemt_connections_bad_total 412253
telemt_connections_current 5031
telemt_connections_me_current 5031
telemt_handshake_timeouts_total 169347
telemt_upstream_connect_attempt_total 24831
telemt_upstream_connect_success_total 24778
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1112
telemt_me_reconnect_success_total 571
telemt_me_reader_eof_total 573
telemt_me_idle_close_by_peer_total 573
telemt_me_route_drop_no_conn_total 2555958
telemt_me_route_drop_channel_closed_total 44
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3787929
telemt_me_endpoint_quarantine_total 424
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 502
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
telemt_me_writers_active_current 43
telemt_desync_total 15503
telemt_desync_full_logged_total 5232
telemt_desync_suppressed_total 10271
telemt_desync_frames_bucket_total{bucket="1_2"} 3303
telemt_desync_frames_bucket_total{bucket="3_10"} 6112
telemt_desync_frames_bucket_total{bucket="gt_10"} 6088
telemt_pool_swap_total 71
telemt_pool_force_close_total 2267
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 357
telemt_me_draining_writers_reap_progress_total 22493
telemt_me_writer_removed_unexpected_total 554
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1971
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20858
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 196
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20226
telemt_me_writer_teardown_success_total{mode="normal"} 22829
telemt_me_writer_teardown_noop_total 22525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45354
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 74.600863
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45354
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 357
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 513
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 3783303
telemt_user_connections_current{user="hello"} 5031
telemt_user_octets_from_client{user="hello"} 61158130164 (56.96 GB)
telemt_user_octets_to_client{user="hello"} 1259792925420 (1.15 TB)
telemt_user_unique_ips_current{user="hello"} 1957
telemt_user_unique_ips_recent_window{user="hello"} 669
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 66708.3 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3781014
telemt_connections_bad_total 411846
telemt_connections_current 4343
telemt_connections_me_current 4343
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 136823
telemt_upstream_connect_attempt_total 29210
telemt_upstream_connect_success_total 28930
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 29068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 484
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1253
telemt_me_reconnect_success_total 570
telemt_me_reader_eof_total 541
telemt_me_idle_close_by_peer_total 541
telemt_me_route_drop_no_conn_total 1186546
telemt_me_route_drop_channel_closed_total 96
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2762340
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 506
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
telemt_me_writers_warm_current 33
telemt_desync_total 12854
telemt_desync_full_logged_total 4335
telemt_desync_suppressed_total 8519
telemt_desync_frames_bucket_total{bucket="1_2"} 3212
telemt_desync_frames_bucket_total{bucket="3_10"} 4972
telemt_desync_frames_bucket_total{bucket="gt_10"} 4670
telemt_pool_swap_total 72
telemt_pool_force_close_total 2074
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 205
telemt_me_draining_writers_reap_progress_total 21683
telemt_me_writer_removed_unexpected_total 525
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1840
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20370
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1936
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 138
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19609
telemt_me_writer_teardown_success_total{mode="normal"} 22210
telemt_me_writer_teardown_noop_total 21684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43894
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.352705
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43894
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 205
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 483
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 2762322
telemt_user_connections_current{user="hello"} 4343
telemt_user_octets_from_client{user="hello"} 51793800685 (48.24 GB)
telemt_user_octets_to_client{user="hello"} 1289239593695 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1710
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 66672.5 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3709306
telemt_connections_bad_total 389360
telemt_connections_current 3350
telemt_connections_me_current 3350
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 110728
telemt_upstream_connect_attempt_total 34442
telemt_upstream_connect_success_total 34207
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 852
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1311
telemt_me_reconnect_success_total 638
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 1292349
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2745377
telemt_me_endpoint_quarantine_total 476
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 496
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 19
telemt_desync_total 12607
telemt_desync_full_logged_total 4221
telemt_desync_suppressed_total 8386
telemt_desync_frames_bucket_total{bucket="1_2"} 3162
telemt_desync_frames_bucket_total{bucket="3_10"} 4746
telemt_desync_frames_bucket_total{bucket="gt_10"} 4699
telemt_pool_swap_total 70
telemt_pool_force_close_total 2003
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 227
telemt_me_draining_writers_reap_progress_total 23108
telemt_me_writer_removed_unexpected_total 553
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1944
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21753
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1825
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 178
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21105
telemt_me_writer_teardown_success_total{mode="normal"} 23697
telemt_me_writer_teardown_noop_total 23113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46810
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.907703
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46810
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 227
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 555
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2749330
telemt_user_connections_current{user="hello"} 3350
telemt_user_octets_from_client{user="hello"} 58569723289 (54.55 GB)
telemt_user_octets_to_client{user="hello"} 1274118144992 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1307
telemt_user_unique_ips_recent_window{user="hello"} 539
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 66711.6 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12710493
telemt_connections_bad_total 830287
telemt_connections_current 5876
telemt_connections_me_current 5876
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 388997
telemt_upstream_connect_attempt_total 115643
telemt_upstream_connect_success_total 105758
telemt_upstream_connect_fail_total 8851
telemt_upstream_connect_attempts_per_request{bucket="1"} 114609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8851
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3841
telemt_me_reconnect_success_total 1378
telemt_me_reader_eof_total 965
telemt_me_idle_close_by_peer_total 964
telemt_me_route_drop_no_conn_total 24335301
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10439110
telemt_me_endpoint_quarantine_total 510
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 521
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_warm_current 35
telemt_desync_total 18534
telemt_desync_full_logged_total 5829
telemt_desync_suppressed_total 12705
telemt_desync_frames_bucket_total{bucket="1_2"} 4020
telemt_desync_frames_bucket_total{bucket="3_10"} 8155
telemt_desync_frames_bucket_total{bucket="gt_10"} 6359
telemt_pool_swap_total 67
telemt_pool_force_close_total 2175
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 472
telemt_me_draining_writers_reap_progress_total 21428
telemt_me_writer_removed_unexpected_total 1326
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2831
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19720
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1825
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 350
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19253
telemt_me_writer_teardown_success_total{mode="normal"} 22551
telemt_me_writer_teardown_noop_total 21438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43989
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 168.443457
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43989
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 472
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 961
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 10515156
telemt_user_connections_current{user="hello"} 5876
telemt_user_octets_from_client{user="hello"} 75346134505 (70.17 GB)
telemt_user_octets_to_client{user="hello"} 787356542937 (733.28 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2077
telemt_user_unique_ips_recent_window{user="hello"} 1216
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 66679.3 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3718895
telemt_connections_bad_total 414856
telemt_connections_current 4250
telemt_connections_me_current 4250
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 80880
telemt_upstream_connect_attempt_total 28149
telemt_upstream_connect_success_total 27839
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 28105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_reconnect_attempts_total 2676
telemt_me_reconnect_success_total 972
telemt_me_reader_eof_total 966
telemt_me_idle_close_by_peer_total 966
telemt_me_route_drop_no_conn_total 1567218
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2863587
telemt_me_endpoint_quarantine_total 413
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 499
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_writers_warm_current 25
telemt_desync_total 13541
telemt_desync_full_logged_total 4721
telemt_desync_suppressed_total 8820
telemt_desync_frames_bucket_total{bucket="1_2"} 2625
telemt_desync_frames_bucket_total{bucket="3_10"} 5347
telemt_desync_frames_bucket_total{bucket="gt_10"} 5569
telemt_pool_swap_total 66
telemt_pool_force_close_total 1918
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 23600
telemt_me_writer_removed_unexpected_total 937
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2318
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22251
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1663
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 255
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21682
telemt_me_writer_teardown_success_total{mode="normal"} 24569
telemt_me_writer_teardown_noop_total 23601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48170
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.326183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48170
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 833
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2847286
telemt_user_connections_current{user="hello"} 4250
telemt_user_octets_from_client{user="hello"} 74882050708 (69.74 GB)
telemt_user_octets_to_client{user="hello"} 1190550885674 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1606
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 3514.9 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 569581
telemt_connections_bad_total 13586
telemt_connections_current 3888
telemt_connections_me_current 3888
telemt_handshake_timeouts_total 282167
telemt_upstream_connect_attempt_total 1356
telemt_upstream_connect_success_total 1327
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 199
telemt_me_reconnect_success_total 69
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 61
telemt_me_route_drop_no_conn_total 249504
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256924
telemt_me_endpoint_quarantine_total 14
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
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
telemt_me_writers_active_current 48
telemt_desync_total 1180
telemt_desync_full_logged_total 393
telemt_desync_suppressed_total 787
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_close_signal_drop_total 7
telemt_me_draining_writers_reap_progress_total 1087
telemt_me_writer_removed_unexpected_total 62
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 122
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1027
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1004
telemt_me_writer_teardown_success_total{mode="normal"} 1149
telemt_me_writer_teardown_noop_total 1087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.402516
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 7
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 61
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 256630
telemt_user_connections_current{user="hello"} 3888
telemt_user_octets_from_client{user="hello"} 6473858032 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 93098239580 (86.70 GB)
telemt_user_unique_ips_current{user="hello"} 1556
telemt_user_unique_ips_recent_window{user="hello"} 619
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 64664.9 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1183542
telemt_connections_bad_total 137290
telemt_connections_current 792
telemt_connections_me_current 792
telemt_handshake_timeouts_total 416500
telemt_upstream_connect_attempt_total 30282
telemt_upstream_connect_success_total 30275
telemt_upstream_connect_attempts_per_request{bucket="1"} 30275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1304
telemt_me_reconnect_success_total 536
telemt_me_reader_eof_total 534
telemt_me_idle_close_by_peer_total 534
telemt_me_route_drop_no_conn_total 259626
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557116
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 542
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
telemt_me_writers_active_current 89
telemt_desync_total 3529
telemt_desync_full_logged_total 1292
telemt_desync_suppressed_total 2237
telemt_desync_frames_bucket_total{bucket="1_2"} 647
telemt_desync_frames_bucket_total{bucket="3_10"} 1263
telemt_desync_frames_bucket_total{bucket="gt_10"} 1619
telemt_pool_swap_total 70
telemt_pool_force_close_total 1603
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 110
telemt_me_draining_writers_reap_progress_total 27089
telemt_me_writer_removed_unexpected_total 508
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2019
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25590
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25486
telemt_me_writer_teardown_success_total{mode="normal"} 27609
telemt_me_writer_teardown_noop_total 27089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54698
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.951985
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54698
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 110
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 447
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 556808
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 11441399427 (10.66 GB)
telemt_user_octets_to_client{user="hello"} 211816980193 (197.27 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 66683.6 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4078495
telemt_connections_bad_total 371160
telemt_connections_current 4616
telemt_connections_me_current 4616
telemt_handshake_timeouts_total 133863
telemt_upstream_connect_attempt_total 26658
telemt_upstream_connect_success_total 26546
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 26623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_reconnect_attempts_total 1135
telemt_me_reconnect_success_total 604
telemt_me_reader_eof_total 569
telemt_me_idle_close_by_peer_total 569
telemt_me_route_drop_no_conn_total 1242204
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3245137
telemt_me_endpoint_quarantine_total 488
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 506
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 40
telemt_me_writers_warm_current 31
telemt_desync_total 12783
telemt_desync_full_logged_total 4217
telemt_desync_suppressed_total 8566
telemt_desync_frames_bucket_total{bucket="1_2"} 3025
telemt_desync_frames_bucket_total{bucket="3_10"} 4764
telemt_desync_frames_bucket_total{bucket="gt_10"} 4994
telemt_pool_swap_total 73
telemt_pool_force_close_total 1908
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 215
telemt_me_draining_writers_reap_progress_total 23883
telemt_me_writer_removed_unexpected_total 559
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1900
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22542
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21975
telemt_me_writer_teardown_success_total{mode="normal"} 24442
telemt_me_writer_teardown_noop_total 23883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48325
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.588776
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48325
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 215
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 535
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 3236896
telemt_user_connections_current{user="hello"} 4616
telemt_user_octets_from_client{user="hello"} 66084700624 (61.55 GB)
telemt_user_octets_to_client{user="hello"} 1525947481164 (1.39 TB)
telemt_user_unique_ips_current{user="hello"} 1699
telemt_user_unique_ips_recent_window{user="hello"} 636
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 66680.3 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3631119
telemt_connections_bad_total 314514
telemt_connections_current 4120
telemt_connections_me_current 4120
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 109940
telemt_upstream_connect_attempt_total 43118
telemt_upstream_connect_success_total 42827
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 43067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_reconnect_attempts_total 3634
telemt_me_reconnect_success_total 811
telemt_me_reader_eof_total 717
telemt_me_idle_close_by_peer_total 717
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1316627
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2924948
telemt_me_endpoint_quarantine_total 550
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 505
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
telemt_me_writers_warm_current 23
telemt_desync_total 11389
telemt_desync_full_logged_total 3864
telemt_desync_suppressed_total 7525
telemt_desync_frames_bucket_total{bucket="1_2"} 2822
telemt_desync_frames_bucket_total{bucket="3_10"} 4247
telemt_desync_frames_bucket_total{bucket="gt_10"} 4320
telemt_pool_swap_total 71
telemt_pool_force_close_total 1847
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 207
telemt_me_draining_writers_reap_progress_total 23301
telemt_me_writer_removed_unexpected_total 730
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2245
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21817
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1699
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 148
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21454
telemt_me_writer_teardown_success_total{mode="normal"} 24062
telemt_me_writer_teardown_noop_total 23302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47364
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.862435
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47364
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 207
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 631
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2933673
telemt_user_connections_current{user="hello"} 4120
telemt_user_octets_from_client{user="hello"} 52856004705 (49.23 GB)
telemt_user_octets_to_client{user="hello"} 1259678516156 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1623
telemt_user_unique_ips_recent_window{user="hello"} 581
```