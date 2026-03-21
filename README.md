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

# Server Metrics 2026-03-21 16:14:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 70691.0 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2526561
telemt_connections_bad_total 151073
telemt_connections_current 1473
telemt_connections_me_current 1473
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 79553
telemt_upstream_connect_attempt_total 29901
telemt_upstream_connect_success_total 29770
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 29858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1735
telemt_me_reconnect_success_total 679
telemt_me_reader_eof_total 652
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 2141468
telemt_me_route_drop_channel_closed_total 670
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2011830
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 490
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 551
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
telemt_me_writers_active_current 43
telemt_desync_total 8017
telemt_desync_full_logged_total 2764
telemt_desync_suppressed_total 5253
telemt_desync_frames_bucket_total{bucket="1_2"} 1756
telemt_desync_frames_bucket_total{bucket="3_10"} 3043
telemt_desync_frames_bucket_total{bucket="gt_10"} 3218
telemt_pool_swap_total 76
telemt_pool_force_close_total 2302
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 520
telemt_me_draining_writers_reap_progress_total 24029
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2065
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22378
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2181
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21727
telemt_me_writer_teardown_success_total{mode="normal"} 24443
telemt_me_writer_teardown_noop_total 24036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48479
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 227.182127
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48479
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 520
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 580
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2013171
telemt_user_connections_current{user="hello"} 1473
telemt_user_octets_from_client{user="hello"} 28468776649 (26.51 GB)
telemt_user_octets_to_client{user="hello"} 499919213506 (465.59 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1815.6 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66246
telemt_connections_bad_total 3310
telemt_connections_current 1114
telemt_connections_me_current 1114
telemt_handshake_timeouts_total 1643
telemt_upstream_connect_attempt_total 744
telemt_upstream_connect_success_total 743
telemt_upstream_connect_attempts_per_request{bucket="1"} 743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 34436
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56102
telemt_me_endpoint_quarantine_total 14
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 200
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 615
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 593
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 588
telemt_me_writer_teardown_success_total{mode="normal"} 618
telemt_me_writer_teardown_noop_total 615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1233
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.046312
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1233
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 55673
telemt_user_connections_current{user="hello"} 1114
telemt_user_octets_from_client{user="hello"} 468876964 (447.16 MB)
telemt_user_octets_to_client{user="hello"} 13652739244 (12.72 GB)
telemt_user_unique_ips_current{user="hello"} 756
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 70688.1 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5179439
telemt_connections_bad_total 447208
telemt_connections_current 4977
telemt_connections_me_current 4977
telemt_handshake_timeouts_total 176681
telemt_upstream_connect_attempt_total 26061
telemt_upstream_connect_success_total 26005
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14205
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1168
telemt_me_reconnect_success_total 591
telemt_me_reader_eof_total 595
telemt_me_idle_close_by_peer_total 595
telemt_me_route_drop_no_conn_total 3150049
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4256483
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 533
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
telemt_desync_total 17475
telemt_desync_full_logged_total 5868
telemt_desync_suppressed_total 11607
telemt_desync_frames_bucket_total{bucket="1_2"} 3688
telemt_desync_frames_bucket_total{bucket="3_10"} 6955
telemt_desync_frames_bucket_total{bucket="gt_10"} 6832
telemt_pool_swap_total 75
telemt_pool_force_close_total 2463
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 23676
telemt_me_writer_removed_unexpected_total 575
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2073
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21912
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2262
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 201
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21213
telemt_me_writer_teardown_success_total{mode="normal"} 23985
telemt_me_writer_teardown_noop_total 23710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47695
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 93.374080
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47695
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 532
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4251372
telemt_user_connections_current{user="hello"} 4977
telemt_user_octets_from_client{user="hello"} 67224773856 (62.61 GB)
telemt_user_octets_to_client{user="hello"} 1362633124460 (1.24 TB)
telemt_user_unique_ips_current{user="hello"} 1855
telemt_user_unique_ips_recent_window{user="hello"} 622
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 70690.0 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4153672
telemt_connections_bad_total 434045
telemt_connections_current 4008
telemt_connections_me_current 4008
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 145192
telemt_upstream_connect_attempt_total 30444
telemt_upstream_connect_success_total 30156
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 30297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14178
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 496
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1397
telemt_me_reconnect_success_total 616
telemt_me_reader_eof_total 580
telemt_me_idle_close_by_peer_total 580
telemt_me_route_drop_no_conn_total 1327853
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3063419
telemt_me_endpoint_quarantine_total 448
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 540
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
telemt_me_writers_active_current 44
telemt_desync_total 14611
telemt_desync_full_logged_total 4818
telemt_desync_suppressed_total 9793
telemt_desync_frames_bucket_total{bucket="1_2"} 3639
telemt_desync_frames_bucket_total{bucket="3_10"} 5651
telemt_desync_frames_bucket_total{bucket="gt_10"} 5321
telemt_pool_swap_total 77
telemt_pool_force_close_total 2260
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 22825
telemt_me_writer_removed_unexpected_total 561
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1970
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21396
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2101
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 159
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20565
telemt_me_writer_teardown_success_total{mode="normal"} 23366
telemt_me_writer_teardown_noop_total 22828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46194
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.832550
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46194
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 3062810
telemt_user_connections_current{user="hello"} 4008
telemt_user_octets_from_client{user="hello"} 68489024797 (63.79 GB)
telemt_user_octets_to_client{user="hello"} 1411714558675 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1583
telemt_user_unique_ips_recent_window{user="hello"} 550
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 70654.0 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4094981
telemt_connections_bad_total 416530
telemt_connections_current 3624
telemt_connections_me_current 3624
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 124060
telemt_upstream_connect_attempt_total 35711
telemt_upstream_connect_success_total 35469
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 865
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1460
telemt_me_reconnect_success_total 667
telemt_me_reader_eof_total 609
telemt_me_idle_close_by_peer_total 609
telemt_me_route_drop_no_conn_total 1418492
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3047517
telemt_me_endpoint_quarantine_total 500
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 532
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
telemt_desync_total 14061
telemt_desync_full_logged_total 4636
telemt_desync_suppressed_total 9425
telemt_desync_frames_bucket_total{bucket="1_2"} 3511
telemt_desync_frames_bucket_total{bucket="3_10"} 5288
telemt_desync_frames_bucket_total{bucket="gt_10"} 5262
telemt_pool_swap_total 75
telemt_pool_force_close_total 2177
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 253
telemt_me_draining_writers_reap_progress_total 24249
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2051
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22799
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1993
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22072
telemt_me_writer_teardown_success_total{mode="normal"} 24850
telemt_me_writer_teardown_noop_total 24255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49105
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.578288
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49105
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 253
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 574
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 3050995
telemt_user_connections_current{user="hello"} 3624
telemt_user_octets_from_client{user="hello"} 72330167337 (67.36 GB)
telemt_user_octets_to_client{user="hello"} 1411054815996 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1381
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 70693.1 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14106008
telemt_connections_bad_total 910602
telemt_connections_current 5456
telemt_connections_me_current 5456
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 418468
telemt_upstream_connect_attempt_total 116833
telemt_upstream_connect_success_total 106908
telemt_upstream_connect_fail_total 8856
telemt_upstream_connect_attempts_per_request{bucket="1"} 115764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8856
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 3900
telemt_me_reconnect_success_total 1425
telemt_me_reader_eof_total 996
telemt_me_idle_close_by_peer_total 995
telemt_me_route_drop_no_conn_total 27888250
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11632269
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 552
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 20518
telemt_desync_full_logged_total 6382
telemt_desync_suppressed_total 14136
telemt_desync_frames_bucket_total{bucket="1_2"} 4477
telemt_desync_frames_bucket_total{bucket="3_10"} 9002
telemt_desync_frames_bucket_total{bucket="gt_10"} 7039
telemt_pool_swap_total 72
telemt_pool_force_close_total 2361
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 513
telemt_me_draining_writers_reap_progress_total 22526
telemt_me_writer_removed_unexpected_total 1356
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20718
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1984
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 377
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20165
telemt_me_writer_teardown_success_total{mode="normal"} 23660
telemt_me_writer_teardown_noop_total 22538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46198
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 175.980419
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46198
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 513
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 998
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 11706866
telemt_user_connections_current{user="hello"} 5456
telemt_user_octets_from_client{user="hello"} 83247158541 (77.53 GB)
telemt_user_octets_to_client{user="hello"} 828486883829 (771.59 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2048
telemt_user_unique_ips_recent_window{user="hello"} 1137
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 70660.7 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4084967
telemt_connections_bad_total 442138
telemt_connections_current 4235
telemt_connections_me_current 4235
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 86849
telemt_upstream_connect_attempt_total 29582
telemt_upstream_connect_success_total 29246
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 29535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_reconnect_attempts_total 3011
telemt_me_reconnect_success_total 1059
telemt_me_reader_eof_total 1053
telemt_me_idle_close_by_peer_total 1053
telemt_me_route_drop_no_conn_total 1741590
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3162801
telemt_me_endpoint_quarantine_total 434
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 527
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 15291
telemt_desync_full_logged_total 5316
telemt_desync_suppressed_total 9975
telemt_desync_frames_bucket_total{bucket="1_2"} 3000
telemt_desync_frames_bucket_total{bucket="3_10"} 6052
telemt_desync_frames_bucket_total{bucket="gt_10"} 6239
telemt_pool_swap_total 70
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 210
telemt_me_draining_writers_reap_progress_total 24829
telemt_me_writer_removed_unexpected_total 1020
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2497
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23388
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1775
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22759
telemt_me_writer_teardown_success_total{mode="normal"} 25885
telemt_me_writer_teardown_noop_total 24830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50715
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.542259
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50715
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 210
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 915
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 3145948
telemt_user_connections_current{user="hello"} 4235
telemt_user_octets_from_client{user="hello"} 82303893344 (76.65 GB)
telemt_user_octets_to_client{user="hello"} 1295475544666 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1661
telemt_user_unique_ips_recent_window{user="hello"} 509
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 7496.1 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1168685
telemt_connections_bad_total 43266
telemt_connections_current 3172
telemt_connections_me_current 3172
telemt_handshake_timeouts_total 540301
telemt_upstream_connect_attempt_total 2650
telemt_upstream_connect_success_total 2601
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 2644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 377
telemt_me_reconnect_success_total 104
telemt_me_reader_eof_total 95
telemt_me_idle_close_by_peer_total 95
telemt_me_route_drop_no_conn_total 461926
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537149
telemt_me_endpoint_quarantine_total 32
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 57
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
telemt_me_writers_active_current 41
telemt_desync_total 2853
telemt_desync_full_logged_total 904
telemt_desync_suppressed_total 1949
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 1038
telemt_desync_frames_bucket_total{bucket="gt_10"} 1267
telemt_pool_swap_total 7
telemt_pool_force_close_total 231
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 2245
telemt_me_writer_removed_unexpected_total 96
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2126
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2014
telemt_me_writer_teardown_success_total{mode="normal"} 2341
telemt_me_writer_teardown_noop_total 2245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4586
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.823611
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4586
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 86
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 536356
telemt_user_connections_current{user="hello"} 3172
telemt_user_octets_from_client{user="hello"} 13309479396 (12.40 GB)
telemt_user_octets_to_client{user="hello"} 199777725136 (186.06 GB)
telemt_user_unique_ips_current{user="hello"} 1246
telemt_user_unique_ips_recent_window{user="hello"} 550
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 68646.5 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1300227
telemt_connections_bad_total 145369
telemt_connections_current 810
telemt_connections_me_current 810
telemt_handshake_timeouts_total 463322
telemt_upstream_connect_attempt_total 31865
telemt_upstream_connect_success_total 31856
telemt_upstream_connect_attempts_per_request{bucket="1"} 31856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1361
telemt_me_reconnect_success_total 569
telemt_me_reader_eof_total 568
telemt_me_idle_close_by_peer_total 568
telemt_me_route_drop_no_conn_total 286374
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614226
telemt_me_endpoint_quarantine_total 610
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 573
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
telemt_me_writers_active_current 43
telemt_desync_total 3710
telemt_desync_full_logged_total 1330
telemt_desync_suppressed_total 2380
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 1326
telemt_desync_frames_bucket_total{bucket="gt_10"} 1684
telemt_pool_swap_total 75
telemt_pool_force_close_total 1772
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 28564
telemt_me_writer_removed_unexpected_total 537
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2168
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26950
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26792
telemt_me_writer_teardown_success_total{mode="normal"} 29118
telemt_me_writer_teardown_noop_total 28564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57682
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.676546
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57682
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 474
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 613795
telemt_user_connections_current{user="hello"} 810
telemt_user_octets_from_client{user="hello"} 12717190635 (11.84 GB)
telemt_user_octets_to_client{user="hello"} 237723815297 (221.40 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 70665.1 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4555246
telemt_connections_bad_total 420845
telemt_connections_current 4922
telemt_connections_me_current 4922
telemt_handshake_timeouts_total 150144
telemt_upstream_connect_attempt_total 27907
telemt_upstream_connect_success_total 27793
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 27872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_reconnect_attempts_total 1195
telemt_me_reconnect_success_total 624
telemt_me_reader_eof_total 591
telemt_me_idle_close_by_peer_total 591
telemt_me_route_drop_no_conn_total 1382314
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3602201
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 541
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 14089
telemt_desync_full_logged_total 4652
telemt_desync_suppressed_total 9437
telemt_desync_frames_bucket_total{bucket="1_2"} 3333
telemt_desync_frames_bucket_total{bucket="3_10"} 5248
telemt_desync_frames_bucket_total{bucket="gt_10"} 5508
telemt_pool_swap_total 78
telemt_pool_force_close_total 2059
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 240
telemt_me_draining_writers_reap_progress_total 25037
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2005
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23613
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22978
telemt_me_writer_teardown_success_total{mode="normal"} 25618
telemt_me_writer_teardown_noop_total 25038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50656
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.254744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50656
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 240
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 553
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3593556
telemt_user_connections_current{user="hello"} 4922
telemt_user_octets_from_client{user="hello"} 72137845804 (67.18 GB)
telemt_user_octets_to_client{user="hello"} 1684277165748 (1.53 TB)
telemt_user_unique_ips_current{user="hello"} 1719
telemt_user_unique_ips_recent_window{user="hello"} 617
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 70661.7 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4031136
telemt_connections_bad_total 365710
telemt_connections_current 3916
telemt_connections_me_current 3916
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 124219
telemt_upstream_connect_attempt_total 44379
telemt_upstream_connect_success_total 44067
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 44324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_reconnect_attempts_total 4037
telemt_me_reconnect_success_total 893
telemt_me_reader_eof_total 772
telemt_me_idle_close_by_peer_total 772
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1460700
telemt_me_route_drop_channel_closed_total 115
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3211976
telemt_me_endpoint_quarantine_total 588
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 536
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
telemt_me_writers_active_current 43
telemt_desync_total 12514
telemt_desync_full_logged_total 4248
telemt_desync_suppressed_total 8266
telemt_desync_frames_bucket_total{bucket="1_2"} 3127
telemt_desync_frames_bucket_total{bucket="3_10"} 4657
telemt_desync_frames_bucket_total{bucket="gt_10"} 4730
telemt_pool_swap_total 76
telemt_pool_force_close_total 2002
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 24397
telemt_me_writer_removed_unexpected_total 785
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2405
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22810
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1831
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 171
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22395
telemt_me_writer_teardown_success_total{mode="normal"} 25215
telemt_me_writer_teardown_noop_total 24398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49613
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.388731
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49613
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 685
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3220086
telemt_user_connections_current{user="hello"} 3916
telemt_user_octets_from_client{user="hello"} 58379162265 (54.37 GB)
telemt_user_octets_to_client{user="hello"} 1369943948196 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1451
telemt_user_unique_ips_recent_window{user="hello"} 527
```