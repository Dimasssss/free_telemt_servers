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

# Server Metrics 2026-03-21 07:19:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 38587.9 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 874433
telemt_connections_bad_total 46844
telemt_connections_current 1536
telemt_connections_me_current 1536
telemt_handshake_timeouts_total 41530
telemt_upstream_connect_attempt_total 15447
telemt_upstream_connect_success_total 15377
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 15424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 486
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 260
telemt_me_idle_close_by_peer_total 260
telemt_me_route_drop_no_conn_total 282883
telemt_me_route_drop_channel_closed_total 103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642301
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 271
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 316
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
telemt_desync_total 2811
telemt_desync_full_logged_total 1014
telemt_desync_suppressed_total 1797
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 1099
telemt_desync_frames_bucket_total{bucket="gt_10"} 1125
telemt_pool_swap_total 42
telemt_pool_force_close_total 1156
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 13926
telemt_me_writer_removed_unexpected_total 244
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1026
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13102
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12770
telemt_me_writer_teardown_success_total{mode="normal"} 14128
telemt_me_writer_teardown_noop_total 13927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28055
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.431269
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28055
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 641553
telemt_user_connections_current{user="hello"} 1536
telemt_user_octets_from_client{user="hello"} 7668358432 (7.14 GB)
telemt_user_octets_to_client{user="hello"} 202991619500 (189.05 GB)
telemt_user_unique_ips_current{user="hello"} 529
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 38589.1 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2170360
telemt_connections_bad_total 240517
telemt_connections_current 3862
telemt_connections_me_current 3862
telemt_handshake_timeouts_total 66377
telemt_upstream_connect_attempt_total 14383
telemt_upstream_connect_success_total 14316
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 14362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 858
telemt_me_reconnect_success_total 288
telemt_me_reader_eof_total 297
telemt_me_idle_close_by_peer_total 296
telemt_me_route_drop_no_conn_total 454432
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1330957
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 307
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
telemt_me_writers_active_current 44
telemt_desync_total 5743
telemt_desync_full_logged_total 2013
telemt_desync_suppressed_total 3730
telemt_desync_frames_bucket_total{bucket="1_2"} 1168
telemt_desync_frames_bucket_total{bucket="3_10"} 2260
telemt_desync_frames_bucket_total{bucket="gt_10"} 2315
telemt_pool_swap_total 41
telemt_pool_force_close_total 1221
telemt_me_writer_close_signal_drop_total 125
telemt_me_draining_writers_reap_progress_total 12907
telemt_me_writer_removed_unexpected_total 278
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12038
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1165
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11686
telemt_me_writer_teardown_success_total{mode="normal"} 13177
telemt_me_writer_teardown_noop_total 12907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26084
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.615033
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26084
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 125
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 240
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1327868
telemt_user_connections_current{user="hello"} 3862
telemt_user_octets_from_client{user="hello"} 18434783800 (17.17 GB)
telemt_user_octets_to_client{user="hello"} 546388623180 (508.86 GB)
telemt_user_unique_ips_current{user="hello"} 1481
telemt_user_unique_ips_recent_window{user="hello"} 557
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 38585.3 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1466785
telemt_connections_bad_total 164461
telemt_connections_current 3390
telemt_connections_me_current 3390
telemt_handshake_timeouts_total 66005
telemt_upstream_connect_attempt_total 15518
telemt_upstream_connect_success_total 15508
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 482
telemt_me_reconnect_success_total 252
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 383321
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1144198
telemt_me_endpoint_quarantine_total 271
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 307
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
telemt_me_writers_active_current 45
telemt_desync_total 4614
telemt_desync_full_logged_total 1660
telemt_desync_suppressed_total 2954
telemt_desync_frames_bucket_total{bucket="1_2"} 1022
telemt_desync_frames_bucket_total{bucket="3_10"} 1770
telemt_desync_frames_bucket_total{bucket="gt_10"} 1822
telemt_pool_swap_total 42
telemt_pool_force_close_total 1182
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 14143
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1096
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13204
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1168
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12961
telemt_me_writer_teardown_success_total{mode="normal"} 14300
telemt_me_writer_teardown_noop_total 14146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28446
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.567852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28446
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 215
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1141901
telemt_user_connections_current{user="hello"} 3390
telemt_user_octets_from_client{user="hello"} 15774037564 (14.69 GB)
telemt_user_octets_to_client{user="hello"} 505474951952 (470.76 GB)
telemt_user_unique_ips_current{user="hello"} 1319
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 38587.2 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1273132
telemt_connections_bad_total 158757
telemt_connections_current 2588
telemt_connections_me_current 2588
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 59265
telemt_upstream_connect_attempt_total 20358
telemt_upstream_connect_success_total 20136
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 718
telemt_me_reconnect_success_total 308
telemt_me_reader_eof_total 294
telemt_me_idle_close_by_peer_total 294
telemt_me_route_drop_no_conn_total 361355
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 878415
telemt_me_endpoint_quarantine_total 279
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 311
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
telemt_desync_total 4052
telemt_desync_full_logged_total 1450
telemt_desync_suppressed_total 2602
telemt_desync_frames_bucket_total{bucket="1_2"} 925
telemt_desync_frames_bucket_total{bucket="3_10"} 1703
telemt_desync_frames_bucket_total{bucket="gt_10"} 1424
telemt_pool_swap_total 42
telemt_pool_force_close_total 1073
telemt_me_writer_close_signal_drop_total 57
telemt_me_draining_writers_reap_progress_total 13994
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1066
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13228
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1050
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12921
telemt_me_writer_teardown_success_total{mode="normal"} 14294
telemt_me_writer_teardown_noop_total 13995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28289
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.498098
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28289
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 57
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 259
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 881367
telemt_user_connections_current{user="hello"} 2588
telemt_user_octets_from_client{user="hello"} 15140028117 (14.10 GB)
telemt_user_octets_to_client{user="hello"} 411471533811 (383.21 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1035
telemt_user_unique_ips_recent_window{user="hello"} 378
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 38550.5 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1221499
telemt_connections_bad_total 148771
telemt_connections_current 2855
telemt_connections_me_current 2855
telemt_handshake_timeouts_total 43897
telemt_upstream_connect_attempt_total 16254
telemt_upstream_connect_success_total 16245
telemt_upstream_connect_attempts_per_request{bucket="1"} 16245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 283
telemt_me_reconnect_success_total 239
telemt_me_reader_eof_total 235
telemt_me_idle_close_by_peer_total 235
telemt_me_route_drop_no_conn_total 258037
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 868854
telemt_me_endpoint_quarantine_total 313
telemt_me_single_endpoint_shadow_rotate_total 306
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
telemt_me_writers_active_current 45
telemt_desync_total 4173
telemt_desync_full_logged_total 1513
telemt_desync_suppressed_total 2660
telemt_desync_frames_bucket_total{bucket="1_2"} 1032
telemt_desync_frames_bucket_total{bucket="3_10"} 1620
telemt_desync_frames_bucket_total{bucket="gt_10"} 1521
telemt_pool_swap_total 42
telemt_pool_force_close_total 1048
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 71
telemt_me_draining_writers_reap_progress_total 14744
telemt_me_writer_removed_unexpected_total 216
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 970
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14010
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1038
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13696
telemt_me_writer_teardown_success_total{mode="normal"} 14980
telemt_me_writer_teardown_noop_total 14745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29725
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.658981
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29725
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 71
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 867280
telemt_user_connections_current{user="hello"} 2855
telemt_user_octets_from_client{user="hello"} 22056611504 (20.54 GB)
telemt_user_octets_to_client{user="hello"} 451496515572 (420.49 GB)
telemt_user_unique_ips_current{user="hello"} 1064
telemt_user_unique_ips_recent_window{user="hello"} 360
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 38589.9 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2792504
telemt_connections_bad_total 182353
telemt_connections_current 4764
telemt_connections_me_current 4764
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 165334
telemt_upstream_connect_attempt_total 41745
telemt_upstream_connect_success_total 39852
telemt_upstream_connect_fail_total 1350
telemt_upstream_connect_attempts_per_request{bucket="1"} 41202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1350
telemt_me_reconnect_attempts_total 1950
telemt_me_reconnect_success_total 654
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 411
telemt_me_route_drop_no_conn_total 2880488
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2244952
telemt_me_endpoint_quarantine_total 310
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 312
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
telemt_me_writers_active_current 46
telemt_desync_total 5427
telemt_desync_full_logged_total 1961
telemt_desync_suppressed_total 3466
telemt_desync_frames_bucket_total{bucket="1_2"} 1233
telemt_desync_frames_bucket_total{bucket="3_10"} 2291
telemt_desync_frames_bucket_total{bucket="gt_10"} 1903
telemt_pool_swap_total 41
telemt_pool_force_close_total 1145
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 13072
telemt_me_writer_removed_unexpected_total 628
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1525
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12144
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1074
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11927
telemt_me_writer_teardown_success_total{mode="normal"} 13669
telemt_me_writer_teardown_noop_total 13076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26745
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.829617
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26745
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 412
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 2267536
telemt_user_connections_current{user="hello"} 4764
telemt_user_octets_from_client{user="hello"} 35021760954 (32.62 GB)
telemt_user_octets_to_client{user="hello"} 476053969678 (443.36 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1719
telemt_user_unique_ips_recent_window{user="hello"} 834
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 38557.4 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1302391
telemt_connections_bad_total 189100
telemt_connections_current 3128
telemt_connections_me_current 3128
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 27390
telemt_upstream_connect_attempt_total 18022
telemt_upstream_connect_success_total 17863
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 18007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_reconnect_attempts_total 1628
telemt_me_reconnect_success_total 502
telemt_me_reader_eof_total 516
telemt_me_idle_close_by_peer_total 516
telemt_me_route_drop_no_conn_total 323715
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940546
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 308
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
telemt_me_writers_active_current 127
telemt_desync_total 3950
telemt_desync_full_logged_total 1500
telemt_desync_suppressed_total 2450
telemt_desync_frames_bucket_total{bucket="1_2"} 760
telemt_desync_frames_bucket_total{bucket="3_10"} 1594
telemt_desync_frames_bucket_total{bucket="gt_10"} 1596
telemt_pool_swap_total 40
telemt_pool_force_close_total 956
telemt_me_writer_close_signal_drop_total 60
telemt_me_draining_writers_reap_progress_total 14722
telemt_me_writer_removed_unexpected_total 496
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13986
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13766
telemt_me_writer_teardown_success_total{mode="normal"} 15238
telemt_me_writer_teardown_noop_total 14722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29960
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.070538
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29960
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 60
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 423
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 938163
telemt_user_connections_current{user="hello"} 3128
telemt_user_octets_from_client{user="hello"} 15699622156 (14.62 GB)
telemt_user_octets_to_client{user="hello"} 462258113398 (430.51 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1268
telemt_user_unique_ips_recent_window{user="hello"} 391
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 38552.1 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1677586
telemt_connections_bad_total 110277
telemt_connections_current 2356
telemt_connections_me_current 2356
telemt_handshake_timeouts_total 611780
telemt_upstream_connect_attempt_total 16895
telemt_upstream_connect_success_total 16867
telemt_upstream_connect_attempts_per_request{bucket="1"} 16867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 266
telemt_me_reconnect_attempts_total 357
telemt_me_reconnect_success_total 248
telemt_me_reader_eof_total 258
telemt_me_idle_close_by_peer_total 258
telemt_me_route_drop_no_conn_total 289964
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837942
telemt_me_endpoint_quarantine_total 326
telemt_me_single_endpoint_shadow_rotate_total 312
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
telemt_me_writers_active_current 44
telemt_desync_total 3894
telemt_desync_full_logged_total 1382
telemt_desync_suppressed_total 2512
telemt_desync_frames_bucket_total{bucket="1_2"} 693
telemt_desync_frames_bucket_total{bucket="3_10"} 1594
telemt_desync_frames_bucket_total{bucket="gt_10"} 1607
telemt_pool_swap_total 42
telemt_pool_force_close_total 975
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 15145
telemt_me_writer_removed_unexpected_total 241
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 898
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14506
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 967
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14170
telemt_me_writer_teardown_success_total{mode="normal"} 15404
telemt_me_writer_teardown_noop_total 15145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30549
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.547300
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30549
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 834913
telemt_user_connections_current{user="hello"} 2356
telemt_user_octets_from_client{user="hello"} 13913791880 (12.96 GB)
telemt_user_octets_to_client{user="hello"} 428397283188 (398.98 GB)
telemt_user_unique_ips_current{user="hello"} 987
telemt_user_unique_ips_recent_window{user="hello"} 429
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 36543.3 (10h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326650
telemt_connections_bad_total 11830
telemt_connections_current 495
telemt_connections_me_current 495
telemt_handshake_timeouts_total 90408
telemt_upstream_connect_attempt_total 18447
telemt_upstream_connect_success_total 18446
telemt_upstream_connect_attempts_per_request{bucket="1"} 18446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 687
telemt_me_reconnect_success_total 289
telemt_me_reader_eof_total 291
telemt_me_idle_close_by_peer_total 291
telemt_me_route_drop_no_conn_total 77174
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203657
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 317
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
telemt_me_writers_active_current 43
telemt_desync_total 1239
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 664
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 40
telemt_pool_force_close_total 824
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 48
telemt_me_draining_writers_reap_progress_total 16461
telemt_me_writer_removed_unexpected_total 274
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1149
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15588
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 824
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15637
telemt_me_writer_teardown_success_total{mode="normal"} 16737
telemt_me_writer_teardown_noop_total 16461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33198
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.204936
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33198
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 48
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 203861
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 2293195331 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 87561177209 (81.55 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 38561.9 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1323383
telemt_connections_bad_total 97798
telemt_connections_current 3291
telemt_connections_me_current 3291
telemt_handshake_timeouts_total 35313
telemt_upstream_connect_attempt_total 17341
telemt_upstream_connect_success_total 17261
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 17312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 592
telemt_me_reconnect_success_total 347
telemt_me_reader_eof_total 330
telemt_me_idle_close_by_peer_total 330
telemt_me_route_drop_no_conn_total 294156
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1037764
telemt_me_endpoint_quarantine_total 317
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 309
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
telemt_me_writers_active_current 44
telemt_desync_total 4075
telemt_desync_full_logged_total 1364
telemt_desync_suppressed_total 2711
telemt_desync_frames_bucket_total{bucket="1_2"} 1056
telemt_desync_frames_bucket_total{bucket="3_10"} 1528
telemt_desync_frames_bucket_total{bucket="gt_10"} 1491
telemt_pool_swap_total 42
telemt_pool_force_close_total 991
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 80
telemt_me_draining_writers_reap_progress_total 15658
telemt_me_writer_removed_unexpected_total 331
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1094
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14902
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 986
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14667
telemt_me_writer_teardown_success_total{mode="normal"} 15996
telemt_me_writer_teardown_noop_total 15658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.632185
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 80
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 316
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 1033264
telemt_user_connections_current{user="hello"} 3291
telemt_user_octets_from_client{user="hello"} 16696407916 (15.55 GB)
telemt_user_octets_to_client{user="hello"} 472130688244 (439.71 GB)
telemt_user_unique_ips_current{user="hello"} 1224
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 38558.6 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1263156
telemt_connections_bad_total 91004
telemt_connections_current 2933
telemt_connections_me_current 2933
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 32627
telemt_upstream_connect_attempt_total 25886
telemt_upstream_connect_success_total 25703
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 25846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_reconnect_attempts_total 2540
telemt_me_reconnect_success_total 466
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 406
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 298255
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1005130
telemt_me_endpoint_quarantine_total 382
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 306
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
telemt_desync_total 4011
telemt_desync_full_logged_total 1249
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1170
telemt_desync_frames_bucket_total{bucket="3_10"} 1469
telemt_desync_frames_bucket_total{bucket="gt_10"} 1372
telemt_pool_swap_total 42
telemt_pool_force_close_total 961
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 14865
telemt_me_writer_removed_unexpected_total 418
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1297
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14008
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13904
telemt_me_writer_teardown_success_total{mode="normal"} 15305
telemt_me_writer_teardown_noop_total 14865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30170
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.503846
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30170
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 118
telemt_me_writer_restored_same_endpoint_total 346
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1009804
telemt_user_connections_current{user="hello"} 2933
telemt_user_octets_from_client{user="hello"} 13035350231 (12.14 GB)
telemt_user_octets_to_client{user="hello"} 444185477439 (413.68 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1141
telemt_user_unique_ips_recent_window{user="hello"} 416
```