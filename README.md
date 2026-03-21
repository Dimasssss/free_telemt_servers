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

# Server Metrics 2026-03-21 08:40:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 43463.3 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127993
telemt_connections_bad_total 56560
telemt_connections_current 1446
telemt_connections_me_current 1446
telemt_handshake_timeouts_total 49302
telemt_upstream_connect_attempt_total 17256
telemt_upstream_connect_success_total 17178
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 17232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10994
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 719
telemt_me_reconnect_success_total 311
telemt_me_reader_eof_total 314
telemt_me_idle_close_by_peer_total 314
telemt_me_route_drop_no_conn_total 476780
telemt_me_route_drop_channel_closed_total 164
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 833231
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_endpoint_quarantine_total 311
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 354
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
telemt_desync_total 3583
telemt_desync_full_logged_total 1264
telemt_desync_suppressed_total 2319
telemt_desync_frames_bucket_total{bucket="1_2"} 755
telemt_desync_frames_bucket_total{bucket="3_10"} 1365
telemt_desync_frames_bucket_total{bucket="gt_10"} 1463
telemt_pool_swap_total 48
telemt_pool_force_close_total 1314
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 15430
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1206
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14450
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14116
telemt_me_writer_teardown_success_total{mode="normal"} 15656
telemt_me_writer_teardown_noop_total 15431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31087
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 65.046770
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31087
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 271
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 832520
telemt_user_connections_current{user="hello"} 1446
telemt_user_octets_from_client{user="hello"} 11899027339 (11.08 GB)
telemt_user_octets_to_client{user="hello"} 240649937931 (224.12 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 43464.5 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2758776
telemt_connections_bad_total 310233
telemt_connections_current 4303
telemt_connections_me_current 4303
telemt_handshake_timeouts_total 77614
telemt_upstream_connect_attempt_total 15902
telemt_upstream_connect_success_total 15827
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 15878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 948
telemt_me_reconnect_success_total 358
telemt_me_reader_eof_total 352
telemt_me_idle_close_by_peer_total 351
telemt_me_route_drop_no_conn_total 747103
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1776963
telemt_me_endpoint_quarantine_total 281
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 341
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
telemt_desync_total 7898
telemt_desync_full_logged_total 2684
telemt_desync_suppressed_total 5214
telemt_desync_frames_bucket_total{bucket="1_2"} 1613
telemt_desync_frames_bucket_total{bucket="3_10"} 3079
telemt_desync_frames_bucket_total{bucket="gt_10"} 3206
telemt_pool_swap_total 47
telemt_pool_force_close_total 1414
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 14230
telemt_me_writer_removed_unexpected_total 330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1305
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13250
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1335
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 79
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12816
telemt_me_writer_teardown_success_total{mode="normal"} 14555
telemt_me_writer_teardown_noop_total 14230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28785
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.895570
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28785
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 287
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1773438
telemt_user_connections_current{user="hello"} 4303
telemt_user_octets_from_client{user="hello"} 25534642856 (23.78 GB)
telemt_user_octets_to_client{user="hello"} 683437041500 (636.50 GB)
telemt_user_unique_ips_current{user="hello"} 1554
telemt_user_unique_ips_recent_window{user="hello"} 606
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 43461.0 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2008781
telemt_connections_bad_total 251106
telemt_connections_current 4107
telemt_connections_me_current 4107
telemt_handshake_timeouts_total 74961
telemt_upstream_connect_attempt_total 17257
telemt_upstream_connect_success_total 17247
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 573
telemt_me_reconnect_success_total 322
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 334
telemt_me_route_drop_no_conn_total 637142
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1544849
telemt_me_endpoint_quarantine_total 298
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 343
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
telemt_desync_total 6446
telemt_desync_full_logged_total 2282
telemt_desync_suppressed_total 4164
telemt_desync_frames_bucket_total{bucket="1_2"} 1432
telemt_desync_frames_bucket_total{bucket="3_10"} 2502
telemt_desync_frames_bucket_total{bucket="gt_10"} 2512
telemt_pool_swap_total 47
telemt_pool_force_close_total 1383
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 15705
telemt_me_writer_removed_unexpected_total 314
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1280
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14642
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1309
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14322
telemt_me_writer_teardown_success_total{mode="normal"} 15922
telemt_me_writer_teardown_noop_total 15714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31636
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.396786
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31636
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 285
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1542140
telemt_user_connections_current{user="hello"} 4107
telemt_user_octets_from_client{user="hello"} 21651612832 (20.16 GB)
telemt_user_octets_to_client{user="hello"} 636391168704 (592.69 GB)
telemt_user_unique_ips_current{user="hello"} 1469
telemt_user_unique_ips_recent_window{user="hello"} 592
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 43462.1 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1687018
telemt_connections_bad_total 206873
telemt_connections_current 4000
telemt_connections_me_current 4000
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 68386
telemt_upstream_connect_attempt_total 21968
telemt_upstream_connect_success_total 21737
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 21860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 866
telemt_me_reconnect_success_total 392
telemt_me_reader_eof_total 367
telemt_me_idle_close_by_peer_total 367
telemt_me_route_drop_no_conn_total 475842
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1160201
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 348
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
telemt_me_writers_active_current 88
telemt_desync_total 5480
telemt_desync_full_logged_total 1889
telemt_desync_suppressed_total 3591
telemt_desync_frames_bucket_total{bucket="1_2"} 1340
telemt_desync_frames_bucket_total{bucket="3_10"} 2213
telemt_desync_frames_bucket_total{bucket="gt_10"} 1927
telemt_pool_swap_total 47
telemt_pool_force_close_total 1237
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 15362
telemt_me_writer_removed_unexpected_total 360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1222
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14514
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14125
telemt_me_writer_teardown_success_total{mode="normal"} 15736
telemt_me_writer_teardown_noop_total 15363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31099
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.372685
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31099
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 334
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1162596
telemt_user_connections_current{user="hello"} 4000
telemt_user_octets_from_client{user="hello"} 21056992709 (19.61 GB)
telemt_user_octets_to_client{user="hello"} 560362937871 (521.88 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1497
telemt_user_unique_ips_recent_window{user="hello"} 717
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 43429.3 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1621511
telemt_connections_bad_total 205952
telemt_connections_current 2388
telemt_connections_me_current 2388
telemt_handshake_timeouts_total 51217
telemt_upstream_connect_attempt_total 18146
telemt_upstream_connect_success_total 18134
telemt_upstream_connect_attempts_per_request{bucket="1"} 18134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 439
telemt_me_reconnect_success_total 318
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 365723
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1156396
telemt_me_endpoint_quarantine_total 342
telemt_me_single_endpoint_shadow_rotate_total 339
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
telemt_me_writers_active_current 44
telemt_desync_total 5581
telemt_desync_full_logged_total 1966
telemt_desync_suppressed_total 3615
telemt_desync_frames_bucket_total{bucket="1_2"} 1445
telemt_desync_frames_bucket_total{bucket="3_10"} 2173
telemt_desync_frames_bucket_total{bucket="gt_10"} 1963
telemt_pool_swap_total 47
telemt_pool_force_close_total 1221
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 16391
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1162
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15550
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1182
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 39
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15170
telemt_me_writer_teardown_success_total{mode="normal"} 16712
telemt_me_writer_teardown_noop_total 16394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33106
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.997225
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33106
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 286
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 1154417
telemt_user_connections_current{user="hello"} 2388
telemt_user_octets_from_client{user="hello"} 28817591288 (26.84 GB)
telemt_user_octets_to_client{user="hello"} 594672841616 (553.83 GB)
telemt_user_unique_ips_current{user="hello"} 890
telemt_user_unique_ips_recent_window{user="hello"} 642
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 43465.4 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4483506
telemt_connections_bad_total 248875
telemt_connections_current 5210
telemt_connections_me_current 5210
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 201651
telemt_upstream_connect_attempt_total 43701
telemt_upstream_connect_success_total 41718
telemt_upstream_connect_fail_total 1369
telemt_upstream_connect_attempts_per_request{bucket="1"} 43087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1277
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1369
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2242
telemt_me_reconnect_success_total 783
telemt_me_reader_eof_total 512
telemt_me_idle_close_by_peer_total 511
telemt_me_route_drop_no_conn_total 6674226
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3743947
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 345
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
telemt_me_writers_active_current 46
telemt_desync_total 7946
telemt_desync_full_logged_total 2665
telemt_desync_suppressed_total 5281
telemt_desync_frames_bucket_total{bucket="1_2"} 1759
telemt_desync_frames_bucket_total{bucket="3_10"} 3430
telemt_desync_frames_bucket_total{bucket="gt_10"} 2757
telemt_pool_swap_total 46
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 14694
telemt_me_writer_removed_unexpected_total 738
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13636
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13341
telemt_me_writer_teardown_success_total{mode="normal"} 15387
telemt_me_writer_teardown_noop_total 14700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30087
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.229537
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30087
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 514
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 3766038
telemt_user_connections_current{user="hello"} 5210
telemt_user_octets_from_client{user="hello"} 41584630578 (38.73 GB)
telemt_user_octets_to_client{user="hello"} 529886890478 (493.50 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1773
telemt_user_unique_ips_recent_window{user="hello"} 983
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 43432.8 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1680932
telemt_connections_bad_total 226270
telemt_connections_current 3239
telemt_connections_me_current 3239
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 32845
telemt_upstream_connect_attempt_total 19636
telemt_upstream_connect_success_total 19454
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 19617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 1706
telemt_me_reconnect_success_total 541
telemt_me_reader_eof_total 555
telemt_me_idle_close_by_peer_total 555
telemt_me_route_drop_no_conn_total 447795
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1246674
telemt_me_endpoint_quarantine_total 269
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 346
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
telemt_me_writers_active_current 45
telemt_desync_total 5514
telemt_desync_full_logged_total 2042
telemt_desync_suppressed_total 3472
telemt_desync_frames_bucket_total{bucket="1_2"} 1056
telemt_desync_frames_bucket_total{bucket="3_10"} 2243
telemt_desync_frames_bucket_total{bucket="gt_10"} 2215
telemt_pool_swap_total 46
telemt_pool_force_close_total 1186
telemt_me_writer_close_signal_drop_total 77
telemt_me_draining_writers_reap_progress_total 16256
telemt_me_writer_removed_unexpected_total 533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1412
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15399
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1116
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15070
telemt_me_writer_teardown_success_total{mode="normal"} 16811
telemt_me_writer_teardown_noop_total 16256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33067
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.264650
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33067
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 77
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 457
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1243680
telemt_user_connections_current{user="hello"} 3239
telemt_user_octets_from_client{user="hello"} 21676580328 (20.19 GB)
telemt_user_octets_to_client{user="hello"} 583275345358 (543.22 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1183
telemt_user_unique_ips_recent_window{user="hello"} 755
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 43427.4 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2214874
telemt_connections_bad_total 135793
telemt_connections_current 3029
telemt_connections_me_current 3029
telemt_handshake_timeouts_total 835120
telemt_upstream_connect_attempt_total 18498
telemt_upstream_connect_success_total 18464
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 276
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 464
telemt_me_reconnect_success_total 284
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 402461
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1097204
telemt_me_endpoint_quarantine_total 352
telemt_me_single_endpoint_shadow_rotate_total 348
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
telemt_desync_total 5482
telemt_desync_full_logged_total 1934
telemt_desync_suppressed_total 3548
telemt_desync_frames_bucket_total{bucket="1_2"} 952
telemt_desync_frames_bucket_total{bucket="3_10"} 2215
telemt_desync_frames_bucket_total{bucket="gt_10"} 2315
telemt_pool_swap_total 48
telemt_pool_force_close_total 1151
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 16560
telemt_me_writer_removed_unexpected_total 275
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1038
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15816
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15409
telemt_me_writer_teardown_success_total{mode="normal"} 16854
telemt_me_writer_teardown_noop_total 16560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33414
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.671604
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33414
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1093566
telemt_user_connections_current{user="hello"} 3029
telemt_user_octets_from_client{user="hello"} 19230728320 (17.91 GB)
telemt_user_octets_to_client{user="hello"} 554125244876 (516.07 GB)
telemt_user_unique_ips_current{user="hello"} 1150
telemt_user_unique_ips_recent_window{user="hello"} 614
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 41418.9 (11h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463488
telemt_connections_bad_total 15624
telemt_connections_current 623
telemt_connections_me_current 623
telemt_handshake_timeouts_total 154900
telemt_upstream_connect_attempt_total 20486
telemt_upstream_connect_success_total 20484
telemt_upstream_connect_attempts_per_request{bucket="1"} 20484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 746
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 316
telemt_me_idle_close_by_peer_total 316
telemt_me_route_drop_no_conn_total 103435
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259942
telemt_me_endpoint_quarantine_total 401
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 354
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
telemt_me_writers_active_current 44
telemt_desync_total 1674
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 984
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 692
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 45
telemt_pool_force_close_total 959
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 18304
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1292
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17313
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 957
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17345
telemt_me_writer_teardown_success_total{mode="normal"} 18605
telemt_me_writer_teardown_noop_total 18304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36909
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.425378
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36909
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 264
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 260125
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 3722438699 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 105666342285 (98.41 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 43437.5 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1721651
telemt_connections_bad_total 149119
telemt_connections_current 3459
telemt_connections_me_current 3459
telemt_handshake_timeouts_total 43910
telemt_upstream_connect_attempt_total 19103
telemt_upstream_connect_success_total 19018
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 19074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 683
telemt_me_reconnect_success_total 407
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 410460
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1353943
telemt_me_endpoint_quarantine_total 350
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 350
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
telemt_me_writers_active_current 44
telemt_desync_total 5460
telemt_desync_full_logged_total 1831
telemt_desync_suppressed_total 3629
telemt_desync_frames_bucket_total{bucket="1_2"} 1334
telemt_desync_frames_bucket_total{bucket="3_10"} 2043
telemt_desync_frames_bucket_total{bucket="gt_10"} 2083
telemt_pool_swap_total 48
telemt_pool_force_close_total 1170
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 17237
telemt_me_writer_removed_unexpected_total 373
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1263
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16356
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1148
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16067
telemt_me_writer_teardown_success_total{mode="normal"} 17619
telemt_me_writer_teardown_noop_total 17237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34856
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.208442
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34856
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 364
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 1348780
telemt_user_connections_current{user="hello"} 3459
telemt_user_octets_from_client{user="hello"} 30119452356 (28.05 GB)
telemt_user_octets_to_client{user="hello"} 628410929248 (585.25 GB)
telemt_user_unique_ips_current{user="hello"} 1215
telemt_user_unique_ips_recent_window{user="hello"} 538
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 43434.0 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1650354
telemt_connections_bad_total 138676
telemt_connections_current 3517
telemt_connections_me_current 3517
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 40958
telemt_upstream_connect_attempt_total 27554
telemt_upstream_connect_success_total 27359
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 27513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9859
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2784
telemt_me_reconnect_success_total 539
telemt_me_reader_eof_total 459
telemt_me_idle_close_by_peer_total 459
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 417977
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1310194
telemt_me_endpoint_quarantine_total 406
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 345
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
telemt_desync_total 5148
telemt_desync_full_logged_total 1683
telemt_desync_suppressed_total 3465
telemt_desync_frames_bucket_total{bucket="1_2"} 1426
telemt_desync_frames_bucket_total{bucket="3_10"} 1879
telemt_desync_frames_bucket_total{bucket="gt_10"} 1843
telemt_pool_swap_total 48
telemt_pool_force_close_total 1146
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 16348
telemt_me_writer_removed_unexpected_total 468
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1475
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15366
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1095
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15202
telemt_me_writer_teardown_success_total{mode="normal"} 16841
telemt_me_writer_teardown_noop_total 16349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33190
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.575675
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33190
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 407
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 1314239
telemt_user_connections_current{user="hello"} 3517
telemt_user_octets_from_client{user="hello"} 20115090019 (18.73 GB)
telemt_user_octets_to_client{user="hello"} 583436078831 (543.37 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1191
telemt_user_unique_ips_recent_window{user="hello"} 494
```