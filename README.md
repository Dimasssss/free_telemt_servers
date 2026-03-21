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

# Server Metrics 2026-03-21 09:36:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 46822.5 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1313924
telemt_connections_bad_total 67641
telemt_connections_current 1575
telemt_connections_me_current 1575
telemt_handshake_timeouts_total 53517
telemt_upstream_connect_attempt_total 18336
telemt_upstream_connect_success_total 18255
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 18312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11645
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 767
telemt_me_reconnect_success_total 324
telemt_me_reader_eof_total 331
telemt_me_idle_close_by_peer_total 331
telemt_me_route_drop_no_conn_total 722484
telemt_me_route_drop_channel_closed_total 224
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 991085
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 329
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 373
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
telemt_desync_total 4190
telemt_desync_full_logged_total 1435
telemt_desync_suppressed_total 2755
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1642
telemt_desync_frames_bucket_total{bucket="gt_10"} 1667
telemt_pool_swap_total 51
telemt_pool_force_close_total 1431
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 16439
telemt_me_writer_removed_unexpected_total 310
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1267
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15383
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1409
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15008
telemt_me_writer_teardown_success_total{mode="normal"} 16650
telemt_me_writer_teardown_noop_total 16440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33090
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 80.685590
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33090
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 284
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 990285
telemt_user_connections_current{user="hello"} 1575
telemt_user_octets_from_client{user="hello"} 14121293507 (13.15 GB)
telemt_user_octets_to_client{user="hello"} 279306748075 (260.12 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 558
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 46824.1 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3298312
telemt_connections_bad_total 364975
telemt_connections_current 4949
telemt_connections_me_current 4949
telemt_handshake_timeouts_total 98165
telemt_upstream_connect_attempt_total 16820
telemt_upstream_connect_success_total 16744
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 16796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 983
telemt_me_reconnect_success_total 377
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 371
telemt_me_route_drop_no_conn_total 1320618
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2191714
telemt_me_endpoint_quarantine_total 296
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 361
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
telemt_me_writers_warm_current 1
telemt_desync_total 9507
telemt_desync_full_logged_total 3201
telemt_desync_suppressed_total 6306
telemt_desync_frames_bucket_total{bucket="1_2"} 1938
telemt_desync_frames_bucket_total{bucket="3_10"} 3749
telemt_desync_frames_bucket_total{bucket="gt_10"} 3820
telemt_pool_swap_total 50
telemt_pool_force_close_total 1516
telemt_me_writer_close_signal_drop_total 178
telemt_me_draining_writers_reap_progress_total 15042
telemt_me_writer_removed_unexpected_total 348
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14005
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1426
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 90
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13526
telemt_me_writer_teardown_success_total{mode="normal"} 15387
telemt_me_writer_teardown_noop_total 15042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30429
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.000304
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30429
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 178
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2187528
telemt_user_connections_current{user="hello"} 4949
telemt_user_octets_from_client{user="hello"} 31136557848 (29.00 GB)
telemt_user_octets_to_client{user="hello"} 765584069876 (713.01 GB)
telemt_user_unique_ips_current{user="hello"} 1810
telemt_user_unique_ips_recent_window{user="hello"} 742
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 46820.3 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2413019
telemt_connections_bad_total 290279
telemt_connections_current 4188
telemt_connections_me_current 4188
telemt_handshake_timeouts_total 89834
telemt_upstream_connect_attempt_total 18265
telemt_upstream_connect_success_total 18254
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 612
telemt_me_reconnect_success_total 344
telemt_me_reader_eof_total 357
telemt_me_idle_close_by_peer_total 357
telemt_me_route_drop_no_conn_total 964947
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1879482
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 364
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
telemt_me_writers_warm_current 1
telemt_desync_total 7968
telemt_desync_full_logged_total 2787
telemt_desync_suppressed_total 5181
telemt_desync_frames_bucket_total{bucket="1_2"} 1677
telemt_desync_frames_bucket_total{bucket="3_10"} 3120
telemt_desync_frames_bucket_total{bucket="gt_10"} 3171
telemt_pool_swap_total 50
telemt_pool_force_close_total 1479
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 195
telemt_me_draining_writers_reap_progress_total 16609
telemt_me_writer_removed_unexpected_total 337
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15482
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1398
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15130
telemt_me_writer_teardown_success_total{mode="normal"} 16843
telemt_me_writer_teardown_noop_total 16619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33462
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 34.255517
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33462
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 195
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 307
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1876421
telemt_user_connections_current{user="hello"} 4188
telemt_user_octets_from_client{user="hello"} 29472966032 (27.45 GB)
telemt_user_octets_to_client{user="hello"} 720216821432 (670.75 GB)
telemt_user_unique_ips_current{user="hello"} 1585
telemt_user_unique_ips_recent_window{user="hello"} 602
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 46821.7 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1978286
telemt_connections_bad_total 230075
telemt_connections_current 3351
telemt_connections_me_current 3351
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 85146
telemt_upstream_connect_attempt_total 23200
telemt_upstream_connect_success_total 22965
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 23090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 388
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 990
telemt_me_reconnect_success_total 435
telemt_me_reader_eof_total 402
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 565092
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1377467
telemt_me_endpoint_quarantine_total 329
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 367
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
telemt_me_writers_warm_current 1
telemt_desync_total 6437
telemt_desync_full_logged_total 2205
telemt_desync_suppressed_total 4232
telemt_desync_frames_bucket_total{bucket="1_2"} 1580
telemt_desync_frames_bucket_total{bucket="3_10"} 2565
telemt_desync_frames_bucket_total{bucket="gt_10"} 2292
telemt_pool_swap_total 50
telemt_pool_force_close_total 1363
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 16494
telemt_me_writer_removed_unexpected_total 395
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1322
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15581
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1282
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15131
telemt_me_writer_teardown_success_total{mode="normal"} 16903
telemt_me_writer_teardown_noop_total 16495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33398
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.800325
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33398
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 365
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1379531
telemt_user_connections_current{user="hello"} 3351
telemt_user_octets_from_client{user="hello"} 28091085669 (26.16 GB)
telemt_user_octets_to_client{user="hello"} 665357162003 (619.66 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1321
telemt_user_unique_ips_recent_window{user="hello"} 449
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 46785.9 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1909492
telemt_connections_bad_total 219702
telemt_connections_current 3264
telemt_connections_me_current 3264
telemt_handshake_timeouts_total 62107
telemt_upstream_connect_attempt_total 19307
telemt_upstream_connect_success_total 19273
telemt_upstream_connect_attempts_per_request{bucket="1"} 19273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 579
telemt_me_reconnect_success_total 400
telemt_me_reader_eof_total 360
telemt_me_idle_close_by_peer_total 360
telemt_me_route_drop_no_conn_total 530931
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1376540
telemt_me_endpoint_quarantine_total 359
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 358
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
telemt_me_writers_active_current 67
telemt_desync_total 6346
telemt_desync_full_logged_total 2225
telemt_desync_suppressed_total 4121
telemt_desync_frames_bucket_total{bucket="1_2"} 1661
telemt_desync_frames_bucket_total{bucket="3_10"} 2452
telemt_desync_frames_bucket_total{bucket="gt_10"} 2233
telemt_pool_swap_total 50
telemt_pool_force_close_total 1323
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 17366
telemt_me_writer_removed_unexpected_total 335
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1273
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16457
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16043
telemt_me_writer_teardown_success_total{mode="normal"} 17730
telemt_me_writer_teardown_noop_total 17369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35099
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.909883
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35099
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 353
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1374203
telemt_user_connections_current{user="hello"} 3264
telemt_user_octets_from_client{user="hello"} 32446102740 (30.22 GB)
telemt_user_octets_to_client{user="hello"} 681012555624 (634.24 GB)
telemt_user_unique_ips_current{user="hello"} 1272
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 46825.1 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5591416
telemt_connections_bad_total 288630
telemt_connections_current 5839
telemt_connections_me_current 5839
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 225298
telemt_upstream_connect_attempt_total 45188
telemt_upstream_connect_success_total 43174
telemt_upstream_connect_fail_total 1380
telemt_upstream_connect_attempts_per_request{bucket="1"} 44554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1380
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2562
telemt_me_reconnect_success_total 931
telemt_me_reader_eof_total 671
telemt_me_idle_close_by_peer_total 670
telemt_me_route_drop_no_conn_total 9241968
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4731476
telemt_me_endpoint_quarantine_total 368
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 87
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 87
telemt_me_single_endpoint_shadow_rotate_total 367
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 3
telemt_desync_total 9656
telemt_desync_full_logged_total 3182
telemt_desync_suppressed_total 6474
telemt_desync_frames_bucket_total{bucket="1_2"} 2124
telemt_desync_frames_bucket_total{bucket="3_10"} 4165
telemt_desync_frames_bucket_total{bucket="gt_10"} 3367
telemt_pool_swap_total 47
telemt_pool_force_close_total 1458
telemt_me_writer_close_signal_drop_total 261
telemt_me_draining_writers_reap_progress_total 15948
telemt_me_writer_removed_unexpected_total 895
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1961
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14809
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14490
telemt_me_writer_teardown_success_total{mode="normal"} 16770
telemt_me_writer_teardown_noop_total 15954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32724
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.642731
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32724
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 261
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 660
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 4753298
telemt_user_connections_current{user="hello"} 5839
telemt_user_octets_from_client{user="hello"} 46188341494 (43.02 GB)
telemt_user_octets_to_client{user="hello"} 566791103966 (527.87 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1954
telemt_user_unique_ips_recent_window{user="hello"} 1068
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 46792.8 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1954082
telemt_connections_bad_total 252119
telemt_connections_current 3415
telemt_connections_me_current 3415
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 38084
telemt_upstream_connect_attempt_total 20695
telemt_upstream_connect_success_total 20490
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 20676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_reconnect_attempts_total 1917
telemt_me_reconnect_success_total 589
telemt_me_reader_eof_total 597
telemt_me_idle_close_by_peer_total 597
telemt_me_route_drop_no_conn_total 580401
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1461881
telemt_me_endpoint_quarantine_total 288
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 366
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
telemt_me_writers_active_current 44
telemt_desync_total 6637
telemt_desync_full_logged_total 2424
telemt_desync_suppressed_total 4213
telemt_desync_frames_bucket_total{bucket="1_2"} 1299
telemt_desync_frames_bucket_total{bucket="3_10"} 2687
telemt_desync_frames_bucket_total{bucket="gt_10"} 2651
telemt_pool_swap_total 49
telemt_pool_force_close_total 1283
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 17153
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1515
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16235
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15870
telemt_me_writer_teardown_success_total{mode="normal"} 17750
telemt_me_writer_teardown_noop_total 17153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34903
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.576499
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34903
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 492
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1458163
telemt_user_connections_current{user="hello"} 3415
telemt_user_octets_from_client{user="hello"} 26795944636 (24.96 GB)
telemt_user_octets_to_client{user="hello"} 674409873130 (628.09 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1381
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 46787.2 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2698974
telemt_connections_bad_total 155502
telemt_connections_current 3137
telemt_connections_me_current 3137
telemt_handshake_timeouts_total 1089230
telemt_upstream_connect_attempt_total 19501
telemt_upstream_connect_success_total 19467
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 515
telemt_me_reconnect_success_total 295
telemt_me_reader_eof_total 296
telemt_me_idle_close_by_peer_total 296
telemt_me_route_drop_no_conn_total 506111
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1296761
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_shadow_rotate_total 369
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
telemt_desync_total 6459
telemt_desync_full_logged_total 2272
telemt_desync_suppressed_total 4187
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 2600
telemt_desync_frames_bucket_total{bucket="gt_10"} 2717
telemt_pool_swap_total 51
telemt_pool_force_close_total 1239
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 17486
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1102
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16689
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1222
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16247
telemt_me_writer_teardown_success_total{mode="normal"} 17791
telemt_me_writer_teardown_noop_total 17486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35277
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.869486
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35277
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 262
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1292596
telemt_user_connections_current{user="hello"} 3137
telemt_user_octets_from_client{user="hello"} 22751922796 (21.19 GB)
telemt_user_octets_to_client{user="hello"} 642828928340 (598.68 GB)
telemt_user_unique_ips_current{user="hello"} 1328
telemt_user_unique_ips_recent_window{user="hello"} 465
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 44778.6 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578065
telemt_connections_bad_total 20105
telemt_connections_current 690
telemt_connections_me_current 690
telemt_handshake_timeouts_total 214533
telemt_upstream_connect_attempt_total 21930
telemt_upstream_connect_success_total 21928
telemt_upstream_connect_attempts_per_request{bucket="1"} 21928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 916
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 361
telemt_me_idle_close_by_peer_total 361
telemt_me_route_drop_no_conn_total 121412
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298597
telemt_me_endpoint_quarantine_total 432
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 382
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 47
telemt_desync_total 1899
telemt_desync_full_logged_total 764
telemt_desync_suppressed_total 1135
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 793
telemt_pool_swap_total 49
telemt_pool_force_close_total 1060
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 19565
telemt_me_writer_removed_unexpected_total 342
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1412
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18499
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1058
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18505
telemt_me_writer_teardown_success_total{mode="normal"} 19911
telemt_me_writer_teardown_noop_total 19565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39476
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.814926
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39476
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 298
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 298755
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 4404251559 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 119559557153 (111.35 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 46797.0 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2017439
telemt_connections_bad_total 175409
telemt_connections_current 4013
telemt_connections_me_current 4013
telemt_handshake_timeouts_total 51199
telemt_upstream_connect_attempt_total 20205
telemt_upstream_connect_success_total 20118
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 20175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 743
telemt_me_reconnect_success_total 433
telemt_me_reader_eof_total 401
telemt_me_idle_close_by_peer_total 401
telemt_me_route_drop_no_conn_total 499768
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1595527
telemt_me_endpoint_quarantine_total 367
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 368
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
telemt_desync_total 6336
telemt_desync_full_logged_total 2117
telemt_desync_suppressed_total 4219
telemt_desync_frames_bucket_total{bucket="1_2"} 1537
telemt_desync_frames_bucket_total{bucket="3_10"} 2367
telemt_desync_frames_bucket_total{bucket="gt_10"} 2432
telemt_pool_swap_total 51
telemt_pool_force_close_total 1256
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 116
telemt_me_draining_writers_reap_progress_total 18202
telemt_me_writer_removed_unexpected_total 400
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1343
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17268
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1233
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16946
telemt_me_writer_teardown_success_total{mode="normal"} 18611
telemt_me_writer_teardown_noop_total 18202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36813
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.371498
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36813
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 116
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 389
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1590065
telemt_user_connections_current{user="hello"} 4013
telemt_user_octets_from_client{user="hello"} 36066452364 (33.59 GB)
telemt_user_octets_to_client{user="hello"} 741704571560 (690.77 GB)
telemt_user_unique_ips_current{user="hello"} 1520
telemt_user_unique_ips_recent_window{user="hello"} 550
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 46793.7 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1902439
telemt_connections_bad_total 156489
telemt_connections_current 3397
telemt_connections_me_current 3397
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 46615
telemt_upstream_connect_attempt_total 28869
telemt_upstream_connect_success_total 28660
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 28826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 2940
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 522
telemt_me_idle_close_by_peer_total 522
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 514118
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1526508
telemt_me_endpoint_quarantine_total 419
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 366
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
telemt_me_writers_active_current 46
telemt_desync_total 5843
telemt_desync_full_logged_total 1953
telemt_desync_suppressed_total 3890
telemt_desync_frames_bucket_total{bucket="1_2"} 1609
telemt_desync_frames_bucket_total{bucket="3_10"} 2153
telemt_desync_frames_bucket_total{bucket="gt_10"} 2081
telemt_pool_swap_total 50
telemt_pool_force_close_total 1229
telemt_me_writer_close_signal_drop_total 106
telemt_me_draining_writers_reap_progress_total 17493
telemt_me_writer_removed_unexpected_total 531
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1592
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16458
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1153
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16264
telemt_me_writer_teardown_success_total{mode="normal"} 18050
telemt_me_writer_teardown_noop_total 17494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35544
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.350561
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35544
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 106
telemt_me_refill_failed_total 133
telemt_me_writer_restored_same_endpoint_total 462
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1530402
telemt_user_connections_current{user="hello"} 3397
telemt_user_octets_from_client{user="hello"} 24803554779 (23.10 GB)
telemt_user_octets_to_client{user="hello"} 680317198251 (633.59 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1384
telemt_user_unique_ips_recent_window{user="hello"} 502
```