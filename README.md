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

# Server Metrics 2026-03-21 07:54:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 40720.5 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979100
telemt_connections_bad_total 51095
telemt_connections_current 1444
telemt_connections_me_current 1444
telemt_handshake_timeouts_total 45143
telemt_upstream_connect_attempt_total 16155
telemt_upstream_connect_success_total 16083
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 16132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 531
telemt_me_reconnect_success_total 260
telemt_me_reader_eof_total 277
telemt_me_idle_close_by_peer_total 277
telemt_me_route_drop_no_conn_total 305799
telemt_me_route_drop_channel_closed_total 115
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707557
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 284
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 333
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
telemt_desync_total 3104
telemt_desync_full_logged_total 1113
telemt_desync_suppressed_total 1991
telemt_desync_frames_bucket_total{bucket="1_2"} 649
telemt_desync_frames_bucket_total{bucket="3_10"} 1192
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 45
telemt_pool_force_close_total 1250
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 14587
telemt_me_writer_removed_unexpected_total 259
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1099
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13693
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13337
telemt_me_writer_teardown_success_total{mode="normal"} 14792
telemt_me_writer_teardown_noop_total 14588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29380
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.186724
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29380
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 236
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 706770
telemt_user_connections_current{user="hello"} 1444
telemt_user_octets_from_client{user="hello"} 9454190796 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 220528992264 (205.38 GB)
telemt_user_unique_ips_current{user="hello"} 536
telemt_user_unique_ips_recent_window{user="hello"} 384
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 40721.7 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2391498
telemt_connections_bad_total 262739
telemt_connections_current 4015
telemt_connections_me_current 4015
telemt_handshake_timeouts_total 70741
telemt_upstream_connect_attempt_total 15135
telemt_upstream_connect_success_total 15063
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 15111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 896
telemt_me_reconnect_success_total 340
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 333
telemt_me_route_drop_no_conn_total 549147
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1505112
telemt_me_endpoint_quarantine_total 274
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 324
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
telemt_desync_total 6555
telemt_desync_full_logged_total 2267
telemt_desync_suppressed_total 4288
telemt_desync_frames_bucket_total{bucket="1_2"} 1343
telemt_desync_frames_bucket_total{bucket="3_10"} 2564
telemt_desync_frames_bucket_total{bucket="gt_10"} 2648
telemt_pool_swap_total 44
telemt_pool_force_close_total 1320
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 13555
telemt_me_writer_removed_unexpected_total 312
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1235
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12627
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1247
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12235
telemt_me_writer_teardown_success_total{mode="normal"} 13862
telemt_me_writer_teardown_noop_total 13555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27417
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.860884
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27417
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 271
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 1501801
telemt_user_connections_current{user="hello"} 4015
telemt_user_octets_from_client{user="hello"} 20535105524 (19.12 GB)
telemt_user_octets_to_client{user="hello"} 604279761476 (562.78 GB)
telemt_user_unique_ips_current{user="hello"} 1393
telemt_user_unique_ips_recent_window{user="hello"} 1081
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 40718.0 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1675808
telemt_connections_bad_total 191395
telemt_connections_current 3992
telemt_connections_me_current 3992
telemt_handshake_timeouts_total 70733
telemt_upstream_connect_attempt_total 16196
telemt_upstream_connect_success_total 16186
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 494
telemt_me_reconnect_success_total 262
telemt_me_reader_eof_total 271
telemt_me_idle_close_by_peer_total 271
telemt_me_route_drop_no_conn_total 449439
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1298892
telemt_me_endpoint_quarantine_total 286
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 327
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
telemt_desync_total 5345
telemt_desync_full_logged_total 1908
telemt_desync_suppressed_total 3437
telemt_desync_frames_bucket_total{bucket="1_2"} 1191
telemt_desync_frames_bucket_total{bucket="3_10"} 2032
telemt_desync_frames_bucket_total{bucket="gt_10"} 2122
telemt_pool_swap_total 45
telemt_pool_force_close_total 1277
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 14761
telemt_me_writer_removed_unexpected_total 253
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1158
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13770
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1254
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13484
telemt_me_writer_teardown_success_total{mode="normal"} 14928
telemt_me_writer_teardown_noop_total 14765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29693
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.062271
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29693
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 225
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1296394
telemt_user_connections_current{user="hello"} 3992
telemt_user_octets_from_client{user="hello"} 18156436500 (16.91 GB)
telemt_user_octets_to_client{user="hello"} 562132676332 (523.53 GB)
telemt_user_unique_ips_current{user="hello"} 1360
telemt_user_unique_ips_recent_window{user="hello"} 1190
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 40719.3 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1432804
telemt_connections_bad_total 168209
telemt_connections_current 2466
telemt_connections_me_current 2466
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 63956
telemt_upstream_connect_attempt_total 21075
telemt_upstream_connect_success_total 20847
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 20967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9229
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 738
telemt_me_reconnect_success_total 318
telemt_me_reader_eof_total 302
telemt_me_idle_close_by_peer_total 302
telemt_me_route_drop_no_conn_total 408454
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 992563
telemt_me_endpoint_quarantine_total 295
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 329
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
telemt_desync_total 4553
telemt_desync_full_logged_total 1618
telemt_desync_suppressed_total 2935
telemt_desync_frames_bucket_total{bucket="1_2"} 1058
telemt_desync_frames_bucket_total{bucket="3_10"} 1889
telemt_desync_frames_bucket_total{bucket="gt_10"} 1606
telemt_pool_swap_total 45
telemt_pool_force_close_total 1166
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 14647
telemt_me_writer_removed_unexpected_total 294
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1117
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13838
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1135
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13481
telemt_me_writer_teardown_success_total{mode="normal"} 14955
telemt_me_writer_teardown_noop_total 14648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29603
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.615171
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29603
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 267
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 995148
telemt_user_connections_current{user="hello"} 2466
telemt_user_octets_from_client{user="hello"} 17296133005 (16.11 GB)
telemt_user_octets_to_client{user="hello"} 473148776195 (440.65 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 867
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 40683.2 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1370229
telemt_connections_bad_total 155030
telemt_connections_current 3587
telemt_connections_me_current 3587
telemt_handshake_timeouts_total 47842
telemt_upstream_connect_attempt_total 17024
telemt_upstream_connect_success_total 17015
telemt_upstream_connect_attempts_per_request{bucket="1"} 17015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 339
telemt_me_reconnect_success_total 260
telemt_me_reader_eof_total 257
telemt_me_idle_close_by_peer_total 257
telemt_me_route_drop_no_conn_total 301709
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 985249
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_shadow_rotate_total 321
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
telemt_desync_total 4740
telemt_desync_full_logged_total 1699
telemt_desync_suppressed_total 3041
telemt_desync_frames_bucket_total{bucket="1_2"} 1202
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 1693
telemt_pool_swap_total 45
telemt_pool_force_close_total 1109
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 15387
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1033
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14613
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14278
telemt_me_writer_teardown_success_total{mode="normal"} 15646
telemt_me_writer_teardown_noop_total 15390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31036
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.488764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31036
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 230
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 983561
telemt_user_connections_current{user="hello"} 3587
telemt_user_octets_from_client{user="hello"} 25925586252 (24.15 GB)
telemt_user_octets_to_client{user="hello"} 513630609856 (478.36 GB)
telemt_user_unique_ips_current{user="hello"} 1321
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 40722.5 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3447743
telemt_connections_bad_total 203854
telemt_connections_current 5499
telemt_connections_me_current 5499
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 180481
telemt_upstream_connect_attempt_total 42592
telemt_upstream_connect_success_total 40664
telemt_upstream_connect_fail_total 1360
telemt_upstream_connect_attempts_per_request{bucket="1"} 42024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1360
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2042
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 471
telemt_me_idle_close_by_peer_total 470
telemt_me_route_drop_no_conn_total 4285312
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2827537
telemt_me_endpoint_quarantine_total 321
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 326
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
telemt_me_writers_active_current 86
telemt_me_writers_warm_current 4
telemt_desync_total 6481
telemt_desync_full_logged_total 2247
telemt_desync_suppressed_total 4234
telemt_desync_frames_bucket_total{bucket="1_2"} 1446
telemt_desync_frames_bucket_total{bucket="3_10"} 2779
telemt_desync_frames_bucket_total{bucket="gt_10"} 2256
telemt_pool_swap_total 43
telemt_pool_force_close_total 1220
telemt_me_writer_close_signal_drop_total 204
telemt_me_draining_writers_reap_progress_total 13715
telemt_me_writer_removed_unexpected_total 689
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1642
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12726
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12495
telemt_me_writer_teardown_success_total{mode="normal"} 14368
telemt_me_writer_teardown_noop_total 13720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28088
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.327561
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28088
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 204
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 471
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 2849972
telemt_user_connections_current{user="hello"} 5499
telemt_user_octets_from_client{user="hello"} 37995628258 (35.39 GB)
telemt_user_octets_to_client{user="hello"} 500686579966 (466.30 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1798
telemt_user_unique_ips_recent_window{user="hello"} 909
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 40690.2 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1460978
telemt_connections_bad_total 207033
telemt_connections_current 3095
telemt_connections_me_current 3095
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 29267
telemt_upstream_connect_attempt_total 18822
telemt_upstream_connect_success_total 18652
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 18805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_reconnect_attempts_total 1649
telemt_me_reconnect_success_total 523
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_route_drop_no_conn_total 369166
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1066386
telemt_me_endpoint_quarantine_total 257
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 328
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
telemt_desync_total 4578
telemt_desync_full_logged_total 1728
telemt_desync_suppressed_total 2850
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1852
telemt_desync_frames_bucket_total{bucket="gt_10"} 1845
telemt_pool_swap_total 43
telemt_pool_force_close_total 1061
telemt_me_writer_close_signal_drop_total 65
telemt_me_draining_writers_reap_progress_total 15491
telemt_me_writer_removed_unexpected_total 515
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1335
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14692
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14430
telemt_me_writer_teardown_success_total{mode="normal"} 16027
telemt_me_writer_teardown_noop_total 15491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.109345
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 65
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 441
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 1063700
telemt_user_connections_current{user="hello"} 3095
telemt_user_octets_from_client{user="hello"} 17761269644 (16.54 GB)
telemt_user_octets_to_client{user="hello"} 511733740062 (476.59 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1169
telemt_user_unique_ips_recent_window{user="hello"} 482
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 40684.6 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1895902
telemt_connections_bad_total 126408
telemt_connections_current 2775
telemt_connections_me_current 2775
telemt_handshake_timeouts_total 698661
telemt_upstream_connect_attempt_total 17635
telemt_upstream_connect_success_total 17607
telemt_upstream_connect_attempts_per_request{bucket="1"} 17607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 271
telemt_me_reconnect_attempts_total 384
telemt_me_reconnect_success_total 261
telemt_me_reader_eof_total 267
telemt_me_idle_close_by_peer_total 267
telemt_me_route_drop_no_conn_total 332761
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943090
telemt_me_endpoint_quarantine_total 340
telemt_me_single_endpoint_shadow_rotate_total 329
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
telemt_me_writers_active_current 43
telemt_desync_total 4580
telemt_desync_full_logged_total 1629
telemt_desync_suppressed_total 2951
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1872
telemt_desync_frames_bucket_total{bucket="gt_10"} 1914
telemt_pool_swap_total 45
telemt_pool_force_close_total 1040
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 15784
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 955
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15099
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14744
telemt_me_writer_teardown_success_total{mode="normal"} 16054
telemt_me_writer_teardown_noop_total 15784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31838
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.620186
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31838
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 233
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 939834
telemt_user_connections_current{user="hello"} 2775
telemt_user_octets_from_client{user="hello"} 16087184556 (14.98 GB)
telemt_user_octets_to_client{user="hello"} 481221730200 (448.17 GB)
telemt_user_unique_ips_current{user="hello"} 1160
telemt_user_unique_ips_recent_window{user="hello"} 403
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 38676.1 (10h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387335
telemt_connections_bad_total 12923
telemt_connections_current 606
telemt_connections_me_current 606
telemt_handshake_timeouts_total 118944
telemt_upstream_connect_attempt_total 19338
telemt_upstream_connect_success_total 19337
telemt_upstream_connect_attempts_per_request{bucket="1"} 19337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 732
telemt_me_reconnect_success_total 302
telemt_me_reader_eof_total 305
telemt_me_idle_close_by_peer_total 305
telemt_me_route_drop_no_conn_total 88124
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228677
telemt_me_endpoint_quarantine_total 377
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 333
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
telemt_me_writers_active_current 46
telemt_desync_total 1417
telemt_desync_full_logged_total 620
telemt_desync_suppressed_total 797
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 42
telemt_pool_force_close_total 875
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 52
telemt_me_draining_writers_reap_progress_total 17256
telemt_me_writer_removed_unexpected_total 287
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1210
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16336
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 875
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16381
telemt_me_writer_teardown_success_total{mode="normal"} 17546
telemt_me_writer_teardown_noop_total 17256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34802
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.357571
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34802
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 52
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 228890
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 2972007879 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 96411769765 (89.79 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 40694.5 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1481682
telemt_connections_bad_total 116719
telemt_connections_current 3610
telemt_connections_me_current 3610
telemt_handshake_timeouts_total 38458
telemt_upstream_connect_attempt_total 18171
telemt_upstream_connect_success_total 18088
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 18142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 617
telemt_me_reconnect_success_total 376
telemt_me_reader_eof_total 350
telemt_me_idle_close_by_peer_total 350
telemt_me_route_drop_no_conn_total 338558
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1163859
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 330
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
telemt_me_writers_active_current 47
telemt_desync_total 4700
telemt_desync_full_logged_total 1572
telemt_desync_suppressed_total 3128
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 1765
telemt_desync_frames_bucket_total{bucket="gt_10"} 1747
telemt_pool_swap_total 45
telemt_pool_force_close_total 1052
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 16356
telemt_me_writer_removed_unexpected_total 350
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1168
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15546
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1039
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15304
telemt_me_writer_teardown_success_total{mode="normal"} 16714
telemt_me_writer_teardown_noop_total 16356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.702081
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1159090
telemt_user_connections_current{user="hello"} 3610
telemt_user_octets_from_client{user="hello"} 19121655128 (17.81 GB)
telemt_user_octets_to_client{user="hello"} 535493830424 (498.72 GB)
telemt_user_unique_ips_current{user="hello"} 1260
telemt_user_unique_ips_recent_window{user="hello"} 509
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 40691.1 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1420346
telemt_connections_bad_total 104875
telemt_connections_current 3364
telemt_connections_me_current 3364
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 36815
telemt_upstream_connect_attempt_total 26595
telemt_upstream_connect_success_total 26403
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 2661
telemt_me_reconnect_success_total 493
telemt_me_reader_eof_total 426
telemt_me_idle_close_by_peer_total 426
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 343528
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1132862
telemt_me_endpoint_quarantine_total 390
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 325
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
telemt_me_writers_active_current 52
telemt_desync_total 4537
telemt_desync_full_logged_total 1448
telemt_desync_suppressed_total 3089
telemt_desync_frames_bucket_total{bucket="1_2"} 1281
telemt_desync_frames_bucket_total{bucket="3_10"} 1662
telemt_desync_frames_bucket_total{bucket="gt_10"} 1594
telemt_pool_swap_total 45
telemt_pool_force_close_total 1022
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 15452
telemt_me_writer_removed_unexpected_total 437
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1367
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14545
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 995
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14430
telemt_me_writer_teardown_success_total{mode="normal"} 15912
telemt_me_writer_teardown_noop_total 15452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31364
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.035322
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31364
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 123
telemt_me_writer_restored_same_endpoint_total 369
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 41
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 1137362
telemt_user_connections_current{user="hello"} 3364
telemt_user_octets_from_client{user="hello"} 14844885783 (13.83 GB)
telemt_user_octets_to_client{user="hello"} 505509537555 (470.79 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1312
telemt_user_unique_ips_recent_window{user="hello"} 473
```