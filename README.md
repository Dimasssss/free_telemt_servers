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

# Server Metrics 2026-03-21 07:39:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 39805.8 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 936115
telemt_connections_bad_total 49087
telemt_connections_current 1420
telemt_connections_me_current 1420
telemt_handshake_timeouts_total 43204
telemt_upstream_connect_attempt_total 15858
telemt_upstream_connect_success_total 15787
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 15835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 522
telemt_me_reconnect_success_total 250
telemt_me_reader_eof_total 266
telemt_me_idle_close_by_peer_total 266
telemt_me_route_drop_no_conn_total 297587
telemt_me_route_drop_channel_closed_total 111
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680583
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 281
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 327
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
telemt_desync_total 2991
telemt_desync_full_logged_total 1072
telemt_desync_suppressed_total 1919
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 1205
telemt_pool_swap_total 44
telemt_pool_force_close_total 1220
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 14316
telemt_me_writer_removed_unexpected_total 250
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1068
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13453
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13096
telemt_me_writer_teardown_success_total{mode="normal"} 14521
telemt_me_writer_teardown_noop_total 14317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28838
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.210016
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28838
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 227
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 679774
telemt_user_connections_current{user="hello"} 1420
telemt_user_octets_from_client{user="hello"} 8397559648 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 213346994688 (198.69 GB)
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 39807.1 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2303263
telemt_connections_bad_total 260399
telemt_connections_current 3998
telemt_connections_me_current 3998
telemt_handshake_timeouts_total 68831
telemt_upstream_connect_attempt_total 14847
telemt_upstream_connect_success_total 14778
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 14826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 881
telemt_me_reconnect_success_total 322
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 318
telemt_me_route_drop_no_conn_total 497740
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1428155
telemt_me_endpoint_quarantine_total 265
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 319
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
telemt_desync_total 6184
telemt_desync_full_logged_total 2153
telemt_desync_suppressed_total 4031
telemt_desync_frames_bucket_total{bucket="1_2"} 1273
telemt_desync_frames_bucket_total{bucket="3_10"} 2418
telemt_desync_frames_bucket_total{bucket="gt_10"} 2493
telemt_pool_swap_total 43
telemt_pool_force_close_total 1259
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 13277
telemt_me_writer_removed_unexpected_total 299
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1192
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12377
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1192
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12018
telemt_me_writer_teardown_success_total{mode="normal"} 13569
telemt_me_writer_teardown_noop_total 13277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26846
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.444546
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26846
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 262
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 1424941
telemt_user_connections_current{user="hello"} 3998
telemt_user_octets_from_client{user="hello"} 19510481556 (18.17 GB)
telemt_user_octets_to_client{user="hello"} 581482049836 (541.55 GB)
telemt_user_unique_ips_current{user="hello"} 1437
telemt_user_unique_ips_recent_window{user="hello"} 810
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 39803.5 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1564014
telemt_connections_bad_total 167091
telemt_connections_current 3830
telemt_connections_me_current 3830
telemt_handshake_timeouts_total 69089
telemt_upstream_connect_attempt_total 15927
telemt_upstream_connect_success_total 15917
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 489
telemt_me_reconnect_success_total 258
telemt_me_reader_eof_total 267
telemt_me_idle_close_by_peer_total 267
telemt_me_route_drop_no_conn_total 416731
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1227189
telemt_me_endpoint_quarantine_total 283
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 319
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
telemt_desync_total 5007
telemt_desync_full_logged_total 1788
telemt_desync_suppressed_total 3219
telemt_desync_frames_bucket_total{bucket="1_2"} 1111
telemt_desync_frames_bucket_total{bucket="3_10"} 1912
telemt_desync_frames_bucket_total{bucket="gt_10"} 1984
telemt_pool_swap_total 44
telemt_pool_force_close_total 1243
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 140
telemt_me_draining_writers_reap_progress_total 14518
telemt_me_writer_removed_unexpected_total 249
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1132
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13549
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1225
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13275
telemt_me_writer_teardown_success_total{mode="normal"} 14681
telemt_me_writer_teardown_noop_total 14521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29202
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.212876
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29202
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 140
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1224779
telemt_user_connections_current{user="hello"} 3830
telemt_user_octets_from_client{user="hello"} 16744295728 (15.59 GB)
telemt_user_octets_to_client{user="hello"} 535890801940 (499.09 GB)
telemt_user_unique_ips_current{user="hello"} 1304
telemt_user_unique_ips_recent_window{user="hello"} 978
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 39805.0 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1356446
telemt_connections_bad_total 161616
telemt_connections_current 2508
telemt_connections_me_current 2508
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 62059
telemt_upstream_connect_attempt_total 20786
telemt_upstream_connect_success_total 20558
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 20678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 734
telemt_me_reconnect_success_total 315
telemt_me_reader_eof_total 299
telemt_me_idle_close_by_peer_total 299
telemt_me_route_drop_no_conn_total 386630
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 941539
telemt_me_endpoint_quarantine_total 290
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 322
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
telemt_desync_total 4288
telemt_desync_full_logged_total 1537
telemt_desync_suppressed_total 2751
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1800
telemt_desync_frames_bucket_total{bucket="gt_10"} 1504
telemt_pool_swap_total 44
telemt_pool_force_close_total 1134
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 14392
telemt_me_writer_removed_unexpected_total 291
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1102
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13595
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1104
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13258
telemt_me_writer_teardown_success_total{mode="normal"} 14697
telemt_me_writer_teardown_noop_total 14393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29090
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.741412
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29090
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 264
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 944267
telemt_user_connections_current{user="hello"} 2508
telemt_user_octets_from_client{user="hello"} 16405347817 (15.28 GB)
telemt_user_octets_to_client{user="hello"} 442664116363 (412.26 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 846
telemt_user_unique_ips_recent_window{user="hello"} 576
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 39768.7 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1302980
telemt_connections_bad_total 150427
telemt_connections_current 3243
telemt_connections_me_current 3243
telemt_handshake_timeouts_total 45930
telemt_upstream_connect_attempt_total 16738
telemt_upstream_connect_success_total 16729
telemt_upstream_connect_attempts_per_request{bucket="1"} 16729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 326
telemt_me_reconnect_success_total 248
telemt_me_reader_eof_total 245
telemt_me_idle_close_by_peer_total 245
telemt_me_route_drop_no_conn_total 282638
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 931871
telemt_me_endpoint_quarantine_total 325
telemt_me_single_endpoint_shadow_rotate_total 313
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
telemt_desync_total 4459
telemt_desync_full_logged_total 1617
telemt_desync_suppressed_total 2842
telemt_desync_frames_bucket_total{bucket="1_2"} 1115
telemt_desync_frames_bucket_total{bucket="3_10"} 1733
telemt_desync_frames_bucket_total{bucket="gt_10"} 1611
telemt_pool_swap_total 44
telemt_pool_force_close_total 1077
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 74
telemt_me_draining_writers_reap_progress_total 15147
telemt_me_writer_removed_unexpected_total 224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1009
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14384
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14070
telemt_me_writer_teardown_success_total{mode="normal"} 15393
telemt_me_writer_teardown_noop_total 15150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30543
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.129240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30543
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 74
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 218
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 930241
telemt_user_connections_current{user="hello"} 3243
telemt_user_octets_from_client{user="hello"} 25013647240 (23.30 GB)
telemt_user_octets_to_client{user="hello"} 483923549812 (450.69 GB)
telemt_user_unique_ips_current{user="hello"} 1218
telemt_user_unique_ips_recent_window{user="hello"} 490
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 39808.0 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3116465
telemt_connections_bad_total 193871
telemt_connections_current 4634
telemt_connections_me_current 4634
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 174805
telemt_upstream_connect_attempt_total 42211
telemt_upstream_connect_success_total 40303
telemt_upstream_connect_fail_total 1354
telemt_upstream_connect_attempts_per_request{bucket="1"} 41657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1354
telemt_me_reconnect_attempts_total 1978
telemt_me_reconnect_success_total 674
telemt_me_reader_eof_total 425
telemt_me_idle_close_by_peer_total 424
telemt_me_route_drop_no_conn_total 3544646
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2530543
telemt_me_endpoint_quarantine_total 320
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 321
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
telemt_me_writers_active_current 47
telemt_desync_total 6008
telemt_desync_full_logged_total 2128
telemt_desync_suppressed_total 3880
telemt_desync_frames_bucket_total{bucket="1_2"} 1370
telemt_desync_frames_bucket_total{bucket="3_10"} 2540
telemt_desync_frames_bucket_total{bucket="gt_10"} 2098
telemt_pool_swap_total 43
telemt_pool_force_close_total 1219
telemt_me_writer_close_signal_drop_total 201
telemt_me_draining_writers_reap_progress_total 13478
telemt_me_writer_removed_unexpected_total 641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1585
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12498
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1138
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12259
telemt_me_writer_teardown_success_total{mode="normal"} 14083
telemt_me_writer_teardown_noop_total 13483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27566
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.244054
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27566
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 201
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 428
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 2553002
telemt_user_connections_current{user="hello"} 4634
telemt_user_octets_from_client{user="hello"} 36579417494 (34.07 GB)
telemt_user_octets_to_client{user="hello"} 490266928874 (456.60 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1542
telemt_user_unique_ips_recent_window{user="hello"} 1287
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 39775.6 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1392207
telemt_connections_bad_total 199431
telemt_connections_current 2733
telemt_connections_me_current 2733
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 28438
telemt_upstream_connect_attempt_total 18526
telemt_upstream_connect_success_total 18361
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 18510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_reconnect_attempts_total 1638
telemt_me_reconnect_success_total 511
telemt_me_reader_eof_total 526
telemt_me_idle_close_by_peer_total 526
telemt_me_route_drop_no_conn_total 346693
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1010632
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 319
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
telemt_me_writers_active_current 43
telemt_desync_total 4290
telemt_desync_full_logged_total 1619
telemt_desync_suppressed_total 2671
telemt_desync_frames_bucket_total{bucket="1_2"} 828
telemt_desync_frames_bucket_total{bucket="3_10"} 1742
telemt_desync_frames_bucket_total{bucket="gt_10"} 1720
telemt_pool_swap_total 42
telemt_pool_force_close_total 1030
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 15246
telemt_me_writer_removed_unexpected_total 505
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14469
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 971
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14216
telemt_me_writer_teardown_success_total{mode="normal"} 15772
telemt_me_writer_teardown_noop_total 15246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31018
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.101519
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31018
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 432
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 1008051
telemt_user_connections_current{user="hello"} 2733
telemt_user_octets_from_client{user="hello"} 16755383048 (15.60 GB)
telemt_user_octets_to_client{user="hello"} 486965526818 (453.52 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1023
telemt_user_unique_ips_recent_window{user="hello"} 470
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 39770.1 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1789616
telemt_connections_bad_total 118313
telemt_connections_current 2827
telemt_connections_me_current 2827
telemt_handshake_timeouts_total 653255
telemt_upstream_connect_attempt_total 17332
telemt_upstream_connect_success_total 17304
telemt_upstream_connect_attempts_per_request{bucket="1"} 17304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 268
telemt_me_reconnect_attempts_total 364
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 264
telemt_me_idle_close_by_peer_total 264
telemt_me_route_drop_no_conn_total 313656
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 894528
telemt_me_endpoint_quarantine_total 337
telemt_me_single_endpoint_shadow_rotate_total 322
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
telemt_desync_total 4298
telemt_desync_full_logged_total 1517
telemt_desync_suppressed_total 2781
telemt_desync_frames_bucket_total{bucket="1_2"} 744
telemt_desync_frames_bucket_total{bucket="3_10"} 1755
telemt_desync_frames_bucket_total{bucket="gt_10"} 1799
telemt_pool_swap_total 44
telemt_pool_force_close_total 1006
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 15510
telemt_me_writer_removed_unexpected_total 247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 932
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14843
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14504
telemt_me_writer_teardown_success_total{mode="normal"} 15775
telemt_me_writer_teardown_noop_total 15510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31285
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.562897
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31285
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 891426
telemt_user_connections_current{user="hello"} 2827
telemt_user_octets_from_client{user="hello"} 15176404676 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 456562619556 (425.21 GB)
telemt_user_unique_ips_current{user="hello"} 1197
telemt_user_unique_ips_recent_window{user="hello"} 387
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 37761.4 (10h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362174
telemt_connections_bad_total 12481
telemt_connections_current 621
telemt_connections_me_current 621
telemt_handshake_timeouts_total 106947
telemt_upstream_connect_attempt_total 18943
telemt_upstream_connect_success_total 18942
telemt_upstream_connect_attempts_per_request{bucket="1"} 18942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10939
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 710
telemt_me_reconnect_success_total 294
telemt_me_reader_eof_total 298
telemt_me_idle_close_by_peer_total 298
telemt_me_route_drop_no_conn_total 83489
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217679
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 326
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 1368
telemt_desync_full_logged_total 605
telemt_desync_suppressed_total 763
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 544
telemt_pool_swap_total 41
telemt_pool_force_close_total 850
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 50
telemt_me_draining_writers_reap_progress_total 16902
telemt_me_writer_removed_unexpected_total 280
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1181
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16004
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 850
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16052
telemt_me_writer_teardown_success_total{mode="normal"} 17185
telemt_me_writer_teardown_noop_total 16902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34087
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.285764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34087
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 50
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 247
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 217887
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 2808038211 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 93171484269 (86.77 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 39779.9 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1411715
telemt_connections_bad_total 111525
telemt_connections_current 3009
telemt_connections_me_current 3009
telemt_handshake_timeouts_total 36586
telemt_upstream_connect_attempt_total 17817
telemt_upstream_connect_success_total 17736
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 17788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 597
telemt_me_reconnect_success_total 353
telemt_me_reader_eof_total 335
telemt_me_idle_close_by_peer_total 335
telemt_me_route_drop_no_conn_total 319615
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1107804
telemt_me_endpoint_quarantine_total 326
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 322
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
telemt_desync_total 4451
telemt_desync_full_logged_total 1488
telemt_desync_suppressed_total 2963
telemt_desync_frames_bucket_total{bucket="1_2"} 1137
telemt_desync_frames_bucket_total{bucket="3_10"} 1674
telemt_desync_frames_bucket_total{bucket="gt_10"} 1640
telemt_pool_swap_total 44
telemt_pool_force_close_total 1023
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 16075
telemt_me_writer_removed_unexpected_total 335
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15279
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1013
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15052
telemt_me_writer_teardown_success_total{mode="normal"} 16418
telemt_me_writer_teardown_noop_total 16075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32493
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.648192
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32493
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 320
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 1103148
telemt_user_connections_current{user="hello"} 3009
telemt_user_octets_from_client{user="hello"} 18226258048 (16.97 GB)
telemt_user_octets_to_client{user="hello"} 506405251336 (471.63 GB)
telemt_user_unique_ips_current{user="hello"} 1155
telemt_user_unique_ips_recent_window{user="hello"} 435
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 39776.6 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1349680
telemt_connections_bad_total 98283
telemt_connections_current 3523
telemt_connections_me_current 3523
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 34990
telemt_upstream_connect_attempt_total 26288
telemt_upstream_connect_success_total 26096
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 2629
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 413
telemt_me_idle_close_by_peer_total 413
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 323478
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1075783
telemt_me_endpoint_quarantine_total 387
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 319
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
telemt_desync_total 4319
telemt_desync_full_logged_total 1363
telemt_desync_suppressed_total 2956
telemt_desync_frames_bucket_total{bucket="1_2"} 1241
telemt_desync_frames_bucket_total{bucket="3_10"} 1575
telemt_desync_frames_bucket_total{bucket="gt_10"} 1503
telemt_pool_swap_total 44
telemt_pool_force_close_total 986
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 15204
telemt_me_writer_removed_unexpected_total 425
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1337
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14314
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 965
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14218
telemt_me_writer_teardown_success_total{mode="normal"} 15651
telemt_me_writer_teardown_noop_total 15204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30855
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.586797
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30855
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 123
telemt_me_writer_restored_same_endpoint_total 348
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1080424
telemt_user_connections_current{user="hello"} 3523
telemt_user_octets_from_client{user="hello"} 14105497755 (13.14 GB)
telemt_user_octets_to_client{user="hello"} 479566150363 (446.63 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1329
telemt_user_unique_ips_recent_window{user="hello"} 444
```