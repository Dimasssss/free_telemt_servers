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

# Server Metrics 2026-03-21 11:44:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 54488.2 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1669864
telemt_connections_bad_total 84634
telemt_connections_current 1563
telemt_connections_me_current 1563
telemt_handshake_timeouts_total 66517
telemt_upstream_connect_attempt_total 21281
telemt_upstream_connect_success_total 21174
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 21243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1088
telemt_me_reconnect_success_total 480
telemt_me_reader_eof_total 464
telemt_me_idle_close_by_peer_total 464
telemt_me_route_drop_no_conn_total 1010685
telemt_me_route_drop_channel_closed_total 392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1287168
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 381
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 432
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
telemt_me_writers_active_current 50
telemt_desync_total 5230
telemt_desync_full_logged_total 1844
telemt_desync_suppressed_total 3386
telemt_desync_frames_bucket_total{bucket="1_2"} 1106
telemt_desync_frames_bucket_total{bucket="3_10"} 2015
telemt_desync_frames_bucket_total{bucket="gt_10"} 2109
telemt_pool_swap_total 59
telemt_pool_force_close_total 1729
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 311
telemt_me_draining_writers_reap_progress_total 19015
telemt_me_writer_removed_unexpected_total 444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1560
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17758
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1665
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17286
telemt_me_writer_teardown_success_total{mode="normal"} 19318
telemt_me_writer_teardown_noop_total 19019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38337
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 125.725586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38337
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 311
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 418
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1286232
telemt_user_connections_current{user="hello"} 1563
telemt_user_octets_from_client{user="hello"} 18384803951 (17.12 GB)
telemt_user_octets_to_client{user="hello"} 352319463943 (328.12 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 593
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 133.3 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6238
telemt_connections_bad_total 196
telemt_connections_current 1080
telemt_connections_me_current 1080
telemt_handshake_timeouts_total 206
telemt_upstream_connect_attempt_total 128
telemt_upstream_connect_success_total 121
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 1579
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5115
telemt_me_endpoint_quarantine_total 6
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
telemt_me_writers_active_current 44
telemt_desync_total 14
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_draining_writers_reap_progress_total 44
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44
telemt_me_writer_teardown_success_total{mode="normal"} 44
telemt_me_writer_teardown_noop_total 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000553
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88
telemt_user_connections_total{user="hello"} 5115
telemt_user_connections_current{user="hello"} 1080
telemt_user_octets_from_client{user="hello"} 33573520 (32.02 MB)
telemt_user_octets_to_client{user="hello"} 1077702248 (1.00 GB)
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 54485.8 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3212621
telemt_connections_bad_total 346525
telemt_connections_current 4212
telemt_connections_me_current 4212
telemt_handshake_timeouts_total 117468
telemt_upstream_connect_attempt_total 20700
telemt_upstream_connect_success_total 20687
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 726
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 401
telemt_me_idle_close_by_peer_total 401
telemt_me_route_drop_no_conn_total 1391135
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2559376
telemt_me_endpoint_quarantine_total 356
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 422
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
telemt_me_writers_active_current 43
telemt_desync_total 11228
telemt_desync_full_logged_total 3776
telemt_desync_suppressed_total 7452
telemt_desync_frames_bucket_total{bucket="1_2"} 2366
telemt_desync_frames_bucket_total{bucket="3_10"} 4375
telemt_desync_frames_bucket_total{bucket="gt_10"} 4487
telemt_pool_swap_total 59
telemt_pool_force_close_total 1814
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 18852
telemt_me_writer_removed_unexpected_total 378
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1550
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17531
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1716
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17038
telemt_me_writer_teardown_success_total{mode="normal"} 19081
telemt_me_writer_teardown_noop_total 18866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37947
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.787604
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37947
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 344
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2555804
telemt_user_connections_current{user="hello"} 4212
telemt_user_octets_from_client{user="hello"} 42201994128 (39.30 GB)
telemt_user_octets_to_client{user="hello"} 927943174044 (864.21 GB)
telemt_user_unique_ips_current{user="hello"} 1662
telemt_user_unique_ips_recent_window{user="hello"} 520
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 54487.2 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2664963
telemt_connections_bad_total 296768
telemt_connections_current 3380
telemt_connections_me_current 3380
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 109873
telemt_upstream_connect_attempt_total 25611
telemt_upstream_connect_success_total 25352
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 25483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 1070
telemt_me_reconnect_success_total 499
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 784938
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1880588
telemt_me_endpoint_quarantine_total 367
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 421
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
telemt_me_writers_active_current 43
telemt_desync_total 8579
telemt_desync_full_logged_total 2944
telemt_desync_suppressed_total 5635
telemt_desync_frames_bucket_total{bucket="1_2"} 2142
telemt_desync_frames_bucket_total{bucket="3_10"} 3349
telemt_desync_frames_bucket_total{bucket="gt_10"} 3088
telemt_pool_swap_total 59
telemt_pool_force_close_total 1640
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 136
telemt_me_draining_writers_reap_progress_total 18573
telemt_me_writer_removed_unexpected_total 450
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1558
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17483
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1530
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16933
telemt_me_writer_teardown_success_total{mode="normal"} 19041
telemt_me_writer_teardown_noop_total 18574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.797847
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 136
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 418
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1882019
telemt_user_connections_current{user="hello"} 3380
telemt_user_octets_from_client{user="hello"} 36084298425 (33.61 GB)
telemt_user_octets_to_client{user="hello"} 904261706295 (842.16 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1351
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 54451.1 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2598077
telemt_connections_bad_total 292968
telemt_connections_current 3359
telemt_connections_me_current 3359
telemt_handshake_timeouts_total 77673
telemt_upstream_connect_attempt_total 22046
telemt_upstream_connect_success_total 21981
telemt_upstream_connect_attempts_per_request{bucket="1"} 21981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 790
telemt_me_reconnect_success_total 536
telemt_me_reader_eof_total 478
telemt_me_idle_close_by_peer_total 478
telemt_me_route_drop_no_conn_total 762650
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1874030
telemt_me_endpoint_quarantine_total 415
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 414
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
telemt_me_writers_active_current 43
telemt_desync_total 8807
telemt_desync_full_logged_total 2959
telemt_desync_suppressed_total 5848
telemt_desync_frames_bucket_total{bucket="1_2"} 2340
telemt_desync_frames_bucket_total{bucket="3_10"} 3343
telemt_desync_frames_bucket_total{bucket="gt_10"} 3124
telemt_pool_swap_total 58
telemt_pool_force_close_total 1617
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 19745
telemt_me_writer_removed_unexpected_total 453
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1582
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18649
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18128
telemt_me_writer_teardown_success_total{mode="normal"} 20231
telemt_me_writer_teardown_noop_total 19748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39979
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.983499
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39979
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 462
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1871135
telemt_user_connections_current{user="hello"} 3359
telemt_user_octets_from_client{user="hello"} 42612966680 (39.69 GB)
telemt_user_octets_to_client{user="hello"} 910430999328 (847.90 GB)
telemt_user_unique_ips_current{user="hello"} 1266
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 54490.3 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8323588
telemt_connections_bad_total 559227
telemt_connections_current 5560
telemt_connections_me_current 5560
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 291051
telemt_upstream_connect_attempt_total 63999
telemt_upstream_connect_success_total 60284
telemt_upstream_connect_fail_total 2946
telemt_upstream_connect_attempts_per_request{bucket="1"} 63230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2946
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3201
telemt_me_reconnect_success_total 1096
telemt_me_reader_eof_total 795
telemt_me_idle_close_by_peer_total 794
telemt_me_route_drop_no_conn_total 14658571
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6927980
telemt_me_endpoint_quarantine_total 425
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 121
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 121
telemt_me_single_endpoint_shadow_rotate_total 429
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 13177
telemt_desync_full_logged_total 4231
telemt_desync_suppressed_total 8946
telemt_desync_frames_bucket_total{bucket="1_2"} 2852
telemt_desync_frames_bucket_total{bucket="3_10"} 5815
telemt_desync_frames_bucket_total{bucket="gt_10"} 4510
telemt_pool_swap_total 55
telemt_pool_force_close_total 1724
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 18130
telemt_me_writer_removed_unexpected_total 1061
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2323
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16764
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1473
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16406
telemt_me_writer_teardown_success_total{mode="normal"} 19087
telemt_me_writer_teardown_noop_total 18139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37226
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.739238
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37226
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 6963602
telemt_user_connections_current{user="hello"} 5560
telemt_user_octets_from_client{user="hello"} 57165330148 (53.24 GB)
telemt_user_octets_to_client{user="hello"} 652974665611 (608.13 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1945
telemt_user_unique_ips_recent_window{user="hello"} 1079
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 54457.9 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2626199
telemt_connections_bad_total 322861
telemt_connections_current 3438
telemt_connections_me_current 3438
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 58038
telemt_upstream_connect_attempt_total 23520
telemt_upstream_connect_success_total 23259
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 23495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_reconnect_attempts_total 2306
telemt_me_reconnect_success_total 766
telemt_me_reader_eof_total 758
telemt_me_idle_close_by_peer_total 758
telemt_me_route_drop_no_conn_total 910116
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1985954
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 419
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
telemt_desync_total 9062
telemt_desync_full_logged_total 3259
telemt_desync_suppressed_total 5803
telemt_desync_frames_bucket_total{bucket="1_2"} 1757
telemt_desync_frames_bucket_total{bucket="3_10"} 3657
telemt_desync_frames_bucket_total{bucket="gt_10"} 3648
telemt_pool_swap_total 56
telemt_pool_force_close_total 1546
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 135
telemt_me_draining_writers_reap_progress_total 19569
telemt_me_writer_removed_unexpected_total 733
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1835
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18492
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1391
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 155
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18023
telemt_me_writer_teardown_success_total{mode="normal"} 20327
telemt_me_writer_teardown_noop_total 19569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39896
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.197037
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39896
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 135
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1971207
telemt_user_connections_current{user="hello"} 3438
telemt_user_octets_from_client{user="hello"} 35832637780 (33.37 GB)
telemt_user_octets_to_client{user="hello"} 879987306934 (819.55 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1380
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 54452.4 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3884026
telemt_connections_bad_total 201806
telemt_connections_current 3276
telemt_connections_me_current 3276
telemt_handshake_timeouts_total 1681165
telemt_upstream_connect_attempt_total 22061
telemt_upstream_connect_success_total 22027
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 22030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 799
telemt_me_reconnect_success_total 396
telemt_me_reader_eof_total 395
telemt_me_idle_close_by_peer_total 395
telemt_me_route_drop_no_conn_total 755654
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1760200
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 430
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
telemt_me_writers_active_current 45
telemt_desync_total 8667
telemt_desync_full_logged_total 3079
telemt_desync_suppressed_total 5588
telemt_desync_frames_bucket_total{bucket="1_2"} 1590
telemt_desync_frames_bucket_total{bucket="3_10"} 3463
telemt_desync_frames_bucket_total{bucket="gt_10"} 3614
telemt_pool_swap_total 59
telemt_pool_force_close_total 1491
telemt_me_writer_close_signal_drop_total 124
telemt_me_draining_writers_reap_progress_total 19749
telemt_me_writer_removed_unexpected_total 383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1331
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18822
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1442
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18258
telemt_me_writer_teardown_success_total{mode="normal"} 20153
telemt_me_writer_teardown_noop_total 19749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39902
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.095145
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39902
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 124
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 347
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 1754003
telemt_user_connections_current{user="hello"} 3276
telemt_user_octets_from_client{user="hello"} 31360945168 (29.21 GB)
telemt_user_octets_to_client{user="hello"} 848100705116 (789.86 GB)
telemt_user_unique_ips_current{user="hello"} 1322
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 52443.8 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814183
telemt_connections_bad_total 56914
telemt_connections_current 661
telemt_connections_me_current 661
telemt_handshake_timeouts_total 296244
telemt_upstream_connect_attempt_total 25216
telemt_upstream_connect_success_total 25214
telemt_upstream_connect_attempts_per_request{bucket="1"} 25214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1084
telemt_me_reconnect_success_total 417
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 412
telemt_me_route_drop_no_conn_total 174094
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398243
telemt_me_endpoint_quarantine_total 488
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 448
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
telemt_desync_total 2767
telemt_desync_full_logged_total 1058
telemt_desync_suppressed_total 1709
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 1005
telemt_desync_frames_bucket_total{bucket="gt_10"} 1324
telemt_pool_swap_total 58
telemt_pool_force_close_total 1291
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 22585
telemt_me_writer_removed_unexpected_total 392
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1648
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21334
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1288
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21294
telemt_me_writer_teardown_success_total{mode="normal"} 22982
telemt_me_writer_teardown_noop_total 22585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45567
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.596808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45567
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 337
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 398115
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 6424321863 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 153437295289 (142.90 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 54462.3 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2778162
telemt_connections_bad_total 258246
telemt_connections_current 3977
telemt_connections_me_current 3977
telemt_handshake_timeouts_total 73166
telemt_upstream_connect_attempt_total 22855
telemt_upstream_connect_success_total 22759
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 22824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 933
telemt_me_reconnect_success_total 516
telemt_me_reader_eof_total 482
telemt_me_idle_close_by_peer_total 482
telemt_me_route_drop_no_conn_total 739449
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2199938
telemt_me_endpoint_quarantine_total 422
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 427
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
telemt_me_writers_active_current 44
telemt_desync_total 8786
telemt_desync_full_logged_total 2916
telemt_desync_suppressed_total 5870
telemt_desync_frames_bucket_total{bucket="1_2"} 2093
telemt_desync_frames_bucket_total{bucket="3_10"} 3274
telemt_desync_frames_bucket_total{bucket="gt_10"} 3419
telemt_pool_swap_total 60
telemt_pool_force_close_total 1506
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 20541
telemt_me_writer_removed_unexpected_total 474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1576
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19455
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1479
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19035
telemt_me_writer_teardown_success_total{mode="normal"} 21031
telemt_me_writer_teardown_noop_total 20541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41572
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.504379
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41572
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 461
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2193343
telemt_user_connections_current{user="hello"} 3977
telemt_user_octets_from_client{user="hello"} 46011067364 (42.85 GB)
telemt_user_octets_to_client{user="hello"} 1025812893348 (955.36 GB)
telemt_user_unique_ips_current{user="hello"} 1430
telemt_user_unique_ips_recent_window{user="hello"} 526
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 54459.1 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2547034
telemt_connections_bad_total 201172
telemt_connections_current 3589
telemt_connections_me_current 3589
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 68731
telemt_upstream_connect_attempt_total 39002
telemt_upstream_connect_success_total 38764
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 38959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_reconnect_attempts_total 3245
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 744906
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2047645
telemt_me_endpoint_quarantine_total 470
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 425
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
telemt_me_writers_active_current 46
telemt_desync_total 7701
telemt_desync_full_logged_total 2637
telemt_desync_suppressed_total 5064
telemt_desync_frames_bucket_total{bucket="1_2"} 2017
telemt_desync_frames_bucket_total{bucket="3_10"} 2863
telemt_desync_frames_bucket_total{bucket="gt_10"} 2821
telemt_pool_swap_total 59
telemt_pool_force_close_total 1461
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 19706
telemt_me_writer_removed_unexpected_total 597
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1844
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18487
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1369
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18245
telemt_me_writer_teardown_success_total{mode="normal"} 20331
telemt_me_writer_teardown_noop_total 19707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40038
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.276586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40038
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 507
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2058386
telemt_user_connections_current{user="hello"} 3589
telemt_user_octets_from_client{user="hello"} 37475198933 (34.90 GB)
telemt_user_octets_to_client{user="hello"} 905361525008 (843.18 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1376
telemt_user_unique_ips_recent_window{user="hello"} 484
```