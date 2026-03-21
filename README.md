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

# Server Metrics 2026-03-21 07:08:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 37978.1 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 843398
telemt_connections_bad_total 44671
telemt_connections_current 1491
telemt_connections_me_current 1491
telemt_handshake_timeouts_total 40712
telemt_upstream_connect_attempt_total 15316
telemt_upstream_connect_success_total 15246
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 15293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 485
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 258
telemt_me_idle_close_by_peer_total 258
telemt_me_route_drop_no_conn_total 275738
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623498
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 271
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 312
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
telemt_desync_total 2734
telemt_desync_full_logged_total 995
telemt_desync_suppressed_total 1739
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 1075
telemt_desync_frames_bucket_total{bucket="gt_10"} 1094
telemt_pool_swap_total 42
telemt_pool_force_close_total 1127
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 13781
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1013
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12969
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1122
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12654
telemt_me_writer_teardown_success_total{mode="normal"} 13982
telemt_me_writer_teardown_noop_total 13782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27764
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.766304
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27764
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 222
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 622773
telemt_user_connections_current{user="hello"} 1491
telemt_user_octets_from_client{user="hello"} 7463734356 (6.95 GB)
telemt_user_octets_to_client{user="hello"} 197191388188 (183.65 GB)
telemt_user_unique_ips_current{user="hello"} 529
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 37979.5 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2108780
telemt_connections_bad_total 232516
telemt_connections_current 3882
telemt_connections_me_current 3882
telemt_handshake_timeouts_total 65450
telemt_upstream_connect_attempt_total 14238
telemt_upstream_connect_success_total 14171
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 14217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 856
telemt_me_reconnect_success_total 286
telemt_me_reader_eof_total 294
telemt_me_idle_close_by_peer_total 293
telemt_me_route_drop_no_conn_total 435452
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1283262
telemt_me_endpoint_quarantine_total 250
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 305
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 5522
telemt_desync_full_logged_total 1919
telemt_desync_suppressed_total 3603
telemt_desync_frames_bucket_total{bucket="1_2"} 1128
telemt_desync_frames_bucket_total{bucket="3_10"} 2169
telemt_desync_frames_bucket_total{bucket="gt_10"} 2225
telemt_pool_swap_total 41
telemt_pool_force_close_total 1190
telemt_me_writer_close_signal_drop_total 124
telemt_me_draining_writers_reap_progress_total 12753
telemt_me_writer_removed_unexpected_total 275
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1122
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11898
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11563
telemt_me_writer_teardown_success_total{mode="normal"} 13020
telemt_me_writer_teardown_noop_total 12753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25773
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.596804
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25773
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 124
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1280231
telemt_user_connections_current{user="hello"} 3882
telemt_user_octets_from_client{user="hello"} 17640222648 (16.43 GB)
telemt_user_octets_to_client{user="hello"} 529235438440 (492.89 GB)
telemt_user_unique_ips_current{user="hello"} 1492
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 37976.0 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1418871
telemt_connections_bad_total 161555
telemt_connections_current 3694
telemt_connections_me_current 3694
telemt_handshake_timeouts_total 64721
telemt_upstream_connect_attempt_total 15379
telemt_upstream_connect_success_total 15369
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 480
telemt_me_reconnect_success_total 248
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 364698
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1105281
telemt_me_endpoint_quarantine_total 270
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 305
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
telemt_me_writers_active_current 41
telemt_desync_total 4440
telemt_desync_full_logged_total 1603
telemt_desync_suppressed_total 2837
telemt_desync_frames_bucket_total{bucket="1_2"} 987
telemt_desync_frames_bucket_total{bucket="3_10"} 1708
telemt_desync_frames_bucket_total{bucket="gt_10"} 1745
telemt_pool_swap_total 42
telemt_pool_force_close_total 1132
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 13960
telemt_me_writer_removed_unexpected_total 241
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1084
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13054
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1118
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12828
telemt_me_writer_teardown_success_total{mode="normal"} 14138
telemt_me_writer_teardown_noop_total 13963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28101
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.118635
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28101
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 213
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1103045
telemt_user_connections_current{user="hello"} 3694
telemt_user_octets_from_client{user="hello"} 15098635760 (14.06 GB)
telemt_user_octets_to_client{user="hello"} 486899543124 (453.46 GB)
telemt_user_unique_ips_current{user="hello"} 1401
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 37977.3 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1235454
telemt_connections_bad_total 157091
telemt_connections_current 2172
telemt_connections_me_current 2172
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 58176
telemt_upstream_connect_attempt_total 20195
telemt_upstream_connect_success_total 19980
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 716
telemt_me_reconnect_success_total 306
telemt_me_reader_eof_total 292
telemt_me_idle_close_by_peer_total 292
telemt_me_route_drop_no_conn_total 348479
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 847869
telemt_me_endpoint_quarantine_total 279
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 310
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
telemt_desync_total 3889
telemt_desync_full_logged_total 1399
telemt_desync_suppressed_total 2490
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 1643
telemt_desync_frames_bucket_total{bucket="gt_10"} 1384
telemt_pool_swap_total 42
telemt_pool_force_close_total 1045
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 13835
telemt_me_writer_removed_unexpected_total 284
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13075
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1022
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12790
telemt_me_writer_teardown_success_total{mode="normal"} 14133
telemt_me_writer_teardown_noop_total 13836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27969
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.258812
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27969
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 257
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 850882
telemt_user_connections_current{user="hello"} 2172
telemt_user_octets_from_client{user="hello"} 14712683245 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 398119013251 (370.78 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 729
telemt_user_unique_ips_recent_window{user="hello"} 351
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 37940.9 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1178230
telemt_connections_bad_total 147048
telemt_connections_current 3141
telemt_connections_me_current 3141
telemt_handshake_timeouts_total 42656
telemt_upstream_connect_attempt_total 16081
telemt_upstream_connect_success_total 16072
telemt_upstream_connect_attempts_per_request{bucket="1"} 16072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8910
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 283
telemt_me_reconnect_success_total 239
telemt_me_reader_eof_total 235
telemt_me_idle_close_by_peer_total 235
telemt_me_route_drop_no_conn_total 246954
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 835998
telemt_me_endpoint_quarantine_total 313
telemt_me_single_endpoint_shadow_rotate_total 301
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
telemt_me_writers_active_current 45
telemt_desync_total 4021
telemt_desync_full_logged_total 1473
telemt_desync_suppressed_total 2548
telemt_desync_frames_bucket_total{bucket="1_2"} 1000
telemt_desync_frames_bucket_total{bucket="3_10"} 1559
telemt_desync_frames_bucket_total{bucket="gt_10"} 1462
telemt_pool_swap_total 42
telemt_pool_force_close_total 1021
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 65
telemt_me_draining_writers_reap_progress_total 14553
telemt_me_writer_removed_unexpected_total 216
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 960
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13829
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13532
telemt_me_writer_teardown_success_total{mode="normal"} 14789
telemt_me_writer_teardown_noop_total 14554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29343
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.527185
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29343
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 65
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 834458
telemt_user_connections_current{user="hello"} 3141
telemt_user_octets_from_client{user="hello"} 21111665604 (19.66 GB)
telemt_user_octets_to_client{user="hello"} 435402374872 (405.50 GB)
telemt_user_unique_ips_current{user="hello"} 1226
telemt_user_unique_ips_recent_window{user="hello"} 362
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 37980.3 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2635749
telemt_connections_bad_total 177862
telemt_connections_current 4712
telemt_connections_me_current 4712
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 160566
telemt_upstream_connect_attempt_total 41523
telemt_upstream_connect_success_total 39670
telemt_upstream_connect_fail_total 1329
telemt_upstream_connect_attempts_per_request{bucket="1"} 40999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1329
telemt_me_reconnect_attempts_total 1878
telemt_me_reconnect_success_total 605
telemt_me_reader_eof_total 409
telemt_me_idle_close_by_peer_total 408
telemt_me_route_drop_no_conn_total 2602150
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2106117
telemt_me_endpoint_quarantine_total 306
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 79
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 79
telemt_me_single_endpoint_shadow_rotate_total 305
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
telemt_me_writers_active_current 45
telemt_desync_total 5070
telemt_desync_full_logged_total 1852
telemt_desync_suppressed_total 3218
telemt_desync_frames_bucket_total{bucket="1_2"} 1160
telemt_desync_frames_bucket_total{bucket="3_10"} 2140
telemt_desync_frames_bucket_total{bucket="gt_10"} 1770
telemt_pool_swap_total 41
telemt_pool_force_close_total 1116
telemt_me_writer_close_signal_drop_total 167
telemt_me_draining_writers_reap_progress_total 12935
telemt_me_writer_removed_unexpected_total 580
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1470
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12014
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1045
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11819
telemt_me_writer_teardown_success_total{mode="normal"} 13484
telemt_me_writer_teardown_noop_total 12939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26423
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.738532
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26423
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 167
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 393
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 2129175
telemt_user_connections_current{user="hello"} 4712
telemt_user_octets_from_client{user="hello"} 34481692122 (32.11 GB)
telemt_user_octets_to_client{user="hello"} 468954033586 (436.75 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1657
telemt_user_unique_ips_recent_window{user="hello"} 821
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 37947.8 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1255370
telemt_connections_bad_total 177113
telemt_connections_current 2999
telemt_connections_me_current 2999
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 26425
telemt_upstream_connect_attempt_total 17710
telemt_upstream_connect_success_total 17551
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 17695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_reconnect_attempts_total 1464
telemt_me_reconnect_success_total 402
telemt_me_reader_eof_total 413
telemt_me_idle_close_by_peer_total 413
telemt_me_route_drop_no_conn_total 310859
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908308
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 304
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
telemt_me_writers_active_current 103
telemt_me_writers_warm_current 27
telemt_desync_total 3787
telemt_desync_full_logged_total 1442
telemt_desync_suppressed_total 2345
telemt_desync_frames_bucket_total{bucket="1_2"} 732
telemt_desync_frames_bucket_total{bucket="3_10"} 1532
telemt_desync_frames_bucket_total{bucket="gt_10"} 1523
telemt_pool_swap_total 40
telemt_pool_force_close_total 956
telemt_me_writer_close_signal_drop_total 60
telemt_me_draining_writers_reap_progress_total 14518
telemt_me_writer_removed_unexpected_total 393
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13792
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13562
telemt_me_writer_teardown_success_total{mode="normal"} 14931
telemt_me_writer_teardown_noop_total 14518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29449
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.066861
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29449
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 60
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 323
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 905921
telemt_user_connections_current{user="hello"} 2999
telemt_user_octets_from_client{user="hello"} 15115159652 (14.08 GB)
telemt_user_octets_to_client{user="hello"} 449933035354 (419.03 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1222
telemt_user_unique_ips_recent_window{user="hello"} 393
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 37942.3 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1623406
telemt_connections_bad_total 106311
telemt_connections_current 2486
telemt_connections_me_current 2486
telemt_handshake_timeouts_total 591703
telemt_upstream_connect_attempt_total 16705
telemt_upstream_connect_success_total 16677
telemt_upstream_connect_attempts_per_request{bucket="1"} 16677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_me_reconnect_attempts_total 352
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 255
telemt_me_idle_close_by_peer_total 255
telemt_me_route_drop_no_conn_total 278552
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 808483
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_shadow_rotate_total 308
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
telemt_me_writers_active_current 43
telemt_desync_total 3692
telemt_desync_full_logged_total 1303
telemt_desync_suppressed_total 2389
telemt_desync_frames_bucket_total{bucket="1_2"} 666
telemt_desync_frames_bucket_total{bucket="3_10"} 1502
telemt_desync_frames_bucket_total{bucket="gt_10"} 1524
telemt_pool_swap_total 42
telemt_pool_force_close_total 947
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 14947
telemt_me_writer_removed_unexpected_total 239
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 883
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14320
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 939
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14000
telemt_me_writer_teardown_success_total{mode="normal"} 15203
telemt_me_writer_teardown_noop_total 14947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30150
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.543893
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30150
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 805502
telemt_user_connections_current{user="hello"} 2486
telemt_user_octets_from_client{user="hello"} 12959576516 (12.07 GB)
telemt_user_octets_to_client{user="hello"} 412758721896 (384.41 GB)
telemt_user_unique_ips_current{user="hello"} 1011
telemt_user_unique_ips_recent_window{user="hello"} 387
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 35933.9 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313796
telemt_connections_bad_total 11619
telemt_connections_current 528
telemt_connections_me_current 528
telemt_handshake_timeouts_total 86933
telemt_upstream_connect_attempt_total 18169
telemt_upstream_connect_success_total 18168
telemt_upstream_connect_attempts_per_request{bucket="1"} 18168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 584
telemt_me_reconnect_success_total 272
telemt_me_reader_eof_total 277
telemt_me_idle_close_by_peer_total 277
telemt_me_route_drop_no_conn_total 74149
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196816
telemt_me_endpoint_quarantine_total 352
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 310
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_me_writers_active_current 44
telemt_desync_total 1202
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 643
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 507
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 39
telemt_pool_force_close_total 800
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 16218
telemt_me_writer_removed_unexpected_total 261
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1121
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15359
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 800
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15418
telemt_me_writer_teardown_success_total{mode="normal"} 16480
telemt_me_writer_teardown_noop_total 16218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32698
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.188867
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32698
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 233
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 197030
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 2182497015 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 83904703309 (78.14 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 37952.2 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280425
telemt_connections_bad_total 95997
telemt_connections_current 3167
telemt_connections_me_current 3167
telemt_handshake_timeouts_total 34496
telemt_upstream_connect_attempt_total 17167
telemt_upstream_connect_success_total 17087
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 17138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 590
telemt_me_reconnect_success_total 346
telemt_me_reader_eof_total 329
telemt_me_idle_close_by_peer_total 329
telemt_me_route_drop_no_conn_total 283017
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1001590
telemt_me_endpoint_quarantine_total 317
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 307
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 3945
telemt_desync_full_logged_total 1320
telemt_desync_suppressed_total 2625
telemt_desync_frames_bucket_total{bucket="1_2"} 1031
telemt_desync_frames_bucket_total{bucket="3_10"} 1477
telemt_desync_frames_bucket_total{bucket="gt_10"} 1437
telemt_pool_swap_total 42
telemt_pool_force_close_total 964
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 78
telemt_me_draining_writers_reap_progress_total 15470
telemt_me_writer_removed_unexpected_total 330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1083
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14724
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 959
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14506
telemt_me_writer_teardown_success_total{mode="normal"} 15807
telemt_me_writer_teardown_noop_total 15470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31277
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.232170
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31277
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 78
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 997153
telemt_user_connections_current{user="hello"} 3167
telemt_user_octets_from_client{user="hello"} 16159449884 (15.05 GB)
telemt_user_octets_to_client{user="hello"} 451574487008 (420.56 GB)
telemt_user_unique_ips_current{user="hello"} 1207
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 37948.9 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1218180
telemt_connections_bad_total 82393
telemt_connections_current 3274
telemt_connections_me_current 3274
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 31752
telemt_upstream_connect_attempt_total 25717
telemt_upstream_connect_success_total 25534
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 25677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_reconnect_attempts_total 2537
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 403
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 286981
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 971590
telemt_me_endpoint_quarantine_total 380
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 302
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
telemt_desync_total 3849
telemt_desync_full_logged_total 1208
telemt_desync_suppressed_total 2641
telemt_desync_frames_bucket_total{bucket="1_2"} 1128
telemt_desync_frames_bucket_total{bucket="3_10"} 1416
telemt_desync_frames_bucket_total{bucket="gt_10"} 1305
telemt_pool_swap_total 42
telemt_pool_force_close_total 934
telemt_me_writer_close_signal_drop_total 77
telemt_me_draining_writers_reap_progress_total 14689
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1282
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13844
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 914
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13755
telemt_me_writer_teardown_success_total{mode="normal"} 15126
telemt_me_writer_teardown_noop_total 14689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29815
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.486261
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29815
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 77
telemt_me_refill_failed_total 118
telemt_me_writer_restored_same_endpoint_total 343
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 976309
telemt_user_connections_current{user="hello"} 3274
telemt_user_octets_from_client{user="hello"} 12489605655 (11.63 GB)
telemt_user_octets_to_client{user="hello"} 430672991587 (401.10 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1183
telemt_user_unique_ips_recent_window{user="hello"} 411
```