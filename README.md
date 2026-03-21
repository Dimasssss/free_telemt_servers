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

# Server Metrics 2026-03-21 11:08:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 52348.8 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1568177
telemt_connections_bad_total 78855
telemt_connections_current 1672
telemt_connections_me_current 1672
telemt_handshake_timeouts_total 62924
telemt_upstream_connect_attempt_total 20534
telemt_upstream_connect_success_total 20428
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 20496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1037
telemt_me_reconnect_success_total 448
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_route_drop_no_conn_total 921657
telemt_me_route_drop_channel_closed_total 350
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1200861
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 370
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 414
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 40
telemt_desync_total 4900
telemt_desync_full_logged_total 1714
telemt_desync_suppressed_total 3186
telemt_desync_frames_bucket_total{bucket="1_2"} 1021
telemt_desync_frames_bucket_total{bucket="3_10"} 1902
telemt_desync_frames_bucket_total{bucket="gt_10"} 1977
telemt_pool_swap_total 57
telemt_pool_force_close_total 1620
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 287
telemt_me_draining_writers_reap_progress_total 18301
telemt_me_writer_removed_unexpected_total 426
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17113
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1559
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16681
telemt_me_writer_teardown_success_total{mode="normal"} 18609
telemt_me_writer_teardown_noop_total 18303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36912
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 113.008652
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36912
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 287
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 1199972
telemt_user_connections_current{user="hello"} 1672
telemt_user_octets_from_client{user="hello"} 16856760435 (15.70 GB)
telemt_user_octets_to_client{user="hello"} 333304092403 (310.41 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 239.7 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42034
telemt_connections_bad_total 2330
telemt_connections_current 4313
telemt_connections_me_current 4313
telemt_handshake_timeouts_total 766
telemt_upstream_connect_attempt_total 141
telemt_upstream_connect_success_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 64
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 28842
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36700
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
telemt_me_writers_active_current 45
telemt_desync_total 116
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 56
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55
telemt_me_writer_teardown_success_total{mode="normal"} 56
telemt_me_writer_teardown_noop_total 56
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.032911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112
telemt_user_connections_total{user="hello"} 36697
telemt_user_connections_current{user="hello"} 4313
telemt_user_octets_from_client{user="hello"} 296361476 (282.63 MB)
telemt_user_octets_to_client{user="hello"} 4944430964 (4.60 GB)
telemt_user_unique_ips_current{user="hello"} 1640
telemt_user_unique_ips_recent_window{user="hello"} 857
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 52346.6 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2985247
telemt_connections_bad_total 328148
telemt_connections_current 4719
telemt_connections_me_current 4719
telemt_handshake_timeouts_total 108734
telemt_upstream_connect_attempt_total 20041
telemt_upstream_connect_success_total 20028
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 686
telemt_me_reconnect_success_total 380
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 393
telemt_me_route_drop_no_conn_total 1275081
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2370005
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 406
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
telemt_me_writers_active_current 42
telemt_desync_total 10321
telemt_desync_full_logged_total 3516
telemt_desync_suppressed_total 6805
telemt_desync_frames_bucket_total{bucket="1_2"} 2145
telemt_desync_frames_bucket_total{bucket="3_10"} 4056
telemt_desync_frames_bucket_total{bucket="gt_10"} 4120
telemt_pool_swap_total 57
telemt_pool_force_close_total 1712
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 239
telemt_me_draining_writers_reap_progress_total 18206
telemt_me_writer_removed_unexpected_total 370
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1499
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16937
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16494
telemt_me_writer_teardown_success_total{mode="normal"} 18436
telemt_me_writer_teardown_noop_total 18219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36655
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.101722
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36655
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 239
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 338
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 2366643
telemt_user_connections_current{user="hello"} 4719
telemt_user_octets_from_client{user="hello"} 37816165744 (35.22 GB)
telemt_user_octets_to_client{user="hello"} 873152812048 (813.19 GB)
telemt_user_unique_ips_current{user="hello"} 1786
telemt_user_unique_ips_recent_window{user="hello"} 700
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 52347.6 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2472081
telemt_connections_bad_total 275958
telemt_connections_current 3576
telemt_connections_me_current 3576
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 103588
telemt_upstream_connect_attempt_total 25027
telemt_upstream_connect_success_total 24774
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 24904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1064
telemt_me_reconnect_success_total 493
telemt_me_reader_eof_total 452
telemt_me_idle_close_by_peer_total 452
telemt_me_route_drop_no_conn_total 720632
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1740381
telemt_me_endpoint_quarantine_total 357
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 404
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
telemt_desync_total 8010
telemt_desync_full_logged_total 2740
telemt_desync_suppressed_total 5270
telemt_desync_frames_bucket_total{bucket="1_2"} 1997
telemt_desync_frames_bucket_total{bucket="3_10"} 3129
telemt_desync_frames_bucket_total{bucket="gt_10"} 2884
telemt_pool_swap_total 57
telemt_pool_force_close_total 1547
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 119
telemt_me_draining_writers_reap_progress_total 18032
telemt_me_writer_removed_unexpected_total 444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1500
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1449
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16485
telemt_me_writer_teardown_success_total{mode="normal"} 18492
telemt_me_writer_teardown_noop_total 18033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36525
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.859912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36525
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 119
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 413
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1742008
telemt_user_connections_current{user="hello"} 3576
telemt_user_octets_from_client{user="hello"} 33472841045 (31.17 GB)
telemt_user_octets_to_client{user="hello"} 836576782159 (779.12 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1394
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 52311.7 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2414995
telemt_connections_bad_total 273175
telemt_connections_current 3439
telemt_connections_me_current 3439
telemt_handshake_timeouts_total 71633
telemt_upstream_connect_attempt_total 21373
telemt_upstream_connect_success_total 21320
telemt_upstream_connect_attempts_per_request{bucket="1"} 21320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 767
telemt_me_reconnect_success_total 517
telemt_me_reader_eof_total 462
telemt_me_idle_close_by_peer_total 462
telemt_me_route_drop_no_conn_total 701909
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1733635
telemt_me_endpoint_quarantine_total 400
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 398
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
telemt_me_writers_warm_current 39
telemt_desync_total 8129
telemt_desync_full_logged_total 2771
telemt_desync_suppressed_total 5358
telemt_desync_frames_bucket_total{bucket="1_2"} 2151
telemt_desync_frames_bucket_total{bucket="3_10"} 3092
telemt_desync_frames_bucket_total{bucket="gt_10"} 2886
telemt_pool_swap_total 55
telemt_pool_force_close_total 1519
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 19119
telemt_me_writer_removed_unexpected_total 439
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1499
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18090
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 113
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17600
telemt_me_writer_teardown_success_total{mode="normal"} 19589
telemt_me_writer_teardown_noop_total 19122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38711
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.061434
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38711
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 449
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1731003
telemt_user_connections_current{user="hello"} 3439
telemt_user_octets_from_client{user="hello"} 39720190460 (36.99 GB)
telemt_user_octets_to_client{user="hello"} 843951599868 (785.99 GB)
telemt_user_unique_ips_current{user="hello"} 1341
telemt_user_unique_ips_recent_window{user="hello"} 511
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 52351.1 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7577575
telemt_connections_bad_total 504220
telemt_connections_current 5406
telemt_connections_me_current 5406
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 270579
telemt_upstream_connect_attempt_total 63382
telemt_upstream_connect_success_total 59689
telemt_upstream_connect_fail_total 2943
telemt_upstream_connect_attempts_per_request{bucket="1"} 62632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2943
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3159
telemt_me_reconnect_success_total 1087
telemt_me_reader_eof_total 784
telemt_me_idle_close_by_peer_total 783
telemt_me_route_drop_no_conn_total 12915039
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6318617
telemt_me_endpoint_quarantine_total 414
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 121
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 121
telemt_me_single_endpoint_shadow_rotate_total 412
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 41
telemt_desync_total 12137
telemt_desync_full_logged_total 3882
telemt_desync_suppressed_total 8255
telemt_desync_frames_bucket_total{bucket="1_2"} 2644
telemt_desync_frames_bucket_total{bucket="3_10"} 5330
telemt_desync_frames_bucket_total{bucket="gt_10"} 4163
telemt_pool_swap_total 53
telemt_pool_force_close_total 1632
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 338
telemt_me_draining_writers_reap_progress_total 17546
telemt_me_writer_removed_unexpected_total 1050
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2267
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16225
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15914
telemt_me_writer_teardown_success_total{mode="normal"} 18492
telemt_me_writer_teardown_noop_total 17555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36047
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.637202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36047
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 338
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 6354516
telemt_user_connections_current{user="hello"} 5406
telemt_user_octets_from_client{user="hello"} 53973954412 (50.27 GB)
telemt_user_octets_to_client{user="hello"} 629569925007 (586.33 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1919
telemt_user_unique_ips_recent_window{user="hello"} 969
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 52318.5 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2408814
telemt_connections_bad_total 284431
telemt_connections_current 3743
telemt_connections_me_current 3743
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 51079
telemt_upstream_connect_attempt_total 22785
telemt_upstream_connect_success_total 22549
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 22763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_reconnect_attempts_total 2189
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 725
telemt_me_idle_close_by_peer_total 725
telemt_me_route_drop_no_conn_total 825596
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1828369
telemt_me_endpoint_quarantine_total 326
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 402
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
telemt_me_writers_active_current 41
telemt_me_writers_warm_current 32
telemt_desync_total 8481
telemt_desync_full_logged_total 3065
telemt_desync_suppressed_total 5416
telemt_desync_frames_bucket_total{bucket="1_2"} 1620
telemt_desync_frames_bucket_total{bucket="3_10"} 3428
telemt_desync_frames_bucket_total{bucket="gt_10"} 3433
telemt_pool_swap_total 53
telemt_pool_force_close_total 1451
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 125
telemt_me_draining_writers_reap_progress_total 18919
telemt_me_writer_removed_unexpected_total 702
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1760
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17884
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17468
telemt_me_writer_teardown_success_total{mode="normal"} 19644
telemt_me_writer_teardown_noop_total 18919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38563
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.874294
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38563
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 125
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 610
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 1814275
telemt_user_connections_current{user="hello"} 3743
telemt_user_octets_from_client{user="hello"} 33305174100 (31.02 GB)
telemt_user_octets_to_client{user="hello"} 821099744634 (764.71 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1525
telemt_user_unique_ips_recent_window{user="hello"} 570
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 52312.9 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3556089
telemt_connections_bad_total 188777
telemt_connections_current 2995
telemt_connections_me_current 2995
telemt_handshake_timeouts_total 1515279
telemt_upstream_connect_attempt_total 21228
telemt_upstream_connect_success_total 21194
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 701
telemt_me_reconnect_success_total 350
telemt_me_reader_eof_total 346
telemt_me_idle_close_by_peer_total 346
telemt_me_route_drop_no_conn_total 659909
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1628519
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 410
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 38
telemt_desync_total 7930
telemt_desync_full_logged_total 2833
telemt_desync_suppressed_total 5097
telemt_desync_frames_bucket_total{bucket="1_2"} 1438
telemt_desync_frames_bucket_total{bucket="3_10"} 3156
telemt_desync_frames_bucket_total{bucket="gt_10"} 3336
telemt_pool_swap_total 57
telemt_pool_force_close_total 1407
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 18963
telemt_me_writer_removed_unexpected_total 334
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1237
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18081
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1386
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17556
telemt_me_writer_teardown_success_total{mode="normal"} 19318
telemt_me_writer_teardown_noop_total 18963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38281
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.031392
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38281
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 302
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1623784
telemt_user_connections_current{user="hello"} 2995
telemt_user_octets_from_client{user="hello"} 28995817232 (27.00 GB)
telemt_user_octets_to_client{user="hello"} 788953136972 (734.77 GB)
telemt_user_unique_ips_current{user="hello"} 1324
telemt_user_unique_ips_recent_window{user="hello"} 476
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 50304.4 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722532
telemt_connections_bad_total 23786
telemt_connections_current 716
telemt_connections_me_current 716
telemt_handshake_timeouts_total 269686
telemt_upstream_connect_attempt_total 24259
telemt_upstream_connect_success_total 24257
telemt_upstream_connect_attempts_per_request{bucket="1"} 24257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1060
telemt_me_reconnect_success_total 389
telemt_me_reader_eof_total 389
telemt_me_idle_close_by_peer_total 389
telemt_me_route_drop_no_conn_total 154796
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369429
telemt_me_endpoint_quarantine_total 472
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 429
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
telemt_desync_total 2455
telemt_desync_full_logged_total 959
telemt_desync_suppressed_total 1496
telemt_desync_frames_bucket_total{bucket="1_2"} 392
telemt_desync_frames_bucket_total{bucket="3_10"} 883
telemt_desync_frames_bucket_total{bucket="gt_10"} 1180
telemt_pool_swap_total 55
telemt_pool_force_close_total 1215
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 21716
telemt_me_writer_removed_unexpected_total 370
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1577
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20513
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1212
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20501
telemt_me_writer_teardown_success_total{mode="normal"} 22090
telemt_me_writer_teardown_noop_total 21716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43806
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.442405
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43806
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 317
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 369535
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 5441083251 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 142938758053 (133.12 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 52322.9 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2563457
telemt_connections_bad_total 240648
telemt_connections_current 4561
telemt_connections_me_current 4561
telemt_handshake_timeouts_total 61275
telemt_upstream_connect_attempt_total 22179
telemt_upstream_connect_success_total 22085
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 22149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11037
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 893
telemt_me_reconnect_success_total 497
telemt_me_reader_eof_total 463
telemt_me_idle_close_by_peer_total 463
telemt_me_route_drop_no_conn_total 678155
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2027220
telemt_me_endpoint_quarantine_total 413
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 408
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
telemt_me_writers_active_current 40
telemt_desync_total 8017
telemt_desync_full_logged_total 2680
telemt_desync_suppressed_total 5337
telemt_desync_frames_bucket_total{bucket="1_2"} 1949
telemt_desync_frames_bucket_total{bucket="3_10"} 3001
telemt_desync_frames_bucket_total{bucket="gt_10"} 3067
telemt_pool_swap_total 58
telemt_pool_force_close_total 1425
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 19916
telemt_me_writer_removed_unexpected_total 456
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1504
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18883
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1401
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18491
telemt_me_writer_teardown_success_total{mode="normal"} 20387
telemt_me_writer_teardown_noop_total 19916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40303
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.238767
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40303
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 444
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 2021097
telemt_user_connections_current{user="hello"} 4561
telemt_user_octets_from_client{user="hello"} 43071954080 (40.11 GB)
telemt_user_octets_to_client{user="hello"} 948884247044 (883.72 GB)
telemt_user_unique_ips_current{user="hello"} 1599
telemt_user_unique_ips_recent_window{user="hello"} 644
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 52319.6 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2345638
telemt_connections_bad_total 184857
telemt_connections_current 3582
telemt_connections_me_current 3582
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 58260
telemt_upstream_connect_attempt_total 38323
telemt_upstream_connect_success_total 38091
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 38280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 581
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 3153
telemt_me_reconnect_success_total 649
telemt_me_reader_eof_total 567
telemt_me_idle_close_by_peer_total 567
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 681525
telemt_me_route_drop_channel_closed_total 48
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1897854
telemt_me_endpoint_quarantine_total 458
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 407
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
telemt_desync_total 7153
telemt_desync_full_logged_total 2440
telemt_desync_suppressed_total 4713
telemt_desync_frames_bucket_total{bucket="1_2"} 1878
telemt_desync_frames_bucket_total{bucket="3_10"} 2662
telemt_desync_frames_bucket_total{bucket="gt_10"} 2613
telemt_pool_swap_total 57
telemt_pool_force_close_total 1377
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 19079
telemt_me_writer_removed_unexpected_total 578
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1771
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17913
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1289
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17702
telemt_me_writer_teardown_success_total{mode="normal"} 19684
telemt_me_writer_teardown_noop_total 19080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38764
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.618744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38764
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 494
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1908887
telemt_user_connections_current{user="hello"} 3582
telemt_user_octets_from_client{user="hello"} 34476209761 (32.11 GB)
telemt_user_octets_to_client{user="hello"} 842431075964 (784.58 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1407
telemt_user_unique_ips_recent_window{user="hello"} 512
```