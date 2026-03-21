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

# Server Metrics 2026-03-21 12:55:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 58775.3 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1923853
telemt_connections_bad_total 96380
telemt_connections_current 1466
telemt_connections_me_current 1466
telemt_handshake_timeouts_total 71148
telemt_upstream_connect_attempt_total 22722
telemt_upstream_connect_success_total 22607
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 22683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1262
telemt_me_reconnect_success_total 520
telemt_me_reader_eof_total 503
telemt_me_idle_close_by_peer_total 503
telemt_me_route_drop_no_conn_total 1454488
telemt_me_route_drop_channel_closed_total 472
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1510682
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 415
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 467
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_me_writers_active_current 46
telemt_desync_total 5861
telemt_desync_full_logged_total 2049
telemt_desync_suppressed_total 3812
telemt_desync_frames_bucket_total{bucket="1_2"} 1264
telemt_desync_frames_bucket_total{bucket="3_10"} 2249
telemt_desync_frames_bucket_total{bucket="gt_10"} 2348
telemt_pool_swap_total 64
telemt_pool_force_close_total 1874
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 20306
telemt_me_writer_removed_unexpected_total 484
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1682
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18960
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1809
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18432
telemt_me_writer_teardown_success_total{mode="normal"} 20642
telemt_me_writer_teardown_noop_total 20310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40952
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.598238
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40952
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 450
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1509554
telemt_user_connections_current{user="hello"} 1466
telemt_user_octets_from_client{user="hello"} 22388270011 (20.85 GB)
telemt_user_octets_to_client{user="hello"} 391144902627 (364.28 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 4421.3 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291584
telemt_connections_bad_total 17696
telemt_connections_current 2951
telemt_connections_me_current 2951
telemt_handshake_timeouts_total 16381
telemt_upstream_connect_attempt_total 1913
telemt_upstream_connect_success_total 1854
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 134
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 101
telemt_me_idle_close_by_peer_total 101
telemt_me_route_drop_no_conn_total 229852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237890
telemt_me_endpoint_quarantine_total 26
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_me_writers_active_current 85
telemt_desync_total 897
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 482
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 2
telemt_pool_force_close_total 80
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 1533
telemt_me_writer_removed_unexpected_total 109
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1448
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1453
telemt_me_writer_teardown_success_total{mode="normal"} 1642
telemt_me_writer_teardown_noop_total 1533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3175
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.230176
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3175
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 95
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 237787
telemt_user_connections_current{user="hello"} 2951
telemt_user_octets_from_client{user="hello"} 3823630400 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 65173611184 (60.70 GB)
telemt_user_unique_ips_current{user="hello"} 1493
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 58773.1 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3722451
telemt_connections_bad_total 381622
telemt_connections_current 3423
telemt_connections_me_current 3423
telemt_handshake_timeouts_total 145775
telemt_upstream_connect_attempt_total 22188
telemt_upstream_connect_success_total 22154
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 816
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 463
telemt_me_idle_close_by_peer_total 463
telemt_me_route_drop_no_conn_total 1783983
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2977927
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 451
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
telemt_desync_total 12702
telemt_desync_full_logged_total 4312
telemt_desync_suppressed_total 8390
telemt_desync_frames_bucket_total{bucket="1_2"} 2696
telemt_desync_frames_bucket_total{bucket="3_10"} 4962
telemt_desync_frames_bucket_total{bucket="gt_10"} 5044
telemt_pool_swap_total 63
telemt_pool_force_close_total 1986
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 295
telemt_me_draining_writers_reap_progress_total 20165
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1717
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18716
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18179
telemt_me_writer_teardown_success_total{mode="normal"} 20433
telemt_me_writer_teardown_noop_total 20181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40614
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 58.469427
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40614
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 295
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2974048
telemt_user_connections_current{user="hello"} 3422
telemt_user_octets_from_client{user="hello"} 48465675340 (45.14 GB)
telemt_user_octets_to_client{user="hello"} 1042122011156 (970.55 GB)
telemt_user_unique_ips_current{user="hello"} 1268
telemt_user_unique_ips_recent_window{user="hello"} 605
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 58774.4 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3054272
telemt_connections_bad_total 332322
telemt_connections_current 3980
telemt_connections_me_current 3980
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 119915
telemt_upstream_connect_attempt_total 26917
telemt_upstream_connect_success_total 26644
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 26777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 476
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1144
telemt_me_reconnect_success_total 528
telemt_me_reader_eof_total 490
telemt_me_idle_close_by_peer_total 490
telemt_me_route_drop_no_conn_total 951312
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2191631
telemt_me_endpoint_quarantine_total 391
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 453
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
telemt_desync_total 10144
telemt_desync_full_logged_total 3424
telemt_desync_suppressed_total 6720
telemt_desync_frames_bucket_total{bucket="1_2"} 2517
telemt_desync_frames_bucket_total{bucket="3_10"} 3923
telemt_desync_frames_bucket_total{bucket="gt_10"} 3704
telemt_pool_swap_total 64
telemt_pool_force_close_total 1793
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 19669
telemt_me_writer_removed_unexpected_total 478
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1664
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18503
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1675
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17876
telemt_me_writer_teardown_success_total{mode="normal"} 20167
telemt_me_writer_teardown_noop_total 19670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39837
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.432534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39837
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 443
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2192612
telemt_user_connections_current{user="hello"} 3980
telemt_user_octets_from_client{user="hello"} 41389747229 (38.55 GB)
telemt_user_octets_to_client{user="hello"} 1036352712115 (965.18 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1461
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 58738.2 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2982376
telemt_connections_bad_total 326675
telemt_connections_current 3134
telemt_connections_me_current 3134
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 86986
telemt_upstream_connect_attempt_total 32098
telemt_upstream_connect_success_total 31875
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13562
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 837
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1269
telemt_me_reconnect_success_total 610
telemt_me_reader_eof_total 553
telemt_me_idle_close_by_peer_total 553
telemt_me_route_drop_no_conn_total 903236
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2167063
telemt_me_endpoint_quarantine_total 435
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 445
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
telemt_me_writers_active_current 48
telemt_desync_total 10001
telemt_desync_full_logged_total 3347
telemt_desync_suppressed_total 6654
telemt_desync_frames_bucket_total{bucket="1_2"} 2587
telemt_desync_frames_bucket_total{bucket="3_10"} 3813
telemt_desync_frames_bucket_total{bucket="gt_10"} 3601
telemt_pool_swap_total 62
telemt_pool_force_close_total 1743
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 204
telemt_me_draining_writers_reap_progress_total 21010
telemt_me_writer_removed_unexpected_total 527
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1781
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19790
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1588
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 155
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19267
telemt_me_writer_teardown_success_total{mode="normal"} 21571
telemt_me_writer_teardown_noop_total 21014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.310565
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 204
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 531
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2172151
telemt_user_connections_current{user="hello"} 3134
telemt_user_octets_from_client{user="hello"} 48502894957 (45.17 GB)
telemt_user_octets_to_client{user="hello"} 1031936212588 (961.07 GB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1078
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 58777.5 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9906895
telemt_connections_bad_total 664726
telemt_connections_current 5286
telemt_connections_me_current 5286
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 326354
telemt_upstream_connect_attempt_total 89256
telemt_upstream_connect_success_total 84070
telemt_upstream_connect_fail_total 4327
telemt_upstream_connect_attempts_per_request{bucket="1"} 88397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4327
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3487
telemt_me_reconnect_success_total 1182
telemt_me_reader_eof_total 835
telemt_me_idle_close_by_peer_total 834
telemt_me_route_drop_no_conn_total 17970741
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8172525
telemt_me_endpoint_quarantine_total 449
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 462
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
telemt_desync_total 15616
telemt_desync_full_logged_total 4993
telemt_desync_suppressed_total 10623
telemt_desync_frames_bucket_total{bucket="1_2"} 3331
telemt_desync_frames_bucket_total{bucket="3_10"} 6869
telemt_desync_frames_bucket_total{bucket="gt_10"} 5416
telemt_pool_swap_total 60
telemt_pool_force_close_total 1906
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 392
telemt_me_draining_writers_reap_progress_total 19192
telemt_me_writer_removed_unexpected_total 1144
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2489
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17730
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1632
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17286
telemt_me_writer_teardown_success_total{mode="normal"} 20219
telemt_me_writer_teardown_noop_total 19201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39420
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.321268
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39420
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 392
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 822
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 8230208
telemt_user_connections_current{user="hello"} 5286
telemt_user_octets_from_client{user="hello"} 64390685497 (59.97 GB)
telemt_user_octets_to_client{user="hello"} 697707622672 (649.79 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1883
telemt_user_unique_ips_recent_window{user="hello"} 1098
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 58745.2 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3008807
telemt_connections_bad_total 355615
telemt_connections_current 3513
telemt_connections_me_current 3513
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 65722
telemt_upstream_connect_attempt_total 25221
telemt_upstream_connect_success_total 24941
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 25191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_reconnect_attempts_total 2476
telemt_me_reconnect_success_total 850
telemt_me_reader_eof_total 841
telemt_me_idle_close_by_peer_total 841
telemt_me_route_drop_no_conn_total 1105891
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2281684
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 449
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
telemt_desync_total 10599
telemt_desync_full_logged_total 3704
telemt_desync_suppressed_total 6895
telemt_desync_frames_bucket_total{bucket="1_2"} 2075
telemt_desync_frames_bucket_total{bucket="3_10"} 4236
telemt_desync_frames_bucket_total{bucket="gt_10"} 4288
telemt_pool_swap_total 60
telemt_pool_force_close_total 1687
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 156
telemt_me_draining_writers_reap_progress_total 21045
telemt_me_writer_removed_unexpected_total 813
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2023
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19863
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19358
telemt_me_writer_teardown_success_total{mode="normal"} 21886
telemt_me_writer_teardown_noop_total 21046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42932
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.474716
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42932
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 156
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 715
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 2266441
telemt_user_connections_current{user="hello"} 3513
telemt_user_octets_from_client{user="hello"} 43170219536 (40.21 GB)
telemt_user_octets_to_client{user="hello"} 995623057366 (927.25 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1397
telemt_user_unique_ips_recent_window{user="hello"} 561
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 58739.6 (16h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4573950
telemt_connections_bad_total 229764
telemt_connections_current 3110
telemt_connections_me_current 3110
telemt_handshake_timeouts_total 2016976
telemt_upstream_connect_attempt_total 23440
telemt_upstream_connect_success_total 23406
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 23409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 982
telemt_me_reconnect_success_total 420
telemt_me_reader_eof_total 427
telemt_me_idle_close_by_peer_total 427
telemt_me_route_drop_no_conn_total 996138
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2042178
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 459
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
telemt_desync_total 9699
telemt_desync_full_logged_total 3451
telemt_desync_suppressed_total 6248
telemt_desync_frames_bucket_total{bucket="1_2"} 1782
telemt_desync_frames_bucket_total{bucket="3_10"} 3861
telemt_desync_frames_bucket_total{bucket="gt_10"} 4056
telemt_pool_swap_total 64
telemt_pool_force_close_total 1628
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 20982
telemt_me_writer_removed_unexpected_total 410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1434
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19984
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19354
telemt_me_writer_teardown_success_total{mode="normal"} 21418
telemt_me_writer_teardown_noop_total 20982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42400
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.398382
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42400
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 365
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2035541
telemt_user_connections_current{user="hello"} 3110
telemt_user_octets_from_client{user="hello"} 37614083092 (35.03 GB)
telemt_user_octets_to_client{user="hello"} 963899959032 (897.70 GB)
telemt_user_unique_ips_current{user="hello"} 1190
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 56731.3 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 977405
telemt_connections_bad_total 112738
telemt_connections_current 696
telemt_connections_me_current 696
telemt_handshake_timeouts_total 344999
telemt_upstream_connect_attempt_total 26848
telemt_upstream_connect_success_total 26846
telemt_upstream_connect_attempts_per_request{bucket="1"} 26846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1123
telemt_me_reconnect_success_total 438
telemt_me_reader_eof_total 437
telemt_me_idle_close_by_peer_total 437
telemt_me_route_drop_no_conn_total 202320
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452204
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 478
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_warm_current 7
telemt_desync_total 3097
telemt_desync_full_logged_total 1161
telemt_desync_suppressed_total 1936
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 1101
telemt_desync_frames_bucket_total{bucket="gt_10"} 1456
telemt_pool_swap_total 62
telemt_pool_force_close_total 1393
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 24062
telemt_me_writer_removed_unexpected_total 414
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1750
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22734
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1390
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22669
telemt_me_writer_teardown_success_total{mode="normal"} 24484
telemt_me_writer_teardown_noop_total 24062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48546
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.034694
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48546
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 357
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 452024
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 7343396379 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 172714666425 (160.85 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 58749.6 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3237422
telemt_connections_bad_total 313939
telemt_connections_current 3917
telemt_connections_me_current 3917
telemt_handshake_timeouts_total 95684
telemt_upstream_connect_attempt_total 24262
telemt_upstream_connect_success_total 24162
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 24231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 973
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 884611
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2544981
telemt_me_endpoint_quarantine_total 453
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
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
telemt_me_writers_active_current 43
telemt_desync_total 10403
telemt_desync_full_logged_total 3418
telemt_desync_suppressed_total 6985
telemt_desync_frames_bucket_total{bucket="1_2"} 2478
telemt_desync_frames_bucket_total{bucket="3_10"} 3865
telemt_desync_frames_bucket_total{bucket="gt_10"} 4060
telemt_pool_swap_total 65
telemt_pool_force_close_total 1672
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 21802
telemt_me_writer_removed_unexpected_total 505
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1686
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20619
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1642
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20130
telemt_me_writer_teardown_success_total{mode="normal"} 22305
telemt_me_writer_teardown_noop_total 21802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44107
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.581732
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44107
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 490
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 2537895
telemt_user_connections_current{user="hello"} 3917
telemt_user_octets_from_client{user="hello"} 53494863284 (49.82 GB)
telemt_user_octets_to_client{user="hello"} 1195102148372 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 1359
telemt_user_unique_ips_recent_window{user="hello"} 565
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 58746.2 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2915022
telemt_connections_bad_total 242713
telemt_connections_current 3825
telemt_connections_me_current 3825
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 83308
telemt_upstream_connect_attempt_total 40489
telemt_upstream_connect_success_total 40229
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 40444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 586
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_reconnect_attempts_total 3418
telemt_me_reconnect_success_total 730
telemt_me_reader_eof_total 631
telemt_me_idle_close_by_peer_total 631
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 946190
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2345110
telemt_me_endpoint_quarantine_total 509
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 455
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
telemt_desync_total 9091
telemt_desync_full_logged_total 3077
telemt_desync_suppressed_total 6014
telemt_desync_frames_bucket_total{bucket="1_2"} 2337
telemt_desync_frames_bucket_total{bucket="3_10"} 3351
telemt_desync_frames_bucket_total{bucket="gt_10"} 3403
telemt_pool_swap_total 64
telemt_pool_force_close_total 1618
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 21000
telemt_me_writer_removed_unexpected_total 644
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19682
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1510
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19382
telemt_me_writer_teardown_success_total{mode="normal"} 21672
telemt_me_writer_teardown_noop_total 21001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42673
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.605867
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42673
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 555
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2355164
telemt_user_connections_current{user="hello"} 3825
telemt_user_octets_from_client{user="hello"} 43820865389 (40.81 GB)
telemt_user_octets_to_client{user="hello"} 1030737221372 (959.95 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1343
telemt_user_unique_ips_recent_window{user="hello"} 568
```