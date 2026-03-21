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

# Server Metrics 2026-03-21 12:09:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 56020.4 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1808439
telemt_connections_bad_total 89045
telemt_connections_current 2003
telemt_connections_me_current 2003
telemt_handshake_timeouts_total 68810
telemt_upstream_connect_attempt_total 21846
telemt_upstream_connect_success_total 21738
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 21808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1102
telemt_me_reconnect_success_total 492
telemt_me_reader_eof_total 476
telemt_me_idle_close_by_peer_total 476
telemt_me_route_drop_no_conn_total 1397903
telemt_me_route_drop_channel_closed_total 435
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1413921
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 445
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
telemt_desync_total 5455
telemt_desync_full_logged_total 1922
telemt_desync_suppressed_total 3533
telemt_desync_frames_bucket_total{bucket="1_2"} 1162
telemt_desync_frames_bucket_total{bucket="3_10"} 2111
telemt_desync_frames_bucket_total{bucket="gt_10"} 2182
telemt_pool_swap_total 61
telemt_pool_force_close_total 1788
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 348
telemt_me_draining_writers_reap_progress_total 19538
telemt_me_writer_removed_unexpected_total 457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1612
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18236
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1724
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17750
telemt_me_writer_teardown_success_total{mode="normal"} 19848
telemt_me_writer_teardown_noop_total 19542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39390
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 147.627421
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39390
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 348
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1412883
telemt_user_connections_current{user="hello"} 2003
telemt_user_octets_from_client{user="hello"} 19517140715 (18.18 GB)
telemt_user_octets_to_client{user="hello"} 364303182491 (339.28 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 582
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1666.1 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101519
telemt_connections_bad_total 9117
telemt_connections_current 2245
telemt_connections_me_current 2245
telemt_handshake_timeouts_total 3394
telemt_upstream_connect_attempt_total 609
telemt_upstream_connect_success_total 593
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 34
telemt_me_reconnect_success_total 16
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 48552
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82025
telemt_me_endpoint_quarantine_total 17
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 15
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
telemt_desync_total 301
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 1
telemt_pool_force_close_total 31
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 470
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 39
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 439
telemt_me_writer_teardown_success_total{mode="normal"} 480
telemt_me_writer_teardown_noop_total 470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 950
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.123365
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 950
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 10
telemt_user_connections_total{user="hello"} 82000
telemt_user_connections_current{user="hello"} 2245
telemt_user_octets_from_client{user="hello"} 1323509808 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 22922797444 (21.35 GB)
telemt_user_unique_ips_current{user="hello"} 1161
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 56019.1 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3370270
telemt_connections_bad_total 364720
telemt_connections_current 4628
telemt_connections_me_current 4628
telemt_handshake_timeouts_total 123591
telemt_upstream_connect_attempt_total 21192
telemt_upstream_connect_success_total 21179
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 21180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 761
telemt_me_reconnect_success_total 421
telemt_me_reader_eof_total 436
telemt_me_idle_close_by_peer_total 436
telemt_me_route_drop_no_conn_total 1460819
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2687708
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 429
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
telemt_me_writers_active_current 72
telemt_me_writers_warm_current 13
telemt_desync_total 11754
telemt_desync_full_logged_total 3976
telemt_desync_suppressed_total 7778
telemt_desync_frames_bucket_total{bucket="1_2"} 2489
telemt_desync_frames_bucket_total{bucket="3_10"} 4579
telemt_desync_frames_bucket_total{bucket="gt_10"} 4686
telemt_pool_swap_total 60
telemt_pool_force_close_total 1857
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 262
telemt_me_draining_writers_reap_progress_total 19227
telemt_me_writer_removed_unexpected_total 413
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1604
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17876
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 100
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17370
telemt_me_writer_teardown_success_total{mode="normal"} 19480
telemt_me_writer_teardown_noop_total 19241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38721
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.132429
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38721
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 262
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 377
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 2684042
telemt_user_connections_current{user="hello"} 4628
telemt_user_octets_from_client{user="hello"} 43938017100 (40.92 GB)
telemt_user_octets_to_client{user="hello"} 973021380092 (906.20 GB)
telemt_user_unique_ips_current{user="hello"} 1792
telemt_user_unique_ips_recent_window{user="hello"} 603
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 56019.9 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2814080
telemt_connections_bad_total 312737
telemt_connections_current 3554
telemt_connections_me_current 3554
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 114285
telemt_upstream_connect_attempt_total 26083
telemt_upstream_connect_success_total 25816
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 25948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 466
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1101
telemt_me_reconnect_success_total 508
telemt_me_reader_eof_total 470
telemt_me_idle_close_by_peer_total 470
telemt_me_route_drop_no_conn_total 870529
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1995773
telemt_me_endpoint_quarantine_total 375
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 433
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
telemt_me_writers_active_current 46
telemt_desync_total 9157
telemt_desync_full_logged_total 3123
telemt_desync_suppressed_total 6034
telemt_desync_frames_bucket_total{bucket="1_2"} 2296
telemt_desync_frames_bucket_total{bucket="3_10"} 3570
telemt_desync_frames_bucket_total{bucket="gt_10"} 3291
telemt_pool_swap_total 61
telemt_pool_force_close_total 1701
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 18948
telemt_me_writer_removed_unexpected_total 460
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1595
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17831
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1589
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17247
telemt_me_writer_teardown_success_total{mode="normal"} 19426
telemt_me_writer_teardown_noop_total 18949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38375
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.892961
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38375
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 426
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 1997052
telemt_user_connections_current{user="hello"} 3554
telemt_user_octets_from_client{user="hello"} 37540416729 (34.96 GB)
telemt_user_octets_to_client{user="hello"} 951255361967 (885.93 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1263
telemt_user_unique_ips_recent_window{user="hello"} 863
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 55984.6 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2733409
telemt_connections_bad_total 309114
telemt_connections_current 3634
telemt_connections_me_current 3634
telemt_handshake_timeouts_total 81168
telemt_upstream_connect_attempt_total 22743
telemt_upstream_connect_success_total 22656
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 857
telemt_me_reconnect_success_total 586
telemt_me_reader_eof_total 533
telemt_me_idle_close_by_peer_total 533
telemt_me_route_drop_no_conn_total 819733
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1979958
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 422
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
telemt_desync_total 9199
telemt_desync_full_logged_total 3087
telemt_desync_suppressed_total 6112
telemt_desync_frames_bucket_total{bucket="1_2"} 2431
telemt_desync_frames_bucket_total{bucket="3_10"} 3498
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 59
telemt_pool_force_close_total 1645
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 182
telemt_me_draining_writers_reap_progress_total 20239
telemt_me_writer_removed_unexpected_total 507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1677
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19107
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18594
telemt_me_writer_teardown_success_total{mode="normal"} 20784
telemt_me_writer_teardown_noop_total 20243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41027
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.841114
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41027
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 182
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 511
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1976947
telemt_user_connections_current{user="hello"} 3634
telemt_user_octets_from_client{user="hello"} 44172865164 (41.14 GB)
telemt_user_octets_to_client{user="hello"} 955665988628 (890.03 GB)
telemt_user_unique_ips_current{user="hello"} 1326
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 56023.0 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8915336
telemt_connections_bad_total 607532
telemt_connections_current 4978
telemt_connections_me_current 4978
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 305601
telemt_upstream_connect_attempt_total 88424
telemt_upstream_connect_success_total 83269
telemt_upstream_connect_fail_total 4323
telemt_upstream_connect_attempts_per_request{bucket="1"} 87592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4323
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3457
telemt_me_reconnect_success_total 1151
telemt_me_reader_eof_total 808
telemt_me_idle_close_by_peer_total 807
telemt_me_route_drop_no_conn_total 15879307
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7361400
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 443
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 14017
telemt_desync_full_logged_total 4504
telemt_desync_suppressed_total 9513
telemt_desync_frames_bucket_total{bucket="1_2"} 3004
telemt_desync_frames_bucket_total{bucket="3_10"} 6217
telemt_desync_frames_bucket_total{bucket="gt_10"} 4796
telemt_pool_swap_total 57
telemt_pool_force_close_total 1804
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 373
telemt_me_draining_writers_reap_progress_total 18495
telemt_me_writer_removed_unexpected_total 1118
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2403
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17092
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1548
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 256
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16691
telemt_me_writer_teardown_success_total{mode="normal"} 19495
telemt_me_writer_teardown_noop_total 18504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37999
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.061602
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37999
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 373
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 793
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 7419425
telemt_user_connections_current{user="hello"} 4978
telemt_user_octets_from_client{user="hello"} 59199035609 (55.13 GB)
telemt_user_octets_to_client{user="hello"} 668962605436 (623.02 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1752
telemt_user_unique_ips_recent_window{user="hello"} 1744
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 55990.7 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2780346
telemt_connections_bad_total 341394
telemt_connections_current 4079
telemt_connections_me_current 4079
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 60999
telemt_upstream_connect_attempt_total 24047
telemt_upstream_connect_success_total 23780
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 24022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_reconnect_attempts_total 2376
telemt_me_reconnect_success_total 802
telemt_me_reader_eof_total 797
telemt_me_idle_close_by_peer_total 797
telemt_me_route_drop_no_conn_total 965088
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2093003
telemt_me_endpoint_quarantine_total 348
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 430
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
telemt_me_writers_active_current 72
telemt_me_writers_warm_current 15
telemt_desync_total 9640
telemt_desync_full_logged_total 3410
telemt_desync_suppressed_total 6230
telemt_desync_frames_bucket_total{bucket="1_2"} 1898
telemt_desync_frames_bucket_total{bucket="3_10"} 3859
telemt_desync_frames_bucket_total{bucket="gt_10"} 3883
telemt_pool_swap_total 57
telemt_pool_force_close_total 1578
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 19971
telemt_me_writer_removed_unexpected_total 771
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1897
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18871
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1421
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18393
telemt_me_writer_teardown_success_total{mode="normal"} 20768
telemt_me_writer_teardown_noop_total 19971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.211849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 678
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 2078100
telemt_user_connections_current{user="hello"} 4079
telemt_user_octets_from_client{user="hello"} 38464820040 (35.82 GB)
telemt_user_octets_to_client{user="hello"} 920720584802 (857.49 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1718
telemt_user_unique_ips_recent_window{user="hello"} 674
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 55985.3 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4110582
telemt_connections_bad_total 211985
telemt_connections_current 2188
telemt_connections_me_current 2188
telemt_handshake_timeouts_total 1780999
telemt_upstream_connect_attempt_total 22549
telemt_upstream_connect_success_total 22515
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 22518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 820
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 403
telemt_me_route_drop_no_conn_total 897649
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1864277
telemt_me_endpoint_quarantine_total 430
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 439
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
telemt_desync_total 9067
telemt_desync_full_logged_total 3217
telemt_desync_suppressed_total 5850
telemt_desync_frames_bucket_total{bucket="1_2"} 1674
telemt_desync_frames_bucket_total{bucket="3_10"} 3624
telemt_desync_frames_bucket_total{bucket="gt_10"} 3769
telemt_pool_swap_total 61
telemt_pool_force_close_total 1550
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 20196
telemt_me_writer_removed_unexpected_total 389
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1368
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19240
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18646
telemt_me_writer_teardown_success_total{mode="normal"} 20608
telemt_me_writer_teardown_noop_total 20196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40804
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.161717
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40804
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 352
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 1857910
telemt_user_connections_current{user="hello"} 2188
telemt_user_octets_from_client{user="hello"} 34046283944 (31.71 GB)
telemt_user_octets_to_client{user="hello"} 888001869364 (827.02 GB)
telemt_user_unique_ips_current{user="hello"} 824
telemt_user_unique_ips_recent_window{user="hello"} 763
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 53976.4 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 863068
telemt_connections_bad_total 68012
telemt_connections_current 700
telemt_connections_me_current 700
telemt_handshake_timeouts_total 312762
telemt_upstream_connect_attempt_total 25785
telemt_upstream_connect_success_total 25783
telemt_upstream_connect_attempts_per_request{bucket="1"} 25783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1093
telemt_me_reconnect_success_total 424
telemt_me_reader_eof_total 420
telemt_me_idle_close_by_peer_total 420
telemt_me_route_drop_no_conn_total 183894
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418737
telemt_me_endpoint_quarantine_total 494
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 457
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
telemt_me_writers_active_current 44
telemt_desync_total 2914
telemt_desync_full_logged_total 1102
telemt_desync_suppressed_total 1812
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 1046
telemt_desync_frames_bucket_total{bucket="gt_10"} 1388
telemt_pool_swap_total 59
telemt_pool_force_close_total 1317
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 88
telemt_me_draining_writers_reap_progress_total 23104
telemt_me_writer_removed_unexpected_total 399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1678
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21831
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1314
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21787
telemt_me_writer_teardown_success_total{mode="normal"} 23509
telemt_me_writer_teardown_noop_total 23104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46613
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.675598
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46613
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 88
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 344
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 418597
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 6687360191 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 160189750157 (149.19 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 55995.3 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2938753
telemt_connections_bad_total 278717
telemt_connections_current 3689
telemt_connections_me_current 3689
telemt_handshake_timeouts_total 81285
telemt_upstream_connect_attempt_total 23406
telemt_upstream_connect_success_total 23307
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 23375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_reconnect_attempts_total 957
telemt_me_reconnect_success_total 536
telemt_me_reader_eof_total 500
telemt_me_idle_close_by_peer_total 500
telemt_me_route_drop_no_conn_total 787920
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2324091
telemt_me_endpoint_quarantine_total 432
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 437
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 9360
telemt_desync_full_logged_total 3084
telemt_desync_suppressed_total 6276
telemt_desync_frames_bucket_total{bucket="1_2"} 2235
telemt_desync_frames_bucket_total{bucket="3_10"} 3490
telemt_desync_frames_bucket_total{bucket="gt_10"} 3635
telemt_pool_swap_total 62
telemt_pool_force_close_total 1566
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 166
telemt_me_draining_writers_reap_progress_total 21023
telemt_me_writer_removed_unexpected_total 491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1629
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19902
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1538
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19457
telemt_me_writer_teardown_success_total{mode="normal"} 21531
telemt_me_writer_teardown_noop_total 21023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42554
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.752928
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42554
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 166
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 476
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 2317325
telemt_user_connections_current{user="hello"} 3689
telemt_user_octets_from_client{user="hello"} 48714509168 (45.37 GB)
telemt_user_octets_to_client{user="hello"} 1085064846692 (1010.55 GB)
telemt_user_unique_ips_current{user="hello"} 1169
telemt_user_unique_ips_recent_window{user="hello"} 1089
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 55991.9 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2684034
telemt_connections_bad_total 221796
telemt_connections_current 4306
telemt_connections_me_current 4306
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 74657
telemt_upstream_connect_attempt_total 39565
telemt_upstream_connect_success_total 39315
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 39522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 3358
telemt_me_reconnect_success_total 696
telemt_me_reader_eof_total 605
telemt_me_idle_close_by_peer_total 605
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 795943
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2153011
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 435
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
telemt_me_writers_active_current 44
telemt_desync_total 8145
telemt_desync_full_logged_total 2801
telemt_desync_suppressed_total 5344
telemt_desync_frames_bucket_total{bucket="1_2"} 2122
telemt_desync_frames_bucket_total{bucket="3_10"} 3020
telemt_desync_frames_bucket_total{bucket="gt_10"} 3003
telemt_pool_swap_total 61
telemt_pool_force_close_total 1492
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 20172
telemt_me_writer_removed_unexpected_total 617
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1899
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18918
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1396
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 96
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18680
telemt_me_writer_teardown_success_total{mode="normal"} 20817
telemt_me_writer_teardown_noop_total 20173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40990
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.369024
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40990
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 530
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 2163527
telemt_user_connections_current{user="hello"} 4306
telemt_user_octets_from_client{user="hello"} 39485209165 (36.77 GB)
telemt_user_octets_to_client{user="hello"} 949682692488 (884.46 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1631
telemt_user_unique_ips_recent_window{user="hello"} 803
```