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

# Server Metrics 2026-03-21 13:31:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 60920.4 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2011849
telemt_connections_bad_total 100589
telemt_connections_current 1704
telemt_connections_me_current 1704
telemt_handshake_timeouts_total 72765
telemt_upstream_connect_attempt_total 23394
telemt_upstream_connect_success_total 23279
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 23356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1317
telemt_me_reconnect_success_total 532
telemt_me_reader_eof_total 515
telemt_me_idle_close_by_peer_total 515
telemt_me_route_drop_no_conn_total 1497758
telemt_me_route_drop_channel_closed_total 503
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1587325
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 428
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 480
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
telemt_desync_total 6277
telemt_desync_full_logged_total 2159
telemt_desync_suppressed_total 4118
telemt_desync_frames_bucket_total{bucket="1_2"} 1402
telemt_desync_frames_bucket_total{bucket="3_10"} 2374
telemt_desync_frames_bucket_total{bucket="gt_10"} 2501
telemt_pool_swap_total 66
telemt_pool_force_close_total 1963
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 20929
telemt_me_writer_removed_unexpected_total 495
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1719
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19530
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18966
telemt_me_writer_teardown_success_total{mode="normal"} 21249
telemt_me_writer_teardown_noop_total 20934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42183
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 166.356808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42183
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1586102
telemt_user_connections_current{user="hello"} 1704
telemt_user_octets_from_client{user="hello"} 23739308223 (22.11 GB)
telemt_user_octets_to_client{user="hello"} 413850662987 (385.43 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 473.3 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60932
telemt_connections_bad_total 2941
telemt_connections_current 4918
telemt_connections_me_current 4918
telemt_handshake_timeouts_total 2015
telemt_upstream_connect_attempt_total 188
telemt_upstream_connect_success_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 88
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_success_total 5
telemt_me_route_drop_no_conn_total 23782
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52690
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 224
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_me_draining_writers_reap_progress_total 107
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 106
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 107
telemt_me_writer_teardown_success_total{mode="normal"} 107
telemt_me_writer_teardown_noop_total 107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 214
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.002909
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 214
telemt_user_connections_total{user="hello"} 52639
telemt_user_connections_current{user="hello"} 4918
telemt_user_octets_from_client{user="hello"} 590645068 (563.28 MB)
telemt_user_octets_to_client{user="hello"} 10965885240 (10.21 GB)
telemt_user_unique_ips_current{user="hello"} 1623
telemt_user_unique_ips_recent_window{user="hello"} 700
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 60918.0 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3988356
telemt_connections_bad_total 391553
telemt_connections_current 4897
telemt_connections_me_current 4897
telemt_handshake_timeouts_total 153728
telemt_upstream_connect_attempt_total 23059
telemt_upstream_connect_success_total 23022
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12510
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 891
telemt_me_reconnect_success_total 521
telemt_me_reader_eof_total 518
telemt_me_idle_close_by_peer_total 518
telemt_me_route_drop_no_conn_total 2014961
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3213194
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 463
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
telemt_me_writers_active_current 94
telemt_desync_total 13539
telemt_desync_full_logged_total 4589
telemt_desync_suppressed_total 8950
telemt_desync_frames_bucket_total{bucket="1_2"} 2871
telemt_desync_frames_bucket_total{bucket="3_10"} 5314
telemt_desync_frames_bucket_total{bucket="gt_10"} 5354
telemt_pool_swap_total 64
telemt_pool_force_close_total 2022
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 311
telemt_me_draining_writers_reap_progress_total 20893
telemt_me_writer_removed_unexpected_total 501
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1810
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19393
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1871
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18871
telemt_me_writer_teardown_success_total{mode="normal"} 21203
telemt_me_writer_teardown_noop_total 20911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42114
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.578878
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42114
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 311
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 473
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 3209178
telemt_user_connections_current{user="hello"} 4897
telemt_user_octets_from_client{user="hello"} 52533885524 (48.93 GB)
telemt_user_octets_to_client{user="hello"} 1105284385408 (1.01 TB)
telemt_user_unique_ips_current{user="hello"} 1989
telemt_user_unique_ips_recent_window{user="hello"} 613
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 60919.7 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3257819
telemt_connections_bad_total 362969
telemt_connections_current 3863
telemt_connections_me_current 3863
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 123742
telemt_upstream_connect_attempt_total 27539
telemt_upstream_connect_success_total 27265
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 27399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 477
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1161
telemt_me_reconnect_success_total 546
telemt_me_reader_eof_total 509
telemt_me_idle_close_by_peer_total 509
telemt_me_route_drop_no_conn_total 1013522
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2346393
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 466
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
telemt_desync_total 10742
telemt_desync_full_logged_total 3647
telemt_desync_suppressed_total 7095
telemt_desync_frames_bucket_total{bucket="1_2"} 2678
telemt_desync_frames_bucket_total{bucket="3_10"} 4134
telemt_desync_frames_bucket_total{bucket="gt_10"} 3930
telemt_pool_swap_total 66
telemt_pool_force_close_total 1856
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 20222
telemt_me_writer_removed_unexpected_total 496
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1714
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19025
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1733
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 123
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18366
telemt_me_writer_teardown_success_total{mode="normal"} 20739
telemt_me_writer_teardown_noop_total 20223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40962
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.361521
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40962
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 460
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 2347174
telemt_user_connections_current{user="hello"} 3863
telemt_user_octets_from_client{user="hello"} 44028175097 (41.00 GB)
telemt_user_octets_to_client{user="hello"} 1106525245019 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1492
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 60883.8 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3164540
telemt_connections_bad_total 338121
telemt_connections_current 3545
telemt_connections_me_current 3545
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 91698
telemt_upstream_connect_attempt_total 32729
telemt_upstream_connect_success_total 32502
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 844
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1276
telemt_me_reconnect_success_total 616
telemt_me_reader_eof_total 559
telemt_me_idle_close_by_peer_total 559
telemt_me_route_drop_no_conn_total 972059
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2316259
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 456
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
telemt_me_writers_active_current 45
telemt_desync_total 10730
telemt_desync_full_logged_total 3574
telemt_desync_suppressed_total 7156
telemt_desync_frames_bucket_total{bucket="1_2"} 2734
telemt_desync_frames_bucket_total{bucket="3_10"} 4059
telemt_desync_frames_bucket_total{bucket="gt_10"} 3937
telemt_pool_swap_total 64
telemt_pool_force_close_total 1809
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 211
telemt_me_draining_writers_reap_progress_total 21580
telemt_me_writer_removed_unexpected_total 533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1821
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20326
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1646
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 163
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19771
telemt_me_writer_teardown_success_total{mode="normal"} 22147
telemt_me_writer_teardown_noop_total 21584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43731
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.711790
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43731
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 211
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2321057
telemt_user_connections_current{user="hello"} 3545
telemt_user_octets_from_client{user="hello"} 51370831193 (47.84 GB)
telemt_user_octets_to_client{user="hello"} 1104088084952 (1.00 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1384
telemt_user_unique_ips_recent_window{user="hello"} 519
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 60922.3 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10720454
telemt_connections_bad_total 726404
telemt_connections_current 6863
telemt_connections_me_current 6863
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 342185
telemt_upstream_connect_attempt_total 90092
telemt_upstream_connect_success_total 84858
telemt_upstream_connect_fail_total 4333
telemt_upstream_connect_attempts_per_request{bucket="1"} 89191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4333
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3543
telemt_me_reconnect_success_total 1235
telemt_me_reader_eof_total 890
telemt_me_idle_close_by_peer_total 889
telemt_me_route_drop_no_conn_total 19914776
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8812758
telemt_me_endpoint_quarantine_total 458
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 479
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
telemt_me_writers_active_current 45
telemt_desync_total 16488
telemt_desync_full_logged_total 5273
telemt_desync_suppressed_total 11215
telemt_desync_frames_bucket_total{bucket="1_2"} 3515
telemt_desync_frames_bucket_total{bucket="3_10"} 7225
telemt_desync_frames_bucket_total{bucket="gt_10"} 5748
telemt_pool_swap_total 61
telemt_pool_force_close_total 2016
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 406
telemt_me_draining_writers_reap_progress_total 19929
telemt_me_writer_removed_unexpected_total 1199
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2585
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18374
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1685
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17913
telemt_me_writer_teardown_success_total{mode="normal"} 20959
telemt_me_writer_teardown_noop_total 19939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40898
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.287859
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40898
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 406
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 874
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 8870221
telemt_user_connections_current{user="hello"} 6863
telemt_user_octets_from_client{user="hello"} 67560013445 (62.92 GB)
telemt_user_octets_to_client{user="hello"} 722025816696 (672.44 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 2089
telemt_user_unique_ips_recent_window{user="hello"} 1345
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 60889.7 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3191686
telemt_connections_bad_total 369228
telemt_connections_current 3935
telemt_connections_me_current 3935
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 70563
telemt_upstream_connect_attempt_total 26151
telemt_upstream_connect_success_total 25866
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 26121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2530
telemt_me_reconnect_success_total 901
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 1225473
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2431551
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 461
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 11359
telemt_desync_full_logged_total 3942
telemt_desync_suppressed_total 7417
telemt_desync_frames_bucket_total{bucket="1_2"} 2212
telemt_desync_frames_bucket_total{bucket="3_10"} 4523
telemt_desync_frames_bucket_total{bucket="gt_10"} 4624
telemt_pool_swap_total 61
telemt_pool_force_close_total 1741
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 21871
telemt_me_writer_removed_unexpected_total 864
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20641
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1527
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 214
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20130
telemt_me_writer_teardown_success_total{mode="normal"} 22765
telemt_me_writer_teardown_noop_total 21872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44637
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.826832
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44637
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 766
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 2416189
telemt_user_connections_current{user="hello"} 3935
telemt_user_octets_from_client{user="hello"} 49470946844 (46.07 GB)
telemt_user_octets_to_client{user="hello"} 1050779803366 (978.61 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1586
telemt_user_unique_ips_recent_window{user="hello"} 557
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 60884.5 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4886618
telemt_connections_bad_total 240831
telemt_connections_current 3489
telemt_connections_me_current 3489
telemt_handshake_timeouts_total 2158167
telemt_upstream_connect_attempt_total 24112
telemt_upstream_connect_success_total 24078
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13027
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 290
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1014
telemt_me_reconnect_success_total 432
telemt_me_reader_eof_total 440
telemt_me_idle_close_by_peer_total 440
telemt_me_route_drop_no_conn_total 1125586
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2192907
telemt_me_endpoint_quarantine_total 451
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 473
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
telemt_desync_total 10422
telemt_desync_full_logged_total 3697
telemt_desync_suppressed_total 6725
telemt_desync_frames_bucket_total{bucket="1_2"} 1926
telemt_desync_frames_bucket_total{bucket="3_10"} 4136
telemt_desync_frames_bucket_total{bucket="gt_10"} 4360
telemt_pool_swap_total 66
telemt_pool_force_close_total 1684
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 21585
telemt_me_writer_removed_unexpected_total 422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1477
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20557
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1627
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 57
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19901
telemt_me_writer_teardown_success_total{mode="normal"} 22034
telemt_me_writer_teardown_noop_total 21585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43619
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.580685
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43619
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 2186075
telemt_user_connections_current{user="hello"} 3489
telemt_user_octets_from_client{user="hello"} 44526402936 (41.47 GB)
telemt_user_octets_to_client{user="hello"} 1018891840848 (948.92 GB)
telemt_user_unique_ips_current{user="hello"} 1400
telemt_user_unique_ips_recent_window{user="hello"} 663
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 58875.9 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1048069
telemt_connections_bad_total 133403
telemt_connections_current 750
telemt_connections_me_current 750
telemt_handshake_timeouts_total 364008
telemt_upstream_connect_attempt_total 27717
telemt_upstream_connect_success_total 27715
telemt_upstream_connect_attempts_per_request{bucket="1"} 27715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1189
telemt_me_reconnect_success_total 461
telemt_me_reader_eof_total 459
telemt_me_idle_close_by_peer_total 459
telemt_me_route_drop_no_conn_total 218903
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481056
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 498
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
telemt_me_writers_active_current 43
telemt_desync_total 3172
telemt_desync_full_logged_total 1183
telemt_desync_suppressed_total 1989
telemt_desync_frames_bucket_total{bucket="1_2"} 554
telemt_desync_frames_bucket_total{bucket="3_10"} 1128
telemt_desync_frames_bucket_total{bucket="gt_10"} 1490
telemt_pool_swap_total 65
telemt_pool_force_close_total 1473
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 24855
telemt_me_writer_removed_unexpected_total 433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1831
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23468
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1470
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23382
telemt_me_writer_teardown_success_total{mode="normal"} 25299
telemt_me_writer_teardown_noop_total 24855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50154
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.327747
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50154
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 374
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 480845
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 8691209887 (8.09 GB)
telemt_user_octets_to_client{user="hello"} 183424731513 (170.83 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 60894.3 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3457113
telemt_connections_bad_total 324190
telemt_connections_current 4299
telemt_connections_me_current 4299
telemt_handshake_timeouts_total 103830
telemt_upstream_connect_attempt_total 24922
telemt_upstream_connect_success_total 24819
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 24891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1016
telemt_me_reconnect_success_total 568
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 1002287
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2730904
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 10969
telemt_desync_full_logged_total 3608
telemt_desync_suppressed_total 7361
telemt_desync_frames_bucket_total{bucket="1_2"} 2608
telemt_desync_frames_bucket_total{bucket="3_10"} 4083
telemt_desync_frames_bucket_total{bucket="gt_10"} 4278
telemt_pool_swap_total 67
telemt_pool_force_close_total 1731
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 22388
telemt_me_writer_removed_unexpected_total 519
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1736
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21169
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20657
telemt_me_writer_teardown_success_total{mode="normal"} 22905
telemt_me_writer_teardown_noop_total 22388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45293
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.634943
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45293
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 501
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 2723544
telemt_user_connections_current{user="hello"} 4299
telemt_user_octets_from_client{user="hello"} 57772233860 (53.80 GB)
telemt_user_octets_to_client{user="hello"} 1281857606340 (1.17 TB)
telemt_user_unique_ips_current{user="hello"} 1527
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 60891.0 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3100238
telemt_connections_bad_total 258122
telemt_connections_current 4180
telemt_connections_me_current 4180
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 91186
telemt_upstream_connect_attempt_total 41111
telemt_upstream_connect_success_total 40845
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 41066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 587
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_reconnect_attempts_total 3492
telemt_me_reconnect_success_total 739
telemt_me_reader_eof_total 645
telemt_me_idle_close_by_peer_total 645
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 1036738
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2495601
telemt_me_endpoint_quarantine_total 520
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 470
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
telemt_me_writers_active_current 41
telemt_desync_total 9672
telemt_desync_full_logged_total 3301
telemt_desync_suppressed_total 6371
telemt_desync_frames_bucket_total{bucket="1_2"} 2466
telemt_desync_frames_bucket_total{bucket="3_10"} 3573
telemt_desync_frames_bucket_total{bucket="gt_10"} 3633
telemt_pool_swap_total 66
telemt_pool_force_close_total 1678
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 21562
telemt_me_writer_removed_unexpected_total 657
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20207
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1567
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 111
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19884
telemt_me_writer_teardown_success_total{mode="normal"} 22249
telemt_me_writer_teardown_noop_total 21563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43812
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.920987
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43812
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 563
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2504993
telemt_user_connections_current{user="hello"} 4180
telemt_user_octets_from_client{user="hello"} 46015182277 (42.85 GB)
telemt_user_octets_to_client{user="hello"} 1094570185224 (1019.40 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1555
telemt_user_unique_ips_recent_window{user="hello"} 598
```