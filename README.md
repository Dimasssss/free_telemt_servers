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

# Server Metrics 2026-03-21 09:41:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 47127.6 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1325186
telemt_connections_bad_total 68190
telemt_connections_current 1584
telemt_connections_me_current 1584
telemt_handshake_timeouts_total 53921
telemt_upstream_connect_attempt_total 18546
telemt_upstream_connect_success_total 18465
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 18522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 842
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 728799
telemt_me_route_drop_channel_closed_total 244
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1000648
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 379
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
telemt_me_writers_active_current 89
telemt_desync_total 4223
telemt_desync_full_logged_total 1448
telemt_desync_suppressed_total 2775
telemt_desync_frames_bucket_total{bucket="1_2"} 887
telemt_desync_frames_bucket_total{bucket="3_10"} 1650
telemt_desync_frames_bucket_total{bucket="gt_10"} 1686
telemt_pool_swap_total 51
telemt_pool_force_close_total 1431
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 207
telemt_me_draining_writers_reap_progress_total 16558
telemt_me_writer_removed_unexpected_total 353
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1312
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15497
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1409
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15127
telemt_me_writer_teardown_success_total{mode="normal"} 16809
telemt_me_writer_teardown_noop_total 16559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33368
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 82.613557
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33368
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 207
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 324
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 999848
telemt_user_connections_current{user="hello"} 1584
telemt_user_octets_from_client{user="hello"} 14278866507 (13.30 GB)
telemt_user_octets_to_client{user="hello"} 283705857987 (264.22 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 543
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 47128.7 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3345508
telemt_connections_bad_total 365489
telemt_connections_current 4588
telemt_connections_me_current 4588
telemt_handshake_timeouts_total 98930
telemt_upstream_connect_attempt_total 16958
telemt_upstream_connect_success_total 16879
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 16933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 987
telemt_me_reconnect_success_total 381
telemt_me_reader_eof_total 376
telemt_me_idle_close_by_peer_total 375
telemt_me_route_drop_no_conn_total 1375891
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2234382
telemt_me_endpoint_quarantine_total 300
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 366
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
telemt_desync_total 9658
telemt_desync_full_logged_total 3259
telemt_desync_suppressed_total 6399
telemt_desync_frames_bucket_total{bucket="1_2"} 1965
telemt_desync_frames_bucket_total{bucket="3_10"} 3812
telemt_desync_frames_bucket_total{bucket="gt_10"} 3881
telemt_pool_swap_total 51
telemt_pool_force_close_total 1560
telemt_me_writer_close_signal_drop_total 184
telemt_me_draining_writers_reap_progress_total 15176
telemt_me_writer_removed_unexpected_total 352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1402
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14110
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1469
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13616
telemt_me_writer_teardown_success_total{mode="normal"} 15512
telemt_me_writer_teardown_noop_total 15176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30688
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.312341
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30688
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 184
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 307
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2230102
telemt_user_connections_current{user="hello"} 4588
telemt_user_octets_from_client{user="hello"} 31844628108 (29.66 GB)
telemt_user_octets_to_client{user="hello"} 772132566940 (719.10 GB)
telemt_user_unique_ips_current{user="hello"} 1619
telemt_user_unique_ips_recent_window{user="hello"} 664
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 47125.2 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2452251
telemt_connections_bad_total 299074
telemt_connections_current 4264
telemt_connections_me_current 4264
telemt_handshake_timeouts_total 93811
telemt_upstream_connect_attempt_total 18421
telemt_upstream_connect_success_total 18410
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 617
telemt_me_reconnect_success_total 348
telemt_me_reader_eof_total 362
telemt_me_idle_close_by_peer_total 362
telemt_me_route_drop_no_conn_total 980024
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1907457
telemt_me_endpoint_quarantine_total 312
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 371
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
telemt_me_writers_active_current 47
telemt_desync_total 8145
telemt_desync_full_logged_total 2842
telemt_desync_suppressed_total 5303
telemt_desync_frames_bucket_total{bucket="1_2"} 1719
telemt_desync_frames_bucket_total{bucket="3_10"} 3196
telemt_desync_frames_bucket_total{bucket="gt_10"} 3230
telemt_pool_swap_total 51
telemt_pool_force_close_total 1529
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 201
telemt_me_draining_writers_reap_progress_total 16754
telemt_me_writer_removed_unexpected_total 341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1380
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15597
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15225
telemt_me_writer_teardown_success_total{mode="normal"} 16977
telemt_me_writer_teardown_noop_total 16765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33742
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 36.261675
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33742
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 201
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1904347
telemt_user_connections_current{user="hello"} 4264
telemt_user_octets_from_client{user="hello"} 29876098308 (27.82 GB)
telemt_user_octets_to_client{user="hello"} 728539748700 (678.51 GB)
telemt_user_unique_ips_current{user="hello"} 1531
telemt_user_unique_ips_recent_window{user="hello"} 587
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 47126.6 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2010263
telemt_connections_bad_total 231866
telemt_connections_current 2754
telemt_connections_me_current 2754
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 86207
telemt_upstream_connect_attempt_total 23355
telemt_upstream_connect_success_total 23119
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 23244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 997
telemt_me_reconnect_success_total 440
telemt_me_reader_eof_total 407
telemt_me_idle_close_by_peer_total 407
telemt_me_route_drop_no_conn_total 578285
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1400331
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 373
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
telemt_desync_total 6547
telemt_desync_full_logged_total 2238
telemt_desync_suppressed_total 4309
telemt_desync_frames_bucket_total{bucket="1_2"} 1614
telemt_desync_frames_bucket_total{bucket="3_10"} 2607
telemt_desync_frames_bucket_total{bucket="gt_10"} 2326
telemt_pool_swap_total 51
telemt_pool_force_close_total 1391
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 16631
telemt_me_writer_removed_unexpected_total 400
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1348
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15697
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1309
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15240
telemt_me_writer_teardown_success_total{mode="normal"} 17045
telemt_me_writer_teardown_noop_total 16632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33677
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.047393
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33677
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 370
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1402330
telemt_user_connections_current{user="hello"} 2754
telemt_user_octets_from_client{user="hello"} 28387332929 (26.44 GB)
telemt_user_octets_to_client{user="hello"} 672787925479 (626.58 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 992
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 47090.4 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1932926
telemt_connections_bad_total 221036
telemt_connections_current 3857
telemt_connections_me_current 3857
telemt_handshake_timeouts_total 62675
telemt_upstream_connect_attempt_total 19538
telemt_upstream_connect_success_total 19498
telemt_upstream_connect_attempts_per_request{bucket="1"} 19498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10658
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_reconnect_attempts_total 620
telemt_me_reconnect_success_total 441
telemt_me_reader_eof_total 402
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 538971
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1396023
telemt_me_endpoint_quarantine_total 359
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 362
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
telemt_me_writers_active_current 111
telemt_desync_total 6425
telemt_desync_full_logged_total 2251
telemt_desync_suppressed_total 4174
telemt_desync_frames_bucket_total{bucket="1_2"} 1690
telemt_desync_frames_bucket_total{bucket="3_10"} 2476
telemt_desync_frames_bucket_total{bucket="gt_10"} 2259
telemt_pool_swap_total 50
telemt_pool_force_close_total 1323
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 17494
telemt_me_writer_removed_unexpected_total 378
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1323
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16578
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16171
telemt_me_writer_teardown_success_total{mode="normal"} 17901
telemt_me_writer_teardown_noop_total 17497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35398
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.914844
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35398
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 394
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1393685
telemt_user_connections_current{user="hello"} 3857
telemt_user_octets_from_client{user="hello"} 32698655528 (30.45 GB)
telemt_user_octets_to_client{user="hello"} 690142445944 (642.75 GB)
telemt_user_unique_ips_current{user="hello"} 1509
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 47129.6 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5692254
telemt_connections_bad_total 290811
telemt_connections_current 4697
telemt_connections_me_current 4697
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 227113
telemt_upstream_connect_attempt_total 58847
telemt_upstream_connect_success_total 56264
telemt_upstream_connect_fail_total 1915
telemt_upstream_connect_attempts_per_request{bucket="1"} 58179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2011
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1915
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2806
telemt_me_reconnect_success_total 974
telemt_me_reader_eof_total 677
telemt_me_idle_close_by_peer_total 676
telemt_me_route_drop_no_conn_total 9363001
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4806450
telemt_me_endpoint_quarantine_total 377
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 115
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 115
telemt_me_single_endpoint_shadow_rotate_total 375
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 9735
telemt_desync_full_logged_total 3210
telemt_desync_suppressed_total 6525
telemt_desync_frames_bucket_total{bucket="1_2"} 2142
telemt_desync_frames_bucket_total{bucket="3_10"} 4198
telemt_desync_frames_bucket_total{bucket="gt_10"} 3395
telemt_pool_swap_total 48
telemt_pool_force_close_total 1495
telemt_me_writer_close_signal_drop_total 296
telemt_me_draining_writers_reap_progress_total 16042
telemt_me_writer_removed_unexpected_total 940
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2045
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14866
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1283
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 212
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14547
telemt_me_writer_teardown_success_total{mode="normal"} 16911
telemt_me_writer_teardown_noop_total 16048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.562036
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 296
telemt_me_refill_failed_total 66
telemt_me_writer_restored_same_endpoint_total 673
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 4841139
telemt_user_connections_current{user="hello"} 4697
telemt_user_octets_from_client{user="hello"} 46610504172 (43.41 GB)
telemt_user_octets_to_client{user="hello"} 569756851211 (530.63 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1649
telemt_user_unique_ips_recent_window{user="hello"} 964
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 47097.3 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1978859
telemt_connections_bad_total 254346
telemt_connections_current 3845
telemt_connections_me_current 3845
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 38586
telemt_upstream_connect_attempt_total 20888
telemt_upstream_connect_success_total 20678
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 20869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_reconnect_attempts_total 1960
telemt_me_reconnect_success_total 632
telemt_me_reader_eof_total 640
telemt_me_idle_close_by_peer_total 640
telemt_me_route_drop_no_conn_total 594792
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1481583
telemt_me_endpoint_quarantine_total 288
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 369
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
telemt_me_writers_active_current 89
telemt_desync_total 6710
telemt_desync_full_logged_total 2452
telemt_desync_suppressed_total 4258
telemt_desync_frames_bucket_total{bucket="1_2"} 1309
telemt_desync_frames_bucket_total{bucket="3_10"} 2716
telemt_desync_frames_bucket_total{bucket="gt_10"} 2685
telemt_pool_swap_total 49
telemt_pool_force_close_total 1283
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 94
telemt_me_draining_writers_reap_progress_total 17251
telemt_me_writer_removed_unexpected_total 617
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1563
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16328
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15968
telemt_me_writer_teardown_success_total{mode="normal"} 17891
telemt_me_writer_teardown_noop_total 17251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35142
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.579789
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35142
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 94
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 535
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1477622
telemt_user_connections_current{user="hello"} 3845
telemt_user_octets_from_client{user="hello"} 27041802716 (25.18 GB)
telemt_user_octets_to_client{user="hello"} 682635168534 (635.75 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1599
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 47091.8 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2746189
telemt_connections_bad_total 157478
telemt_connections_current 2711
telemt_connections_me_current 2711
telemt_handshake_timeouts_total 1115290
telemt_upstream_connect_attempt_total 19664
telemt_upstream_connect_success_total 19630
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 520
telemt_me_reconnect_success_total 300
telemt_me_reader_eof_total 301
telemt_me_idle_close_by_peer_total 301
telemt_me_route_drop_no_conn_total 512623
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1314698
telemt_me_endpoint_quarantine_total 365
telemt_me_single_endpoint_shadow_rotate_total 373
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
telemt_desync_total 6543
telemt_desync_full_logged_total 2304
telemt_desync_suppressed_total 4239
telemt_desync_frames_bucket_total{bucket="1_2"} 1158
telemt_desync_frames_bucket_total{bucket="3_10"} 2623
telemt_desync_frames_bucket_total{bucket="gt_10"} 2762
telemt_pool_swap_total 52
telemt_pool_force_close_total 1269
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 17618
telemt_me_writer_removed_unexpected_total 291
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1123
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16805
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16349
telemt_me_writer_teardown_success_total{mode="normal"} 17928
telemt_me_writer_teardown_noop_total 17618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35546
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.926611
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35546
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 267
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1310445
telemt_user_connections_current{user="hello"} 2711
telemt_user_octets_from_client{user="hello"} 23070448320 (21.49 GB)
telemt_user_octets_to_client{user="hello"} 650739138544 (606.05 GB)
telemt_user_unique_ips_current{user="hello"} 1033
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 45083.2 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586171
telemt_connections_bad_total 20510
telemt_connections_current 617
telemt_connections_me_current 617
telemt_handshake_timeouts_total 218769
telemt_upstream_connect_attempt_total 22066
telemt_upstream_connect_success_total 22064
telemt_upstream_connect_attempts_per_request{bucket="1"} 22064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 916
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 361
telemt_me_idle_close_by_peer_total 361
telemt_me_route_drop_no_conn_total 123293
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301790
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
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 32
telemt_desync_total 1922
telemt_desync_full_logged_total 772
telemt_desync_suppressed_total 1150
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 752
telemt_desync_frames_bucket_total{bucket="gt_10"} 810
telemt_pool_swap_total 49
telemt_pool_force_close_total 1060
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 19669
telemt_me_writer_removed_unexpected_total 342
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1412
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18603
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1058
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18609
telemt_me_writer_teardown_success_total{mode="normal"} 20015
telemt_me_writer_teardown_noop_total 19669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39684
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.829878
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39684
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 298
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 301948
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 4464180239 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 120689380177 (112.40 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 47101.6 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2046992
telemt_connections_bad_total 178416
telemt_connections_current 4011
telemt_connections_me_current 4011
telemt_handshake_timeouts_total 51693
telemt_upstream_connect_attempt_total 20353
telemt_upstream_connect_success_total 20266
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 20323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10112
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 761
telemt_me_reconnect_success_total 435
telemt_me_reader_eof_total 404
telemt_me_idle_close_by_peer_total 404
telemt_me_route_drop_no_conn_total 508438
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1618898
telemt_me_endpoint_quarantine_total 373
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 374
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
telemt_desync_total 6409
telemt_desync_full_logged_total 2143
telemt_desync_suppressed_total 4266
telemt_desync_frames_bucket_total{bucket="1_2"} 1557
telemt_desync_frames_bucket_total{bucket="3_10"} 2382
telemt_desync_frames_bucket_total{bucket="gt_10"} 2470
telemt_pool_swap_total 52
telemt_pool_force_close_total 1286
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 18345
telemt_me_writer_removed_unexpected_total 403
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1359
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17398
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17059
telemt_me_writer_teardown_success_total{mode="normal"} 18757
telemt_me_writer_teardown_noop_total 18345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37102
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.531203
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37102
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 391
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1613357
telemt_user_connections_current{user="hello"} 4011
telemt_user_octets_from_client{user="hello"} 36810385284 (34.28 GB)
telemt_user_octets_to_client{user="hello"} 752156306936 (700.50 GB)
telemt_user_unique_ips_current{user="hello"} 1376
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 47098.3 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1925727
telemt_connections_bad_total 158339
telemt_connections_current 3397
telemt_connections_me_current 3397
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 47118
telemt_upstream_connect_attempt_total 29014
telemt_upstream_connect_success_total 28806
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 28972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 2943
telemt_me_reconnect_success_total 602
telemt_me_reader_eof_total 524
telemt_me_idle_close_by_peer_total 524
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 521589
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1546227
telemt_me_endpoint_quarantine_total 424
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 371
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
telemt_me_writers_active_current 45
telemt_desync_total 5899
telemt_desync_full_logged_total 1971
telemt_desync_suppressed_total 3928
telemt_desync_frames_bucket_total{bucket="1_2"} 1621
telemt_desync_frames_bucket_total{bucket="3_10"} 2179
telemt_desync_frames_bucket_total{bucket="gt_10"} 2099
telemt_pool_swap_total 51
telemt_pool_force_close_total 1260
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 17634
telemt_me_writer_removed_unexpected_total 534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1606
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16588
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16374
telemt_me_writer_teardown_success_total{mode="normal"} 18194
telemt_me_writer_teardown_noop_total 17635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35829
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.403205
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35829
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 133
telemt_me_writer_restored_same_endpoint_total 464
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1549988
telemt_user_connections_current{user="hello"} 3397
telemt_user_octets_from_client{user="hello"} 25199207987 (23.47 GB)
telemt_user_octets_to_client{user="hello"} 689052790463 (641.73 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1258
telemt_user_unique_ips_recent_window{user="hello"} 470
```