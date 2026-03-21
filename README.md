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

# Server Metrics 2026-03-21 10:17:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 49276.1 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1414962
telemt_connections_bad_total 73368
telemt_connections_current 1669
telemt_connections_me_current 1669
telemt_handshake_timeouts_total 57240
telemt_upstream_connect_attempt_total 19418
telemt_upstream_connect_success_total 19335
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 19394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 908
telemt_me_reconnect_success_total 378
telemt_me_reader_eof_total 391
telemt_me_idle_close_by_peer_total 391
telemt_me_route_drop_no_conn_total 768789
telemt_me_route_drop_channel_closed_total 289
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1075881
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 343
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 393
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
telemt_desync_total 4533
telemt_desync_full_logged_total 1572
telemt_desync_suppressed_total 2961
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 1758
telemt_desync_frames_bucket_total{bucket="gt_10"} 1832
telemt_pool_swap_total 53
telemt_pool_force_close_total 1511
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 239
telemt_me_draining_writers_reap_progress_total 17397
telemt_me_writer_removed_unexpected_total 369
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1383
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16279
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1458
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15886
telemt_me_writer_teardown_success_total{mode="normal"} 17662
telemt_me_writer_teardown_noop_total 17399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35061
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 90.772790
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35061
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 239
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 337
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1075056
telemt_user_connections_current{user="hello"} 1669
telemt_user_octets_from_client{user="hello"} 15105707675 (14.07 GB)
telemt_user_octets_to_client{user="hello"} 306633130459 (285.57 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 588
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 49277.5 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3619703
telemt_connections_bad_total 376167
telemt_connections_current 4993
telemt_connections_me_current 4993
telemt_handshake_timeouts_total 104724
telemt_upstream_connect_attempt_total 17609
telemt_upstream_connect_success_total 17525
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 1094
telemt_me_reconnect_success_total 407
telemt_me_reader_eof_total 400
telemt_me_idle_close_by_peer_total 399
telemt_me_route_drop_no_conn_total 1565051
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2461077
telemt_me_endpoint_quarantine_total 312
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 379
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
telemt_me_writers_active_current 45
telemt_desync_total 10612
telemt_desync_full_logged_total 3566
telemt_desync_suppressed_total 7046
telemt_desync_frames_bucket_total{bucket="1_2"} 2171
telemt_desync_frames_bucket_total{bucket="3_10"} 4179
telemt_desync_frames_bucket_total{bucket="gt_10"} 4262
telemt_pool_swap_total 53
telemt_pool_force_close_total 1626
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 15736
telemt_me_writer_removed_unexpected_total 374
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1470
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14626
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1529
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 97
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14110
telemt_me_writer_teardown_success_total{mode="normal"} 16096
telemt_me_writer_teardown_noop_total 15736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31832
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.065976
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31832
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 325
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2456518
telemt_user_connections_current{user="hello"} 4993
telemt_user_octets_from_client{user="hello"} 34486819336 (32.12 GB)
telemt_user_octets_to_client{user="hello"} 829073335384 (772.13 GB)
telemt_user_unique_ips_current{user="hello"} 1735
telemt_user_unique_ips_recent_window{user="hello"} 729
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 49274.0 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2672132
telemt_connections_bad_total 312710
telemt_connections_current 4418
telemt_connections_me_current 4418
telemt_handshake_timeouts_total 99714
telemt_upstream_connect_attempt_total 19056
telemt_upstream_connect_success_total 19043
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 629
telemt_me_reconnect_success_total 358
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 1088984
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2095666
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 385
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
telemt_me_writers_active_current 43
telemt_desync_total 9132
telemt_desync_full_logged_total 3126
telemt_desync_suppressed_total 6006
telemt_desync_frames_bucket_total{bucket="1_2"} 1894
telemt_desync_frames_bucket_total{bucket="3_10"} 3634
telemt_desync_frames_bucket_total{bucket="gt_10"} 3604
telemt_pool_swap_total 53
telemt_pool_force_close_total 1595
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 216
telemt_me_draining_writers_reap_progress_total 17334
telemt_me_writer_removed_unexpected_total 351
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1424
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16143
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1509
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15739
telemt_me_writer_teardown_success_total{mode="normal"} 17567
telemt_me_writer_teardown_noop_total 17346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34913
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 39.606905
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34913
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 216
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 321
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 2092431
telemt_user_connections_current{user="hello"} 4418
telemt_user_octets_from_client{user="hello"} 33297481888 (31.01 GB)
telemt_user_octets_to_client{user="hello"} 788281610724 (734.14 GB)
telemt_user_unique_ips_current{user="hello"} 1638
telemt_user_unique_ips_recent_window{user="hello"} 609
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 49275.1 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2199190
telemt_connections_bad_total 248253
telemt_connections_current 3467
telemt_connections_me_current 3467
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 93197
telemt_upstream_connect_attempt_total 24044
telemt_upstream_connect_success_total 23800
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 23926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 403
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1020
telemt_me_reconnect_success_total 446
telemt_me_reader_eof_total 414
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 645517
telemt_me_route_drop_channel_closed_total 48
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1539461
telemt_me_endpoint_quarantine_total 339
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 385
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
telemt_me_writers_active_current 45
telemt_desync_total 7121
telemt_desync_full_logged_total 2453
telemt_desync_suppressed_total 4668
telemt_desync_frames_bucket_total{bucket="1_2"} 1769
telemt_desync_frames_bucket_total{bucket="3_10"} 2821
telemt_desync_frames_bucket_total{bucket="gt_10"} 2531
telemt_pool_swap_total 53
telemt_pool_force_close_total 1446
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 17223
telemt_me_writer_removed_unexpected_total 407
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1393
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16251
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15777
telemt_me_writer_teardown_success_total{mode="normal"} 17644
telemt_me_writer_teardown_noop_total 17224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34868
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.688514
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34868
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1541342
telemt_user_connections_current{user="hello"} 3467
telemt_user_octets_from_client{user="hello"} 30795619169 (28.68 GB)
telemt_user_octets_to_client{user="hello"} 739995625143 (689.17 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1303
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 49239.0 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2136575
telemt_connections_bad_total 239145
telemt_connections_current 3165
telemt_connections_me_current 3165
telemt_handshake_timeouts_total 66177
telemt_upstream_connect_attempt_total 20417
telemt_upstream_connect_success_total 20371
telemt_upstream_connect_attempts_per_request{bucket="1"} 20371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 678
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 425
telemt_me_idle_close_by_peer_total 425
telemt_me_route_drop_no_conn_total 597856
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1535626
telemt_me_endpoint_quarantine_total 373
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 377
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 7282
telemt_desync_full_logged_total 2487
telemt_desync_suppressed_total 4795
telemt_desync_frames_bucket_total{bucket="1_2"} 1931
telemt_desync_frames_bucket_total{bucket="3_10"} 2789
telemt_desync_frames_bucket_total{bucket="gt_10"} 2562
telemt_pool_swap_total 52
telemt_pool_force_close_total 1428
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 135
telemt_me_draining_writers_reap_progress_total 18339
telemt_me_writer_removed_unexpected_total 400
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1402
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17368
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16911
telemt_me_writer_teardown_success_total{mode="normal"} 18770
telemt_me_writer_teardown_noop_total 18342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37112
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.281138
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37112
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 135
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 412
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1533149
telemt_user_connections_current{user="hello"} 3165
telemt_user_octets_from_client{user="hello"} 36271269784 (33.78 GB)
telemt_user_octets_to_client{user="hello"} 752976394984 (701.26 GB)
telemt_user_unique_ips_current{user="hello"} 1229
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 49278.7 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6436275
telemt_connections_bad_total 349201
telemt_connections_current 5100
telemt_connections_me_current 5100
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 243102
telemt_upstream_connect_attempt_total 59484
telemt_upstream_connect_success_total 56870
telemt_upstream_connect_fail_total 1922
telemt_upstream_connect_attempts_per_request{bucket="1"} 58792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2021
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1922
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2916
telemt_me_reconnect_success_total 998
telemt_me_reader_eof_total 698
telemt_me_idle_close_by_peer_total 697
telemt_me_route_drop_no_conn_total 10681752
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5430421
telemt_me_endpoint_quarantine_total 386
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 116
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 116
telemt_me_single_endpoint_shadow_rotate_total 390
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 10834
telemt_desync_full_logged_total 3493
telemt_desync_suppressed_total 7341
telemt_desync_frames_bucket_total{bucket="1_2"} 2384
telemt_desync_frames_bucket_total{bucket="3_10"} 4713
telemt_desync_frames_bucket_total{bucket="gt_10"} 3737
telemt_pool_swap_total 50
telemt_pool_force_close_total 1556
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 314
telemt_me_draining_writers_reap_progress_total 16561
telemt_me_writer_removed_unexpected_total 963
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2109
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15344
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1340
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 216
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15005
telemt_me_writer_teardown_success_total{mode="normal"} 17453
telemt_me_writer_teardown_noop_total 16568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34021
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.388407
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34021
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 314
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 691
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 5464857
telemt_user_connections_current{user="hello"} 5100
telemt_user_octets_from_client{user="hello"} 49880544220 (46.45 GB)
telemt_user_octets_to_client{user="hello"} 594810334991 (553.96 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1812
telemt_user_unique_ips_recent_window{user="hello"} 1041
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 49245.8 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2144143
telemt_connections_bad_total 264785
telemt_connections_current 3614
telemt_connections_me_current 3614
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 41290
telemt_upstream_connect_attempt_total 21752
telemt_upstream_connect_success_total 21537
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 21733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_reconnect_attempts_total 2089
telemt_me_reconnect_success_total 679
telemt_me_reader_eof_total 693
telemt_me_idle_close_by_peer_total 693
telemt_me_route_drop_no_conn_total 705641
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1620627
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 381
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
telemt_me_writers_active_current 83
telemt_desync_total 7449
telemt_desync_full_logged_total 2713
telemt_desync_suppressed_total 4736
telemt_desync_frames_bucket_total{bucket="1_2"} 1404
telemt_desync_frames_bucket_total{bucket="3_10"} 3025
telemt_desync_frames_bucket_total{bucket="gt_10"} 3020
telemt_pool_swap_total 50
telemt_pool_force_close_total 1335
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 101
telemt_me_draining_writers_reap_progress_total 18023
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1656
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17060
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1225
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16688
telemt_me_writer_teardown_success_total{mode="normal"} 18716
telemt_me_writer_teardown_noop_total 18023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.612512
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 101
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 582
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1611744
telemt_user_connections_current{user="hello"} 3614
telemt_user_octets_from_client{user="hello"} 29254025512 (27.24 GB)
telemt_user_octets_to_client{user="hello"} 741108556142 (690.21 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1507
telemt_user_unique_ips_recent_window{user="hello"} 517
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 49240.4 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3058270
telemt_connections_bad_total 169182
telemt_connections_current 3041
telemt_connections_me_current 3041
telemt_handshake_timeouts_total 1272405
telemt_upstream_connect_attempt_total 20305
telemt_upstream_connect_success_total 20271
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 543
telemt_me_reconnect_success_total 306
telemt_me_reader_eof_total 309
telemt_me_idle_close_by_peer_total 309
telemt_me_route_drop_no_conn_total 571726
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1443530
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_shadow_rotate_total 387
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
telemt_me_writers_active_current 42
telemt_desync_total 7152
telemt_desync_full_logged_total 2525
telemt_desync_suppressed_total 4627
telemt_desync_frames_bucket_total{bucket="1_2"} 1266
telemt_desync_frames_bucket_total{bucket="3_10"} 2842
telemt_desync_frames_bucket_total{bucket="gt_10"} 3044
telemt_pool_swap_total 54
telemt_pool_force_close_total 1320
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 18197
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1160
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17355
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16877
telemt_me_writer_teardown_success_total{mode="normal"} 18515
telemt_me_writer_teardown_noop_total 18197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36712
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.953253
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36712
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1439116
telemt_user_connections_current{user="hello"} 3041
telemt_user_octets_from_client{user="hello"} 25838326580 (24.06 GB)
telemt_user_octets_to_client{user="hello"} 708143516148 (659.51 GB)
telemt_user_unique_ips_current{user="hello"} 1208
telemt_user_unique_ips_recent_window{user="hello"} 490
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 47231.9 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 640304
telemt_connections_bad_total 22112
telemt_connections_current 683
telemt_connections_me_current 683
telemt_handshake_timeouts_total 238199
telemt_upstream_connect_attempt_total 22984
telemt_upstream_connect_success_total 22982
telemt_upstream_connect_attempts_per_request{bucket="1"} 22982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1026
telemt_me_reconnect_success_total 375
telemt_me_reader_eof_total 376
telemt_me_idle_close_by_peer_total 376
telemt_me_route_drop_no_conn_total 136118
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 331016
telemt_me_endpoint_quarantine_total 452
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 406
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 2153
telemt_desync_full_logged_total 854
telemt_desync_suppressed_total 1299
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 814
telemt_desync_frames_bucket_total{bucket="gt_10"} 961
telemt_pool_swap_total 52
telemt_pool_force_close_total 1137
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 20550
telemt_me_writer_removed_unexpected_total 357
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1500
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19411
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19413
telemt_me_writer_teardown_success_total{mode="normal"} 20911
telemt_me_writer_teardown_noop_total 20550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41461
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.191400
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41461
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 305
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 331152
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 4946154955 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 128776868005 (119.93 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 49250.3 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2263199
telemt_connections_bad_total 208437
telemt_connections_current 3972
telemt_connections_me_current 3972
telemt_handshake_timeouts_total 55988
telemt_upstream_connect_attempt_total 21071
telemt_upstream_connect_success_total 20981
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 21041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 827
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 432
telemt_me_idle_close_by_peer_total 432
telemt_me_route_drop_no_conn_total 585776
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1782913
telemt_me_endpoint_quarantine_total 390
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 388
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
telemt_me_writers_active_current 49
telemt_desync_total 6964
telemt_desync_full_logged_total 2334
telemt_desync_suppressed_total 4630
telemt_desync_frames_bucket_total{bucket="1_2"} 1687
telemt_desync_frames_bucket_total{bucket="3_10"} 2604
telemt_desync_frames_bucket_total{bucket="gt_10"} 2673
telemt_pool_swap_total 54
telemt_pool_force_close_total 1342
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 18966
telemt_me_writer_removed_unexpected_total 428
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1423
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17983
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17624
telemt_me_writer_teardown_success_total{mode="normal"} 19406
telemt_me_writer_teardown_noop_total 18966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38372
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.762628
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38372
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 419
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 1776935
telemt_user_connections_current{user="hello"} 3972
telemt_user_octets_from_client{user="hello"} 39349616172 (36.65 GB)
telemt_user_octets_to_client{user="hello"} 835548826472 (778.17 GB)
telemt_user_unique_ips_current{user="hello"} 1422
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 49247.2 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2093751
telemt_connections_bad_total 171298
telemt_connections_current 3760
telemt_connections_me_current 3760
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 51232
telemt_upstream_connect_attempt_total 29639
telemt_upstream_connect_success_total 29424
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 29597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 3031
telemt_me_reconnect_success_total 609
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 582133
telemt_me_route_drop_channel_closed_total 35
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1688240
telemt_me_endpoint_quarantine_total 430
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 384
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 6452
telemt_desync_full_logged_total 2175
telemt_desync_suppressed_total 4277
telemt_desync_frames_bucket_total{bucket="1_2"} 1738
telemt_desync_frames_bucket_total{bucket="3_10"} 2394
telemt_desync_frames_bucket_total{bucket="gt_10"} 2320
telemt_pool_swap_total 53
telemt_pool_force_close_total 1319
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 18183
telemt_me_writer_removed_unexpected_total 546
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1657
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17098
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16864
telemt_me_writer_teardown_success_total{mode="normal"} 18755
telemt_me_writer_teardown_noop_total 18184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36939
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.508897
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36939
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 471
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1691828
telemt_user_connections_current{user="hello"} 3760
telemt_user_octets_from_client{user="hello"} 28349457119 (26.40 GB)
telemt_user_octets_to_client{user="hello"} 755030655431 (703.18 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1390
telemt_user_unique_ips_recent_window{user="hello"} 484
```