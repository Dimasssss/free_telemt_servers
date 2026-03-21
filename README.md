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

# Server Metrics 2026-03-21 10:06:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 48665.8 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1388072
telemt_connections_bad_total 71659
telemt_connections_current 1765
telemt_connections_me_current 1765
telemt_handshake_timeouts_total 56260
telemt_upstream_connect_attempt_total 19224
telemt_upstream_connect_success_total 19143
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 19200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 868
telemt_me_reconnect_success_total 372
telemt_me_reader_eof_total 383
telemt_me_idle_close_by_peer_total 383
telemt_me_route_drop_no_conn_total 750978
telemt_me_route_drop_channel_closed_total 273
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1053439
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 340
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 386
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
telemt_me_writers_warm_current 19
telemt_desync_total 4394
telemt_desync_full_logged_total 1520
telemt_desync_suppressed_total 2874
telemt_desync_frames_bucket_total{bucket="1_2"} 921
telemt_desync_frames_bucket_total{bucket="3_10"} 1701
telemt_desync_frames_bucket_total{bucket="gt_10"} 1772
telemt_pool_swap_total 52
telemt_pool_force_close_total 1485
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 226
telemt_me_draining_writers_reap_progress_total 17213
telemt_me_writer_removed_unexpected_total 362
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1359
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16111
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1432
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15728
telemt_me_writer_teardown_success_total{mode="normal"} 17470
telemt_me_writer_teardown_noop_total 17215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 88.170295
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 226
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 332
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1052638
telemt_user_connections_current{user="hello"} 1765
telemt_user_octets_from_client{user="hello"} 14865988795 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 300251598635 (279.63 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 577
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 48667.0 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3547992
telemt_connections_bad_total 373347
telemt_connections_current 4560
telemt_connections_me_current 4560
telemt_handshake_timeouts_total 103334
telemt_upstream_connect_attempt_total 17406
telemt_upstream_connect_success_total 17324
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 1033
telemt_me_reconnect_success_total 389
telemt_me_reader_eof_total 385
telemt_me_idle_close_by_peer_total 384
telemt_me_route_drop_no_conn_total 1519661
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2399176
telemt_me_endpoint_quarantine_total 301
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 372
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
telemt_me_writers_warm_current 22
telemt_desync_total 10415
telemt_desync_full_logged_total 3500
telemt_desync_suppressed_total 6915
telemt_desync_frames_bucket_total{bucket="1_2"} 2132
telemt_desync_frames_bucket_total{bucket="3_10"} 4099
telemt_desync_frames_bucket_total{bucket="gt_10"} 4184
telemt_pool_swap_total 52
telemt_pool_force_close_total 1595
telemt_me_writer_close_signal_drop_total 190
telemt_me_draining_writers_reap_progress_total 15547
telemt_me_writer_removed_unexpected_total 360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1435
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14457
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1500
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 95
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13952
telemt_me_writer_teardown_success_total{mode="normal"} 15892
telemt_me_writer_teardown_noop_total 15547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31439
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.888608
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31439
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 190
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 313
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2394703
telemt_user_connections_current{user="hello"} 4560
telemt_user_octets_from_client{user="hello"} 33792105780 (31.47 GB)
telemt_user_octets_to_client{user="hello"} 811500768240 (755.77 GB)
telemt_user_unique_ips_current{user="hello"} 1740
telemt_user_unique_ips_recent_window{user="hello"} 650
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 48663.3 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2608427
telemt_connections_bad_total 305472
telemt_connections_current 4045
telemt_connections_me_current 4045
telemt_handshake_timeouts_total 97610
telemt_upstream_connect_attempt_total 18880
telemt_upstream_connect_success_total 18868
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 627
telemt_me_reconnect_success_total 357
telemt_me_reader_eof_total 371
telemt_me_idle_close_by_peer_total 371
telemt_me_route_drop_no_conn_total 1060237
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2044406
telemt_me_endpoint_quarantine_total 318
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 378
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 20
telemt_desync_total 8897
telemt_desync_full_logged_total 3056
telemt_desync_suppressed_total 5841
telemt_desync_frames_bucket_total{bucket="1_2"} 1866
telemt_desync_frames_bucket_total{bucket="3_10"} 3533
telemt_desync_frames_bucket_total{bucket="gt_10"} 3498
telemt_pool_swap_total 52
telemt_pool_force_close_total 1562
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 17150
telemt_me_writer_removed_unexpected_total 350
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1413
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15969
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1477
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15588
telemt_me_writer_teardown_success_total{mode="normal"} 17382
telemt_me_writer_teardown_noop_total 17161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34543
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.884928
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34543
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 320
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 2041225
telemt_user_connections_current{user="hello"} 4045
telemt_user_octets_from_client{user="hello"} 32280648092 (30.06 GB)
telemt_user_octets_to_client{user="hello"} 771656504164 (718.66 GB)
telemt_user_unique_ips_current{user="hello"} 1616
telemt_user_unique_ips_recent_window{user="hello"} 584
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 48664.7 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2138180
telemt_connections_bad_total 242620
telemt_connections_current 3432
telemt_connections_me_current 3432
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 91352
telemt_upstream_connect_attempt_total 23832
telemt_upstream_connect_success_total 23590
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 23716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 1018
telemt_me_reconnect_success_total 444
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 412
telemt_me_route_drop_no_conn_total 625697
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1496895
telemt_me_endpoint_quarantine_total 337
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 27
telemt_desync_total 6950
telemt_desync_full_logged_total 2392
telemt_desync_suppressed_total 4558
telemt_desync_frames_bucket_total{bucket="1_2"} 1714
telemt_desync_frames_bucket_total{bucket="3_10"} 2758
telemt_desync_frames_bucket_total{bucket="gt_10"} 2478
telemt_pool_swap_total 52
telemt_pool_force_close_total 1415
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 17026
telemt_me_writer_removed_unexpected_total 405
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1371
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16074
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1333
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15611
telemt_me_writer_teardown_success_total{mode="normal"} 17445
telemt_me_writer_teardown_noop_total 17027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34472
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.633814
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34472
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 374
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1498843
telemt_user_connections_current{user="hello"} 3432
telemt_user_octets_from_client{user="hello"} 30127862369 (28.06 GB)
telemt_user_octets_to_client{user="hello"} 720137635539 (670.68 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1340
telemt_user_unique_ips_recent_window{user="hello"} 465
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 48628.6 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2079079
telemt_connections_bad_total 230754
telemt_connections_current 3447
telemt_connections_me_current 3447
telemt_handshake_timeouts_total 64861
telemt_upstream_connect_attempt_total 20170
telemt_upstream_connect_success_total 20127
telemt_upstream_connect_attempts_per_request{bucket="1"} 20127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 632
telemt_me_reconnect_success_total 453
telemt_me_reader_eof_total 415
telemt_me_idle_close_by_peer_total 415
telemt_me_route_drop_no_conn_total 579137
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1494802
telemt_me_endpoint_quarantine_total 369
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 370
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 5
telemt_desync_total 7045
telemt_desync_full_logged_total 2426
telemt_desync_suppressed_total 4619
telemt_desync_frames_bucket_total{bucket="1_2"} 1869
telemt_desync_frames_bucket_total{bucket="3_10"} 2706
telemt_desync_frames_bucket_total{bucket="gt_10"} 2470
telemt_pool_swap_total 51
telemt_pool_force_close_total 1398
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 18137
telemt_me_writer_removed_unexpected_total 390
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1370
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17187
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1289
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16739
telemt_me_writer_teardown_success_total{mode="normal"} 18557
telemt_me_writer_teardown_noop_total 18140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36697
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.225225
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36697
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 405
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1492400
telemt_user_connections_current{user="hello"} 3447
telemt_user_octets_from_client{user="hello"} 35154471248 (32.74 GB)
telemt_user_octets_to_client{user="hello"} 736191839620 (685.63 GB)
telemt_user_unique_ips_current{user="hello"} 1348
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 48668.1 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6207425
telemt_connections_bad_total 329487
telemt_connections_current 5629
telemt_connections_me_current 5629
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 238314
telemt_upstream_connect_attempt_total 59289
telemt_upstream_connect_success_total 56684
telemt_upstream_connect_fail_total 1920
telemt_upstream_connect_attempts_per_request{bucket="1"} 58604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1920
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2908
telemt_me_reconnect_success_total 991
telemt_me_reader_eof_total 692
telemt_me_idle_close_by_peer_total 691
telemt_me_route_drop_no_conn_total 10227061
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5241507
telemt_me_endpoint_quarantine_total 382
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 116
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 116
telemt_me_single_endpoint_shadow_rotate_total 382
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
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 21
telemt_desync_total 10562
telemt_desync_full_logged_total 3425
telemt_desync_suppressed_total 7137
telemt_desync_frames_bucket_total{bucket="1_2"} 2331
telemt_desync_frames_bucket_total{bucket="3_10"} 4562
telemt_desync_frames_bucket_total{bucket="gt_10"} 3669
telemt_pool_swap_total 49
telemt_pool_force_close_total 1525
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 303
telemt_me_draining_writers_reap_progress_total 16371
telemt_me_writer_removed_unexpected_total 957
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2083
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15174
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1313
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 212
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14846
telemt_me_writer_teardown_success_total{mode="normal"} 17257
telemt_me_writer_teardown_noop_total 16377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33634
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 39.244764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33634
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 303
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 685
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 5276050
telemt_user_connections_current{user="hello"} 5629
telemt_user_octets_from_client{user="hello"} 48683427032 (45.34 GB)
telemt_user_octets_to_client{user="hello"} 588040864655 (547.66 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1874
telemt_user_unique_ips_recent_window{user="hello"} 1118
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 48635.5 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2093965
telemt_connections_bad_total 262035
telemt_connections_current 3541
telemt_connections_me_current 3541
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 40566
telemt_upstream_connect_attempt_total 21446
telemt_upstream_connect_success_total 21233
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 21427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_reconnect_attempts_total 2000
telemt_me_reconnect_success_total 640
telemt_me_reader_eof_total 650
telemt_me_idle_close_by_peer_total 650
telemt_me_route_drop_no_conn_total 654914
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1578042
telemt_me_endpoint_quarantine_total 298
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 376
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 5
telemt_desync_total 7254
telemt_desync_full_logged_total 2649
telemt_desync_suppressed_total 4605
telemt_desync_frames_bucket_total{bucket="1_2"} 1384
telemt_desync_frames_bucket_total{bucket="3_10"} 2949
telemt_desync_frames_bucket_total{bucket="gt_10"} 2921
telemt_pool_swap_total 50
telemt_pool_force_close_total 1335
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 100
telemt_me_draining_writers_reap_progress_total 17806
telemt_me_writer_removed_unexpected_total 627
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1603
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16853
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1225
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16471
telemt_me_writer_teardown_success_total{mode="normal"} 18456
telemt_me_writer_teardown_noop_total 17806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36262
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.609040
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36262
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 100
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 543
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1572466
telemt_user_connections_current{user="hello"} 3541
telemt_user_octets_from_client{user="hello"} 28678402380 (26.71 GB)
telemt_user_octets_to_client{user="hello"} 724301003918 (674.56 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1443
telemt_user_unique_ips_recent_window{user="hello"} 532
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 48629.9 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2971593
telemt_connections_bad_total 167740
telemt_connections_current 3423
telemt_connections_me_current 3423
telemt_handshake_timeouts_total 1227541
telemt_upstream_connect_attempt_total 20103
telemt_upstream_connect_success_total 20069
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 524
telemt_me_reconnect_success_total 303
telemt_me_reader_eof_total 305
telemt_me_idle_close_by_peer_total 305
telemt_me_route_drop_no_conn_total 556252
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1407172
telemt_me_endpoint_quarantine_total 368
telemt_me_single_endpoint_shadow_rotate_total 381
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 7
telemt_desync_total 6963
telemt_desync_full_logged_total 2457
telemt_desync_suppressed_total 4506
telemt_desync_frames_bucket_total{bucket="1_2"} 1233
telemt_desync_frames_bucket_total{bucket="3_10"} 2785
telemt_desync_frames_bucket_total{bucket="gt_10"} 2945
telemt_pool_swap_total 53
telemt_pool_force_close_total 1292
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 18009
telemt_me_writer_removed_unexpected_total 294
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1145
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17178
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1275
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16717
telemt_me_writer_teardown_success_total{mode="normal"} 18323
telemt_me_writer_teardown_noop_total 18009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36332
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.947678
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36332
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 270
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1402883
telemt_user_connections_current{user="hello"} 3423
telemt_user_octets_from_client{user="hello"} 25123875136 (23.40 GB)
telemt_user_octets_to_client{user="hello"} 691303098744 (643.83 GB)
telemt_user_unique_ips_current{user="hello"} 1356
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 46621.5 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 623369
telemt_connections_bad_total 21955
telemt_connections_current 747
telemt_connections_me_current 747
telemt_handshake_timeouts_total 231510
telemt_upstream_connect_attempt_total 22684
telemt_upstream_connect_success_total 22682
telemt_upstream_connect_attempts_per_request{bucket="1"} 22682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 953
telemt_me_reconnect_success_total 369
telemt_me_reader_eof_total 367
telemt_me_idle_close_by_peer_total 367
telemt_me_route_drop_no_conn_total 132531
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322849
telemt_me_endpoint_quarantine_total 445
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 398
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 2080
telemt_desync_full_logged_total 826
telemt_desync_suppressed_total 1254
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 791
telemt_desync_frames_bucket_total{bucket="gt_10"} 915
telemt_pool_swap_total 51
telemt_pool_force_close_total 1112
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 67
telemt_me_draining_writers_reap_progress_total 20280
telemt_me_writer_removed_unexpected_total 348
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19169
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1109
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19168
telemt_me_writer_teardown_success_total{mode="normal"} 20632
telemt_me_writer_teardown_noop_total 20280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40912
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.938672
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40912
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 67
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 302
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 322994
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 4803402407 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 126649107853 (117.95 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 48639.9 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2206082
telemt_connections_bad_total 203011
telemt_connections_current 4201
telemt_connections_me_current 4201
telemt_handshake_timeouts_total 54897
telemt_upstream_connect_attempt_total 20802
telemt_upstream_connect_success_total 20713
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 20772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 770
telemt_me_reconnect_success_total 442
telemt_me_reader_eof_total 414
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 552512
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1734213
telemt_me_endpoint_quarantine_total 377
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 381
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 8
telemt_desync_total 6804
telemt_desync_full_logged_total 2275
telemt_desync_suppressed_total 4529
telemt_desync_frames_bucket_total{bucket="1_2"} 1658
telemt_desync_frames_bucket_total{bucket="3_10"} 2534
telemt_desync_frames_bucket_total{bucket="gt_10"} 2612
telemt_pool_swap_total 53
telemt_pool_force_close_total 1314
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 18736
telemt_me_writer_removed_unexpected_total 410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1390
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17768
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1291
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17422
telemt_me_writer_teardown_success_total{mode="normal"} 19158
telemt_me_writer_teardown_noop_total 18736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37894
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.624358
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37894
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 398
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1728549
telemt_user_connections_current{user="hello"} 4201
telemt_user_octets_from_client{user="hello"} 38748897884 (36.09 GB)
telemt_user_octets_to_client{user="hello"} 811307135924 (755.59 GB)
telemt_user_unique_ips_current{user="hello"} 1538
telemt_user_unique_ips_recent_window{user="hello"} 585
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 48636.5 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2045411
telemt_connections_bad_total 168188
telemt_connections_current 3790
telemt_connections_me_current 3790
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 50022
telemt_upstream_connect_attempt_total 29414
telemt_upstream_connect_success_total 29202
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 29372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_reconnect_attempts_total 2996
telemt_me_reconnect_success_total 607
telemt_me_reader_eof_total 532
telemt_me_idle_close_by_peer_total 532
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 564854
telemt_me_route_drop_channel_closed_total 35
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1646539
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 378
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
telemt_me_writers_warm_current 7
telemt_desync_total 6343
telemt_desync_full_logged_total 2137
telemt_desync_suppressed_total 4206
telemt_desync_frames_bucket_total{bucket="1_2"} 1725
telemt_desync_frames_bucket_total{bucket="3_10"} 2356
telemt_desync_frames_bucket_total{bucket="gt_10"} 2262
telemt_pool_swap_total 52
telemt_pool_force_close_total 1289
telemt_me_writer_close_signal_drop_total 116
telemt_me_draining_writers_reap_progress_total 17979
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1633
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16914
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16690
telemt_me_writer_teardown_success_total{mode="normal"} 18547
telemt_me_writer_teardown_noop_total 17980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36527
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.476036
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36527
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 116
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 469
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 1650206
telemt_user_connections_current{user="hello"} 3790
telemt_user_octets_from_client{user="hello"} 27695341679 (25.79 GB)
telemt_user_octets_to_client{user="hello"} 735040414959 (684.56 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1402
telemt_user_unique_ips_recent_window{user="hello"} 494
```