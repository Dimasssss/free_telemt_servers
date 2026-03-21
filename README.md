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

# Server Metrics 2026-03-21 11:18:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 52958.4 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1602666
telemt_connections_bad_total 79918
telemt_connections_current 1843
telemt_connections_me_current 1843
telemt_handshake_timeouts_total 63818
telemt_upstream_connect_attempt_total 20706
telemt_upstream_connect_success_total 20600
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 20668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13186
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1039
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 448
telemt_me_idle_close_by_peer_total 448
telemt_me_route_drop_no_conn_total 971157
telemt_me_route_drop_channel_closed_total 364
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1231526
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 371
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 420
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
telemt_desync_total 4992
telemt_desync_full_logged_total 1748
telemt_desync_suppressed_total 3244
telemt_desync_frames_bucket_total{bucket="1_2"} 1046
telemt_desync_frames_bucket_total{bucket="3_10"} 1934
telemt_desync_frames_bucket_total{bucket="gt_10"} 2012
telemt_pool_swap_total 57
telemt_pool_force_close_total 1669
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 297
telemt_me_draining_writers_reap_progress_total 18497
telemt_me_writer_removed_unexpected_total 428
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1509
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17275
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1608
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16828
telemt_me_writer_teardown_success_total{mode="normal"} 18784
telemt_me_writer_teardown_noop_total 18501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37285
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 120.747760
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37285
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 297
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 397
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 1230645
telemt_user_connections_current{user="hello"} 1843
telemt_user_octets_from_client{user="hello"} 17217727123 (16.04 GB)
telemt_user_octets_to_client{user="hello"} 338376244691 (315.14 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 321
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 849.6 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86673
telemt_connections_bad_total 3518
telemt_connections_current 3058
telemt_connections_me_current 3058
telemt_handshake_timeouts_total 2609
telemt_upstream_connect_attempt_total 288
telemt_upstream_connect_success_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 2
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 65344
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76251
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 7
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
telemt_me_writers_active_current 46
telemt_desync_total 282
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 180
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 177
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 179
telemt_me_writer_teardown_success_total{mode="normal"} 182
telemt_me_writer_teardown_noop_total 180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.035478
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 362
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 76243
telemt_user_connections_current{user="hello"} 3058
telemt_user_octets_from_client{user="hello"} 858083256 (818.33 MB)
telemt_user_octets_to_client{user="hello"} 15750390956 (14.67 GB)
telemt_user_unique_ips_current{user="hello"} 1605
telemt_user_unique_ips_recent_window{user="hello"} 513
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 52956.3 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3053505
telemt_connections_bad_total 331987
telemt_connections_current 3838
telemt_connections_me_current 3838
telemt_handshake_timeouts_total 110076
telemt_upstream_connect_attempt_total 20198
telemt_upstream_connect_success_total 20184
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 690
telemt_me_reconnect_success_total 385
telemt_me_reader_eof_total 396
telemt_me_idle_close_by_peer_total 396
telemt_me_route_drop_no_conn_total 1322925
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2429281
telemt_me_endpoint_quarantine_total 347
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 411
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
telemt_me_writers_active_current 45
telemt_desync_total 10601
telemt_desync_full_logged_total 3586
telemt_desync_suppressed_total 7015
telemt_desync_frames_bucket_total{bucket="1_2"} 2203
telemt_desync_frames_bucket_total{bucket="3_10"} 4173
telemt_desync_frames_bucket_total{bucket="gt_10"} 4225
telemt_pool_swap_total 57
telemt_pool_force_close_total 1743
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 18367
telemt_me_writer_removed_unexpected_total 373
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1512
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17088
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16624
telemt_me_writer_teardown_success_total{mode="normal"} 18600
telemt_me_writer_teardown_noop_total 18380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36980
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.042638
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36980
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 2425861
telemt_user_connections_current{user="hello"} 3838
telemt_user_octets_from_client{user="hello"} 39645259068 (36.92 GB)
telemt_user_octets_to_client{user="hello"} 887763228056 (826.79 GB)
telemt_user_unique_ips_current{user="hello"} 1492
telemt_user_unique_ips_recent_window{user="hello"} 542
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 52957.8 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2527360
telemt_connections_bad_total 281433
telemt_connections_current 3532
telemt_connections_me_current 3532
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 105233
telemt_upstream_connect_attempt_total 25174
telemt_upstream_connect_success_total 24919
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 25049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 428
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1066
telemt_me_reconnect_success_total 494
telemt_me_reader_eof_total 453
telemt_me_idle_close_by_peer_total 453
telemt_me_route_drop_no_conn_total 736675
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1780882
telemt_me_endpoint_quarantine_total 358
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 409
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
telemt_me_writers_active_current 47
telemt_desync_total 8169
telemt_desync_full_logged_total 2799
telemt_desync_suppressed_total 5370
telemt_desync_frames_bucket_total{bucket="1_2"} 2028
telemt_desync_frames_bucket_total{bucket="3_10"} 3203
telemt_desync_frames_bucket_total{bucket="gt_10"} 2938
telemt_pool_swap_total 57
telemt_pool_force_close_total 1572
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 18180
telemt_me_writer_removed_unexpected_total 445
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1514
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17127
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16608
telemt_me_writer_teardown_success_total{mode="normal"} 18641
telemt_me_writer_teardown_noop_total 18181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36822
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.875745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36822
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 414
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1782451
telemt_user_connections_current{user="hello"} 3532
telemt_user_octets_from_client{user="hello"} 34019452009 (31.68 GB)
telemt_user_octets_to_client{user="hello"} 855958978943 (797.17 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1416
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 52921.6 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2466685
telemt_connections_bad_total 279926
telemt_connections_current 3217
telemt_connections_me_current 3217
telemt_handshake_timeouts_total 73017
telemt_upstream_connect_attempt_total 21557
telemt_upstream_connect_success_total 21503
telemt_upstream_connect_attempts_per_request{bucket="1"} 21503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 783
telemt_me_reconnect_success_total 529
telemt_me_reader_eof_total 470
telemt_me_idle_close_by_peer_total 470
telemt_me_route_drop_no_conn_total 717318
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1774299
telemt_me_endpoint_quarantine_total 408
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 403
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
telemt_me_writers_active_current 46
telemt_desync_total 8344
telemt_desync_full_logged_total 2834
telemt_desync_suppressed_total 5510
telemt_desync_frames_bucket_total{bucket="1_2"} 2213
telemt_desync_frames_bucket_total{bucket="3_10"} 3182
telemt_desync_frames_bucket_total{bucket="gt_10"} 2949
telemt_pool_swap_total 56
telemt_pool_force_close_total 1551
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 19315
telemt_me_writer_removed_unexpected_total 446
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1531
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18262
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1436
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17764
telemt_me_writer_teardown_success_total{mode="normal"} 19793
telemt_me_writer_teardown_noop_total 19318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39111
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.379408
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39111
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1771575
telemt_user_connections_current{user="hello"} 3217
telemt_user_octets_from_client{user="hello"} 40515969940 (37.73 GB)
telemt_user_octets_to_client{user="hello"} 863414083076 (804.12 GB)
telemt_user_unique_ips_current{user="hello"} 1237
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 52961.0 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7808859
telemt_connections_bad_total 529123
telemt_connections_current 5019
telemt_connections_me_current 5019
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 276246
telemt_upstream_connect_attempt_total 63533
telemt_upstream_connect_success_total 59836
telemt_upstream_connect_fail_total 2943
telemt_upstream_connect_attempts_per_request{bucket="1"} 62779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2943
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3161
telemt_me_reconnect_success_total 1089
telemt_me_reader_eof_total 786
telemt_me_idle_close_by_peer_total 785
telemt_me_route_drop_no_conn_total 13465068
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6500543
telemt_me_endpoint_quarantine_total 414
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 121
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 121
telemt_me_single_endpoint_shadow_rotate_total 416
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 12452
telemt_desync_full_logged_total 3991
telemt_desync_suppressed_total 8461
telemt_desync_frames_bucket_total{bucket="1_2"} 2706
telemt_desync_frames_bucket_total{bucket="3_10"} 5478
telemt_desync_frames_bucket_total{bucket="gt_10"} 4268
telemt_pool_swap_total 53
telemt_pool_force_close_total 1661
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 17706
telemt_me_writer_removed_unexpected_total 1052
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2275
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16379
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16045
telemt_me_writer_teardown_success_total{mode="normal"} 18654
telemt_me_writer_teardown_noop_total 17715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36369
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.435261
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36369
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 765
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 6536363
telemt_user_connections_current{user="hello"} 5019
telemt_user_octets_from_client{user="hello"} 55006128252 (51.23 GB)
telemt_user_octets_to_client{user="hello"} 635389145047 (591.75 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1865
telemt_user_unique_ips_recent_window{user="hello"} 1050
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 52928.6 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2469094
telemt_connections_bad_total 294555
telemt_connections_current 3644
telemt_connections_me_current 3644
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 53428
telemt_upstream_connect_attempt_total 22998
telemt_upstream_connect_success_total 22759
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 22973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_reconnect_attempts_total 2208
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 741
telemt_me_idle_close_by_peer_total 741
telemt_me_route_drop_no_conn_total 847316
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1872543
telemt_me_endpoint_quarantine_total 337
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 407
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
telemt_me_writers_active_current 45
telemt_desync_total 8622
telemt_desync_full_logged_total 3112
telemt_desync_suppressed_total 5510
telemt_desync_frames_bucket_total{bucket="1_2"} 1657
telemt_desync_frames_bucket_total{bucket="3_10"} 3480
telemt_desync_frames_bucket_total{bucket="gt_10"} 3485
telemt_pool_swap_total 54
telemt_pool_force_close_total 1482
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 19126
telemt_me_writer_removed_unexpected_total 718
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1790
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18077
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 148
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17644
telemt_me_writer_teardown_success_total{mode="normal"} 19867
telemt_me_writer_teardown_noop_total 19126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38993
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.902528
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38993
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 626
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 1858226
telemt_user_connections_current{user="hello"} 3644
telemt_user_octets_from_client{user="hello"} 33893184908 (31.57 GB)
telemt_user_octets_to_client{user="hello"} 838071082682 (780.51 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1427
telemt_user_unique_ips_recent_window{user="hello"} 522
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 52923.3 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3646680
telemt_connections_bad_total 192480
telemt_connections_current 3422
telemt_connections_me_current 3422
telemt_handshake_timeouts_total 1559450
telemt_upstream_connect_attempt_total 21542
telemt_upstream_connect_success_total 21508
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 754
telemt_me_reconnect_success_total 387
telemt_me_reader_eof_total 385
telemt_me_idle_close_by_peer_total 385
telemt_me_route_drop_no_conn_total 697298
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1664504
telemt_me_endpoint_quarantine_total 403
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 416
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
telemt_me_writers_active_current 83
telemt_desync_total 8118
telemt_desync_full_logged_total 2906
telemt_desync_suppressed_total 5212
telemt_desync_frames_bucket_total{bucket="1_2"} 1475
telemt_desync_frames_bucket_total{bucket="3_10"} 3229
telemt_desync_frames_bucket_total{bucket="gt_10"} 3414
telemt_pool_swap_total 57
telemt_pool_force_close_total 1407
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 19220
telemt_me_writer_removed_unexpected_total 373
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1283
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18331
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1386
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17813
telemt_me_writer_teardown_success_total{mode="normal"} 19614
telemt_me_writer_teardown_noop_total 19220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.033396
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1659750
telemt_user_connections_current{user="hello"} 3422
telemt_user_octets_from_client{user="hello"} 29553945200 (27.52 GB)
telemt_user_octets_to_client{user="hello"} 805909093164 (750.56 GB)
telemt_user_unique_ips_current{user="hello"} 1432
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 50914.4 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 753343
telemt_connections_bad_total 36219
telemt_connections_current 658
telemt_connections_me_current 658
telemt_handshake_timeouts_total 277875
telemt_upstream_connect_attempt_total 24538
telemt_upstream_connect_success_total 24536
telemt_upstream_connect_attempts_per_request{bucket="1"} 24536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1073
telemt_me_reconnect_success_total 406
telemt_me_reader_eof_total 401
telemt_me_idle_close_by_peer_total 401
telemt_me_route_drop_no_conn_total 158770
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378563
telemt_me_endpoint_quarantine_total 479
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 437
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
telemt_desync_total 2560
telemt_desync_full_logged_total 991
telemt_desync_suppressed_total 1569
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 920
telemt_desync_frames_bucket_total{bucket="gt_10"} 1227
telemt_pool_swap_total 56
telemt_pool_force_close_total 1242
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 21959
telemt_me_writer_removed_unexpected_total 382
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1607
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20738
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20717
telemt_me_writer_teardown_success_total{mode="normal"} 22345
telemt_me_writer_teardown_noop_total 21959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44304
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.456929
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44304
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 328
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 378648
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 5519637139 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 146467928489 (136.41 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 52932.8 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2625332
telemt_connections_bad_total 245035
telemt_connections_current 4252
telemt_connections_me_current 4252
telemt_handshake_timeouts_total 63192
telemt_upstream_connect_attempt_total 22360
telemt_upstream_connect_success_total 22266
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 22330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 920
telemt_me_reconnect_success_total 504
telemt_me_reader_eof_total 470
telemt_me_idle_close_by_peer_total 470
telemt_me_route_drop_no_conn_total 694786
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2077107
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 415
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
telemt_desync_total 8239
telemt_desync_full_logged_total 2750
telemt_desync_suppressed_total 5489
telemt_desync_frames_bucket_total{bucket="1_2"} 1978
telemt_desync_frames_bucket_total{bucket="3_10"} 3082
telemt_desync_frames_bucket_total{bucket="gt_10"} 3179
telemt_pool_swap_total 58
telemt_pool_force_close_total 1450
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 20100
telemt_me_writer_removed_unexpected_total 462
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1530
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19048
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1426
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18650
telemt_me_writer_teardown_success_total{mode="normal"} 20578
telemt_me_writer_teardown_noop_total 20100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40678
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.369089
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40678
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 449
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2070883
telemt_user_connections_current{user="hello"} 4252
telemt_user_octets_from_client{user="hello"} 43853448984 (40.84 GB)
telemt_user_octets_to_client{user="hello"} 971347913540 (904.64 GB)
telemt_user_unique_ips_current{user="hello"} 1520
telemt_user_unique_ips_recent_window{user="hello"} 583
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 52929.6 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2402972
telemt_connections_bad_total 189159
telemt_connections_current 3730
telemt_connections_me_current 3730
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 62200
telemt_upstream_connect_attempt_total 38487
telemt_upstream_connect_success_total 38255
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 38444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 581
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 3158
telemt_me_reconnect_success_total 654
telemt_me_reader_eof_total 572
telemt_me_idle_close_by_peer_total 572
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 699738
telemt_me_route_drop_channel_closed_total 49
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1942353
telemt_me_endpoint_quarantine_total 460
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 411
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
telemt_me_writers_active_current 46
telemt_desync_total 7306
telemt_desync_full_logged_total 2494
telemt_desync_suppressed_total 4812
telemt_desync_frames_bucket_total{bucket="1_2"} 1909
telemt_desync_frames_bucket_total{bucket="3_10"} 2716
telemt_desync_frames_bucket_total{bucket="gt_10"} 2681
telemt_pool_swap_total 57
telemt_pool_force_close_total 1404
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 19247
telemt_me_writer_removed_unexpected_total 583
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1790
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18067
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1316
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17843
telemt_me_writer_teardown_success_total{mode="normal"} 19857
telemt_me_writer_teardown_noop_total 19248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39105
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.735911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39105
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 499
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1953298
telemt_user_connections_current{user="hello"} 3730
telemt_user_octets_from_client{user="hello"} 35127207709 (32.71 GB)
telemt_user_octets_to_client{user="hello"} 859922831184 (800.87 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1413
telemt_user_unique_ips_recent_window{user="hello"} 553
```