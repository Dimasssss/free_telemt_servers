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

# Server Metrics 2026-03-21 13:10:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 59692.5 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1964615
telemt_connections_bad_total 98336
telemt_connections_current 1601
telemt_connections_me_current 1601
telemt_handshake_timeouts_total 72091
telemt_upstream_connect_attempt_total 23023
telemt_upstream_connect_success_total 22908
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 22985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1293
telemt_me_reconnect_success_total 528
telemt_me_reader_eof_total 510
telemt_me_idle_close_by_peer_total 510
telemt_me_route_drop_no_conn_total 1480348
telemt_me_route_drop_channel_closed_total 487
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1545787
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 422
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 473
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
telemt_me_writers_active_current 44
telemt_desync_total 6055
telemt_desync_full_logged_total 2095
telemt_desync_suppressed_total 3960
telemt_desync_frames_bucket_total{bucket="1_2"} 1330
telemt_desync_frames_bucket_total{bucket="3_10"} 2311
telemt_desync_frames_bucket_total{bucket="gt_10"} 2414
telemt_pool_swap_total 65
telemt_pool_force_close_total 1927
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 20604
telemt_me_writer_removed_unexpected_total 491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1701
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19222
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18677
telemt_me_writer_teardown_success_total{mode="normal"} 20923
telemt_me_writer_teardown_noop_total 20609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41532
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 163.857347
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41532
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 1544644
telemt_user_connections_current{user="hello"} 1601
telemt_user_octets_from_client{user="hello"} 23083543019 (21.50 GB)
telemt_user_octets_to_client{user="hello"} 401771997779 (374.18 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 583
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 5337.6 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378206
telemt_connections_bad_total 20063
telemt_connections_current 2992
telemt_connections_me_current 2992
telemt_handshake_timeouts_total 19039
telemt_upstream_connect_attempt_total 2273
telemt_upstream_connect_success_total 2209
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 2255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 195
telemt_me_reconnect_success_total 134
telemt_me_reader_eof_total 121
telemt_me_idle_close_by_peer_total 121
telemt_me_route_drop_no_conn_total 326462
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315510
telemt_me_endpoint_quarantine_total 38
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_me_writers_active_current 50
telemt_desync_total 1103
telemt_desync_full_logged_total 509
telemt_desync_suppressed_total 594
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 452
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 3
telemt_pool_force_close_total 131
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 9
telemt_me_draining_writers_reap_progress_total 1867
telemt_me_writer_removed_unexpected_total 129
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 236
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1760
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1736
telemt_me_writer_teardown_success_total{mode="normal"} 1996
telemt_me_writer_teardown_noop_total 1867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3863
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.914212
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3863
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 9
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 123
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 315312
telemt_user_connections_current{user="hello"} 2992
telemt_user_octets_from_client{user="hello"} 4547674232 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 80521359004 (74.99 GB)
telemt_user_unique_ips_current{user="hello"} 1478
telemt_user_unique_ips_recent_window{user="hello"} 684
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 59691.2 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3842245
telemt_connections_bad_total 386898
telemt_connections_current 4015
telemt_connections_me_current 4015
telemt_handshake_timeouts_total 148359
telemt_upstream_connect_attempt_total 22512
telemt_upstream_connect_success_total 22478
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 846
telemt_me_reconnect_success_total 478
telemt_me_reader_eof_total 474
telemt_me_idle_close_by_peer_total 474
telemt_me_route_drop_no_conn_total 1889896
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3085199
telemt_me_endpoint_quarantine_total 382
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 457
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
telemt_me_writers_active_current 52
telemt_desync_total 13087
telemt_desync_full_logged_total 4439
telemt_desync_suppressed_total 8648
telemt_desync_frames_bucket_total{bucket="1_2"} 2784
telemt_desync_frames_bucket_total{bucket="3_10"} 5127
telemt_desync_frames_bucket_total{bucket="gt_10"} 5176
telemt_pool_swap_total 64
telemt_pool_force_close_total 2022
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 308
telemt_me_draining_writers_reap_progress_total 20460
telemt_me_writer_removed_unexpected_total 457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1754
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18972
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1871
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18438
telemt_me_writer_teardown_success_total{mode="normal"} 20726
telemt_me_writer_teardown_noop_total 20478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41204
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.471138
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41204
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 308
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 3081196
telemt_user_connections_current{user="hello"} 4016
telemt_user_octets_from_client{user="hello"} 50016798888 (46.58 GB)
telemt_user_octets_to_client{user="hello"} 1069366776688 (995.93 GB)
telemt_user_unique_ips_current{user="hello"} 1429
telemt_user_unique_ips_recent_window{user="hello"} 791
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 59691.5 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3137432
telemt_connections_bad_total 340497
telemt_connections_current 4000
telemt_connections_me_current 4000
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 121557
telemt_upstream_connect_attempt_total 27170
telemt_upstream_connect_success_total 26896
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 27030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 476
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1153
telemt_me_reconnect_success_total 537
telemt_me_reader_eof_total 500
telemt_me_idle_close_by_peer_total 500
telemt_me_route_drop_no_conn_total 981822
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2259303
telemt_me_endpoint_quarantine_total 393
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 458
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
telemt_desync_total 10427
telemt_desync_full_logged_total 3530
telemt_desync_suppressed_total 6897
telemt_desync_frames_bucket_total{bucket="1_2"} 2599
telemt_desync_frames_bucket_total{bucket="3_10"} 4031
telemt_desync_frames_bucket_total{bucket="gt_10"} 3797
telemt_pool_swap_total 65
telemt_pool_force_close_total 1825
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 19898
telemt_me_writer_removed_unexpected_total 487
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1688
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18718
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1704
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18073
telemt_me_writer_teardown_success_total{mode="normal"} 20406
telemt_me_writer_teardown_noop_total 19899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40305
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.417720
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40305
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 452
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2260135
telemt_user_connections_current{user="hello"} 4000
telemt_user_octets_from_client{user="hello"} 42487442757 (39.57 GB)
telemt_user_octets_to_client{user="hello"} 1069450883815 (996.00 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1389
telemt_user_unique_ips_recent_window{user="hello"} 576
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 59656.1 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3064220
telemt_connections_bad_total 331251
telemt_connections_current 3684
telemt_connections_me_current 3684
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 89446
telemt_upstream_connect_attempt_total 32369
telemt_upstream_connect_success_total 32144
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13720
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 840
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1273
telemt_me_reconnect_success_total 613
telemt_me_reader_eof_total 556
telemt_me_idle_close_by_peer_total 556
telemt_me_route_drop_no_conn_total 933050
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2231932
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 449
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
telemt_desync_total 10326
telemt_desync_full_logged_total 3454
telemt_desync_suppressed_total 6872
telemt_desync_frames_bucket_total{bucket="1_2"} 2646
telemt_desync_frames_bucket_total{bucket="3_10"} 3933
telemt_desync_frames_bucket_total{bucket="gt_10"} 3747
telemt_pool_swap_total 63
telemt_pool_force_close_total 1779
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 207
telemt_me_draining_writers_reap_progress_total 21258
telemt_me_writer_removed_unexpected_total 530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1798
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20024
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 160
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19479
telemt_me_writer_teardown_success_total{mode="normal"} 21822
telemt_me_writer_teardown_noop_total 21262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43084
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.383116
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43084
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 207
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 534
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2236861
telemt_user_connections_current{user="hello"} 3684
telemt_user_octets_from_client{user="hello"} 49814415309 (46.39 GB)
telemt_user_octets_to_client{user="hello"} 1063697561280 (990.65 GB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1374
telemt_user_unique_ips_recent_window{user="hello"} 586
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 59695.0 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10291725
telemt_connections_bad_total 702443
telemt_connections_current 6007
telemt_connections_me_current 6007
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 332849
telemt_upstream_connect_attempt_total 89590
telemt_upstream_connect_success_total 84377
telemt_upstream_connect_fail_total 4331
telemt_upstream_connect_attempts_per_request{bucket="1"} 88708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4331
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3531
telemt_me_reconnect_success_total 1225
telemt_me_reader_eof_total 879
telemt_me_idle_close_by_peer_total 878
telemt_me_route_drop_no_conn_total 18942123
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8465886
telemt_me_endpoint_quarantine_total 449
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 468
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
telemt_me_writers_active_current 86
telemt_desync_total 15985
telemt_desync_full_logged_total 5103
telemt_desync_suppressed_total 10882
telemt_desync_frames_bucket_total{bucket="1_2"} 3405
telemt_desync_frames_bucket_total{bucket="3_10"} 7016
telemt_desync_frames_bucket_total{bucket="gt_10"} 5564
telemt_pool_swap_total 60
telemt_pool_force_close_total 1906
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 19395
telemt_me_writer_removed_unexpected_total 1189
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2544
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17923
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1632
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17489
telemt_me_writer_teardown_success_total{mode="normal"} 20467
telemt_me_writer_teardown_noop_total 19404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39871
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.381227
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39871
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 865
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 8523530
telemt_user_connections_current{user="hello"} 6007
telemt_user_octets_from_client{user="hello"} 65662054793 (61.15 GB)
telemt_user_octets_to_client{user="hello"} 707935362344 (659.32 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 2065
telemt_user_unique_ips_recent_window{user="hello"} 1219
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 59662.9 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3092868
telemt_connections_bad_total 364189
telemt_connections_current 4818
telemt_connections_me_current 4818
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 67759
telemt_upstream_connect_attempt_total 25550
telemt_upstream_connect_success_total 25265
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 25520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2522
telemt_me_reconnect_success_total 894
telemt_me_reader_eof_total 885
telemt_me_idle_close_by_peer_total 885
telemt_me_route_drop_no_conn_total 1157420
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2348975
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 455
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 10923
telemt_desync_full_logged_total 3804
telemt_desync_suppressed_total 7119
telemt_desync_frames_bucket_total{bucket="1_2"} 2132
telemt_desync_frames_bucket_total{bucket="3_10"} 4363
telemt_desync_frames_bucket_total{bucket="gt_10"} 4428
telemt_pool_swap_total 60
telemt_pool_force_close_total 1687
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 157
telemt_me_draining_writers_reap_progress_total 21259
telemt_me_writer_removed_unexpected_total 857
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2076
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20068
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19572
telemt_me_writer_teardown_success_total{mode="normal"} 22144
telemt_me_writer_teardown_noop_total 21260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43404
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.480341
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43404
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 157
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 759
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 2333772
telemt_user_connections_current{user="hello"} 4818
telemt_user_octets_from_client{user="hello"} 45829978048 (42.68 GB)
telemt_user_octets_to_client{user="hello"} 1019333261718 (949.33 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1800
telemt_user_unique_ips_recent_window{user="hello"} 609
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 59657.1 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4708563
telemt_connections_bad_total 234573
telemt_connections_current 3156
telemt_connections_me_current 3156
telemt_handshake_timeouts_total 2076910
telemt_upstream_connect_attempt_total 23726
telemt_upstream_connect_success_total 23692
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 23695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 988
telemt_me_reconnect_success_total 425
telemt_me_reader_eof_total 433
telemt_me_idle_close_by_peer_total 433
telemt_me_route_drop_no_conn_total 1051924
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2107049
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 465
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
telemt_me_writers_active_current 43
telemt_desync_total 10065
telemt_desync_full_logged_total 3572
telemt_desync_suppressed_total 6493
telemt_desync_frames_bucket_total{bucket="1_2"} 1851
telemt_desync_frames_bucket_total{bucket="3_10"} 4002
telemt_desync_frames_bucket_total{bucket="gt_10"} 4212
telemt_pool_swap_total 65
telemt_pool_force_close_total 1658
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 21242
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1455
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20229
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1601
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 57
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19584
telemt_me_writer_teardown_success_total{mode="normal"} 21684
telemt_me_writer_teardown_noop_total 21242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42926
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.470956
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42926
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 370
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2100285
telemt_user_connections_current{user="hello"} 3156
telemt_user_octets_from_client{user="hello"} 39267804336 (36.57 GB)
telemt_user_octets_to_client{user="hello"} 988690281288 (920.79 GB)
telemt_user_unique_ips_current{user="hello"} 1210
telemt_user_unique_ips_recent_window{user="hello"} 656
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 57648.3 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1008215
telemt_connections_bad_total 121352
telemt_connections_current 723
telemt_connections_me_current 723
telemt_handshake_timeouts_total 353792
telemt_upstream_connect_attempt_total 27195
telemt_upstream_connect_success_total 27193
telemt_upstream_connect_attempts_per_request{bucket="1"} 27193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1150
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 447
telemt_me_idle_close_by_peer_total 447
telemt_me_route_drop_no_conn_total 208406
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464074
telemt_me_endpoint_quarantine_total 530
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 485
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 14
telemt_desync_total 3150
telemt_desync_full_logged_total 1172
telemt_desync_suppressed_total 1978
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 1118
telemt_desync_frames_bucket_total{bucket="gt_10"} 1482
telemt_pool_swap_total 63
telemt_pool_force_close_total 1416
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 24375
telemt_me_writer_removed_unexpected_total 424
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1787
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23020
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1413
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22959
telemt_me_writer_teardown_success_total{mode="normal"} 24807
telemt_me_writer_teardown_noop_total 24375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49182
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.207530
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49182
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 367
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 463884
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 7827647343 (7.29 GB)
telemt_user_octets_to_client{user="hello"} 177735924577 (165.53 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 59667.4 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3336983
telemt_connections_bad_total 318827
telemt_connections_current 4582
telemt_connections_me_current 4582
telemt_handshake_timeouts_total 97890
telemt_upstream_connect_attempt_total 24531
telemt_upstream_connect_success_total 24431
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 24500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 995
telemt_me_reconnect_success_total 553
telemt_me_reader_eof_total 517
telemt_me_idle_close_by_peer_total 517
telemt_me_route_drop_no_conn_total 954581
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2631792
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 461
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 10687
telemt_desync_full_logged_total 3514
telemt_desync_suppressed_total 7173
telemt_desync_frames_bucket_total{bucket="1_2"} 2553
telemt_desync_frames_bucket_total{bucket="3_10"} 3979
telemt_desync_frames_bucket_total{bucket="gt_10"} 4155
telemt_pool_swap_total 66
telemt_pool_force_close_total 1703
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 22052
telemt_me_writer_removed_unexpected_total 508
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1709
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20849
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1672
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20349
telemt_me_writer_teardown_success_total{mode="normal"} 22558
telemt_me_writer_teardown_noop_total 22052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44610
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.610166
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44610
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 492
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 2624598
telemt_user_connections_current{user="hello"} 4582
telemt_user_octets_from_client{user="hello"} 55369802236 (51.57 GB)
telemt_user_octets_to_client{user="hello"} 1230953218056 (1.12 TB)
telemt_user_unique_ips_current{user="hello"} 1552
telemt_user_unique_ips_recent_window{user="hello"} 755
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 59663.9 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2997596
telemt_connections_bad_total 250956
telemt_connections_current 3947
telemt_connections_me_current 3947
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 87629
telemt_upstream_connect_attempt_total 40784
telemt_upstream_connect_success_total 40520
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 40739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 586
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_reconnect_attempts_total 3426
telemt_me_reconnect_success_total 737
telemt_me_reader_eof_total 639
telemt_me_idle_close_by_peer_total 639
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 982557
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2407557
telemt_me_endpoint_quarantine_total 513
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 463
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
telemt_desync_total 9272
telemt_desync_full_logged_total 3159
telemt_desync_suppressed_total 6113
telemt_desync_frames_bucket_total{bucket="1_2"} 2386
telemt_desync_frames_bucket_total{bucket="3_10"} 3414
telemt_desync_frames_bucket_total{bucket="gt_10"} 3472
telemt_pool_swap_total 65
telemt_pool_force_close_total 1647
telemt_me_writer_close_signal_drop_total 168
telemt_me_draining_writers_reap_progress_total 21258
telemt_me_writer_removed_unexpected_total 651
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19921
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1539
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19611
telemt_me_writer_teardown_success_total{mode="normal"} 21939
telemt_me_writer_teardown_noop_total 21259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43198
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.775741
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43198
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 168
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 561
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2417465
telemt_user_connections_current{user="hello"} 3947
telemt_user_octets_from_client{user="hello"} 44578274249 (41.52 GB)
telemt_user_octets_to_client{user="hello"} 1058226609664 (985.55 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1296
telemt_user_unique_ips_recent_window{user="hello"} 576
```