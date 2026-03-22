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

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
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
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
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

# Server Metrics 2026-03-22 14:06:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 61199.5 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1949000
telemt_connections_bad_total 83687
telemt_connections_current 1916
telemt_connections_me_current 1916
telemt_handshake_timeouts_total 80570
telemt_upstream_connect_attempt_total 22871
telemt_upstream_connect_success_total 22870
telemt_upstream_connect_attempts_per_request{bucket="1"} 22870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 917
telemt_me_reconnect_success_total 371
telemt_me_reader_eof_total 376
telemt_me_idle_close_by_peer_total 376
telemt_me_route_drop_no_conn_total 1414464
telemt_me_route_drop_channel_closed_total 626
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1661408
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 418
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 481
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
telemt_desync_total 8988
telemt_desync_full_logged_total 2769
telemt_desync_suppressed_total 6219
telemt_desync_frames_bucket_total{bucket="1_2"} 2497
telemt_desync_frames_bucket_total{bucket="3_10"} 3377
telemt_desync_frames_bucket_total{bucket="gt_10"} 3114
telemt_pool_swap_total 67
telemt_pool_force_close_total 2004
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 332
telemt_me_draining_writers_reap_progress_total 20844
telemt_me_writer_removed_unexpected_total 366
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1484
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1968
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18840
telemt_me_writer_teardown_success_total{mode="normal"} 21070
telemt_me_writer_teardown_noop_total 20848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41918
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 160.565558
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41918
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 332
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 329
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1658462
telemt_user_connections_current{user="hello"} 1916
telemt_user_octets_from_client{user="hello"} 25842061356 (24.07 GB)
telemt_user_octets_to_client{user="hello"} 479826850164 (446.87 GB)
telemt_user_unique_ips_current{user="hello"} 729
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 74565.7 (20h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3133626
telemt_connections_bad_total 291117
telemt_connections_current 3348
telemt_connections_me_current 3348
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 74667
telemt_upstream_connect_attempt_total 47854
telemt_upstream_connect_success_total 47284
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 47789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3745
telemt_me_reconnect_success_total 1721
telemt_me_reader_eof_total 1594
telemt_me_idle_close_by_peer_total 1594
telemt_me_route_drop_no_conn_total 2938657
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2468534
telemt_me_endpoint_quarantine_total 614
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 582
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 127
telemt_desync_total 9791
telemt_desync_full_logged_total 5459
telemt_desync_suppressed_total 4332
telemt_desync_frames_bucket_total{bucket="1_2"} 2310
telemt_desync_frames_bucket_total{bucket="3_10"} 3857
telemt_desync_frames_bucket_total{bucket="gt_10"} 3624
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 29530
telemt_me_writer_removed_unexpected_total 1552
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3261
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27822
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27460
telemt_me_writer_teardown_success_total{mode="normal"} 31083
telemt_me_writer_teardown_noop_total 29530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60613
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.879778
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60613
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 2480100
telemt_user_connections_current{user="hello"} 3348
telemt_user_octets_from_client{user="hello"} 29860435947 (27.81 GB)
telemt_user_octets_to_client{user="hello"} 567734354458 (528.74 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1745
telemt_user_unique_ips_recent_window{user="hello"} 790
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 149426.6 (41h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14138864
telemt_connections_bad_total 1246973
telemt_connections_current 6079
telemt_connections_me_current 6079
telemt_handshake_timeouts_total 354954
telemt_upstream_connect_attempt_total 54118
telemt_upstream_connect_success_total 54036
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 54044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2459
telemt_me_reconnect_success_total 1283
telemt_me_reader_eof_total 1226
telemt_me_idle_close_by_peer_total 1225
telemt_me_route_drop_no_conn_total 12422133
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11339809
telemt_me_endpoint_quarantine_total 951
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1111
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_warm_current 5
telemt_desync_total 46068
telemt_desync_full_logged_total 14576
telemt_desync_suppressed_total 31492
telemt_desync_frames_bucket_total{bucket="1_2"} 10431
telemt_desync_frames_bucket_total{bucket="3_10"} 18029
telemt_desync_frames_bucket_total{bucket="gt_10"} 17608
telemt_pool_swap_total 160
telemt_pool_force_close_total 5473
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 868
telemt_me_draining_writers_reap_progress_total 49348
telemt_me_writer_removed_unexpected_total 1182
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4279
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5037
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 436
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43875
telemt_me_writer_teardown_success_total{mode="normal"} 49865
telemt_me_writer_teardown_noop_total 49397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99262
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 254.383995
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99262
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 868
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1105
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 11327524
telemt_user_connections_current{user="hello"} 6079
telemt_user_octets_from_client{user="hello"} 161968729800 (150.85 GB)
telemt_user_octets_to_client{user="hello"} 3000213648524 (2.73 TB)
telemt_user_unique_ips_current{user="hello"} 2378
telemt_user_unique_ips_recent_window{user="hello"} 1071
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 149427.8 (41h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10452313
telemt_connections_bad_total 997126
telemt_connections_current 4655
telemt_connections_me_current 4655
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 311571
telemt_upstream_connect_attempt_total 80499
telemt_upstream_connect_success_total 79358
telemt_upstream_connect_fail_total 820
telemt_upstream_connect_attempts_per_request{bucket="1"} 80178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 820
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3700
telemt_me_reconnect_success_total 1472
telemt_me_reader_eof_total 1346
telemt_me_idle_close_by_peer_total 1346
telemt_me_route_drop_no_conn_total 4150026
telemt_me_route_drop_channel_closed_total 454
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7798436
telemt_me_endpoint_quarantine_total 931
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1131
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_warm_current 4
telemt_desync_total 34833
telemt_desync_full_logged_total 11718
telemt_desync_suppressed_total 23115
telemt_desync_frames_bucket_total{bucket="1_2"} 8589
telemt_desync_frames_bucket_total{bucket="3_10"} 13390
telemt_desync_frames_bucket_total{bucket="gt_10"} 12854
telemt_pool_swap_total 159
telemt_pool_force_close_total 4907
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 47559
telemt_me_writer_removed_unexpected_total 1379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4316
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44478
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4484
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42652
telemt_me_writer_teardown_success_total{mode="normal"} 48794
telemt_me_writer_teardown_noop_total 47574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96368
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 91.874554
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96368
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1249
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 7737873
telemt_user_connections_current{user="hello"} 4655
telemt_user_octets_from_client{user="hello"} 195944001873 (182.49 GB)
telemt_user_octets_to_client{user="hello"} 3489488944118 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1908
telemt_user_unique_ips_recent_window{user="hello"} 601
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 149391.5 (41h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9897530
telemt_connections_bad_total 835652
telemt_connections_current 4374
telemt_connections_me_current 4374
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 319226
telemt_upstream_connect_attempt_total 65941
telemt_upstream_connect_success_total 65036
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 65217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2014
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4181
telemt_me_reconnect_success_total 1808
telemt_me_reader_eof_total 1575
telemt_me_idle_close_by_peer_total 1574
telemt_me_route_drop_no_conn_total 4875884
telemt_me_route_drop_channel_closed_total 331
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7475232
telemt_me_endpoint_quarantine_total 1020
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1094
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 34667
telemt_desync_full_logged_total 11488
telemt_desync_suppressed_total 23179
telemt_desync_frames_bucket_total{bucket="1_2"} 8772
telemt_desync_frames_bucket_total{bucket="3_10"} 13278
telemt_desync_frames_bucket_total{bucket="gt_10"} 12617
telemt_pool_swap_total 155
telemt_pool_force_close_total 4848
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 48209
telemt_me_writer_removed_unexpected_total 1720
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4819
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45023
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4333
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43361
telemt_me_writer_teardown_success_total{mode="normal"} 49842
telemt_me_writer_teardown_noop_total 48276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3158.794682
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98118
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 122
telemt_me_writer_restored_same_endpoint_total 1578
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 7469103
telemt_user_connections_current{user="hello"} 4374
telemt_user_octets_from_client{user="hello"} 175177616169 (163.15 GB)
telemt_user_octets_to_client{user="hello"} 3118016248817 (2.84 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1855
telemt_user_unique_ips_recent_window{user="hello"} 696
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 19670.7 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8307886
telemt_connections_bad_total 520220
telemt_connections_current 7140
telemt_connections_me_current 7140
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 133873
telemt_upstream_connect_attempt_total 28479
telemt_upstream_connect_success_total 27075
telemt_upstream_connect_fail_total 1024
telemt_upstream_connect_attempts_per_request{bucket="1"} 28099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4732
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1024
telemt_me_keepalive_timeout_total 718
telemt_me_reconnect_attempts_total 5463
telemt_me_reconnect_success_total 546
telemt_me_reader_eof_total 328
telemt_me_idle_close_by_peer_total 328
telemt_me_route_drop_no_conn_total 20278134
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6917985
telemt_me_endpoint_quarantine_total 126
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 152
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
telemt_me_writers_active_current 59
telemt_desync_total 10092
telemt_desync_full_logged_total 2606
telemt_desync_suppressed_total 7486
telemt_desync_frames_bucket_total{bucket="1_2"} 1801
telemt_desync_frames_bucket_total{bucket="3_10"} 4081
telemt_desync_frames_bucket_total{bucket="gt_10"} 4210
telemt_pool_swap_total 18
telemt_pool_force_close_total 745
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 268
telemt_me_draining_writers_reap_progress_total 5118
telemt_me_writer_removed_unexpected_total 458
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 886
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4647
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4373
telemt_me_writer_teardown_success_total{mode="normal"} 5533
telemt_me_writer_teardown_noop_total 5121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.001727
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 268
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 6932913
telemt_user_connections_current{user="hello"} 7140
telemt_user_octets_from_client{user="hello"} 39589922307 (36.87 GB)
telemt_user_octets_to_client{user="hello"} 203429393900 (189.46 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2614
telemt_user_unique_ips_recent_window{user="hello"} 1462
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 149397.4 (41h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9622379
telemt_connections_bad_total 794084
telemt_connections_current 5391
telemt_connections_me_current 5391
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 208304
telemt_upstream_connect_attempt_total 90227
telemt_upstream_connect_success_total 89322
telemt_upstream_connect_fail_total 783
telemt_upstream_connect_attempts_per_request{bucket="1"} 90105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1253
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 783
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71354
telemt_me_reconnect_success_total 2424
telemt_me_reader_eof_total 2154
telemt_me_idle_close_by_peer_total 2153
telemt_me_route_drop_no_conn_total 4707901
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7597827
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1112
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 39006
telemt_desync_full_logged_total 13342
telemt_desync_suppressed_total 25664
telemt_desync_frames_bucket_total{bucket="1_2"} 7910
telemt_desync_frames_bucket_total{bucket="3_10"} 15126
telemt_desync_frames_bucket_total{bucket="gt_10"} 15970
telemt_pool_swap_total 153
telemt_pool_force_close_total 4532
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 554
telemt_me_draining_writers_reap_progress_total 50838
telemt_me_writer_removed_unexpected_total 2181
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5357
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47679
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3915
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 617
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46306
telemt_me_writer_teardown_success_total{mode="normal"} 53036
telemt_me_writer_teardown_noop_total 50839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103875
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.832485
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103875
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 554
telemt_me_refill_failed_total 4253
telemt_me_writer_restored_same_endpoint_total 2032
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 7598884
telemt_user_connections_current{user="hello"} 5391
telemt_user_octets_from_client{user="hello"} 174545186383 (162.56 GB)
telemt_user_octets_to_client{user="hello"} 2881855832185 (2.62 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2067
telemt_user_unique_ips_recent_window{user="hello"} 778
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 86233.4 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9657808
telemt_connections_bad_total 349051
telemt_connections_current 4860
telemt_connections_me_current 4860
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4050688
telemt_upstream_connect_attempt_total 42482
telemt_upstream_connect_success_total 42173
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 42475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_reconnect_attempts_total 47931
telemt_me_reconnect_success_total 1445
telemt_me_reader_eof_total 1113
telemt_me_idle_close_by_peer_total 1113
telemt_me_route_drop_no_conn_total 3546550
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4660415
telemt_me_endpoint_quarantine_total 562
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 648
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 25487
telemt_desync_full_logged_total 8556
telemt_desync_suppressed_total 16931
telemt_desync_frames_bucket_total{bucket="1_2"} 5143
telemt_desync_frames_bucket_total{bucket="3_10"} 10101
telemt_desync_frames_bucket_total{bucket="gt_10"} 10243
telemt_pool_swap_total 90
telemt_pool_force_close_total 2803
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 289
telemt_me_draining_writers_reap_progress_total 29827
telemt_me_writer_removed_unexpected_total 1178
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2694
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28339
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2394
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27024
telemt_me_writer_teardown_success_total{mode="normal"} 31033
telemt_me_writer_teardown_noop_total 29834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60867
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.206934
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60867
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 289
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1292
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4654856
telemt_user_connections_current{user="hello"} 4860
telemt_user_octets_from_client{user="hello"} 101439749456 (94.47 GB)
telemt_user_octets_to_client{user="hello"} 1772094524702 (1.61 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1901
telemt_user_unique_ips_recent_window{user="hello"} 736
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 67204.3 (18h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809773
telemt_connections_bad_total 10687
telemt_connections_current 1097
telemt_connections_me_current 1097
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15188
telemt_upstream_connect_attempt_total 33948
telemt_upstream_connect_success_total 33863
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 33932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 443
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1557
telemt_me_reconnect_success_total 660
telemt_me_reader_eof_total 635
telemt_me_idle_close_by_peer_total 635
telemt_me_route_drop_no_conn_total 277706
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 723860
telemt_me_endpoint_quarantine_total 601
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 560
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
telemt_me_writers_active_current 49
telemt_desync_total 4001
telemt_desync_full_logged_total 1209
telemt_desync_suppressed_total 2792
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1597
telemt_desync_frames_bucket_total{bucket="gt_10"} 1432
telemt_pool_swap_total 71
telemt_pool_force_close_total 1769
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 27894
telemt_me_writer_removed_unexpected_total 614
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2148
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26383
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1691
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26125
telemt_me_writer_teardown_success_total{mode="normal"} 28531
telemt_me_writer_teardown_noop_total 27896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56427
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.057413
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56427
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 563
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 725097
telemt_user_connections_current{user="hello"} 1097
telemt_user_octets_from_client{user="hello"} 13512182457 (12.58 GB)
telemt_user_octets_to_client{user="hello"} 340382507647 (317.01 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 149402.3 (41h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11721873
telemt_connections_bad_total 1365894
telemt_connections_current 6105
telemt_connections_me_current 6105
telemt_handshake_timeouts_total 320586
telemt_upstream_connect_attempt_total 56196
telemt_upstream_connect_success_total 55978
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 56147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_reconnect_attempts_total 2194
telemt_me_reconnect_success_total 1169
telemt_me_reader_eof_total 1134
telemt_me_idle_close_by_peer_total 1134
telemt_me_route_drop_no_conn_total 3728393
telemt_me_route_drop_channel_closed_total 106
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8822803
telemt_me_endpoint_quarantine_total 1019
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1117
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 36435
telemt_desync_full_logged_total 11911
telemt_desync_suppressed_total 24524
telemt_desync_frames_bucket_total{bucket="1_2"} 8697
telemt_desync_frames_bucket_total{bucket="3_10"} 13480
telemt_desync_frames_bucket_total{bucket="gt_10"} 14258
telemt_pool_swap_total 165
telemt_pool_force_close_total 4546
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 572
telemt_me_draining_writers_reap_progress_total 50635
telemt_me_writer_removed_unexpected_total 1089
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4149
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47605
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4390
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 156
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46089
telemt_me_writer_teardown_success_total{mode="normal"} 51754
telemt_me_writer_teardown_noop_total 50637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102391
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.515385
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102391
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 572
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1025
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8793007
telemt_user_connections_current{user="hello"} 6105
telemt_user_octets_from_client{user="hello"} 169731410484 (158.07 GB)
telemt_user_octets_to_client{user="hello"} 3958179363520 (3.60 TB)
telemt_user_unique_ips_current{user="hello"} 2319
telemt_user_unique_ips_recent_window{user="hello"} 786
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 149398.5 (41h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10153127
telemt_connections_bad_total 1137482
telemt_connections_current 5296
telemt_connections_me_current 5296
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 265140
telemt_upstream_connect_attempt_total 81817
telemt_upstream_connect_success_total 81214
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 81736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_reconnect_attempts_total 8599
telemt_me_reconnect_success_total 1952
telemt_me_reader_eof_total 1817
telemt_me_idle_close_by_peer_total 1817
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4700282
telemt_me_route_drop_channel_closed_total 323
telemt_me_route_drop_queue_full_total 17
telemt_me_route_drop_queue_full_profile_total{profile="high"} 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7824151
telemt_me_endpoint_quarantine_total 1140
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1120
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 35601
telemt_desync_full_logged_total 11559
telemt_desync_suppressed_total 24042
telemt_desync_frames_bucket_total{bucket="1_2"} 8804
telemt_desync_frames_bucket_total{bucket="3_10"} 13275
telemt_desync_frames_bucket_total{bucket="gt_10"} 13522
telemt_pool_swap_total 158
telemt_pool_force_close_total 4407
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 570
telemt_me_draining_writers_reap_progress_total 49973
telemt_me_writer_removed_unexpected_total 1842
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5179
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46703
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4003
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 404
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45566
telemt_me_writer_teardown_success_total{mode="normal"} 51882
telemt_me_writer_teardown_noop_total 49977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101859
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.407318
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101859
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 570
telemt_me_refill_failed_total 341
telemt_me_writer_restored_same_endpoint_total 1583
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 7831001
telemt_user_connections_current{user="hello"} 5296
telemt_user_octets_from_client{user="hello"} 137735807757 (128.28 GB)
telemt_user_octets_to_client{user="hello"} 3060632962555 (2.78 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2019
telemt_user_unique_ips_recent_window{user="hello"} 768
```