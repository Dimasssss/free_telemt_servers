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

# Server Metrics 2026-03-21 12:14:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 56326.9 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1822158
telemt_connections_bad_total 89965
telemt_connections_current 1764
telemt_connections_me_current 1764
telemt_handshake_timeouts_total 69225
telemt_upstream_connect_attempt_total 21932
telemt_upstream_connect_success_total 21824
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 21894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1102
telemt_me_reconnect_success_total 492
telemt_me_reader_eof_total 476
telemt_me_idle_close_by_peer_total 476
telemt_me_route_drop_no_conn_total 1401844
telemt_me_route_drop_channel_closed_total 437
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1425331
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 446
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
telemt_desync_total 5492
telemt_desync_full_logged_total 1929
telemt_desync_suppressed_total 3563
telemt_desync_frames_bucket_total{bucket="1_2"} 1172
telemt_desync_frames_bucket_total{bucket="3_10"} 2119
telemt_desync_frames_bucket_total{bucket="gt_10"} 2201
telemt_pool_swap_total 61
telemt_pool_force_close_total 1788
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 348
telemt_me_draining_writers_reap_progress_total 19624
telemt_me_writer_removed_unexpected_total 457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1613
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18321
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1724
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17836
telemt_me_writer_teardown_success_total{mode="normal"} 19934
telemt_me_writer_teardown_noop_total 19628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39562
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 147.668566
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39562
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 348
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1424292
telemt_user_connections_current{user="hello"} 1764
telemt_user_octets_from_client{user="hello"} 19680927751 (18.33 GB)
telemt_user_octets_to_client{user="hello"} 368560914739 (343.25 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1974.7 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125751
telemt_connections_bad_total 9375
telemt_connections_current 2172
telemt_connections_me_current 2172
telemt_handshake_timeouts_total 5204
telemt_upstream_connect_attempt_total 747
telemt_upstream_connect_success_total 718
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 57
telemt_me_reconnect_success_total 35
telemt_me_reader_eof_total 31
telemt_me_idle_close_by_peer_total 31
telemt_me_route_drop_no_conn_total 56212
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99827
telemt_me_endpoint_quarantine_total 17
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 60
telemt_me_writers_warm_current 19
telemt_desync_total 360
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 184
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 1
telemt_pool_force_close_total 31
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 525
telemt_me_writer_removed_unexpected_total 38
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 493
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 494
telemt_me_writer_teardown_success_total{mode="normal"} 563
telemt_me_writer_teardown_noop_total 525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1088
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.125283
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1088
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 99809
telemt_user_connections_current{user="hello"} 2172
telemt_user_octets_from_client{user="hello"} 1587904088 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 26737899944 (24.90 GB)
telemt_user_unique_ips_current{user="hello"} 1103
telemt_user_unique_ips_recent_window{user="hello"} 841
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 56327.5 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3413231
telemt_connections_bad_total 366079
telemt_connections_current 4187
telemt_connections_me_current 4187
telemt_handshake_timeouts_total 126732
telemt_upstream_connect_attempt_total 21349
telemt_upstream_connect_success_total 21324
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 21328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 782
telemt_me_reconnect_success_total 439
telemt_me_reader_eof_total 450
telemt_me_idle_close_by_peer_total 450
telemt_me_route_drop_no_conn_total 1472345
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2718173
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 432
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
telemt_me_writers_active_current 86
telemt_desync_total 11862
telemt_desync_full_logged_total 4021
telemt_desync_suppressed_total 7841
telemt_desync_frames_bucket_total{bucket="1_2"} 2519
telemt_desync_frames_bucket_total{bucket="3_10"} 4626
telemt_desync_frames_bucket_total{bucket="gt_10"} 4717
telemt_pool_swap_total 60
telemt_pool_force_close_total 1857
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 263
telemt_me_draining_writers_reap_progress_total 19348
telemt_me_writer_removed_unexpected_total 431
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1629
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17990
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 100
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17491
telemt_me_writer_teardown_success_total{mode="normal"} 19619
telemt_me_writer_teardown_noop_total 19362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38981
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.157375
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38981
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 263
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 2714515
telemt_user_connections_current{user="hello"} 4187
telemt_user_octets_from_client{user="hello"} 44318079464 (41.27 GB)
telemt_user_octets_to_client{user="hello"} 980207516804 (912.89 GB)
telemt_user_unique_ips_current{user="hello"} 1682
telemt_user_unique_ips_recent_window{user="hello"} 956
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 56325.9 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2841090
telemt_connections_bad_total 315306
telemt_connections_current 3789
telemt_connections_me_current 3789
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 114769
telemt_upstream_connect_attempt_total 26150
telemt_upstream_connect_success_total 25882
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 26014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 466
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1101
telemt_me_reconnect_success_total 508
telemt_me_reader_eof_total 470
telemt_me_idle_close_by_peer_total 470
telemt_me_route_drop_no_conn_total 880932
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2016922
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 434
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
telemt_desync_total 9236
telemt_desync_full_logged_total 3152
telemt_desync_suppressed_total 6084
telemt_desync_frames_bucket_total{bucket="1_2"} 2315
telemt_desync_frames_bucket_total{bucket="3_10"} 3603
telemt_desync_frames_bucket_total{bucket="gt_10"} 3318
telemt_pool_swap_total 61
telemt_pool_force_close_total 1701
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 19013
telemt_me_writer_removed_unexpected_total 460
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1597
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17894
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1589
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17312
telemt_me_writer_teardown_success_total{mode="normal"} 19491
telemt_me_writer_teardown_noop_total 19014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38505
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.915785
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38505
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 426
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 2018168
telemt_user_connections_current{user="hello"} 3789
telemt_user_octets_from_client{user="hello"} 37902758741 (35.30 GB)
telemt_user_octets_to_client{user="hello"} 962515056815 (896.41 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1397
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 56289.7 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2759300
telemt_connections_bad_total 310798
telemt_connections_current 3344
telemt_connections_me_current 3344
telemt_handshake_timeouts_total 82019
telemt_upstream_connect_attempt_total 22814
telemt_upstream_connect_success_total 22726
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 857
telemt_me_reconnect_success_total 586
telemt_me_reader_eof_total 533
telemt_me_idle_close_by_peer_total 533
telemt_me_route_drop_no_conn_total 828808
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2001482
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 426
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
telemt_desync_total 9345
telemt_desync_full_logged_total 3126
telemt_desync_suppressed_total 6219
telemt_desync_frames_bucket_total{bucket="1_2"} 2473
telemt_desync_frames_bucket_total{bucket="3_10"} 3555
telemt_desync_frames_bucket_total{bucket="gt_10"} 3317
telemt_pool_swap_total 59
telemt_pool_force_close_total 1675
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 20331
telemt_me_writer_removed_unexpected_total 507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1685
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19191
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1526
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18656
telemt_me_writer_teardown_success_total{mode="normal"} 20876
telemt_me_writer_teardown_noop_total 20335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41211
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.917149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41211
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 511
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1998438
telemt_user_connections_current{user="hello"} 3344
telemt_user_octets_from_client{user="hello"} 44895357040 (41.81 GB)
telemt_user_octets_to_client{user="hello"} 965943154272 (899.60 GB)
telemt_user_unique_ips_current{user="hello"} 1351
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 56328.9 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9031003
telemt_connections_bad_total 615808
telemt_connections_current 5465
telemt_connections_me_current 5465
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 308683
telemt_upstream_connect_attempt_total 88505
telemt_upstream_connect_success_total 83349
telemt_upstream_connect_fail_total 4323
telemt_upstream_connect_attempts_per_request{bucket="1"} 87672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4323
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3459
telemt_me_reconnect_success_total 1153
telemt_me_reader_eof_total 810
telemt_me_idle_close_by_peer_total 809
telemt_me_route_drop_no_conn_total 16123130
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7446381
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 447
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
telemt_me_writers_active_current 44
telemt_desync_total 14176
telemt_desync_full_logged_total 4554
telemt_desync_suppressed_total 9622
telemt_desync_frames_bucket_total{bucket="1_2"} 3033
telemt_desync_frames_bucket_total{bucket="3_10"} 6286
telemt_desync_frames_bucket_total{bucket="gt_10"} 4857
telemt_pool_swap_total 57
telemt_pool_force_close_total 1804
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 18563
telemt_me_writer_removed_unexpected_total 1120
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2408
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17157
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1548
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 256
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16759
telemt_me_writer_teardown_success_total{mode="normal"} 19565
telemt_me_writer_teardown_noop_total 18572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38137
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.081626
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38137
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 795
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 7504396
telemt_user_connections_current{user="hello"} 5465
telemt_user_octets_from_client{user="hello"} 59616427469 (55.52 GB)
telemt_user_octets_to_client{user="hello"} 671963485876 (625.81 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1877
telemt_user_unique_ips_recent_window{user="hello"} 910
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 56296.9 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2801911
telemt_connections_bad_total 342397
telemt_connections_current 3689
telemt_connections_me_current 3689
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 61440
telemt_upstream_connect_attempt_total 24203
telemt_upstream_connect_success_total 23936
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 24178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_reconnect_attempts_total 2389
telemt_me_reconnect_success_total 815
telemt_me_reader_eof_total 810
telemt_me_idle_close_by_peer_total 810
telemt_me_route_drop_no_conn_total 976236
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2111307
telemt_me_endpoint_quarantine_total 348
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 432
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
telemt_me_writers_active_current 87
telemt_desync_total 9737
telemt_desync_full_logged_total 3445
telemt_desync_suppressed_total 6292
telemt_desync_frames_bucket_total{bucket="1_2"} 1912
telemt_desync_frames_bucket_total{bucket="3_10"} 3904
telemt_desync_frames_bucket_total{bucket="gt_10"} 3921
telemt_pool_swap_total 57
telemt_pool_force_close_total 1578
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 20113
telemt_me_writer_removed_unexpected_total 784
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1912
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19011
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1421
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18535
telemt_me_writer_teardown_success_total{mode="normal"} 20923
telemt_me_writer_teardown_noop_total 20113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41036
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.214839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41036
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 691
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 2096411
telemt_user_connections_current{user="hello"} 3689
telemt_user_octets_from_client{user="hello"} 38772320080 (36.11 GB)
telemt_user_octets_to_client{user="hello"} 929371940354 (865.55 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1634
telemt_user_unique_ips_recent_window{user="hello"} 435
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 56291.1 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4168229
telemt_connections_bad_total 213804
telemt_connections_current 2697
telemt_connections_me_current 2697
telemt_handshake_timeouts_total 1810809
telemt_upstream_connect_attempt_total 22637
telemt_upstream_connect_success_total 22603
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 22606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 823
telemt_me_reconnect_success_total 403
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 904231
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1882942
telemt_me_endpoint_quarantine_total 430
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 443
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
telemt_me_writers_active_current 44
telemt_desync_total 9122
telemt_desync_full_logged_total 3241
telemt_desync_suppressed_total 5881
telemt_desync_frames_bucket_total{bucket="1_2"} 1684
telemt_desync_frames_bucket_total{bucket="3_10"} 3640
telemt_desync_frames_bucket_total{bucket="gt_10"} 3798
telemt_pool_swap_total 61
telemt_pool_force_close_total 1550
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 20254
telemt_me_writer_removed_unexpected_total 391
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1371
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19298
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18704
telemt_me_writer_teardown_success_total{mode="normal"} 20669
telemt_me_writer_teardown_noop_total 20254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40923
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.162021
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40923
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 354
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 1876576
telemt_user_connections_current{user="hello"} 2697
telemt_user_octets_from_client{user="hello"} 34259288144 (31.91 GB)
telemt_user_octets_to_client{user="hello"} 896323294108 (834.77 GB)
telemt_user_unique_ips_current{user="hello"} 1120
telemt_user_unique_ips_recent_window{user="hello"} 477
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 54282.5 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872331
telemt_connections_bad_total 68322
telemt_connections_current 802
telemt_connections_me_current 802
telemt_handshake_timeouts_total 316236
telemt_upstream_connect_attempt_total 25943
telemt_upstream_connect_success_total 25941
telemt_upstream_connect_attempts_per_request{bucket="1"} 25941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1110
telemt_me_reconnect_success_total 425
telemt_me_reader_eof_total 423
telemt_me_idle_close_by_peer_total 423
telemt_me_route_drop_no_conn_total 186187
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423021
telemt_me_endpoint_quarantine_total 498
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 463
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
telemt_me_writers_active_current 43
telemt_desync_total 2944
telemt_desync_full_logged_total 1110
telemt_desync_suppressed_total 1834
telemt_desync_frames_bucket_total{bucket="1_2"} 488
telemt_desync_frames_bucket_total{bucket="3_10"} 1055
telemt_desync_frames_bucket_total{bucket="gt_10"} 1401
telemt_pool_swap_total 60
telemt_pool_force_close_total 1343
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 94
telemt_me_draining_writers_reap_progress_total 23251
telemt_me_writer_removed_unexpected_total 401
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1692
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21967
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1340
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21908
telemt_me_writer_teardown_success_total{mode="normal"} 23659
telemt_me_writer_teardown_noop_total 23251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.722814
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 94
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 345
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 422870
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 6735920939 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 161756855565 (150.65 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 56300.8 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2974502
telemt_connections_bad_total 284015
telemt_connections_current 4398
telemt_connections_me_current 4398
telemt_handshake_timeouts_total 82020
telemt_upstream_connect_attempt_total 23473
telemt_upstream_connect_success_total 23374
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 23442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11714
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_reconnect_attempts_total 957
telemt_me_reconnect_success_total 536
telemt_me_reader_eof_total 500
telemt_me_idle_close_by_peer_total 500
telemt_me_route_drop_no_conn_total 800326
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2350223
telemt_me_endpoint_quarantine_total 432
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 439
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 9457
telemt_desync_full_logged_total 3112
telemt_desync_suppressed_total 6345
telemt_desync_frames_bucket_total{bucket="1_2"} 2259
telemt_desync_frames_bucket_total{bucket="3_10"} 3523
telemt_desync_frames_bucket_total{bucket="gt_10"} 3675
telemt_pool_swap_total 62
telemt_pool_force_close_total 1566
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 166
telemt_me_draining_writers_reap_progress_total 21089
telemt_me_writer_removed_unexpected_total 491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1630
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19967
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1538
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19523
telemt_me_writer_teardown_success_total{mode="normal"} 21597
telemt_me_writer_teardown_noop_total 21089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42686
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.754680
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42686
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 166
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 476
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 2343423
telemt_user_connections_current{user="hello"} 4398
telemt_user_octets_from_client{user="hello"} 49326636420 (45.94 GB)
telemt_user_octets_to_client{user="hello"} 1097687315128 (1022.30 GB)
telemt_user_unique_ips_current{user="hello"} 1563
telemt_user_unique_ips_recent_window{user="hello"} 534
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 56297.6 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2711514
telemt_connections_bad_total 223855
telemt_connections_current 3712
telemt_connections_me_current 3712
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 76772
telemt_upstream_connect_attempt_total 39614
telemt_upstream_connect_success_total 39364
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 39571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 3359
telemt_me_reconnect_success_total 697
telemt_me_reader_eof_total 605
telemt_me_idle_close_by_peer_total 605
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 814900
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2175168
telemt_me_endpoint_quarantine_total 490
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 437
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
telemt_desync_total 8207
telemt_desync_full_logged_total 2832
telemt_desync_suppressed_total 5375
telemt_desync_frames_bucket_total{bucket="1_2"} 2134
telemt_desync_frames_bucket_total{bucket="3_10"} 3045
telemt_desync_frames_bucket_total{bucket="gt_10"} 3028
telemt_pool_swap_total 61
telemt_pool_force_close_total 1520
telemt_me_writer_close_signal_drop_total 143
telemt_me_draining_writers_reap_progress_total 20248
telemt_me_writer_removed_unexpected_total 618
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1906
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18988
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1424
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 96
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18728
telemt_me_writer_teardown_success_total{mode="normal"} 20894
telemt_me_writer_teardown_noop_total 20249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41143
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.385455
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41143
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 143
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 530
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 2185617
telemt_user_connections_current{user="hello"} 3712
telemt_user_octets_from_client{user="hello"} 40022059621 (37.27 GB)
telemt_user_octets_to_client{user="hello"} 958792698076 (892.95 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1368
telemt_user_unique_ips_recent_window{user="hello"} 484
```