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

# Server Metrics 2026-03-21 07:44:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 40110.6 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 950059
telemt_connections_bad_total 49828
telemt_connections_current 1566
telemt_connections_me_current 1566
telemt_handshake_timeouts_total 43765
telemt_upstream_connect_attempt_total 15928
telemt_upstream_connect_success_total 15857
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 15905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 523
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 268
telemt_me_idle_close_by_peer_total 268
telemt_me_route_drop_no_conn_total 300064
telemt_me_route_drop_channel_closed_total 112
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689189
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
telemt_desync_total 3026
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 1940
telemt_desync_frames_bucket_total{bucket="1_2"} 624
telemt_desync_frames_bucket_total{bucket="3_10"} 1176
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 44
telemt_pool_force_close_total 1220
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 14369
telemt_me_writer_removed_unexpected_total 251
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1072
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13504
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13149
telemt_me_writer_teardown_success_total{mode="normal"} 14576
telemt_me_writer_teardown_noop_total 14370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28946
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.212168
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28946
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 228
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 688393
telemt_user_connections_current{user="hello"} 1566
telemt_user_octets_from_client{user="hello"} 8727026540 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 215542755588 (200.74 GB)
telemt_user_unique_ips_current{user="hello"} 558
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 40111.7 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2329495
telemt_connections_bad_total 260685
telemt_connections_current 3903
telemt_connections_me_current 3903
telemt_handshake_timeouts_total 69481
telemt_upstream_connect_attempt_total 14927
telemt_upstream_connect_success_total 14858
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 14906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 886
telemt_me_reconnect_success_total 326
telemt_me_reader_eof_total 324
telemt_me_idle_close_by_peer_total 323
telemt_me_route_drop_no_conn_total 513401
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1452208
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
telemt_desync_total 6301
telemt_desync_full_logged_total 2190
telemt_desync_suppressed_total 4111
telemt_desync_frames_bucket_total{bucket="1_2"} 1292
telemt_desync_frames_bucket_total{bucket="3_10"} 2466
telemt_desync_frames_bucket_total{bucket="gt_10"} 2543
telemt_pool_swap_total 43
telemt_pool_force_close_total 1285
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 13360
telemt_me_writer_removed_unexpected_total 303
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1207
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12450
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1218
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12075
telemt_me_writer_teardown_success_total{mode="normal"} 13657
telemt_me_writer_teardown_noop_total 13360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.525632
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 266
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 1448967
telemt_user_connections_current{user="hello"} 3903
telemt_user_octets_from_client{user="hello"} 19820840792 (18.46 GB)
telemt_user_octets_to_client{user="hello"} 589568929056 (549.08 GB)
telemt_user_unique_ips_current{user="hello"} 1427
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 40108.3 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1596733
telemt_connections_bad_total 173061
telemt_connections_current 4361
telemt_connections_me_current 4361
telemt_handshake_timeouts_total 69567
telemt_upstream_connect_attempt_total 16006
telemt_upstream_connect_success_total 15996
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 493
telemt_me_reconnect_success_total 261
telemt_me_reader_eof_total 270
telemt_me_idle_close_by_peer_total 270
telemt_me_route_drop_no_conn_total 426925
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1249948
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
telemt_desync_total 5137
telemt_desync_full_logged_total 1835
telemt_desync_suppressed_total 3302
telemt_desync_frames_bucket_total{bucket="1_2"} 1143
telemt_desync_frames_bucket_total{bucket="3_10"} 1958
telemt_desync_frames_bucket_total{bucket="gt_10"} 2036
telemt_pool_swap_total 44
telemt_pool_force_close_total 1243
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 140
telemt_me_draining_writers_reap_progress_total 14574
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1137
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13603
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1225
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13331
telemt_me_writer_teardown_success_total{mode="normal"} 14740
telemt_me_writer_teardown_noop_total 14577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.216440
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 140
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 224
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1247518
telemt_user_connections_current{user="hello"} 4361
telemt_user_octets_from_client{user="hello"} 17091848080 (15.92 GB)
telemt_user_octets_to_client{user="hello"} 544799446752 (507.38 GB)
telemt_user_unique_ips_current{user="hello"} 1550
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 40109.3 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1381873
telemt_connections_bad_total 163417
telemt_connections_current 3306
telemt_connections_me_current 3306
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 62659
telemt_upstream_connect_attempt_total 20862
telemt_upstream_connect_success_total 20634
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 20754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 735
telemt_me_reconnect_success_total 316
telemt_me_reader_eof_total 300
telemt_me_idle_close_by_peer_total 300
telemt_me_route_drop_no_conn_total 392615
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959009
telemt_me_endpoint_quarantine_total 290
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
telemt_desync_total 4371
telemt_desync_full_logged_total 1561
telemt_desync_suppressed_total 2810
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1827
telemt_desync_frames_bucket_total{bucket="gt_10"} 1532
telemt_pool_swap_total 44
telemt_pool_force_close_total 1134
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 14453
telemt_me_writer_removed_unexpected_total 292
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1104
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13655
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1104
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13319
telemt_me_writer_teardown_success_total{mode="normal"} 14759
telemt_me_writer_teardown_noop_total 14454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29213
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.744154
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29213
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 961720
telemt_user_connections_current{user="hello"} 3306
telemt_user_octets_from_client{user="hello"} 16756002185 (15.61 GB)
telemt_user_octets_to_client{user="hello"} 453449996755 (422.31 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1181
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 40073.3 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1324696
telemt_connections_bad_total 151460
telemt_connections_current 3139
telemt_connections_me_current 3139
telemt_handshake_timeouts_total 46577
telemt_upstream_connect_attempt_total 16819
telemt_upstream_connect_success_total 16810
telemt_upstream_connect_attempts_per_request{bucket="1"} 16810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 329
telemt_me_reconnect_success_total 250
telemt_me_reader_eof_total 247
telemt_me_idle_close_by_peer_total 247
telemt_me_route_drop_no_conn_total 288609
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 949853
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
telemt_desync_total 4536
telemt_desync_full_logged_total 1641
telemt_desync_suppressed_total 2895
telemt_desync_frames_bucket_total{bucket="1_2"} 1139
telemt_desync_frames_bucket_total{bucket="3_10"} 1762
telemt_desync_frames_bucket_total{bucket="gt_10"} 1635
telemt_pool_swap_total 44
telemt_pool_force_close_total 1108
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 15238
telemt_me_writer_removed_unexpected_total 226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1014
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14472
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14130
telemt_me_writer_teardown_success_total{mode="normal"} 15486
telemt_me_writer_teardown_noop_total 15241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30727
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.484618
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30727
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 220
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 948186
telemt_user_connections_current{user="hello"} 3139
telemt_user_octets_from_client{user="hello"} 25313785440 (23.58 GB)
telemt_user_octets_to_client{user="hello"} 493465526116 (459.58 GB)
telemt_user_unique_ips_current{user="hello"} 1073
telemt_user_unique_ips_recent_window{user="hello"} 413
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 40112.7 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3213093
telemt_connections_bad_total 196555
telemt_connections_current 5473
telemt_connections_me_current 5473
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 176693
telemt_upstream_connect_attempt_total 42315
telemt_upstream_connect_success_total 40406
telemt_upstream_connect_fail_total 1354
telemt_upstream_connect_attempts_per_request{bucket="1"} 41760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1354
telemt_me_reconnect_attempts_total 1983
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 430
telemt_me_idle_close_by_peer_total 429
telemt_me_route_drop_no_conn_total 3771826
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2616722
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
telemt_desync_total 6136
telemt_desync_full_logged_total 2160
telemt_desync_suppressed_total 3976
telemt_desync_frames_bucket_total{bucket="1_2"} 1388
telemt_desync_frames_bucket_total{bucket="3_10"} 2606
telemt_desync_frames_bucket_total{bucket="gt_10"} 2142
telemt_pool_swap_total 43
telemt_pool_force_close_total 1220
telemt_me_writer_close_signal_drop_total 201
telemt_me_draining_writers_reap_progress_total 13549
telemt_me_writer_removed_unexpected_total 646
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1594
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12565
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12329
telemt_me_writer_teardown_success_total{mode="normal"} 14159
telemt_me_writer_teardown_noop_total 13554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.266495
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 201
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 433
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 2639174
telemt_user_connections_current{user="hello"} 5473
telemt_user_octets_from_client{user="hello"} 37040324774 (34.50 GB)
telemt_user_octets_to_client{user="hello"} 493745404014 (459.84 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1758
telemt_user_unique_ips_recent_window{user="hello"} 976
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 40080.3 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1415139
telemt_connections_bad_total 201910
telemt_connections_current 3070
telemt_connections_me_current 3070
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 28587
telemt_upstream_connect_attempt_total 18612
telemt_upstream_connect_success_total 18447
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 18596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9352
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_reconnect_attempts_total 1640
telemt_me_reconnect_success_total 512
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 353094
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1029032
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 322
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
telemt_desync_total 4405
telemt_desync_full_logged_total 1656
telemt_desync_suppressed_total 2749
telemt_desync_frames_bucket_total{bucket="1_2"} 852
telemt_desync_frames_bucket_total{bucket="3_10"} 1784
telemt_desync_frames_bucket_total{bucket="gt_10"} 1769
telemt_pool_swap_total 42
telemt_pool_force_close_total 1058
telemt_me_writer_close_signal_drop_total 65
telemt_me_draining_writers_reap_progress_total 15339
telemt_me_writer_removed_unexpected_total 507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14553
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14281
telemt_me_writer_teardown_success_total{mode="normal"} 15867
telemt_me_writer_teardown_noop_total 15339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31206
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.104185
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31206
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 65
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 433
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 1026422
telemt_user_connections_current{user="hello"} 3070
telemt_user_octets_from_client{user="hello"} 16979046056 (15.81 GB)
telemt_user_octets_to_client{user="hello"} 495188924814 (461.18 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1176
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 40074.6 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1821321
telemt_connections_bad_total 119942
telemt_connections_current 2762
telemt_connections_me_current 2762
telemt_handshake_timeouts_total 667021
telemt_upstream_connect_attempt_total 17431
telemt_upstream_connect_success_total 17403
telemt_upstream_connect_attempts_per_request{bucket="1"} 17403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 270
telemt_me_reconnect_attempts_total 365
telemt_me_reconnect_success_total 256
telemt_me_reader_eof_total 265
telemt_me_idle_close_by_peer_total 265
telemt_me_route_drop_no_conn_total 319069
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 910571
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
telemt_desync_total 4408
telemt_desync_full_logged_total 1555
telemt_desync_suppressed_total 2853
telemt_desync_frames_bucket_total{bucket="1_2"} 761
telemt_desync_frames_bucket_total{bucket="3_10"} 1808
telemt_desync_frames_bucket_total{bucket="gt_10"} 1839
telemt_pool_swap_total 44
telemt_pool_force_close_total 1036
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 15615
telemt_me_writer_removed_unexpected_total 248
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 941
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14940
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14579
telemt_me_writer_teardown_success_total{mode="normal"} 15881
telemt_me_writer_teardown_noop_total 15615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31496
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.589582
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31496
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 230
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 907419
telemt_user_connections_current{user="hello"} 2762
telemt_user_octets_from_client{user="hello"} 15552938900 (14.48 GB)
telemt_user_octets_to_client{user="hello"} 464104307204 (432.23 GB)
telemt_user_unique_ips_current{user="hello"} 1094
telemt_user_unique_ips_recent_window{user="hello"} 411
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 38066.3 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369674
telemt_connections_bad_total 12578
telemt_connections_current 633
telemt_connections_me_current 633
telemt_handshake_timeouts_total 109367
telemt_upstream_connect_attempt_total 19124
telemt_upstream_connect_success_total 19123
telemt_upstream_connect_attempts_per_request{bucket="1"} 19123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 731
telemt_me_reconnect_success_total 300
telemt_me_reader_eof_total 304
telemt_me_idle_close_by_peer_total 304
telemt_me_route_drop_no_conn_total 84973
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221567
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
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 1389
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 777
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 553
telemt_pool_swap_total 42
telemt_pool_force_close_total 875
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 52
telemt_me_draining_writers_reap_progress_total 17062
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1208
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16143
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 875
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16187
telemt_me_writer_teardown_success_total{mode="normal"} 17351
telemt_me_writer_teardown_noop_total 17062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34413
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.328629
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34413
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 52
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 252
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 221776
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 2852095843 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 94195396169 (87.73 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 40084.6 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1434117
telemt_connections_bad_total 113051
telemt_connections_current 3260
telemt_connections_me_current 3260
telemt_handshake_timeouts_total 37340
telemt_upstream_connect_attempt_total 17916
telemt_upstream_connect_success_total 17835
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 17887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 603
telemt_me_reconnect_success_total 359
telemt_me_reader_eof_total 341
telemt_me_idle_close_by_peer_total 341
telemt_me_route_drop_no_conn_total 325273
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1126213
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
telemt_desync_total 4549
telemt_desync_full_logged_total 1519
telemt_desync_suppressed_total 3030
telemt_desync_frames_bucket_total{bucket="1_2"} 1148
telemt_desync_frames_bucket_total{bucket="3_10"} 1717
telemt_desync_frames_bucket_total{bucket="gt_10"} 1684
telemt_pool_swap_total 44
telemt_pool_force_close_total 1049
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 83
telemt_me_draining_writers_reap_progress_total 16169
telemt_me_writer_removed_unexpected_total 341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1148
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15370
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1039
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15120
telemt_me_writer_teardown_success_total{mode="normal"} 16518
telemt_me_writer_teardown_noop_total 16169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32687
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.669041
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32687
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 83
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 326
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 1121474
telemt_user_connections_current{user="hello"} 3260
telemt_user_octets_from_client{user="hello"} 18528105080 (17.26 GB)
telemt_user_octets_to_client{user="hello"} 516338903224 (480.88 GB)
telemt_user_unique_ips_current{user="hello"} 1180
telemt_user_unique_ips_recent_window{user="hello"} 434
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 40081.3 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1372936
telemt_connections_bad_total 100435
telemt_connections_current 3418
telemt_connections_me_current 3418
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 35584
telemt_upstream_connect_attempt_total 26365
telemt_upstream_connect_success_total 26173
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 2631
telemt_me_reconnect_success_total 472
telemt_me_reader_eof_total 415
telemt_me_idle_close_by_peer_total 415
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 329742
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1095277
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
telemt_desync_total 4395
telemt_desync_full_logged_total 1393
telemt_desync_suppressed_total 3002
telemt_desync_frames_bucket_total{bucket="1_2"} 1259
telemt_desync_frames_bucket_total{bucket="3_10"} 1594
telemt_desync_frames_bucket_total{bucket="gt_10"} 1542
telemt_pool_swap_total 44
telemt_pool_force_close_total 1016
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 15290
telemt_me_writer_removed_unexpected_total 427
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1342
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14397
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 995
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14274
telemt_me_writer_teardown_success_total{mode="normal"} 15739
telemt_me_writer_teardown_noop_total 15290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31029
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.002267
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31029
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 123
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1099801
telemt_user_connections_current{user="hello"} 3418
telemt_user_octets_from_client{user="hello"} 14407130231 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 487230386963 (453.77 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1228
telemt_user_unique_ips_recent_window{user="hello"} 462
```