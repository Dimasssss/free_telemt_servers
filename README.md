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

# Server Metrics 2026-03-21 09:51:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 47737.5 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1348049
telemt_connections_bad_total 69844
telemt_connections_current 1465
telemt_connections_me_current 1465
telemt_handshake_timeouts_total 54733
telemt_upstream_connect_attempt_total 18874
telemt_upstream_connect_success_total 18793
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 18850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11973
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 848
telemt_me_reconnect_success_total 369
telemt_me_reader_eof_total 379
telemt_me_idle_close_by_peer_total 379
telemt_me_route_drop_no_conn_total 735445
telemt_me_route_drop_channel_closed_total 253
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1019641
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
telemt_me_writers_active_current 90
telemt_me_writers_warm_current 7
telemt_desync_total 4288
telemt_desync_full_logged_total 1474
telemt_desync_suppressed_total 2814
telemt_desync_frames_bucket_total{bucket="1_2"} 896
telemt_desync_frames_bucket_total{bucket="3_10"} 1671
telemt_desync_frames_bucket_total{bucket="gt_10"} 1721
telemt_pool_swap_total 51
telemt_pool_force_close_total 1431
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 208
telemt_me_draining_writers_reap_progress_total 16851
telemt_me_writer_removed_unexpected_total 358
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1324
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15783
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1409
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15420
telemt_me_writer_teardown_success_total{mode="normal"} 17107
telemt_me_writer_teardown_noop_total 16852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 82.846469
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 208
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 329
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1018875
telemt_user_connections_current{user="hello"} 1465
telemt_user_octets_from_client{user="hello"} 14496308739 (13.50 GB)
telemt_user_octets_to_client{user="hello"} 290409034527 (270.46 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 543
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 47738.5 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3434735
telemt_connections_bad_total 367791
telemt_connections_current 4451
telemt_connections_me_current 4451
telemt_handshake_timeouts_total 100622
telemt_upstream_connect_attempt_total 17099
telemt_upstream_connect_success_total 17020
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 17074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 990
telemt_me_reconnect_success_total 383
telemt_me_reader_eof_total 378
telemt_me_idle_close_by_peer_total 377
telemt_me_route_drop_no_conn_total 1461441
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2309501
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
telemt_me_writers_warm_current 9
telemt_desync_total 9932
telemt_desync_full_logged_total 3341
telemt_desync_suppressed_total 6591
telemt_desync_frames_bucket_total{bucket="1_2"} 2021
telemt_desync_frames_bucket_total{bucket="3_10"} 3932
telemt_desync_frames_bucket_total{bucket="gt_10"} 3979
telemt_pool_swap_total 51
telemt_pool_force_close_total 1560
telemt_me_writer_close_signal_drop_total 184
telemt_me_draining_writers_reap_progress_total 15286
telemt_me_writer_removed_unexpected_total 354
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1406
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14218
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1469
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13726
telemt_me_writer_teardown_success_total{mode="normal"} 15624
telemt_me_writer_teardown_noop_total 15286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.321003
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 184
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 309
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2305214
telemt_user_connections_current{user="hello"} 4451
telemt_user_octets_from_client{user="hello"} 32557351996 (30.32 GB)
telemt_user_octets_to_client{user="hello"} 784011168320 (730.17 GB)
telemt_user_unique_ips_current{user="hello"} 1690
telemt_user_unique_ips_recent_window{user="hello"} 647
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 47735.1 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2515482
telemt_connections_bad_total 300975
telemt_connections_current 4285
telemt_connections_me_current 4285
telemt_handshake_timeouts_total 95376
telemt_upstream_connect_attempt_total 18590
telemt_upstream_connect_success_total 18579
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 620
telemt_me_reconnect_success_total 350
telemt_me_reader_eof_total 364
telemt_me_idle_close_by_peer_total 364
telemt_me_route_drop_no_conn_total 1022058
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1963586
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
telemt_me_writers_warm_current 7
telemt_desync_total 8527
telemt_desync_full_logged_total 2944
telemt_desync_suppressed_total 5583
telemt_desync_frames_bucket_total{bucket="1_2"} 1793
telemt_desync_frames_bucket_total{bucket="3_10"} 3367
telemt_desync_frames_bucket_total{bucket="gt_10"} 3367
telemt_pool_swap_total 51
telemt_pool_force_close_total 1529
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 202
telemt_me_draining_writers_reap_progress_total 16895
telemt_me_writer_removed_unexpected_total 343
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1386
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15734
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15366
telemt_me_writer_teardown_success_total{mode="normal"} 17120
telemt_me_writer_teardown_noop_total 16906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34026
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 36.283581
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34026
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 202
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 313
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1960469
telemt_user_connections_current{user="hello"} 4285
telemt_user_octets_from_client{user="hello"} 30514051284 (28.42 GB)
telemt_user_octets_to_client{user="hello"} 743434012308 (692.38 GB)
telemt_user_unique_ips_current{user="hello"} 1596
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 47737.5 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2058340
telemt_connections_bad_total 235984
telemt_connections_current 2887
telemt_connections_me_current 2887
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 88109
telemt_upstream_connect_attempt_total 23527
telemt_upstream_connect_success_total 23291
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 23416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 999
telemt_me_reconnect_success_total 441
telemt_me_reader_eof_total 408
telemt_me_idle_close_by_peer_total 408
telemt_me_route_drop_no_conn_total 595273
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1435236
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
telemt_me_writers_warm_current 10
telemt_desync_total 6722
telemt_desync_full_logged_total 2298
telemt_desync_suppressed_total 4424
telemt_desync_frames_bucket_total{bucket="1_2"} 1658
telemt_desync_frames_bucket_total{bucket="3_10"} 2675
telemt_desync_frames_bucket_total{bucket="gt_10"} 2389
telemt_pool_swap_total 51
telemt_pool_force_close_total 1391
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 16768
telemt_me_writer_removed_unexpected_total 401
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1351
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15832
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1309
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15377
telemt_me_writer_teardown_success_total{mode="normal"} 17183
telemt_me_writer_teardown_noop_total 16769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33952
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.098795
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33952
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 371
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1437233
telemt_user_connections_current{user="hello"} 2887
telemt_user_octets_from_client{user="hello"} 28961998577 (26.97 GB)
telemt_user_octets_to_client{user="hello"} 691005932735 (643.55 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1146
telemt_user_unique_ips_recent_window{user="hello"} 484
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 47700.3 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1981894
telemt_connections_bad_total 224656
telemt_connections_current 3686
telemt_connections_me_current 3686
telemt_handshake_timeouts_total 63353
telemt_upstream_connect_attempt_total 19853
telemt_upstream_connect_success_total 19813
telemt_upstream_connect_attempts_per_request{bucket="1"} 19813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 623
telemt_me_reconnect_success_total 444
telemt_me_reader_eof_total 405
telemt_me_idle_close_by_peer_total 405
telemt_me_route_drop_no_conn_total 553811
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1432338
telemt_me_endpoint_quarantine_total 359
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 364
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
telemt_desync_total 6636
telemt_desync_full_logged_total 2311
telemt_desync_suppressed_total 4325
telemt_desync_frames_bucket_total{bucket="1_2"} 1741
telemt_desync_frames_bucket_total{bucket="3_10"} 2546
telemt_desync_frames_bucket_total{bucket="gt_10"} 2349
telemt_pool_swap_total 50
telemt_pool_force_close_total 1323
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 119
telemt_me_draining_writers_reap_progress_total 17795
telemt_me_writer_removed_unexpected_total 381
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1330
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16875
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16472
telemt_me_writer_teardown_success_total{mode="normal"} 18205
telemt_me_writer_teardown_noop_total 17798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36003
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.926279
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36003
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 119
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 397
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1430008
telemt_user_connections_current{user="hello"} 3686
telemt_user_octets_from_client{user="hello"} 33643664160 (31.33 GB)
telemt_user_octets_to_client{user="hello"} 708521948916 (659.86 GB)
telemt_user_unique_ips_current{user="hello"} 1495
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 47739.6 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5891913
telemt_connections_bad_total 315382
telemt_connections_current 5125
telemt_connections_me_current 5125
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 231486
telemt_upstream_connect_attempt_total 58976
telemt_upstream_connect_success_total 56388
telemt_upstream_connect_fail_total 1915
telemt_upstream_connect_attempts_per_request{bucket="1"} 58303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1915
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2812
telemt_me_reconnect_success_total 979
telemt_me_reader_eof_total 681
telemt_me_idle_close_by_peer_total 680
telemt_me_route_drop_no_conn_total 9682921
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4967264
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
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 11
telemt_desync_total 10037
telemt_desync_full_logged_total 3292
telemt_desync_suppressed_total 6745
telemt_desync_frames_bucket_total{bucket="1_2"} 2216
telemt_desync_frames_bucket_total{bucket="3_10"} 4345
telemt_desync_frames_bucket_total{bucket="gt_10"} 3476
telemt_pool_swap_total 48
telemt_pool_force_close_total 1495
telemt_me_writer_close_signal_drop_total 297
telemt_me_draining_writers_reap_progress_total 16125
telemt_me_writer_removed_unexpected_total 945
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2050
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14949
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1283
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 212
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14630
telemt_me_writer_teardown_success_total{mode="normal"} 16999
telemt_me_writer_teardown_noop_total 16131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33130
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.582610
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33130
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 297
telemt_me_refill_failed_total 66
telemt_me_writer_restored_same_endpoint_total 678
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 5001939
telemt_user_connections_current{user="hello"} 5125
telemt_user_octets_from_client{user="hello"} 47382040996 (44.13 GB)
telemt_user_octets_to_client{user="hello"} 577004377415 (537.38 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1806
telemt_user_unique_ips_recent_window{user="hello"} 808
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 47707.1 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2019597
telemt_connections_bad_total 257310
telemt_connections_current 3668
telemt_connections_me_current 3668
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 39343
telemt_upstream_connect_attempt_total 21186
telemt_upstream_connect_success_total 20976
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 21167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_reconnect_attempts_total 1964
telemt_me_reconnect_success_total 636
telemt_me_reader_eof_total 644
telemt_me_idle_close_by_peer_total 644
telemt_me_route_drop_no_conn_total 612611
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1514775
telemt_me_endpoint_quarantine_total 288
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 370
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
telemt_me_writers_active_current 90
telemt_desync_total 6897
telemt_desync_full_logged_total 2520
telemt_desync_suppressed_total 4377
telemt_desync_frames_bucket_total{bucket="1_2"} 1329
telemt_desync_frames_bucket_total{bucket="3_10"} 2804
telemt_desync_frames_bucket_total{bucket="gt_10"} 2764
telemt_pool_swap_total 49
telemt_pool_force_close_total 1283
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 94
telemt_me_draining_writers_reap_progress_total 17531
telemt_me_writer_removed_unexpected_total 621
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1575
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16600
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16248
telemt_me_writer_teardown_success_total{mode="normal"} 18175
telemt_me_writer_teardown_noop_total 17531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35706
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.582404
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35706
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 94
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 539
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1510783
telemt_user_connections_current{user="hello"} 3668
telemt_user_octets_from_client{user="hello"} 27760442368 (25.85 GB)
telemt_user_octets_to_client{user="hello"} 699311693762 (651.28 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1562
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 47701.5 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2839313
telemt_connections_bad_total 162036
telemt_connections_current 3082
telemt_connections_me_current 3082
telemt_handshake_timeouts_total 1164707
telemt_upstream_connect_attempt_total 19812
telemt_upstream_connect_success_total 19778
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 522
telemt_me_reconnect_success_total 302
telemt_me_reader_eof_total 303
telemt_me_idle_close_by_peer_total 303
telemt_me_route_drop_no_conn_total 527884
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1350411
telemt_me_endpoint_quarantine_total 365
telemt_me_single_endpoint_shadow_rotate_total 374
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
telemt_desync_total 6724
telemt_desync_full_logged_total 2369
telemt_desync_suppressed_total 4355
telemt_desync_frames_bucket_total{bucket="1_2"} 1197
telemt_desync_frames_bucket_total{bucket="3_10"} 2686
telemt_desync_frames_bucket_total{bucket="gt_10"} 2841
telemt_pool_swap_total 52
telemt_pool_force_close_total 1269
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 17751
telemt_me_writer_removed_unexpected_total 293
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1126
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16937
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16482
telemt_me_writer_teardown_success_total{mode="normal"} 18063
telemt_me_writer_teardown_noop_total 17751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35814
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.927289
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35814
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 269
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1346157
telemt_user_connections_current{user="hello"} 3082
telemt_user_octets_from_client{user="hello"} 23988397716 (22.34 GB)
telemt_user_octets_to_client{user="hello"} 666130076252 (620.38 GB)
telemt_user_unique_ips_current{user="hello"} 1214
telemt_user_unique_ips_recent_window{user="hello"} 462
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 45693.0 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598582
telemt_connections_bad_total 21520
telemt_connections_current 668
telemt_connections_me_current 668
telemt_handshake_timeouts_total 221960
telemt_upstream_connect_attempt_total 22322
telemt_upstream_connect_success_total 22320
telemt_upstream_connect_attempts_per_request{bucket="1"} 22320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 918
telemt_me_reconnect_success_total 367
telemt_me_reader_eof_total 363
telemt_me_idle_close_by_peer_total 363
telemt_me_route_drop_no_conn_total 126068
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309363
telemt_me_endpoint_quarantine_total 439
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 390
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
telemt_me_writers_active_current 45
telemt_desync_total 1962
telemt_desync_full_logged_total 788
telemt_desync_suppressed_total 1174
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 838
telemt_pool_swap_total 50
telemt_pool_force_close_total 1087
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 19940
telemt_me_writer_removed_unexpected_total 344
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1436
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18852
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1084
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18853
telemt_me_writer_teardown_success_total{mode="normal"} 20288
telemt_me_writer_teardown_noop_total 19940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40228
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.867397
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40228
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 300
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 309515
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 4543651651 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 122532556137 (114.12 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 47711.5 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2108962
telemt_connections_bad_total 189729
telemt_connections_current 4063
telemt_connections_me_current 4063
telemt_handshake_timeouts_total 52960
telemt_upstream_connect_attempt_total 20499
telemt_upstream_connect_success_total 20412
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 20469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10177
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 766
telemt_me_reconnect_success_total 439
telemt_me_reader_eof_total 408
telemt_me_idle_close_by_peer_total 408
telemt_me_route_drop_no_conn_total 525125
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1661896
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
telemt_desync_total 6571
telemt_desync_full_logged_total 2194
telemt_desync_suppressed_total 4377
telemt_desync_frames_bucket_total{bucket="1_2"} 1603
telemt_desync_frames_bucket_total{bucket="3_10"} 2446
telemt_desync_frames_bucket_total{bucket="gt_10"} 2522
telemt_pool_swap_total 52
telemt_pool_force_close_total 1286
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 18465
telemt_me_writer_removed_unexpected_total 407
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1364
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17517
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17179
telemt_me_writer_teardown_success_total{mode="normal"} 18881
telemt_me_writer_teardown_noop_total 18465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37346
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.536789
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37346
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1656349
telemt_user_connections_current{user="hello"} 4063
telemt_user_octets_from_client{user="hello"} 37751337900 (35.16 GB)
telemt_user_octets_to_client{user="hello"} 774370721900 (721.19 GB)
telemt_user_unique_ips_current{user="hello"} 1492
telemt_user_unique_ips_recent_window{user="hello"} 553
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 47708.2 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1970738
telemt_connections_bad_total 162177
telemt_connections_current 3475
telemt_connections_me_current 3475
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 47933
telemt_upstream_connect_attempt_total 29146
telemt_upstream_connect_success_total 28938
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 29104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 2945
telemt_me_reconnect_success_total 604
telemt_me_reader_eof_total 526
telemt_me_idle_close_by_peer_total 526
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 537562
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1583056
telemt_me_endpoint_quarantine_total 424
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 372
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
telemt_desync_total 6013
telemt_desync_full_logged_total 2016
telemt_desync_suppressed_total 3997
telemt_desync_frames_bucket_total{bucket="1_2"} 1659
telemt_desync_frames_bucket_total{bucket="3_10"} 2214
telemt_desync_frames_bucket_total{bucket="gt_10"} 2140
telemt_pool_swap_total 51
telemt_pool_force_close_total 1260
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 17746
telemt_me_writer_removed_unexpected_total 536
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1611
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16697
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16486
telemt_me_writer_teardown_success_total{mode="normal"} 18308
telemt_me_writer_teardown_noop_total 17747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36055
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.406489
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36055
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 133
telemt_me_writer_restored_same_endpoint_total 466
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1586821
telemt_user_connections_current{user="hello"} 3475
telemt_user_octets_from_client{user="hello"} 26284975519 (24.48 GB)
telemt_user_octets_to_client{user="hello"} 708368956607 (659.72 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1379
telemt_user_unique_ips_recent_window{user="hello"} 489
```